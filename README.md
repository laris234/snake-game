# 🐍 Snake Game

Um jogo clássico da cobrinha desenvolvido com **HTML5, CSS3 e JavaScript Vanilla**, com interface moderna, responsiva e inspirada em jogos arcade.

## 🎮 Demonstração

O jogador controla uma cobra em um tabuleiro e deve coletar alimentos para aumentar sua pontuação, evitando colisões com as paredes e com o próprio corpo.

---

## ✨ Funcionalidades

- 🎯 Sistema de pontuação em tempo real
- 🏆 Recorde salvo localmente com LocalStorage
- 🍎 Geração aleatória de alimentos
- 🎨 Interface moderna com tema escuro
- 💀 Tela de Game Over
- 🔄 Reinício rápido da partida
- ⌨️ Controles simples utilizando as setas do teclado
- 📱 Layout centralizado e visual amigável

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Finalidade |
|------------|------------|
| HTML5 | Estrutura da aplicação |
| CSS3 | Estilização da interface |
| JavaScript (Vanilla) | Regras do jogo e interações |
| Canvas API | Renderização gráfica |
| LocalStorage | Armazenamento do recorde |

---

## 📂 Estrutura do Projeto

```text
📦 Snake Game
 ├── cobrinha.html
 └── README.md
```

---

## 🚀 Como Executar

1. Baixe ou clone o repositório:

```bash
git clone https://github.com/seu-usuario/snake-game.git
```

2. Acesse a pasta do projeto:

```bash
cd snake-game
```

3. Abra o arquivo:

```text
cobrinha.html
```

em qualquer navegador moderno.

---

## 🎮 Controles

| Tecla | Ação |
|--------|--------|
| ⬆️ | Mover para cima |
| ⬇️ | Mover para baixo |
| ⬅️ | Mover para esquerda |
| ➡️ | Mover para direita |

---

## 🧠 Regras do Jogo

- 🍎 Coma os alimentos para crescer.
- 📈 Cada alimento aumenta sua pontuação.
- 🚫 Evite bater nas paredes.
- 🐍 Evite colidir com o próprio corpo.
- 💀 Ao colidir, a partida termina.

---

## 🏗️ Arquitetura

O projeto foi desenvolvido utilizando uma arquitetura simples baseada em funções:

- `init()` → Inicializa uma nova partida.
- `spawnFood()` → Gera alimentos aleatoriamente.
- `draw()` → Renderiza todos os elementos.
- `update()` → Atualiza a lógica do jogo.
- `tick()` → Executa o loop principal.
- `startGame()` → Inicia a partida.
- `restart()` → Reinicia o jogo.
- `endGame()` → Finaliza a partida.

---

## 🎨 Características Visuais

- Tema escuro inspirado em interfaces gamer.
- Destaque em verde neon para a cobra.
- Efeitos de brilho utilizando CSS.
- Bordas arredondadas para uma aparência moderna.
- Interface minimalista e intuitiva.

---

## 🔮 Possíveis Melhorias Futuras

- 🎵 Efeitos sonoros
- 🏅 Sistema de conquistas
- 🌎 Ranking online
- 📱 Suporte para dispositivos móveis
- ⚡ Níveis de dificuldade
- 🎨 Temas personalizáveis

---

## 👨‍💻 Autor

Desenvolvido como projeto de estudo para demonstrar conceitos de:

- HTML5 Canvas
- Manipulação do DOM
- Eventos de teclado
- Lógica de jogos 2D
- Armazenamento local com LocalStorage

---

## ⭐ Apoie o Projeto

Se este projeto foi útil para você:

⭐ Deixe uma estrela no repositório.

🐍 Divirta-se jogando!
