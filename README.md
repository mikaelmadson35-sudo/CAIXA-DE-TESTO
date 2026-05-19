<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Caixas de Texto</title>
</head>
<body>

<form method="post">
    <?php
    // Cria 5 caixas de texto
    for ($i = 1; $i <= 5; $i++) {
        echo "Texto $i: <input type='text' name='texto$i'><br><br>";
    }
    ?>

    <input type="submit" value="Enviar">
</form>

</body>
</html>
