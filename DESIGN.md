---
name: "Yago Dev Portfolio"
description: "Landing Pages de Alta Conversão para Profissionais e Empresas Locais"
colors:
  primary: "#C0202A"
  secondary: "#2563EB"
  accent-cyan: "#38BDF8"
  whatsapp: "#22C55E"
  neutral-bg: "#07090E"
  neutral-bg-alt: "#0B0E17"
  neutral-surface: "#0D1424"
  neutral-text: "#F8FAFC"
  neutral-text-secondary: "#CBD5E1"
  neutral-text-muted: "#94A3B8"
typography:
  display:
    fontFamily: "Plus Jakarta Sans, sans-serif"
    fontSize: "clamp(28px, 8.5vw, 56px)"
    fontWeight: 800
    lineHeight: 1.15
  body:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.65
rounded:
  sm: "8px"
  md: "14px"
  lg: "20px"
  full: "9999px"
spacing:
  container-max: "1200px"
  section-padding: "110px 0"
  section-padding-mobile: "68px 0"
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.neutral-text}"
    rounded: "{rounded.sm}"
    padding: "16px 32px"
  button-primary-hover:
    backgroundColor: "#A01820"
  button-whatsapp:
    backgroundColor: "{colors.whatsapp}"
    textColor: "{colors.neutral-text}"
    rounded: "{rounded.sm}"
    padding: "16px 32px"
  button-whatsapp-hover:
    backgroundColor: "#16A34A"
---

# Design System: Yago Dev Portfolio

## Overview

**Creative North Star: "The Dark Tech Studio"**

O visual é escuro por padrão, evocando alta tecnologia e acabamento de alto nível (estilo agência premium de tecnologia internacional). Cores e luzes neon (ciano e vermelho) são cirurgicamente aplicadas para direcionar a atenção do usuário.

**Key Characteristics:**
- Fundo preto vácuo com grid e orbes luminosos azuis.
- Tipografia geométrica impactante (Plus Jakarta Sans) contrastando com corpo legível (Inter).
- Transparências de vidro (glassmorphism) com bordas azuis ativas.
- Micro-interações elásticas com transições fluidas.

## Colors

A paleta de cores é composta por um fundo preto profundo de alto contraste, acentos azul e ciano que delimitam a profundidade e a tecnologia, e acento vermelho chumbo elétrico que é o ponto focal máximo da interface.

### Primary
- **Vermelho Chumbo Elétrico** (#C0202A): Usado exclusivamente para ações imediatas (CTAs principais de conversão para o WhatsApp) e badges de maior destaque ("Mais Pedido").

### Secondary
- **Azul Elétrico** (#2563EB): Usado em links secundários, ornamentações de suporte de tecnologia, ícones e estados hover de cartas.

### Neutral
- **Vácuo Espacial Profundo** (#07090E): Fundo principal da página.
- **Preto Sombra do Vácuo** (#0B0E17): Fundo de seções alternadas.
- **Vidro Interestelar** (rgba(13, 20, 36, 0.7)): Preenchimento translúcido de cards e superfícies.
- **Off-White Primário** (#F8FAFC): Texto principal de headlines.
- **Off-White Secundário** (#CBD5E1): Texto de leitura do corpo.
- **Cinza Muted** (#94A3B8): Textos de apoio e descrições menores.

**The Color Rarity Rule.** O acento vermelho chumbo elétrico é reservado exclusivamente para os botões de ação imediata (CTAs) e badges mais importantes, garantindo contraste máximo.

## Typography

**Display Font:** Plus Jakarta Sans (com fallback sans-serif)
**Body Font:** Inter (com fallback sans-serif)

**Character:** O contraste entre a robustez geométrica de Plus Jakarta Sans e a simplicidade de produto digital do Inter confere ao portfólio um ar refinado, limpo e de alta autoridade técnica.

### Hierarchy
- **Display** (Extra Bold (800), clamp(28px, 8.5vw, 56px), 1.15): Título principal do Hero.
- **Headline** (Bold (700), clamp(24px, 7.5vw, 42px), 1.2): Títulos de seções principais.
- **Title** (Bold (700), 18px a 22px, 1.3): Títulos de cards e itens menores.
- **Body** (Regular (400), 16px, 1.65): Texto geral e descrições.
- **Label** (Medium (500), 12px a 14px, 1.1): Tags, badges e pequenos metadados de rodapé.

## Layout

O layout segue um grid flexível e responsivo com contêiner máximo de (1200px). O espaçamento vertical das seções é generoso (110px no desktop e 68px no mobile) para permitir que cada bloco respire e guie a leitura de forma linear e organizada.

## Elevation & Depth

Este sistema utiliza glassmorphism (vidro jateado translúcido) com bordas azuis semitransparentes que mudam de cor no hover para criar profundidade espacial. Não há sombras pretas pesadas na interface.

### Shadow Vocabulary
- **Sombra Glassmorphic** (`0 16px 36px -10px rgba(0, 0, 0, 0.5)` com borda fina): Usada em cards a repouso.
- **Glow Ativo de Hover** (`0 0 28px rgba(37, 99, 235, 0.25)`): Usado ao passar o mouse em elementos interativos de vidro.

**The Glow-Instead-Of-Shadow Rule.** Em fundos escuros, sombras pretas puras não criam profundidade. A profundidade deve ser gerada por brilhos sutis (glows) coloridos e bordas semi-transparentes.

## Shapes

O sistema de formas é baseado em cantos suaves e arredondados, que variam de curvas curtas em botões a curvas mais profundas em contêineres e fotos, estabelecendo um design acolhedor e de acabamento fino.

- **Borda Suave** (8px de raio): Usado em botões e pequenas badges.
- **Canto de Card** (14px e 20px de raio): Usado em contêineres e imagens de projetos.

## Components

### Buttons
- **Shape:** Borda Suave (8px de raio).
- **Primary:** Fundo Vermelho Chumbo Elétrico (#C0202A) com padding de (16px 32px) e texto branco em negrito.
- **Hover / Focus:** Transição de cor para Vermelho Hover (#A01820) e deslocamento vertical elástico de (translateY(-2px)).
- **WhatsApp Button:** Gradiente verde reativo (#22C55E a #16A34A).

### Cards / Containers
- **Corner Style:** Canto de Card (14px ou 20px de raio).
- **Background:** Vidro Interestelar (rgba(13, 20, 36, 0.7)) com desfoque de fundo de (blur(14px)).
- **Border:** Borda fina azul de (1px solid rgba(38, 110, 255, 0.15)) que intensifica no hover.

### Navigation
- **Header Fixo:** Barra superior com desfoque de fundo inteligente e transição de borda no scroll.
- **Menu Hambúrguer:** Transição suave lateral (drawer) para telas móveis.

## Do's and Don'ts

### Do:
- **Do** manter a hierarquia de cores aplicando vermelho apenas a botões primários de chamada direta.
- **Do** usar o contorno de foco em ciano elétrico (#38BDF8) para elementos focados via teclado.
- **Do** garantir que todos os textos secundários mantenham o contraste mínimo de (WCAG 2.1 AA).

### Don't:
- **Don't** misturar o vermelho de ação com o azul de suporte no mesmo componente para evitar poluição visual.
- **Don't** utilizar fundos brancos ou claros em seções para não quebrar a identidade Dark Premium.
- **Don't** usar mais do que uma fonte de display (Syne foi preterida em favor de Plus Jakarta Sans para consistência).
