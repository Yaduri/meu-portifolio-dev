---
name: "Yago Duarte Portfolio"
description: "Sites de Alta Conversão e Sistemas Web sob Medida"
colors:
  primary: "#FF6B00"
  primary-hover: "#FF8533"
  whatsapp: "#22C55E"
  whatsapp-hover: "#2ED86E"
  whatsapp-text: "#032310"
  neutral-bg: "#0F1115"
  neutral-bg-alt: "#14171D"
  footer-bg: "#0A0C0F"
  surface-border: "rgba(156, 163, 175, 0.12)"
  neutral-text: "#F8F9FA"
  neutral-text-secondary: "#9CA3AF"
typography:
  display:
    fontFamily: "Young Serif, Georgia, serif"
    fontSize: "clamp(2.5rem, 6vw, 4.75rem)"
    fontWeight: 400
    lineHeight: 1.04
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "Young Serif, Georgia, serif"
    fontSize: "clamp(1.875rem, 4.2vw, 3.25rem)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.025em"
  headline-closing:
    fontFamily: "Young Serif, Georgia, serif"
    fontSize: "clamp(2rem, 5.2vw, 4rem)"
    fontWeight: 400
  numeral:
    fontFamily: "Young Serif, Georgia, serif"
    fontSize: "2.75rem"
    fontWeight: 400
  statement:
    fontFamily: "Young Serif, Georgia, serif"
    fontSize: "clamp(1.25rem, 2.1vw, 1.625rem)"
    fontWeight: 400
    lineHeight: 1.3
  row-title:
    fontFamily: "Young Serif, Georgia, serif"
    fontSize: "clamp(1.375rem, 2.4vw, 1.875rem)"
    fontWeight: 400
    lineHeight: 1.15
  title:
    fontFamily: "Inter, sans-serif"
    fontSize: "22px"
    fontWeight: 600
    lineHeight: 1.3
  title-sm:
    fontFamily: "Inter, sans-serif"
    fontSize: "18px"
    fontWeight: 600
    lineHeight: 1.3
  body-lead:
    fontFamily: "Inter, sans-serif"
    fontSize: "clamp(16px, 1.8vw, 18px)"
    fontWeight: 400
    lineHeight: 1.65
  body:
    fontFamily: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.65
  body-sm:
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.6
  caption:
    fontSize: "13px"
    fontWeight: 500
  label:
    fontSize: "11px"
    fontWeight: 600
    letterSpacing: "0.08em"
rounded:
  xs: "6px"
  sm: "8px"
  md: "8px"
  full: "50%"
spacing:
  container: "1200px"
  section: "120px"
  section-mobile: "72px"
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.neutral-bg}"
    rounded: "{rounded.sm}"
    padding: "16px 28px"
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
    textColor: "{colors.neutral-bg}"
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.neutral-text}"
    rounded: "{rounded.sm}"
    padding: "14px 28px"
---

# Design System: Yago Duarte Portfolio

## Overview

**Direção: editorial escuro, plano e direto.** Uma página grafite, sem enfeites, em que a tipografia grande faz o trabalho que antes era de cards, ícones e efeitos. O único acento é o laranja da marca, reservado para a ação.

- Fundo grafite único e liso; seções separadas por linhas de 1px.
- Títulos em serifa de peso (Young Serif), texto e interface em Inter.
- Laranja apenas nos botões de ação e em um trecho do título do hero.
- Imagens reais: foto do Yago em preto e branco e capturas dos projetos.
- Sem cards, sombras, gradientes, blur decorativo ou ícones ilustrativos.

## Colors

- **Grafite Escuro** (`#0F1115`): fundo da página e texto sobre botões laranja.
- **Branco Neve** (`#F8F9FA`): títulos e texto de destaque.
- **Cinza Fumaça** (`#9CA3AF`): parágrafos, legendas e metadados.
- **Linha** (`rgba(156, 163, 175, 0.12)`): divisórias de seção e de itens.
- **Laranja Chama** (`#FF6B00`, hover `#FF8533`): botões primários, destaque do título do hero, seleção de texto e hover de links.
- **Verde WhatsApp** (`#22C55E`): exclusivo do botão flutuante e do botão do menu mobile.

