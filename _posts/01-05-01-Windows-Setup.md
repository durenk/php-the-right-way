---
title: Pengaturan di Windows
isChild: true
---

## Pengaturan di Windows {#windows_setup_title}

PHP disediakan dengan beberapa pilihan di Windows. Anda dapat [mengunduh file binarinya][php-downloads] dan sampai sekarang Anda dapat menggunakan file instalisasi '.msi'. Cara penginstalan sudah tidak disupport dan dihentikan pada versi PHP 5.3.0.

Untuk pembelajaran dan pengembangan di lokal, Anda dapat menggunakan webserver bawaan pada PHP 5.4 sehingga Anda tidak perlu khawatir 
tentang mengkonfigurasinya. Jika Anda lebih suka "semua-dalam-satu" paket yang mencakup webserver yang lengkap dan juga MySQL maka 
applikasi seperti [Web Platform Installer][wpi], [Zend Server CE][zsce], [XAMPP][xampp] dan [WAMP][wamp] akan memudahkan untuk 
membuat lingkungan pengembangan di Windows dan berjalan cepat. Yang artinya, alat ini akan sedikit berbeda dari produksi jadi 
hati-hati dari perbedaan lingkungan jika Anda bekerja di Windows dan menjalankannya di Linux.

Jika Anda perlu untuk menjalankan sistem produksi Anda di Windows maka IIS7 akan memberikan kinerja yang paling stabil dan terbaik. 
Anda dapat menggunakan [phpmanager][phpmanager] (GUI plugin untuk IIS7) untuk membuat mengkonfigurasi dan mengelola PHP. 
IIS7 dilengkapi dengan FastCGI bawaan dan siap digunakan, Anda hanya perlu mengkonfigurasi PHP sebagai pengontroll. 
Untuk bantuan dan tambahan sumber daya, ada [area khusus di iis.net][php-iis] untuk PHP.

[php-downloads]: http://windows.php.net
[phpmanager]: http://phpmanager.codeplex.com/
[wpi]: http://www.microsoft.com/web/downloads/platform.aspx
[zsce]: http://www.zend.com/en/products/server-ce/
[xampp]: http://www.apachefriends.org/en/xampp.html
[wamp]: http://www.wampserver.com/
[php-iis]: http://php.iis.net/
