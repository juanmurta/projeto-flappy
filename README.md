# Flappy Bird com Reinício - Jogo em Python

## Descrição  
Este projeto é uma recriação do clássico jogo **Flappy Bird**, desenvolvido em **Python** utilizando a biblioteca **Pygame**. O jogador controla um pássaro que deve navegar entre canos, evitando colisões, enquanto acumula pontos. Esta versão inclui uma funcionalidade de reinício automático ao colidir com canos ou o chão, reiniciando o jogo com um novo pássaro, canos e pontuação zerada. O jogo apresenta gráficos 2D, animações do pássaro e movimentação de cenário.

## Funcionalidades Principais  
- **Controle do Pássaro**:  
  - Pressione a tecla **espaço** para fazer o pássaro pular, controlando sua trajetória.  
  - O pássaro possui animações de bater asas e rotação para simular voo e queda.  
- **Geração de Canos**:  
  - Canos são gerados aleatoriamente com alturas variadas, movendo-se da direita para a esquerda.  
  - O jogador ganha pontos ao passar por cada par de canos sem colidir.  
- **Colisão e Reinício Automático**:  
  - Detecta colisões entre o pássaro e os canos, o chão ou o limite superior da tela.  
  - Ao colidir, o jogo reinicia automaticamente, resetando o pássaro, os canos e a pontuação.  
- **Interface Gráfica e Pontuação**:  
  - Exibe um fundo animado, chão em movimento e a pontuação na tela.  
  - Usa imagens escaladas para o pássaro, canos, chão e fundo, carregadas de uma pasta `imgs`.  

## Como Contribuir  
1. Faça um fork do repositório.  
2. Crie um branch para suas alterações.  
3. Commit suas mudanças.  
4. Faça push para o branch.  
5. Abra um Pull Request.  

Para mais detalhes sobre como contribuir, veja a [documentação oficial do GitHub sobre Pull Requests](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests).