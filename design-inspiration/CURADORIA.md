# Curadoria de Design — App de Mentoria Agêntica para Residência Médica

**Contexto:** App iOS para acompanhamento contínuo e mentoria por IA de estudantes preparando para a prova de residência médica. Pilares: feedback agêntico, progresso diário, gamificação leve, leitura prolongada.

---

## SELEÇÃO PRINCIPAL

### 1. Mentoring App — Flows e Estrutura

**Fonte:** Dribbble → "mentoring app"

| Shot | Designer | Por que é relevante |
|------|----------|---------------------|
| **Mentees** | Appering | "Learn & grow with help from world-class mentors" — estrutura de mentoria com perfil do mentor, sessões e acompanhamento. Layout limpo, profissional |
| **Pelonous Mentoring** | Pelonous (494 ❤️) | Fluxo completo de mentoring app — onboarding, match mentor/aluno, chat, progresso. Alta qualidade |
| **Ohspace UX Mentoring** | Ohspace UX/UI (100 ❤️, 15.9k views) | Dashboard de mentoring moderno, mobile-first, componentes bem definidos |
| **Synco** | LAIN (156 ❤️, 21.3k views) | Interface de coaching com kanban e tracking contínuo |

**Screenshots salvos:** `dribbble/04-mentoring-app.png`

---

### 2. AI Coaching — Interface do Agente

**Fonte:** Dribbble → "ai coaching app dashboard"

| Shot | Designer | Por que é relevante |
|------|----------|---------------------|
| **AI-Enabled Coaching Platform** | Ruslan Kosinov (44 ❤️, 10.1k views) | Dashboard azul/branco muito limpo. Seção de "AI coaching" com chat + métricas. Exatamente o padrão visual certo |
| **Dark AI Dashboard** | Garrett (4.3k views) | Dark mode para sessões noturnas de estudo. Boa legibilidade, contraste |
| **Emote AI Interface** | Emote PRO (97 ❤️, 15.4k) | Interface conversacional com IA, feedback emocional — relevante para mentoria adaptativa |

**Screenshots salvos:** `dribbble/05-ai-coaching-dashboard.png`

---

### 3. Progress Tracking — Acompanhamento Diário

**Fonte:** Dribbble → "progress tracking app ios"

| Shot | Designer | Por que é relevante |
|------|----------|---------------------|
| **Artspire Fitness** | Artspire PRO (313 ❤️, 53.5k views) | Padrão de "Get Full Guidance / Track Progress / Workout Plans" — adaptável para "Estudar / Progredir / Revisar" |
| **Health Coaching** | Gm Sharrem Hossam (17 ❤️, 10.4k) | Healthcare progress tracking com métricas — visual referência para dashboard de desempenho |
| **Deleau UX Health** | Deleau UX/UI SA (múltiplos, 100+ ❤️ cada) | Série completa de healthcare mobile — consistência visual, tipografia, espaçamento |

**Screenshots salvos:** `dribbble/06-progress-tracking.png`

---

### 4. Clinical / Medical Study App

**Fonte:** Dribbble → "medical study app dashboard mobile"

| Shot | Designer | Por que é relevante |
|------|----------|---------------------|
| **Clinical Trials App** | Purwedli UX/UI (112 ❤️, 40.1k views) | "Clinical Studies" — UI diretamente do contexto médico, com progress, dados estruturados. Altíssima relevância |
| **Medixa** | Bayzid PRO (40 ❤️, 12k views) | App médico verde/moderno, icons de saúde, fluxo de acompanhamento |
| **Phenomenon Studio** | Phenomenon Studio PRO (870 ❤️, 130k views 🔥) | Design mobile escuro/dourado com métricas sofisticadas. Nível de qualidade AAA — referência de execução |
| **Glycoso+** | Vários | App de monitoramento contínuo de saúde — padrão de "acompanhamento 24h" que mapeia direto para mentoria contínua |

**Screenshots salvos:** `dribbble/08-medical-study.png`

