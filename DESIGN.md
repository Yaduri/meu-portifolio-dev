---
name: "Yago Dev Portfolio"
description: "Sites de Alta Conversão e Sistemas Web sob Medida"
colors:
  primary: "#C0202A"
  primary-hover: "#A01820"
  primary-gradient-end: "#D82631"
  primary-gradient-hover: "#B91C1C"
  accent-red-light: "#FF6B72"
  accent-red-lighter: "#FFA3A8"
  accent-red-dark: "#9B121B"
  secondary: "#2563EB"
  secondary-dark: "#1D4ED8"
  accent-cyan: "#38BDF8"
  step-3-blue: "#0369A1"
  step-3-blue-dark: "#075985"
  whatsapp: "#22C55E"
  whatsapp-hover: "#16A34A"
  whatsapp-light: "#4ADE80"
  whatsapp-text: "#032310"
  whatsapp-dark: "#15803D"
  step-4-green: "#14532D"
  status-live: "#4ADE80"
  badge-amber: "#FBBF24"
  badge-amber-bg: "rgba(245, 158, 11, 0.15)"
  badge-emerald: "#34D399"
  badge-emerald-bg: "rgba(16, 185, 129, 0.12)"
  neutral-bg: "#07090E"
  neutral-bg-alt: "#0B0E17"
  neutral-surface: "rgba(13, 20, 36, 0.7)"
  neutral-surface-hover: "rgba(19, 29, 53, 0.85)"
  surface-border: "rgba(38, 110, 255, 0.15)"
  surface-border-hover: "rgba(38, 110, 255, 0.4)"
  neutral-text: "#F8FAFC"
  neutral-text-secondary: "#CBD5E1"
  neutral-text-muted: "#94A3B8"
  neutral-text-dim: "#94A3B8"
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
  title-display-max:
    fontSize: "40px"
    fontWeight: 800
    lineHeight: 1.2
  title-display-mobile:
    fontSize: "38px"
    fontWeight: 800
    lineHeight: 1.2
  title-display-sm:
    fontSize: "36px"
    fontWeight: 800
    lineHeight: 1.2
  title-xl:
    fontSize: "32px"
    fontWeight: 700
    lineHeight: 1.3
  title-hero-sub:
    fontSize: "28px"
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
  title-section-sub:
    fontSize: "21px"
    fontWeight: 700
    lineHeight: 1.3
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
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.6
  body:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.65
  body-alt:
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.6
  body-sm:
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.5
  caption:
    fontSize: "13px"
    fontWeight: 500
    lineHeight: 1.4
  caption-sm:
    fontSize: "12px"
    fontWeight: 500
    lineHeight: 1.4
  badge:
    fontSize: "11px"
    fontWeight: 600
    lineHeight: 1.2
  micro:
    fontSize: "10px"
    fontWeight: 500
    lineHeight: 1.2
  icon-lg:
    fontSize: "30px"
    lineHeight: 1
  icon-md:
    fontSize: "24px"
    lineHeight: 1
  icon-sm:
    fontSize: "20px"
    lineHeight: 1
rounded:
  pill: "2px"
  xs: "6px"
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
    backgroundColor: "{colors.primary-hover}"
  button-whatsapp:
    backgroundColor: "{colors.whatsapp}"
    textColor: "{colors.whatsapp-text}"
    rounded: "{rounded.sm}"
    padding: "16px 32px"
  button-whatsapp-hover:
    backgroundColor: "{colors.whatsapp-light}"
---

# Design System: Yago Dev Portfolio

## Overview

**Creative North Star: "The Dark Tech Studio"**

O visual é escuro por padrão, evocando alta tecnologia, autoridade técnica e refinamento de alto nível. Projetado para profissionais autônomos, clínicas, consultorias e empresas locais que buscam **Sites de Alta Conversão** e **Sistemas Web sob Medida** (ex: gestão de estoque automotivo para concessionárias, mini lojas e catálogos dinâmicos).

