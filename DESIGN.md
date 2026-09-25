---
name: "Yago Duarte Portfolio"
description: "Sites de Alta Conversão e Sistemas Web sob Medida"
colors:
  primary: "#FF6B00"
  primary-hover: "#E66000"
  primary-gradient-end: "#FF8533"
  primary-gradient-hover: "#E66000"
  accent-orange-light: "#FF8533"
  accent-orange-lighter: "#FFA366"
  accent-orange-dark: "#FF6B00"
  secondary: "#FF8533"
  secondary-dark: "#E66000"
  accent-cyan: "#FF6B00"
  step-3-blue: "#0369A1"
  step-3-blue-dark: "#075985"
  whatsapp: "#22C55E"
  whatsapp-hover: "#16A34A"
  whatsapp-light: "#2ED86E"
  whatsapp-text: "#032310"
  whatsapp-dark: "#15803D"
  step-4-green: "#14532D"
  status-live: "#4ADE80"
  badge-amber: "#FBBF24"
  badge-amber-bg: "rgba(245, 158, 11, 0.15)"
  badge-emerald: "#34D399"
  badge-emerald-bg: "rgba(16, 185, 129, 0.12)"
  neutral-bg: "#0F1115"
  neutral-bg-alt: "#14171D"
  neutral-surface: "rgba(20, 23, 29, 0.85)"
  neutral-surface-hover: "rgba(26, 30, 38, 0.95)"
  surface-border: "rgba(156, 163, 175, 0.12)"
  surface-border-hover: "rgba(255, 107, 0, 0.5)"
  neutral-text: "#F8F9FA"
  neutral-text-secondary: "#9CA3AF"
  neutral-text-muted: "#9CA3AF"
  neutral-text-dim: "#9CA3AF"
  footer-bg: "#0A0C0F"
  shimmer-border: "rgba(255, 255, 255, 0.1)"
typography:
  display:
    fontFamily: "Plus Jakarta Sans, sans-serif"
    fontSize: "clamp(32px, 5.5vw, 56px)"
    fontWeight: 800
    lineHeight: 1.15
    letterSpacing: "-0.025em"
  headline:
    fontFamily: "Plus Jakarta Sans, sans-serif"
    fontSize: "clamp(26px, 3.5vw, 40px)"
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "-0.02em"
  headline-sub:
    fontSize: "clamp(28px, 3.5vw, 36px)"
    fontWeight: 700
    lineHeight: 1.2
  title-hero-fluid:
    fontSize: "clamp(16px, 1.8vw, 18px)"
    fontWeight: 600
  title-mobile-hero:
    fontSize: "38px"
    fontWeight: 800
  title-xl:
    fontSize: "30px"
    fontWeight: 700
    lineHeight: 1.3
  title-lg:
    fontSize: "24px"
    fontWeight: 700
    lineHeight: 1.3
  title-md:
    fontSize: "22px"
    fontWeight: 700
    lineHeight: 1.3
  title-sub:
    fontSize: "21px"
    fontWeight: 600
  title:
    fontSize: "20px"
    fontWeight: 700
    lineHeight: 1.3
  title-sm:
    fontSize: "19px"
    fontWeight: 700
    lineHeight: 1.3
  title-xs:
    fontSize: "18px"
    fontWeight: 700
    lineHeight: 1.3
  body-lead:
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.6
  body:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.65
  body-sm:
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.6
  caption:
    fontSize: "14px"
    fontWeight: 500
    lineHeight: 1.5
  caption-sm:
    fontSize: "13px"
    fontWeight: 500
    lineHeight: 1.5
  label:
    fontSize: "12px"
    fontWeight: 700
    letterSpacing: "0.05em"
  sub-label:
    fontSize: "11px"
    fontWeight: 600
    letterSpacing: "0.08em"
  micro-label:
    fontSize: "10px"
    fontWeight: 600
    letterSpacing: "0.1em"
