# EJERCICIO5
TAREA DE BOOTCAMP
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Disposición de elementos en CSS</title>
    <link rel="stylesheet" href="tarea5.css">
</head>
<body>
    <div class="galeria">
        <img class="imagen-galeria" src="peli1.jpeg" alt="imagen1"/>
        <img class="imagen-galeria" src="peli2.jpeg" alt="imagen2"/>
        <img class="imagen-galeria" src="peli3.jpeg" alt="imagen3"/>
        <img class="imagen-galeria" src="peli4.jpeg" alt="imagen4"/>
        <img class="imagen-galeria" src="peli5.jpeg" alt="imagen5"/>
        <img class="imagen-galeria" src="peli6.jpeg" alt="imagen6"/>


    </div>
    
</body>
</html>


.imagen {
     display: flex;
    flex-wrap: wrap;
    }

.imagen-galeria {
width: 300px;
}