**Key Characteristics:**
- Fundo vácuo espacial profundo com iluminação direcional sóbria.
- Tipografia geométrica expressiva (Plus Jakarta Sans) contrastando com corpo legível e funcional (Inter).
- Transparências de vidro (glassmorphism) com bordas azuis discretas e elevação realista.
- Micro-interações elásticas em hover e scroll suave desacelerado com Lenis e GSAP ScrollTrigger.
- Zero halos cromáticos de IA: profundidade obtida por elevação direcional neutra.

## Colors

A paleta de cores é calibrada para atender com folga às diretrizes de contraste WCAG AA e AAA:

### Primary
- **Vermelho Chumbo Elétrico** (`#C0202A` / `#D82631`): Reservado para ações imediatas (CTAs principais de conversão para o WhatsApp) e selos de alto destaque ("Mais Pedido").
- **Tons de Apoio:** `#FF6B72`, `#FFA3A8`, `#9B121B`.

### Secondary & Tech Accents
- **Azul Elétrico** (`#2563EB`): Utilizado em ornamentações de tecnologia, etapas de processo e links de apoio.
- **Ciano Elétrico** (`#38BDF8`): Utilizado em ícones editoriais de diferenciais, tags técnicas e anéis de foco acessível `:focus-visible`.
- **Azul Oceano** (`#0369A1` / `#075985`): Utilizado no gradiente da etapa 3 do processo.

### Conversion & Status
- **Verde WhatsApp** (`#22C55E` / `#16A34A`): Ação de contato direto.
- **Verde Escuro Alto Contraste** (`#032310`): Texto e ícone sobre o verde WhatsApp (proporção de contraste **8.5:1, nível AAA**).
- **Verde Esmeralda** (`#34D399`): Badge de E-commerce Ágil e selos de velocidade.
- **Amarelo Âmbar** (`#FBBF24`): Estrelas de avaliação e badges de conversão.

### Neutral
- **Vácuo Espacial Profundo** (`#07090E`): Fundo principal da página.
- **Preto Sombra do Vácuo** (`#0B0E17`): Fundo de seções alternadas.
- **Vidro Translúcido** (`rgba(13, 20, 36, 0.7)`): Preenchimento de superfícies e cards.
- **Off-White Primário** (`#F8FAFC`): Títulos principais (contraste > 14:1).
- **Off-White Secundário** (`#CBD5E1`): Texto de leitura do corpo.
- **Cinza Muted Alto Contraste** (`#94A3B8`): Textos de apoio, descrições menores e notas secundárias (contraste **6.2:1**, WCAG AA).

## Typography

**Display Font:** Plus Jakarta Sans (com fallback sans-serif)  
**Body Font:** Inter (com fallback sans-serif)

**Ritmo e Rastreamento (Tracking):**
- Títulos Display: `-0.025em` com `text-wrap: balance` para prevenir quebras isoladas de linha.
- Títulos de Seção: `-0.02em` com `text-wrap: balance`.
- Subtítulos e Parágrafos: `text-wrap: pretty` para fluxo harmonioso.

