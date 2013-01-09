Aptitude
=======
Sekilas tentang Aptitude
------------------------

Aptitude merupakan paket manager Debian GNU/Linux yang berbasiskan text menggunakan antarmuka ``ncurses``. Aptitude merupakan ``front-end`` lain dari tool ``apt-get`` yang sudah begitu terkenal di Debian GNU/linux. 
``Aptitude`` bisa bekerja langsung untuk kegiatan manajemen paket di command line maupun berjalan dalam mode interaktif dalam antarmuka ``semigrafis``.

Aptitude dalam mode interaktif
------------------------------
 
Untuk menjalankan ``aptitude`` dalam mode interaktif, jalankan perintah ini di terminal::
debian:~# aptitude
.. image:: ../images/paket/aptitude-ui.png
Tool instalasi `dselect` ini memberikan kemudahan kepada user debian
GNU/Linux dalam melakukan instalasi karena dilengkapi dengan tampilan semi
grafis. Anda hanya menyorot opsi [I]nstall jika ingin menginstal atau meng-
upgrade paket software, opsi [R]emove jika ingin menghapus sebuah software
dari sistem, opsi [C]onfig untuk mengkonfigurasi paket software yang belum
terkonfigurasi, dan beberapa opsi lain yang diperlukan. Pengaksesan tool
`dselect` dapat menggunakan perintah berikut::

 debian:~# dselect

atau bila menggunakan sudo::

 debian:~$ sudo dselect

Maka akan nampak pada terminal sebagai berikut.

.. image:: ../images/paket/dselect.png
