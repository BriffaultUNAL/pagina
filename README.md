<html>
 <body>
<?php
$prueba = fopen("test.txt", "r") or die("error al leer");
while (!feof($prueba)) {
    $linea=fgets($prueba);
    echo $linea;
}
fclose($prueba);
?>
 </body>
</html>
