# 🐢 Tartaruga do Mar

Jogo estilo Snake com tema fundo do mar, desenvolvido como PWA (Progressive Web App) para a disciplina de **Programação para Dispositivos Móveis**.

## 🎮 Como Jogar

- Guie a tartaruga para coletar peixinhos e outros frutos do mar
- Evite bater nas paredes ou na própria cauda
- Cada item tem uma pontuação diferente: 🐟 +1, 🦐 +2, 🦑 +3, 🐙 +5

## 🌊 Níveis

| Nível | Velocidade | Comida |
|-------|-----------|--------|
| 🐠 Fácil | Lenta | 3 itens |
| 🐡 Médio | Normal | 2 itens |
| 🦈 Difícil | Rápida | 1 item |

## 📱 Controles

- **Mobile:** D-pad na tela ou deslize o dedo (swipe)
- **Desktop:** Setas do teclado ou WASD
- **Pausa:** Botão ⏸ ou tecla `P`/`Esc`

## 🚀 Instalação como PWA

1. Acesse o link do GitHub Pages
2. No Android (Chrome): toque em **"Adicionar à tela inicial"**
3. No iOS (Safari): toque em **Compartilhar → Tela de Início**
4. O jogo funciona **offline** após a primeira carga!

## 🛠️ Tecnologias

- HTML5 Canvas
- CSS3 (variáveis, animations, backdrop-filter)
- JavaScript puro (sem frameworks)
- PWA (manifest.json + Service Worker)
- LocalStorage para recordes

## 📁 Estrutura

```
turtle-sea-game/
├── index.html        # Jogo completo
├── manifest.json     # Configuração PWA
├── sw.js             # Service Worker (offline)
└── icons/
    ├── icon-192.png  # Ícone PWA
    └── icon-512.png  # Ícone PWA grande
```

## 🌐 Deploy no GitHub Pages

1. Crie um repositório no GitHub
2. Faça upload de todos os arquivos
3. Vá em **Settings → Pages → Branch: main → / (root)**
4. Aguarde alguns minutos
5. Acesse: `https://SEU_USUARIO.github.io/turtle-sea-game`

## 📝 Desenvolvido por

[Seu Nome] — Programação para Dispositivos Móveis
