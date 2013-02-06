---
title: Vagrant
isChild: true
---

## Vagrant {#vagrant_title}

Menjalankan aplikasi Anda pada lingkungan yang berbeda dalam pengembangan dan produksi dapat menyebabkan bug yang aneh 
muncul ketika Anda meng-upload ke server sesungguhnya. Dan juga sulit untuk menjaga lingkungan pengembangan yang berbeda-beda tetap ter-update 
versinya untuk semua library yang digunakan saat bekerja dalam sebuah tim.

Jika Anda mengembangkan di Windows dan menyebarkan di Linux (atau apa pun yang non-Windows) atau mengembangkan dalam sebuah tim, Anda 
seharusnya mempertimbangkan menggunakan mesin virtual. Ini terdengar rumit, tetapi menggunakan [Vagrant][vagrant], Anda dapat membuat 
mesin virtual dengan hanya beberapa langkah. Kotak-kotak dasar dapat diatur secara manual kemudian, atau Anda dapat menggunakan "provisioning"
software seperti [Puppet][puppet] atau [Chef][chef] untuk melakukan hal ini. Provisioning kotak-kotak dasar adalah cara yang bagus untuk
memastikan bahwa beberapa kotak ditetapkan secara identik dan menghilangkan kebutuhan bagi Anda untuk mempertahankan kerumitan
"mengatur" daftar perintah. Anda juga bisa "menghancurkan" kotak dasar Anda dan menciptakannya kembali tanpa banyak langkah manual, sehingga
mudah untuk menciptakan sebuah instalasi yang "segar".

Vagrant menciptakan folder bersama yang dapat digunakan untuk berbagi kode Anda antara host dan mesin virtual Anda, yang berarti Anda dapat
membuat dan meng-edit file Anda pada mesin host Anda dan kemudian menjalankan kode di dalam mesin virtual Anda.

[vagrant]: http://vagrantup.com/
[puppet]: http://www.puppetlabs.com/
[chef]: http://www.opscode.com/
