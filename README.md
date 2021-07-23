
<img align="center" alt="Robson" src="https://github.com/Robson-Carvalho/OTAKUFLIX-A-COPY-OF-NETFLIX/blob/main/img/icone-otakuflix.png?raw=true">

# OTAKUFLIX <img align="center" height="100" width="100" alt="Robson" src="https://i.pinimg.com/originals/d1/37/db/d137db1d40598f876d12faf92e93709f.jpg">

 Como desafio do bootcamp da digital innovation recriei a interface do principal site de streaming mundial, mas com a minha cara ksksk, só com animes. Utilizando tecnologias simples como HTML5, CSS3 e JavaScript. Nesse projeto eu aprendi: como estruturar um layout, técnicas de CSS3 com containers e variáveis, como posicionar os elementos com Flexbox e como utilizar plugins Jquery. Gostei muito de criar o OTAKUFLIX, foi muito divertido, além de aprender tudo o que foi citado acima!

### Para o carrossel de filmes e séries foi utilizado o  [Owl Carousel 2] do JQuery <img align="center" height="50" width="50" alt="Robson" src="https://flanp.com/images/jquery-logo.png">


### Setup
Será necessário criar um arquivo chamado setup.js, o qual conterá o conteúdo abaixo. E possível controlar o número de filmes que estará na tela de acordo com a largura do dispositivo, além de ativar o loop de rolagem ou não. 
```
$('.owl-carousel').owlCarousel({
      loop:true, 
      margin:10, 
      nav:true, 
      responsive:{ 
      0:{ items:1 },  
      600:{ items:3 },  
      000:{ items:5 } 
	} 
})
```

### html
Dentro da div itens seram adicionados as imagens ou outros arquivos, esses imagens ou arquivos seram configurados automaticamente em carrossel. 
```
<div class="owl-carousel owl-theme">
    <div class="item"><h4>1</h4></div>
    <div class="item"><h4>2</h4></div>
    <div class="item"><h4>3</h4></div>
    <div class="item"><h4>4</h4></div>
    <div class="item"><h4>5</h4></div>
    <div class="item"><h4>6</h4></div>
    <div class="item"><h4>7</h4></div>
    <div class="item"><h4>8</h4></div>
    <div class="item"><h4>9</h4></div>
    <div class="item"><h4>10</h4></div>
    <div class="item"><h4>11</h4></div>
    <div class="item"><h4>12</h4></div>
</div>
```
