# WinPSPortal — Windows Desktop Portal for Sony PSP

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Platform: Sony PSP](https://img.shields.io/badge/Platform-Sony%20PSP-003791.svg)](https://playstation.com/)
[![Tech: HTML5 & JavaScript](https://img.shields.io/badge/Tech-HTML%20%2F%20JS%20%2F%20CSS-E34F26.svg)]()

Portal retrô no estilo Windows Desktop com catálogo integrado de jogos clássicos em JavaScript e mini-aplicativos, especialmente otimizado para o navegador web do **PlayStation Portable (Sony PSP)**.

---

## 🕹️ Catálogo de Jogos Embutidos

- **Campo Minado (Minesweeper):** Tabuleiros customizáveis, contagem de minas e cronômetro.
- **Tetris:** Modos de pontuação com rotação de blocos adaptada ao controle direcional.
- **Pong:** Jogo clássico de tênis arcade com placar.
- **Poker 5 Card Stud & Draw Poker:** Simulação de apostas e baralho clássico.
- **Yahtzee:** Jogo de dados com tabela oficial de pontuação.
- **Jogo da Velha (Tic-Tac-Toe):** Partidas rápidas com interface visual retrô.
- **Xadrez e Damas (Checkers & Chess):** Tabuleiro para jogos estratégicos.
- **Jogos Adicionais:** Conecte 4, Resta Um (Pegs), Batalha Naval (Battleship), Forca (Hangman), Torres de Hanói e Jogo da Memória.

---

## 🛠️ Mini-Aplicativos e Utilitários

- **Calculadora:** Operações aritméticas básicas e funções de memória.
- **Conversor de Unidades:** Conversor métrico e de temperatura.
- **Editor de Texto:** Bloco de notas simples para anotações rápidas.
- **Calendário e Cronômetro:** Controle de datas e contagem progressiva de tempo.
- **Paint / Desenho:** Tela para esboços e desenhos via cursor.

---

## 🚀 Como Executar

### No PlayStation Portable (PSP)
1. Conecte o PSP ao computador via cabo USB.
2. Copie os arquivos da pasta `src/` para o Memory Stick em:
   ```text
   ms0:/PSP/COMMON/portal/
   ```
3. No PSP, abra o **Navegador de Internet**.
4. Digite no endereço:
   ```text
   file:/PSP/COMMON/portal/index.htm
   ```

### Em Navegadores Modernos (PC / Celular)
Abra diretamente o arquivo `src/index.htm` em qualquer navegador moderno ou inicie um servidor web local:
```bash
npx serve src
```

---

## 📄 Licença

Distribuído sob a licença [MIT](LICENSE).
