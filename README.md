# Projeto-Imers-o-Dev-Alura
Primeiro projeto realizado na Imersão Dev - Conversor de Moedas


HTML
<div class="container">
  <h1 class="page-title">
    Conversor de Bitcoin
  </h1>
  <img src="https://www.alura.com.br/assets/img/imersoes/dev-2021/logo-imersao-aluraflix.svg" class="page-logo" alt="">
</div>
<a href="https://alura.com.br/" target="_blank">
  <img src="https://www.alura.com.br/assets/img/home/alura-logo.svg" alt="" class="alura-logo">
  <img src="https://cdn.pixabay.com/photo/2019/04/15/20/42/bitcoin-4130299_1280.png">
</a>

CSS
body {
  font-family: "Roboto Mono", monospace;
  text-align: center;
  background-image: url("https://s36296.pcdn.co/wp-content/uploads/2020/11/cc4c2bf8-financial-market-snapshot-october-2020-scaled.jpeg");
  background-color: #ffff00;
  background-size: cover;
  background-position: center top;
  background-repeat: no-repeat;
  height: 100vh;
}

.container {
  text-align: center;
  padding: 20px;
}

.page-title {
  color: #ffffff;
  margin: 0 0 5px;
}

.page-subtitle {
  color: #ffffff;
  margin-top: 5px;
}

.page-logo {
  width: 200px;
}

.alura-logo {
  width: 40px;
  position: absolute;
  top: 10px;
  right: 10px;
}

body > img {
  margin: 0 10px;
}

img {
  max-height: 250px;
}

JS
var valorEmBitcoin = 20;
var cotacaoDoBitcoin = 182076;

var valorEmReal = valorEmBitcoin * cotacaoDoBitcoin;
valorEmReal = valorEmReal.toFixed(2);
alert(
  "Ola o seu resultado do Conversor de Bitcoin em Reais deu " +
    "R$ " +
    valorEmReal
);
