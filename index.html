<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<title>Teste Qui-Quadrado de Independência</title>
<style>
  body {
    font-family: Arial, sans-serif;
    background: #f3f3f3;
    padding: 20px;
  }
  h2 {
    text-align: center;
  }
  table {
    margin: 10px auto;
    border-collapse: collapse;
  }
  th, td {
    border: 1px solid #888;
    padding: 6px 12px;
    text-align: center;
  }
  button {
    display: block;
    margin: 20px auto;
    padding: 10px 20px;
    cursor: pointer;
  }
  .resultado {
    text-align: center;
    font-weight: bold;
    margin-top: 15px;
  }
</style>
</head>
<body>

<h2>Teste Qui-Quadrado de Independência</h2>

<table>
  <tr>
    <th></th>
    <th>Café</th>
    <th>Chá</th>
    <th>Total</th>
  </tr>
  <tr>
    <th>Homens</th>
    <td id="homens_cafe">30</td>
    <td id="homens_cha">20</td>
    <td>50</td>
  </tr>
  <tr>
    <th>Mulheres</th>
    <td id="mulheres_cafe">10</td>
    <td id="mulheres_cha">40</td>
    <td>50</td>
  </tr>
  <tr>
    <th>Total</th>
    <td>40</td>
    <td>60</td>
    <td>100</td>
  </tr>
</table>

<button onclick="calcularQuiQuadrado()">Calcular Qui-Quadrado</button>

<div class="resultado" id="resultado"></div>

<script>
function calcularQuiQuadrado() {
  // Dados observados
  const O = [
    [30, 20], // Homens
    [10, 40]  // Mulheres
  ];

  // Totais
  const totalLinha = [50, 50];
  const totalColuna = [40, 60];
  const totalGeral = 100;

  let chi2 = 0;

  // Cálculo dos valores esperados e do qui-quadrado
  for (let i = 0; i < 2; i++) {
    for (let j = 0; j < 2; j++) {
      let E = (totalLinha[i] * totalColuna[j]) / totalGeral;
      chi2 += Math.pow(O[i][j] - E, 2) / E;
    }
  }

  // Graus de liberdade: (linhas - 1) * (colunas - 1)
  const gl = (2 - 1) * (2 - 1);

  document.getElementById("resultado").innerHTML =
    `χ² calculado = <b>${chi2.toFixed(2)}</b><br>
     Graus de liberdade = ${gl}<br>
     Valor crítico (5%) = 3.84<br><br>` +
    (chi2 > 3.84
      ? "➡ Existe relação significativa entre gênero e preferência de bebida."
      : "➡ Não há relação significativa entre gênero e preferência de bebida.");
}
</script>

</body>
</html>
