

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=>, initial-scale=1.0">
    <title>Nome</title>
    <style>
        body {
            font: normal 20pt Arial;
        }
    </style>
</head>
<body>
  <script>
      var nome = window.prompt ('Qual é o seu nome?')
      document.write (`ola <strong>${nome}</strong>! seu nome tem ${nome.length} letras.<br/>`)
      document.write (`seu nome em maiúsculo é ${nome.toUpperCase()}<br/>`)
      document.write (`seu nome em minúsculo é ${nome.toLowerCase()}`)


  </script>
</body>
</html>
