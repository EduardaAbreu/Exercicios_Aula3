# Exercecios-Aula3
html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Documento</title>
</head>
<body>
    <form method="get">
        <legend>Dados do paciente</legend>
        Nome do paciente: <input type="text"name="nome="><br>
        Registro hospitalar: <input type="text"name="registro"><br>
        Data de inclusao: <input type="date" name="inclusao"><br>
        Data de nascimento:<input type="date"name="datadenasc"><br>
        Email: <input type="email"name="email"><br>
        Genero:<br>
        <input type="radio" name="genero" value="1">feminino<br>
        <input type="radio" name="genero" value="2">masculino<br>
        Raça declarada:<br>
        <select name="raça">
        <option value="1">Branca</option>
        <option value="2">Negra</option>
        <option value="3">Parda</option>
        <option value="4">Amarela</option>
        </option>
    </select>
    <br>
        Como ficou sabendo do estudo?:<br>
        <input type="checkbox"name="estudo?" value="Convidado">Convidado<br>
        <input type="checkbox"name="estudo?" value="Internet">Internet<br>
        <input type="checkbox"name="estudo?" valeue="Amigos">Amigos<br>
        <input type="checkbox"name="estudo?" value="Familiares">Familiares<br>
        <input type="checkbox"name="estudo?" value="Outros">Outros<br>
        <button type="submit"name= "estudo?" valeu="Enviar"> Enviar Formulario</button>
    
        </form>
        
    </body>
    </html>
