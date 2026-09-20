# GymPlan PWA v6.1

Versão completa da GymPlan PWA.

## Inclui
- plano personalizado e divisão por partes do corpo
- sequência "Começar próximo treino"
- explicações detalhadas
- imagens/ilustrações locais dos exercícios
- alternativas clicáveis
- séries, kg, repetições e descanso
- progresso, histórico e backup
- PWA/offline

## Estrutura
```text
gymplan/
├── .nojekyll
├── index.html
├── manifest.webmanifest
├── sw.js
├── README.md
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
└── images/
    └── (SVG dos exercícios)
```


## Imagens reais — v7
A biblioteca visual foi atualizada para usar fotografias reais/demonstrações do Wikimedia Commons em exercícios principais. Se uma foto externa não carregar, a aplicação usa automaticamente a ilustração local correspondente.

As fotos são carregadas da internet; as ilustrações locais continuam incluídas para fallback e uso offline. As licenças variam por imagem (CC BY, CC BY-SA, CC0 ou domínio público).

Fontes principais: Wikimedia Commons — Bench press, Lat pulldown, Leg press, Shoulder press, Plank, Biceps curl, Romanian deadlift, Push-up e Squat/Calf raise. Ver as páginas de origem das imagens antes de redistribuir.
