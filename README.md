# 🏁 Corrida dos Animais 4D

Jogo de corrida 3D no navegador (Three.js) — 8 mundos, 8 animais lendários e o poder 4D de controlar o tempo!

🎮 **Jogue agora:** https://larandreluizinfo.github.io/corrida-dos-animais-4d/

## 🎯 Objetivo

Corrida com 6 corredores (você + 5 rivais da mesma espécie).

- 🥇🥈🥉 **Chegou em 1º, 2º ou 3º → passa de fase** (desbloqueia o próximo mundo)
- 4º, 5º ou 6º → volta e tenta de novo!
- Vença os 8 mundos para ser o **Campeão 4D** 🏆

## 🌍 Os 8 mundos

| # | Cenário | Animal | Obstáculo | Turbo |
|---|---------|--------|-----------|-------|
| 1 | 🌳 Floresta Amazônica | 🐆 Onça-Pintada | Tronco caído | 🍌 Banana |
| 2 | 🌺 Floresta Tropical | 🦜 Arara-Azul | Arbusto florido | 🥭 Manga |
| 3 | 🌊 Fundo do Mar | 🐬 Golfinho | Coral rosa | ⭐ Pérola |
| 4 | 🏜️ Deserto do Saara | 🐪 Camelo | Cacto | 💧 Água fresca |
| 5 | 🌾 Campo Verde | 🐎 Cavalo | Fardo de feno | 🥕 Cenoura |
| 6 | 🚀 Espaço Sideral | 🐒 Macaco Astronauta | Meteoro | 🌟 Energia estelar |
| 7 | 🌋 Subsolo Vulcânico | 🦔 Tatu-Bola | Rocha de lava | 💎 Cristal |
| 8 | ❄️ Antártida Final | 🐧 Pinguim Imperador | Bloco de gelo | 🐟 Peixe |

## 🕹️ Controles

| Tecla | Ação |
|-------|------|
| ⬆️ / W (segurar) | Correr / acelerar |
| ⬅️ ➡️ / A D | Trocar de raia |
| ESPAÇO | Pular obstáculos |
| SHIFT | ⚡ Poder 4D (desacelera o tempo dos rivais) |

📱 No celular há botões touch na tela.

## ✨ O que é o 4D?

Gráficos 3D (Three.js) + 4ª dimensão = **tempo**:

- SHIFT ativa o BOOST 4D e deixa os rivais em câmera lenta
- Câmera com FOV que abre com a velocidade (efeito warp)
- No Espaço a gravidade é menor e o pulo é mais alto!

## 🚀 Como rodar localmente

É só um arquivo estático, sem build:

```bash
# opção 1: abrir direto
start index.html        # Windows
open index.html         # macOS
xdg-open index.html     # Linux

# opção 2: servidor local (recomendado)
npx serve .
# ou
python -m http.server 8000
```

Depois acesse http://localhost:8000 (ou a porta indicada).

## 🛠️ Tecnologias

- [Three.js](https://threejs.org/) via CDN (gráficos 3D)
- HTML + CSS + JavaScript puro, um único `index.html`
- Progresso salvo em `localStorage` (fases desbloqueadas)
- Hospedado no **GitHub Pages** a partir da branch `main`

## 📁 Estrutura

```
.
├── index.html   # o jogo completo
└── README.md    # este arquivo
```

Divirta-se e boa corrida! 🐆🐬🐧
