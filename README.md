# Robo Think Invest

-   Adicionar script 'lottie.js'
-   Criar object 'lottie.loadAnimation'
    (adicionar a uma variavel para poder controlar a velocidade se desejar)
-   Adicionar um elemento no HTML e aponta-lo no objeto (ja definindo suas propriedades de altura e largura).

`<div id="animation-start"></div>`

```javascript
let animation = lottie.loadAnimation({
    container: document.getElementById('animation-start'), // the dom element that will contain the animation
    renderer: 'svg',
    loop: true,
    autoplay: true,
    path: 'robo-abertura.json' // the path to the animation json
});
animation.setSpeed(1.23);
```

### Animações

Arquivo: **robo-abertura.json**
Animação de início com a apresentação e explicação para o usuário

Arquivo: **robo-pre-loop.json**
Animação de transformação do robo no logo em loop

Arquivo: **robo-loop.json**
Animação de início com a apresentação e explicação para o usuário

**Demo Online**
[http://old-car.surge.sh](http://old-car.surge.sh/ 'http://old-car.surge.sh/')
