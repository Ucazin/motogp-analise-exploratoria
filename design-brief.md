# Design Brief — Apresentação OUV-DF (GitHub Pages + Slides)

- **Superfície / registro:** editorial / data storytelling (registro: marca + dados). Secundário: slides.pdf.
- **Usuário & contexto:** professor/banca avaliando um trabalho acadêmico (desktop/projetor) e colegas; também serve de apoio à apresentação oral do trio. Leitura atenta, ambiente claro.
- **Job principal:** comunicar, com clareza e impacto, **o que o cidadão do DF demanda da Ouvidoria e o que o governo resolve** — fazendo os números falarem.
- **Design read (1 linha):** relatório de dados editorial e institucional — claro, tipografia forte, números grandes como protagonistas, azul-governo + laranja de destaque, motion contido; sério e confiável, mas com impacto visual.
- **Vibe:** institucional · confiável · editorial  ·  **Anti-referências:** dashboard genérico de admin; gradiente roxo→azul; três cards centralizados idênticos; tile de ícone arredondado em todo heading; excesso de animação.
- **Tokens:**
  - Paleta: `#14375a` (azul profundo / títulos-fundo) · `#2a6f97` (azul médio) · `#e8702a` (laranja destaque) · `#2a9d8f` (verde = resolvido) · `#c1121f` (vermelho = não resolvido) · neutros `#0f172a`/`#475569`/`#f1f5f9`/`#ffffff`
  - Tipografia: **Fraunces** (display serif, títulos) + **IBM Plex Sans** (corpo, institucional/dados; tabular nums) · Escala: 1.25
  - Raio: 14px · Sombra: sutil (1 nível) · Espaçamento base: 8px
- **Estilo-skill escolhido:** editorial institucional (via `frontend-design`; minimalismo aplicado).
- **Stack & restrições:** HTML + CSS custom (sem framework de build) + **Chart.js** via CDN para gráficos interativos. GitHub Pages servindo de `/docs`. Acessibilidade **AA** (contraste ≥ 4.5:1). **Mobile-first**, responsivo 320–640 / 640–1024 / ≥1024.
- **Estados obrigatórios:** site estático; gráficos com animação de entrada e tooltip no hover; respeitar `prefers-reduced-motion`.
- **Escopo desta rodada:**
  - **Site (docs/index.html):** Hero (número-âncora 2,15 mi) → Pergunta → Dataset (cards) → Metodologia/Limpeza → Análise (8 gráficos: 4 interativos + 4 imagem, cada um com interpretação) → Conclusões → Footer (integrantes, fonte, repo).
  - **slides.pdf:** redesenho com o mesmo sistema visual.
- **Referências:** sem links; direção definida acima (data storytelling editorial, ex.: relatórios de jornais de dados / Our World in Data, sóbrio).
