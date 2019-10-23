## INCLUDE AND REQUIRE PADA PHP

- Include adalah memasukkan, artinya kita memasukkan file kedalam dokumen kita, 
file tersebut bisa apa saja, termasuk script PHP, file konfigurasi, file HTML, dll.

<?php
   include ("header.php");
?>

- Require adalah Seperti terjemahannya, require berarti butuh, artinya kita butuh file tersebut, sehingga jika file tersebut tidak ada maka script selanjutnya tidak akan berjalan.

<?php
   require ("footer.php");
?>