rounded:
  xs: "6px"
  sm: "8px"
  md: "14px"
  lg: "20px"
  full: "9999px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  2xl: "48px"
  section: "110px"
  section-mobile: "68px"
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.neutral-bg}"
    rounded: "{rounded.sm}"
    padding: "16px 32px"
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
    textColor: "{colors.neutral-bg}"
---

# Design System: Yago Duarte Portfolio

## Overview

**Creative North Star: "High-Conversion Graphite & Flame Forge"**

O visual é ancorado em uma atmosfera escura de alto padrão técnico, projetado especificamente para converter visitantes em clientes pagantes através de extrema clareza, autoridade imediata e refinamento tipográfico. Elimina os azuis genéricos saturados da web comum e adota a paleta oficial da marca Yago Duarte:

- **Grafite Escuro (`#0F1115`)**: Base sólida e densa que reduz a fadiga visual e projeta elegância arquitetural.
- **Laranja Chama (`#FF6B00`)**: Energia de conversão precisa, focado em botões de ação (WhatsApp/Proposta) e detalhes de alta vibração.
- **Branco Neve (`#F8F9FA`)**: Títulos de impacto e legibilidade cristalina.
- **Cinza Fumaça (`#9CA3AF`)**: Apoio estrutural calmo, subtítulos, divisores e metadados.

**Key Characteristics:**
- Fundo grafite profundo com grid pontilhado sutil e difusão de luz ambiente âmbar/laranja
- Superfícies em vidro escuro translúcido (*smoked glass*) com bordas táteis
- Botões primários com alto contraste WCAG AAA (texto escuro sobre gradiente laranja)
- Símbolo 3D oficial da marca em destaque com iluminação volumétrica

## Colors

A paleta é concisa, disciplinada e orientada à conversão direta.

### Primary
- **Laranja Chama** (`#FF6B00` / `#FF8533`): A cor protagonista de conversão. Utilizada exclusivamente em botões de ação direta, destaques textuais estratégicos e detalhes da marca.
- **Laranja Chama Hover** (`#E66000`): Estado ativo e de foco tátil dos botões.

### Neutral
- **Grafite Escuro** (`#0F1115`): Fundo principal do website e cor de texto sobre botões laranjas (garante contraste AAA de 6.6:1).
- **Grafite Superfície** (`#14171D` / `rgba(20, 23, 29, 0.85)`): Fundo de seções alternadas e cards de vidro translúcido.
- **Branco Neve** (`#F8F9FA`): Títulos principais (H1, H2, H3), nome da marca e elementos de destaque máximo.
- **Cinza Fumaça** (`#9CA3AF`): Parágrafos, textos descritivos, metadados e bordas sutis.

### Secondary & Accents
- **Verde WhatsApp** (`#22C55E`): Preservado exclusivamente para o botão flutuante e canais de contato direto.
- **Verde Escuro AAA** (`#032310`): Contraste ideal sobre o botão flutuante.

### Named Rules
**The High-Contrast Action Rule.** Todo botão ou elemento com fundo Laranja Chama (`#FF6B00`) DEVE utilizar texto e ícones na cor Grafite Escuro (`#0F1115 !important`) com peso 800. É estritamente proibido utilizar texto branco sobre laranja puro por violar as diretrizes de contraste WCAG AA.

**The Restrained Flame Rule.** O Laranja Chama cobre no máximo 10% da superfície visível de qualquer viewport, preservando seu valor de chamada irresistível ao olhar do cliente.

## Typography

**Display / Headings Font:** Plus Jakarta Sans (`font-family: 'Plus Jakarta Sans', sans-serif`)
**Body Font:** Inter (`font-family: 'Inter', sans-serif`)