### Hierarchy
- **Display** (Extra Bold (800), `clamp(32px, 5.5vw, 56px)`, 1.15): Título principal do Hero.
- **Headline** (Bold (700), `clamp(26px, 3.5vw, 40px)`, 1.2): Títulos de seções principais.
- **Title-XL** (Bold (700), 32px, 1.3): Títulos de destaque.
- **Title-LG** (Bold (700), 24px, 1.3): Números das etapas e cabeçalhos intermediários.
- **Title-MD** (Bold (700), 22px, 1.3): Título do box de proposta.
- **Title** (Bold (700), 20px, 1.3): Títulos de cards de serviços.
- **Title-SM** (Bold (700), 19px, 1.3): Nome no card Sobre Mim.
- **Title-XS** (Bold (700), 18px, 1.3): Títulos de diferenciais e perguntas do FAQ.
- **Body-Lead** (Regular (400), 17px, 1.6): Subtítulos em destaque e botão principal XL.
- **Body** (Regular (400), 16px, 1.65): Texto geral, descrições e itens de lista.
- **Body-Alt** (Regular (400), 15px, 1.6): Textos de cards compactos.
- **Body-SM** (Regular (400), 14px, 1.5): Textos de apoio nos passos do processo.
- **Caption** (Medium (500), 13px, 1.4): Selo de disponibilidade live no hero.
- **Caption-SM** (Medium (500), 12px, 1.4): Metadados de portfólio e tags.
- **Badge** (Semi-Bold (600), 11px, 1.2): Tags especiais de serviço e status.
- **Micro** (Medium (500), 10px, 1.2): Rótulos de métricas compactas.

## Layout

O layout segue um grid fluido e flexível com largura máxima de `1200px`. O espaçamento vertical das seções é generoso (`110px` no desktop e `68px` no mobile) para garantir respiro e escaneabilidade em qualquer dispositivo.

## Elevation & Depth

O sistema de profundidade baseia-se em elevações direcionais suaves com contraste natural contra o fundo escuro, evitando halos cromáticos saturados ou borrões artificiais.

### Shadow Vocabulary
- **Sombra Glassmorphic:** `0 10px 24px -6px rgba(0, 0, 0, 0.5)` em repouso.
- **Sombra Glassmorphic Hover:** `0 16px 32px -8px rgba(0, 0, 0, 0.7)` ao interagir com cards.
- **Elevação Primária de Botão:** `0 8px 20px -4px rgba(0, 0, 0, 0.6), inset 0 1px 0 rgba(255, 255, 255, 0.25)`.
- **Elevação Flutuante WhatsApp:** `0 10px 24px -4px rgba(0, 0, 0, 0.6)`.

## Shapes

- **Micro:** 2px (pontos de pulso e detalhes).
- **Borda Suave:** 6px / 8px (botões e selos compactos).
- **Canto de Card:** 14px / 20px (contêineres de vidro, cards de serviços e imagens de projetos).
- **Círculo / Pill Completo:** 9999px (botão flutuante, pílulas de status e tags).

## Components

### Buttons
- **Primary:** Gradiente vermelho chumbo elétrico (`#C0202A` a `#D82631`) com efeito sutil de shimmer, elevação direcional e texto branco em negrito.
- **WhatsApp:** Gradiente verde reativo com texto `#032310` de altíssimo contraste (nível AAA).
- **Secondary Glass:** Vidro semitransparente com borda ciano/azul e backdrop blur.

### Cards & Features
- **Serviços:** Três pilares (Sites de Conversão, Sistemas de Estoque, Mini Lojas) com badges específicos, listas de benefícios escaneáveis e CTAs dedicados.
- **Diferenciais:** Diagramação editorial alinhada à esquerda com ícones livres em fluxo natural, substituindo caixas genéricas centralizadas.
- **FAQ:** Expansão via CSS Grid puro (`grid-template-rows: 0fr -> 1fr`) garantindo zero reflow de layout.

## Do's and Don'ts

### Do:
- **Do** manter a hierarquia clara entre Sites de Conversão e Sistemas Web sob medida.
- **Do** utilizar `#032310` em textos sobre o verde WhatsApp para garantir contraste acessível AAA.
- **Do** usar elevação direcional com sombras neutras em vez de brilhos de contorno neon.
- **Do** preservar `text-wrap: balance` nos títulos para manter tipografia visualmente estável.

### Don't:
- **Don't** prometer "0 mensalidade" de forma genérica, pois sistemas web exigem infraestrutura em nuvem e manutenção técnica.
- **Don't** utilizar halos cromáticos de offset zero (`box-shadow: 0 0 Xpx`).
- **Don't** aninhar cards dentro de cards para evitar ruído visual desnecessário.