**Regra do contraste.** Todo fundo laranja usa texto e ícones em Grafite Escuro (`#0F1115`). Texto branco sobre laranja é proibido.

**Regra da chama contida.** Em qualquer tela deve haver, no máximo, um botão laranja em evidência além do destaque do título.

## Typography

- **Young Serif** (peso único 400): voz de display. Usada em h1, h2, nas frases de dor, nos títulos das linhas de diferenciais e nos numerais do processo. Nunca em itálico.
- **Inter** (400, 500, 600, 700, 800): corpo, títulos de item (h3), botões, navegação e a marca "YAGO DUARTE".

Os títulos usam `text-wrap: balance`; parágrafos longos ficam em até 60 caracteres por linha.

## Layout

- **Ordem das seções:** Hero → Caso Mosca Branca Car → Demonstrações → Dores → Serviços → Por que o Yago (diferenciais e história) → Processo → FAQ → CTA final.
- **Hero:** título em largura total; abaixo, texto e botão à esquerda e a foto com legenda à direita. No mobile a foto vira uma miniatura ao lado da legenda.
- **Caso real:** imagem larga (3:1) seguida de título à esquerda e descrição à direita.
- **Demonstrações:** grade de 3 colunas no desktop, 2 no tablet e fileira deslizável com scroll-snap no mobile.
- **Dores e FAQ:** título fixo à esquerda e lista à direita no desktop.
- **Diferenciais:** linhas de largura total, título à esquerda e texto à direita.
- **Processo:** 4 colunas com numeral em serifa; lista vertical no mobile.
- **Container:** 1200px, com 24px de margem lateral (20px abaixo de 480px).
- **Ritmo vertical:** 120px por seção no desktop e 72px no mobile.

## Elevation & Depth

Layout plano. Não há sombras nem blur em blocos de conteúdo. O único blur é o da barra de navegação ao rolar.

## Motion

- Entrada do hero: título e linha de conteúdo sobem 12px com fade, uma única vez.
- Momento de rolagem único: a imagem do caso Mosca Branca abre de cima para baixo (`clip-path`) quando entra na tela.
- Nenhuma outra seção anima ao rolar. Rolagem nativa do navegador.
- `prefers-reduced-motion` desliga tudo.

## Components

### Buttons
- **Primary:** fundo sólido `#FF6B00`, texto `#0F1115`, peso 700, raio 8px. Hover clareia para `#FF8533`.
- **Secondary:** transparente com borda `rgba(255, 255, 255, 0.18)` e texto Branco Neve. Usado na navegação e em ações secundárias.
- **Text link:** texto Branco Neve sublinhado; o sublinhado fica laranja no hover.

### Blocos de conteúdo
Sem fundo, sombra ou raio. A separação é uma linha superior de 1px. O serviço em destaque usa a linha em Branco Neve e o rótulo "Mais pedido".

### Ícones
SVGs inline de traço 1.75, usados só onde ajudam a leitura (checks das listas, seta de link externo, WhatsApp). Não há ícones decorativos em títulos de bloco.

## Do's and Don'ts

### Do
- Deixar o título grande carregar a seção; um título por bloco, sem rótulo acima.
- Usar imagens reais (projetos e a foto do Yago).
- Manter o laranja raro para que o botão continue chamando atenção.

### Don't
- Não reintroduzir cards, sombras, gradientes, brilhos de fundo ou vidro fosco.
- Não usar pílulas ou "eyebrows" acima dos títulos, nem selos de números grandes.
- Não usar itálico na serifa de display nem texto branco sobre laranja.
- Não adicionar uma terceira família tipográfica.
