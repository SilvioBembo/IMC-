<!DOCTYPE html>
<html>
<head>
    <meta charset="">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Introdução Javascript</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" type="text/css" media="screen" href="main.css">
    <script src="main.js"></script>
</head>

<script>

let peso = parseInt(prompt("Digite o peso (kg)"));

// recebe altura com vírgula, ex: 1,75
let alturaTex = prompt("Digite a sua altura (em metros, ex: 1,75)");

// troca vírgula por ponto e converte para número
let altura = parseFloat(alturaTexto.replace(",", "."));

let IMC = peso / (altura * altura);
IMC = IMC.toFixed(2); // 2 casas decimais

if (IMC < 18.5) {
    document.write("IMC é " + IMC + ", Abaixo do peso");
}
else if (IMC >= 18.5 && IMC < 25) {
    document.write("IMC é " + IMC + ", Peso normal");
}
else if (IMC >= 30) {
    document.write("IMC é " + IMC + ", Obesidade");
}

</script>

<body>
</body>
</html>
