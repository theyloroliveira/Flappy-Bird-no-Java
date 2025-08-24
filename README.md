# Flappy-Bird-no-Java
Criei meu primeiro Flappy Bird através da linguagem de programação Java.
Só possui uma tecla de comando (Space).
Utilizei de um ArrayList mais o método Random para gerar os canos de forma e tamanhos aleatórios e coloquei num método chamado placePipes junto de um Timer que
a cada 1.5seg vai me gerar (ou pintar) novos canos na tela.
Para limitar a altura máxima que o pássaro pode chegar eu utilizei "bird.y = Math.max(bird.y, 0)" Aonde Y é a altura.
A velocidade do pulo do pássaro está em -8 e a variavel 'gravidade' está em 1.
