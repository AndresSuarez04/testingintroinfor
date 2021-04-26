<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Formulario #1</title>
  <style media="screen">
    *{font-family: Arial, "Helvetica Neue", Helvetica, sans-serif;}
    table {width: 420px;}
    td {padding: 10px;}
  fieldset {padding: 10px; border: 1px solid #ccc; width: 420px; margin: 0 auto;}
  legend {text-align: right; font-style: italic; font-size: 20px; font-weight: bold; color: #999;}
  input [type=text], input[text=Email], textarea {padding: 5px; font-style: 18px; border: 1px solid #ccc; width: 300px;}
  </style>
</head>
<body>
  <main>
    <section>
      <form action="" method="post">
        <fieldset>
          <legend>Datos personales</legend>
          <table>
            <tr>
              <td align="right">Nombre:</td>
              <td><input type="text" name="nombre" required autofocus></td>
            </tr>
            <tr>
              <td aling="right">Email:</td>
              <td><input type="email" name="Correo" id="" required></td>
            </tr>
            <tr>
              <td aling="right">Movil:</td>
              <td><input type="text" name="Movil" required pattern="[0-9]{3}\s[0-9]{3}\s[0-9]{4}$" title="Debes escribir un numero de telefono valido. Ej: 123 456 7890"></td>
            </tr>
            <tr>
              <td aling="right" valing="top">Mensaje:</td>
              <td><textarea name="mensaje" id="" cols="30" rows="4" required></textarea></td>
            </tr>
            <tr>
              <td></td>
              <td><input type="image" src="img/Boton.png" alt="Enviar Datos" width="120" height="40"></td>
            </tr>
          </table>
        </fieldset>
      </form>

    </section>
  </main>
</body>
</html>
