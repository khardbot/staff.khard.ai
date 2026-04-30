# Análise Completa — Neuform.ai

**URL:** https://neuform.ai  
**Categoria:** AI Design Builder (Prompt-to-Production)  
**Tagline:** "Turn one prompt into web, mobile & design systems"  
**Usuários:** 13.1K ativos, 14.9k designs gerados

---

## O que é o Neuform

Neuform é uma ferramenta que transforma um prompt de texto em layouts completos de design (web, mobile, sistemas de design). O conceito central é o **DESIGN.md** — um arquivo de contexto de design que você alimenta à IA para gerar outputs consistentes com sua identidade visual, sem perder o conceito ao escalar para outros formatos.

**Fluxo de uso:**
```
Prompt → Geração paralela de variações → Remix/refinamento → Export (DESIGN.md / HTML / Figma)
```

---

## Screenshots capturados

| Arquivo | Conteúdo |
|---------|----------|
| `01-homepage-fold.png` | Hero com formulário de cadastro + placeholders carregando |
| `02-homepage-loaded.png` | 4 painéis de designs gerados em live rendering |
| `06-pricing.png` | Página de planos |
| `07-faq.png` | FAQ com categorias de dúvidas |
| `08-pricing-features-detail.png` | Onboarding wizard (3 steps) |
| `09-templates.png` | Galeria de templates públicos |
| `10-skills.png` | Biblioteca de prompt skills |
| `11-learn.png` | Página de aprendizado com vídeos |
| `13-templates-scroll1.png` | Tags da galeria (Dashboard, Charts, Bento, etc.) |
| `15-templates-dashboard-tag.png` | Templates filtrados por Dashboard |
| `20-aether-dashboard.png` | Detalhe de template com preview + DESIGN.md + Remix |

---

## Feature 1 — Homepage Live Rendering

**Screenshot:** `02-homepage-loaded.png`

A homepage mostra 4 painéis que carregam designs em tempo real — demonstrando o produto enquanto você está no site. Os designs gerados no momento da captura foram:

- **"Deploy your credential"** — design minimalista branco, credential product
- **"Executive Financial Summary / Capital Overview"** — dashboard financeiro escuro com gráficos, métricas ($412k, $339k, $102k), donut chart
- **"Freelance Website Designer & Growth Partner"** — bold typography, fundo escuro, foto humana
- **"Find a mentor to help you grow your career / Simple steps from curiosity to confidence"** — landing page de mentoring com mentor cards, steps de onboarding

O quarto painel é diretamente relevante para o app de residência — mostra o padrão visual de um produto de mentoria.

---

## Feature 2 — Onboarding Wizard (3 passos)

**Screenshot:** `08-pricing-features-detail.png`

Ao tentar acessar o Workspace, um wizard de personalização aparece:

**Step 1 — "What do you design most?"**
Opções: `Web` · `Mobile` · `Branding` · `Product` · `3D` · `Motion`

**Step 2 — "What tools do you mainly use?"**
Opções: `Figma` · `Illustrator` · `Framer` · `Framer` · e mais

**Step 3 — "Who do you build mostly for?"**
Opções: `Solo` · `Instagram` · `Discord` · `Work` · `More`

**Relevância para o app:** Esse padrão de wizard de segmentação é excelente para o onboarding de estudantes — categorizar por especialidade (Clínica, Cirurgia, GO, Pediatria), nível de preparação e objetivo de prova.

---

## Feature 3 — Pricing / Planos

**Screenshot:** `06-pricing.png`

| Plano | Preço | Prompts/mês | Concurrent | Highlights |
|-------|-------|-------------|------------|------------|
| **Free** | $0 | Sem geração | — | Browse biblioteca pública, iniciar trial |
| **Pro** | $25/mês | 200 | 6 | Uso comercial, privado, Figma handoff, Discord |
| **Max** | $50/mês | 500 | 8 | Para estúdios — tudo do Pro + mais volume |
| **Ultra** | $100/mês | 1.100 | 10 | Agências, always-on production, feedback loops |

Toggle Monthly/Annual disponível (annual = desconto).

---

## Feature 4 — Galeria de Templates

**Screenshots:** `09-templates.png`, `13-templates-scroll1.png`, `15-templates-dashboard-tag.png`

**Stats:** 593 templates públicos · 861 views · 54 favorites · 5 Pro

**Tags disponíveis na sidebar:**
| Tag | Qtd |
|-----|-----|
| Archives | 585 |
| Bento | 315 |
| Effect | 296 |
| Three.js | 297 |
| Modal | 294 |
| Section | 208 |
| Charts | 398 |
| **Dashboard** | **184** |
| Other | 586 |

**Templates mais relevantes para o app:**

