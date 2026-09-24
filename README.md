# 🏓 Ping Pong Canvas Game

Um jogo arcade de Ping-Pong clássico em tempo real desenvolvido com HTML5 Canvas e JavaScript puro (Vanilla JS), com suporte para modo Single Player (contra IA) e Multiplayer local.


---

## 📌 Sobre o Projeto

Este projeto é uma recriação moderna do clássico jogo *Pong*. A aplicação utiliza a API nativa do Canvas do HTML5 para renderização gráfica e um loop de animação contínuo para atualizar a movimentação, colisões e placar de forma fluida.

### 🚀 Funcionalidades

- **Dois Modos de Jogo:**
  - **Single Player:** Enfrente uma Inteligência Artificial (IA) que reage à trajetória da bola.
  - **Multiplayer Local (2 Jogadores):** Dois jogadores competem no mesmo teclado.
- **Aceleração Dinâmica:** A bola ganha 5% a mais de velocidade a cada rebatida (com limite máximo ajustado), aumentando progressivamente a dificuldade do jogo.
- **Detecção de Colisão Precisa:** Mecânica de rebatida nas raquetes e reflexão nos limites superior e inferior da tela.
- **Tela de Game Over & Vitória:** Anúncio visual do vencedor assim que a pontuação máxima (10 pontos) é atingida.
- **Responsividade do Canvas:** Ajuste automático da área de jogo com o redimensionamento da janela (`resize`).

---

## 🎮 Controles

| Ação | Teclas |
| :--- | :--- |
| **Mover Raquete Esquerda (Jogador 1)** | `W` (Cima) / `S` (Baixo) |
| **Mover Raquete Direita (Jogador 2)** | `Seta para Cima` / `Seta para Baixo` |
| **Alternar para Modo vs IA** | `1` |
| **Alternar para Modo 2 Jogadores** | `2` |
| **Reiniciar Partida (Game Over)** | `Espaço` ou `R` |

---

## 🛠️ Tecnologias Utilizadas

- **[HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML):** Elemento `<canvas>` para renderização gráfica bidimensional.
- **[CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS):** Reset de margens e remoção de barras de rolagem (`overflow: hidden`).
- **[JavaScript (ES6+)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript):** Implementação de objetos literais, captura de eventos do teclado, físicas de colisão e ciclo de renderização com `requestAnimationFrame`.

---

## 💻 Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/WeslleyA/NOME-DO-SEU-REPOSITORIO.git](https://github.com/WeslleyA/NOME-DO-SEU-REPOSITORIO.git)
