
# OTAKUFLIX

### Link do site: <a href="https://robson-carvalho.github.io/OTAKUFLIX-A-COPY-OF-NETFLIX/"><img align="center" alt="Robson" src="https://github.com/Robson-Carvalho/OTAKUFLIX-A-COPY-OF-NETFLIX/blob/main/img/icone-otakuflix.png?raw=true" width="30">
</a> 

 Como desafio do bootcamp da digital innovation recriei a interface do principal site de streaming mundial, mas com a minha cara ksksk, só com animes. Utilizando tecnologias simples como HTML5, CSS3 e JavaScript. Nesse projeto eu aprendi: como estruturar um layout, técnicas de CSS3 com containers e variáveis, como posicionar os elementos com Flexbox e como utilizar plugins Jquery. Gostei muito de criar o OTAKUFLIX, foi muito divertido, além de aprender tudo o que foi citado acima!

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
