# 🦊 Info Kid — Evolua+ Profissões

> Aprenda informática jogando! Série de games educativos para crianças e iniciantes.

[![GitHub Pages](https://img.shields.io/badge/Jogar%20Online-GitHub%20Pages-00c896?style=for-the-badge)](https://seuusuario.github.io/info-kid-evolua)
[![Licença](https://img.shields.io/badge/licença-MIT-blue?style=for-the-badge)](LICENSE)

---

## 🎮 O que é o Info Kid?

O **Info Kid** é um projeto open source da [Evolua+ Profissões](https://evoluaprofissoes.com.br) — escola de cursos profissionalizantes em Mirassol D'Oeste, MT — criado para inserir crianças e iniciantes no mundo da informática de forma **divertida, interativa e gratuita**.

Cada game ensina uma habilidade real do computador: controlar o mouse, usar o teclado, reconhecer peças, navegar na internet e muito mais.

---

## 🗺 Trilhas de Aprendizado

### 🖥 Trilha 1 — Conhecendo o PC
| Game | Habilidade | Status |
|---|---|---|
| 💥 Explode-o-PC! | Identificar peças do computador | 🚧 Em breve |
| 🔍 Caça-Peças | Reconhecer componentes | 🚧 Em breve |
| 🧩 Monta-PC | Montar o computador (drag & drop) | 🚧 Em breve |
| 🔌 Conecta Cabos | Ligar cada cabo na porta certa | 🚧 Em breve |

### 🖱 Trilha 2 — Domando o Mouse
| Game | Habilidade | Status |
|---|---|---|
| 🎯 Clique Certo | Precisão e velocidade de clique | 🚧 Em breve |
| 🌀 Labirinto do Cursor | Coordenação do mouse | 🚧 Em breve |
| 👆 Duplo Clique | Double-click | 🚧 Em breve |
| 📦 Arrastar e Soltar | Drag and drop | 🚧 Em breve |

### ⌨ Trilha 3 — Teclado na Veia
| Game | Habilidade | Status |
|---|---|---|
| 🗺 Labirinto das Setas | Teclas direcionais ← ↑ → ↓ | ✅ Pronto |
| ⭐ Coletor WASD | Teclas WASD | ✅ Pronto |
| 🐍 Cobra do Teclado | Setas direcionais + estratégia | ✅ Pronto |
| 🚀 Nave Espacial | WASD + setas direcionais | ✅ Pronto |
| 🦊 Foxy Jump! | Setas + Espaço (estilo Mario) | ✅ Pronto |
| 🔤 Caça-Letra | Reconhecer teclas individuais | 🚧 Em breve |
| ⚡ Digitação Veloz | Velocidade de digitação | 🚧 Em breve |
| ⚡ Atalhos do Poder | Ctrl+C, Ctrl+Z, etc. | 🚧 Em breve |

### 🌐 Trilha 4 — Mundo Digital
| Game | Habilidade | Status |
|---|---|---|
| 🌐 Navegador Novato | Usar o navegador | 🚧 Em breve |
| 📁 Pasta Certa | Organizar arquivos | 🚧 Em breve |
| 🕵️ Fake ou Real? | Segurança digital | 🚧 Em breve |
| 🔐 Código Secreto | Senhas e lógica | 🚧 Em breve |

---

## 🚀 Como Usar

### Jogar online
Acesse direto pelo GitHub Pages (sem instalar nada):
```
https://seuusuario.github.io/info-kid-evolua
```

### Rodar localmente
```bash
git clone https://github.com/seuusuario/info-kid-evolua.git
cd info-kid-evolua
# Abra o index.html no navegador, ou use um servidor local:
npx serve .
```

### Usar na escola
1. Faça o clone do repositório
2. Coloque os arquivos em um pendrive ou servidor local
3. Abra o `index.html` em qualquer navegador moderno
4. **Funciona offline!** Não precisa de internet na sala de aula

---

## 🛠 Tecnologia

- **HTML5 + CSS3 + JavaScript puro** — sem frameworks, sem dependências
- **Canvas API** — para os games com gráficos
- **Responsivo** — funciona no computador e no celular
- **Acessível** — controles mobile incluídos em todos os games

---

## 📁 Estrutura do Projeto

```
info-kid-evolua/
├── index.html              # Hub principal com todos os games
├── README.md
├── LICENSE
└── games/
    ├── plataforma-fox.html     # 🦊 Foxy Jump! (Mario style)
    ├── snake-teclado.html      # 🐍 Cobra do Teclado
    ├── labirinto-setas.html    # 🗺 Labirinto das Setas
    ├── coletor-wasd.html       # ⭐ Coletor WASD
    ├── nave-wasd.html          # 🚀 Nave Espacial
    ├── explode-pc.html         # 💥 Explode-o-PC! (em breve)
    ├── caca-pecas.html         # 🔍 Caça-Peças (em breve)
    ├── monta-pc.html           # 🧩 Monta-PC (em breve)
    ├── conecta-cabos.html      # 🔌 Conecta Cabos (em breve)
    ├── clique-certo.html       # 🎯 Clique Certo (em breve)
    ├── labirinto-cursor.html   # 🌀 Labirinto do Cursor (em breve)
    ├── duplo-clique.html       # 👆 Duplo Clique (em breve)
    ├── arrastar-soltar.html    # 📦 Arrastar e Soltar (em breve)
    ├── caca-letra.html         # 🔤 Caça-Letra (em breve)
    ├── digitacao-veloz.html    # ⚡ Digitação Veloz (em breve)
    ├── atalhos-poder.html      # ⚡ Atalhos do Poder (em breve)
    ├── navegador-novato.html   # 🌐 Navegador Novato (em breve)
    ├── pasta-certa.html        # 📁 Pasta Certa (em breve)
    ├── fake-real.html          # 🕵️ Fake ou Real? (em breve)
    └── codigo-secreto.html     # 🔐 Código Secreto (em breve)
```

---

## 🤝 Contribuindo

Contribuições são muito bem-vindas! Para adicionar um novo game:

1. Crie o arquivo em `games/nome-do-game.html`
2. Siga o padrão visual dos outros games (mesma paleta, header com link ← Voltar)
3. Adicione o card no `index.html`
4. Abra um Pull Request com a descrição do game e qual habilidade ele ensina

---

## 📄 Licença

MIT — use, modifique e distribua livremente, inclusive em outras escolas!

---

<p align="center">
  Feito com ❤️ pela <strong>Evolua+ Profissões</strong> — Mirassol D'Oeste, Mato Grosso<br>
  <em>"Aprender é brincar de mudar o futuro"</em>
</p>