---

### 5. Streak & Gamificação de Estudos

**Fonte:** Dribbble → "streak gamification learning app"

| Shot | Designer | Por que é relevante |
|------|----------|---------------------|
| **Muzemind Streak** | Muzemind PRO (119 ❤️, 16.9k views) | Dashboard com streak visual, progresso semanal, metas. Padrão Duolingo aplicado a conteúdo mais sério |
| **Diana Larussa Streak** | Diana Larussa PRO | Purple/dark learning com streak counter e progress rings — visual moderno |
| **LAIN Study App** | LAIN (156 ❤️, 21.3k views) | App de estudos com gamificação leve — verde, clean, focado em hábito diário |
| **Language Learning UI Kit** | Webnum (130+ telas) | Kit completo de UI para aprendizado com todos os estados possíveis — referência técnica |

**Screenshots salvos:** `dribbble/09-streak-gamification.png`

---

## DIREÇÃO VISUAL RECOMENDADA

Com base na curadoria, o app deveria seguir:

### Paleta
- **Primária:** Azul profundo (`#1A3A5C`) ou Navy — remete a seriedade médica
- **Acento:** Verde-teal (`#00C896`) — progresso, saúde, conquista
- **Superfície:** Branco puro + cinza fundo (`#F8F9FA`) para leitura longa
- **Dark mode:** Disponível — estudantes estudam à noite

### Tipografia
- SF Pro Display (nativa iOS) — sem atrito, legível em sessions longas
- Tamanho mínimo 16pt para conteúdo de estudo

### Padrões de UI confirmados pela curadoria
1. **Progress ring/circle** no dashboard principal (% de preparação)
2. **Streak counter** no topo — motivação diária
3. **Chat do mentor IA** com bolhas limpas e avatar do agente
4. **Cards de disciplina** com progresso individual por área (Clínica, Cirurgia, GO, Pediatria, etc.)
5. **Celebration animation** ao completar meta/streak (Lottie)

### Animações (refs nos vídeos)
- Particle burst para conquistas → `SwiftUI Particle Burst [NpSw849Vo3g]`
- Tab bar animado → `Modern Tab Bar 2025 [d6db5m6qjew]`
- Progress ring animado → `Lottie in SwiftUI [_flwprZxig8]`
- Gradient text para título do agente → `Animated Gradient Text [axhFky0MwCI]`

---

## SITES COM ACESSO LIMITADO (precisam login)

| Site | Status | O que tem lá |
|------|--------|--------------|
| **Mobbin** | Precisa login | 300k+ telas reais de apps — vale criar conta |
| **ScreensDesign** | Precisa assinatura | 2.100+ apps com walkthrough em vídeo |
| **Handheld** | Não resolveu | Verificar URL correta |
| **Neuroform.ai** | Não resolveu | Verificar URL correta |

---

## ARQUIVOS LOCAIS

```
staff.khard.ai/
├── videos/swiftui-animations/     # 9 vídeos MP4, ~250MB
│   ├── ✨ SwiftUI Particle Burst... [NpSw849Vo3g].mp4
│   ├── SwiftUI Animations [mzpZNaseAIE].mp4
│   ├── SwiftUI Animations 2025 [MO_mkFO5X68].mp4
│   ├── Animations & Transitions Users Love [O-v21p8nX1U].mp4
│   ├── Custom Tab Bar Animations [pt-0vhQv4Iw].mp4
│   ├── Lottie in SwiftUI [_flwprZxig8].mp4
│   ├── Modern Tab Bar 2025 [d6db5m6qjew].mp4
│   ├── Animated Gradient Text [axhFky0MwCI].mp4
│   └── Top 2026 App Design Trends [VNDq1Q_W1Bs].mp4
└── design-inspiration/
    ├── dribbble/      # 9 screenshots capturados
    ├── awwwards/      # 3 screenshots
    ├── godly/         # 1 screenshot
    └── CURADORIA.md   # este arquivo
```
