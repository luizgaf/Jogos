# Jogos

Jogos de navegador feitos com HTML, CSS e JavaScript puro — sem dependências nem build.

Abra o `index.html` no navegador para ver o menu.

| Jogo | Arquivo | Controles |
|---|---|---|
| 2048 | `2048.html` | Setas ou deslizar |
| Cobrinha | `cobrinha.html` | Setas/WASD, deslizar ou botões na tela; espaço pausa |
| Jogo da Memória | `memoria.html` | Clique/toque; 3 níveis |
| Jogo da Velha | `velha.html` | Clique/toque; vs computador (minimax) ou 2 jogadores |
| Campo Minado | `campo-minado.html` | Clique abre, botão direito ou toque longo marca bandeira; 3 níveis |
| Quebra-Tijolos | `tijolos.html` | Mouse, dedo ou setas; espaço/clique lança a bola |
| Blocos | `blocos.html` | ← → movem, ↑ gira, ↓ desce, espaço solta, P pausa; botões na tela no celular |
| Pássaro Voador | `passaro.html` | Clique, toque ou espaço |
| Termo | `termo.html` | Teclado físico ou na tela; palavra do dia ou modo livre |
| Pong | `pong.html` | Mouse, dedo ou ← →; 3 níveis |
| Genius | `genius.html` | Clique/toque ou Q W A S |
| Lig 4 | `lig4.html` | Clique na coluna ou teclas 1–7; vs computador ou 2 jogadores |
| Damas | `damas.html` | Clique na peça e no destino; regras brasileiras; vs computador ou 2 jogadores |
| Sudoku | `sudoku.html` | Clique/setas e 1–9; N alterna notas; Ctrl+Z desfaz; 3 níveis |
| Invasores | `invasores.html` | ← → movem, espaço atira, P pausa; botões na tela no celular |
| Forca | `forca.html` | Teclado físico ou na tela; 8 categorias |

`comum.css` guarda as cores, fontes e componentes compartilhados (com tema escuro automático).
Os recordes ficam salvos no `localStorage` do navegador.

As palavras do Termo (`termo-palavras.js`) foram derivadas do corpus [fserb/pt-br](https://github.com/fserb/pt-br) (licença MIT).

## Publicar no GitHub Pages

Settings → Pages → Branch `main` / pasta raiz. O `index.html` vira a página inicial.
