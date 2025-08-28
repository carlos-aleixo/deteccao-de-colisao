# 🚗 Simulação de Ré em p5.js

Este projeto é uma **simulação didática** desenvolvida com [p5.js](https://p5js.org/).  
O objetivo é representar de forma simples o movimento de um carro em **ré**, aplicando os principais conceitos de computação gráfica ensinados em aulas introdutórias:

- Desenho de **primitivas geométricas** (retângulos, círculos).
- Estrutura básica de um sketch (`setup()` e `draw()`).
- **Animação** através da atualização de posição a cada frame.
- **Velocidade e direção** controladas por variáveis.
- **Detecção e tratamento de colisão** com inversão de sentido.
- Efeito visual simples de **impacto** no momento da colisão.

---

## 🎮 Como funciona
- O carro se movimenta horizontalmente pela pista.  
- Ele começa em **ré** (`direction = -1`) e segue até bater em uma das paredes.  
- Ao colidir, o carro **inverte a direção** e aciona um **flash vermelho curto**, simulando o impacto.  
- As **luzes traseiras** ficam brancas quando está em ré e vermelhas quando está em frente.  

---

## 🛠️ Executando
1. Acesse o [editor online do p5.js](https://editor.p5js.org/).  
2. Copie o conteúdo do arquivo `sketch.js` deste repositório.  
3. Cole no editor e clique em **Play ▶️**.  
4. O carro começará a se mover automaticamente dentro da pista.

---

## 📂 Estrutura
- `sketch.js` → código principal da simulação.  

---

## 📸 Demonstração
(Adicione aqui um GIF ou captura de tela da simulação rodando)

---

## ✨ Motivação
Este projeto foi criado como um **exercício prático** para fixar conceitos introdutórios de computação gráfica, tornando mais claro como estruturas simples em p5.js podem ser usadas para criar movimento, detectar colisões e simular comportamentos visuais.

---