| Template | URL | Por que é relevante |
|----------|-----|---------------------|
| Aether Node Dashboard | `/template/aether-node-dashboard` | Dashboard escuro animado, sidebar, métricas, análise |
| Aura Finance - Design Memory | `/template/aura-finance-design-memory` | Pattern de DESIGN.md aplicado a finance = referência |
| Design Inspiration Layout | `/template/design-inspiration-layout` | 139 views, 11 fav — mais popular da galeria |
| Nexus Neural Synchrony | `/template/nexus-neural-synchrony` | Tema neural/IA — estética do agente mentor |
| AuraCore Spatial Visualization | `/template/auracore-spatial-visualization-system` | Dashboard 3D de dados — visualização de progresso |

---

## Feature 5 — Template Detail Page

**Screenshot:** `20-aether-dashboard.png`

Ao abrir um template, a interface mostra:

**Painel esquerdo — Preview interativo:**
- Live preview do design gerado
- Sidebar simulada com navegação (Main Dashboard, Active Report, Security Matrix)
- Visualização de dados (Global Event Matrix com globo 3D)
- Métricas em tempo real simuladas

**Painel direito — Metadata + Ações:**
- Autor (@AKSONVADY)
- Stats: views · favoritos · remixes
- Botão **DESIGN.md** — baixa o arquivo de contexto de design
- Botão **HTML** — baixa o código HTML puro
- Botão **Favorite** — salva na sua biblioteca
- Botão **Remix** — abre o workspace para modificar com prompt
- Overview com tags: `dashboard` · `animated` · `design` · `threads`
- Seção de **Typography** e tokens de cor visíveis abaixo

---

## Feature 6 — Skill Library

**Screenshot:** `10-skills.png`

**Stats:** 63 skills ativas · 10 grupos · 45.6K usos totais

**Top 5 mais usadas:**
1. Border Gradients (5.163 usos)
2. Masked Reveal
3. Aura Asset Images
4. Framed Grid Layout
5. Container Lines

**Categorias de skills:**
`Design System` · `Style` · `Animation` · `Modal` · `Layout` · `Three.js` · `3D` · `Design`

**O que são as Skills:** São prompts pré-definidos (técnicas visuais) que você combina com seu prompt principal. Ex: adicionar "Border Gradients" ao seu prompt gera automaticamente aquele estilo de borda gradiente nos elementos gerados. É uma biblioteca de "tokens de prompt".

**Relevância:** Para o app de residência, skills como `Animation` e `Design System` seriam usados para gerar telas consistentes com identidade visual própria.

---

## Feature 7 — Learn / DESIGN.md

**Screenshot:** `11-learn.png`

**Conceito central do produto:**

> *"Google's open-source DESIGN.md conversation shows why agents need more than a prompt. A clear design file communicates product intent, interaction patterns, and constraints before the next AI edit begins."*

O Neuform é construído ao redor do conceito de **DESIGN.md** — um arquivo de contexto de design (open source do Google) que define:
- Intenção do produto
- Padrões de interação
- Restrições visuais
- Identidade da marca

**Conteúdo da seção Learn:**
| Vídeo | Duração | Tópico |
|-------|---------|--------|
| Why Google's DESIGN.md release matters | ~1m | Contexto histórico |
| Use DESIGN.md to 10x AI landing pages | ~3m | Workflow prático |
| Build a 400+ DESIGN.md landing-page library | ~3m | Escalar |

**Nota:** Um dos vídeos está em **português** — "O Google tomou o DESIGN.md de código aberto. Eis por que isso é importante." — o que indica que há conteúdo em PT-BR na plataforma.

---

## Resumo Executivo — O que o Neuform faz diferente

| Aspecto | Detalhes |
|---------|----------|
| **Entrada** | Prompt de texto + DESIGN.md de contexto |
| **Saída** | HTML puro + DESIGN.md + Figma handoff |
| **Diferencial** | O design "viaja" entre formatos (web → mobile → sistema) sem perder identidade |
| **Modelo de remix** | Qualquer design público pode ser "remixado" com novo prompt, preservando estrutura |
| **Sem código** | Output é HTML semântico, sem framework — pode ser aberto em qualquer editor |
| **Biblioteca pública** | 593 templates remixáveis gratuitos |
| **Skills** | Biblioteca de técnicas visuais como tokens de prompt |

---

## Aplicação ao App de Residência

O Neuform poderia ser usado no projeto de 3 formas:

1. **Gerar variações de tela** — prompt "dashboard de progresso de estudante de medicina com streak counter e gráfico de disciplinas" → gera 6 variações simultâneas para avaliar direção

2. **DESIGN.md do produto** — criar um `DESIGN.md` com a identidade visual do app (cores, tipografia, componentes, tom) e usar como contexto em todas as gerações futuras

3. **Remix de templates** — usar o template "Aether Node Dashboard" como base e remixar com prompt específico para o contexto médico