### Hierarchy
- **Display Hero** (`font-weight: 800`, `clamp(32px, 5.5vw, 56px)`, `line-height: 1.15`, `letter-spacing: -0.025em`): Promessa central de valor no Hero.
- **Headline de Seção** (`font-weight: 700`, `clamp(26px, 3.5vw, 40px)`, `line-height: 1.2`, `letter-spacing: -0.02em`): Abertura das seções.
- **Title Cards** (`font-weight: 700`, `20px` a `24px`, `line-height: 1.3`): Títulos de serviços e projetos.
- **Body** (`font-weight: 400`, `16px`, `line-height: 1.65`): Textos corridos em Cinza Fumaça (`#9CA3AF`).
- **Label / Tag** (`font-weight: 800`, `11px`, `letter-spacing: 1.2px`, uppercase): Badges de categoria e destaque.

## Layout

- **Container Máximo:** 1200px centralizado com padding lateral de 24px (mobile) a 32px (desktop).
- **Ritmo Vertical:** Padding de seção de 110px no desktop e 68px no mobile.
- **Grid de Cards:** Grid adaptativo de 3 colunas (serviços) e 2 colunas (portfólio), colapsando em coluna única no mobile.

## Elevation & Depth

Profundidade construída com elevação direcional tátil e iluminação ambiente difusa:
- **Shadow Glass:** `0 6px 14px -3px rgba(0, 0, 0, 0.55)` para cards em repouso.
- **Shadow Glass Hover:** `0 10px 14px -4px rgba(0, 0, 0, 0.75)` ao pairar sobre cards interativos.
- **Proibição Absoluta:** Sombras coloridas com offset zero (`box-shadow: 0 0 Xpx color`) são banidas em favor de elevação direcional neutra.

## Shapes

- **Raio de Borda dos Botões:** 8px (`--radius-sm`) para botões padrão; 20px (`--radius-lg`) para botões hero/XL.
- **Raio de Borda dos Cards:** 20px (`--radius-lg`) com cantos arredondados suaves.
- **Raio de Pílulas / Badges:** 9999px (`--radius-full`) para tags de destaque.

## Components

### Buttons
- **Primary:** Fundo gradiente linear (`135deg, #FF6B00 0%, #FF8533 100%`), texto `#0F1115 !important`, peso 800, padding 16px 32px, elevação direcional. Efeito hover com deslocamento de -2px e shimmer suave.
- **Secondary:** Fundo grafite translúcido (`rgba(20, 23, 29, 0.6)`), borda laranja fina (`rgba(255, 107, 0, 0.35)`), texto Branco Neve.

### Cards Glassmorphic
- **Estrutura:** Fundo em `rgba(20, 23, 29, 0.85)` com `backdrop-filter: blur(16px)` e borda sutil de 1px em `rgba(156, 163, 175, 0.12)`.
- **Card em Destaque:** Borda em `rgba(255, 107, 0, 0.45)` com badge superior em degradê Laranja Chama.

### Brand Logo Lockup
- **Símbolo:** Renderização do ícone 3D "YD" com sombra suave alaranjada.
- **Tipografia:** `YAGO` (font-weight: 800) + `DUARTE` (font-weight: 500) em Branco Neve + subtítulo `SITES E SISTEMAS WEB` (11px, Cinza Fumaça).

## Do's and Don'ts

### Do:
- **Do** priorizar a legibilidade estrita WCAG AAA em todas as combinações de texto e fundo.
- **Do** usar o Laranja Chama (`#FF6B00`) para conduzir a ação para o WhatsApp e proposta de valor.
- **Do** manter as superfícies com acabamento grafite sóbrio e transições suaves de 0.2s a 0.35s.
- **Do** garantir que todo texto interativo ou funcional possua no mínimo 11px de tamanho de fonte.

### Don't:
- **Don't** utilizar texto branco sobre botões ou badges alaranjadas (contraste insuficiente).
- **Don't** reintroduzir azuis aeroespaciais genéricos ou tons ciano ciberpunk.
- **Don't** aplicar sombras coloridas com offset zero (`box-shadow: 0 0 ...`).
- **Don't** usar templates ou layouts genéricos sem respeitar a identidade oficial da marca.
