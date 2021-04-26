<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Formulario HTML</title>
</head>
<body>
  <form action="" method="post">
     <input type="url" name="Web" id="" required autofocus placeholder="Pagina Web"><br>
     Móvil: <input type="text" name="Movil" pattern="[0-9]{3}\s[0-9]{3}\s[0-9]{4}$"title="Debe ser un numero de 10 digitos validos ej: xxx xxx xxxx">
    Correo: <input type="email" name="Correo" id=""required><br>
    Fecha: <input type="date" name="Fecha" id="" ><br>
    Mes: <input type="month" name="Mes" id=""><br>
    Semana: <input type="week" name="Semana" id=""><br>
    Hora: <input type="time" name="Hora" id=""><br>
    Fecha y Hora: <input type="datetime-local" name="FEcha y hora" id=""><br>
    Edad: <input type="number" name="Edad" id="" min="12" max="50" step="2"><br>
    Puntos: <input type="range" name="Puntos" id="" min="10" max="30"><br>
    Color favorito: <input type="color" name="Color Fav" id=""><br>
  <input list="Colores" name="Colores">
  <datalist id="Colores">
    <option value="Verde">
      <option value="Rojo">
        <option value="Azul">
          <option value="Negro">
            <option value="Blanco">
              <option value="Morado">
  </datalist><br>
<input type="image" src="img/Boton.png" alt="Enviar Datos" width="120" height="40">
</form>
</body>
</html>
