# Design System - Aflora Club

Base de referência visual: linguagem moderna/editorial inspirada em `oryzo.ai`, mas com identidade própria da Aflora (lilás + verde-lima + floral orgânico).

## 1) Direção visual

- Estética: editorial orgânica (premium, artesanal e fresca)
- Sensação: produto vivo, delicado e autoral para B2B gastronômico
- Personalidade: técnica no processo + poética na apresentação

## 2) Paleta de cores (marca)

## Cores principais

- `--aflora-lilas-600: #A66BEA;` (cor principal da marca)
- `--aflora-lilas-800: #6D35B3;` (hover, contraste e títulos escuros)
- `--aflora-lima-500: #D7F05B;` (acento da marca e detalhes de destaque)

## Cores de suporte

- `--aflora-pink-500: #F05FA8;` (detalhes florais e elementos promocionais)
- `--aflora-verde-500: #5C8F3A;` (apoio natural/botânico)
- `--aflora-terra-700: #3B2A2A;` (texto forte em fundos claros)

## Neutros

- `--aflora-cream-50: #FFFDF8;` (fundo base)
- `--aflora-cream-100: #F8F4EB;` (blocos alternados)
- `--aflora-gray-600: #6B6872;` (texto secundário)
- `--aflora-ink-900: #19161F;` (texto principal)
- `--aflora-white: #FFFFFF;`

## Cores funcionais

- `--success-whatsapp: #25D366;`
- `--warning: #F4B740;`
- `--error: #E14D5A;`

## 3) Tipografia

## Família sugerida

- Títulos: `Syne` (600/700) -> expressiva, contemporânea, memorável
- Texto/UI: `Manrope` (400/500/600) -> legível e limpa

## Escala tipográfica

- `display`: 56/64, peso 700 (hero desktop)
- `h1`: 44/52, peso 700
- `h2`: 34/42, peso 700
- `h3`: 26/34, peso 600
- `body-lg`: 20/30, peso 400
- `body`: 16/26, peso 400
- `small`: 14/22, peso 500
- `label`: 12/18, peso 600, caixa alta opcional

## 4) Tokens de spacing e layout

- Grid desktop: 12 colunas, `max-width: 1200px`
- Grid mobile: 4 colunas
- Espaçamentos base: `4, 8, 12, 16, 24, 32, 48, 64, 96`
- Raio padrão: `12px`
- Raio card premium: `18px`
- Botão pill: `999px`

## 5) Componentes-base

## Botões

- Primário: fundo lilás 600, texto branco, hover lilás 800
- Secundário: fundo transparente, borda lilás 600, texto lilás 800
- WhatsApp: fundo `--success-whatsapp`, texto branco, ícone WhatsApp

## Card de pack (produto)

- Imagem no topo com proporção 4:3
- Nome do pack + descrição curta + preço
- Meta-info: "entrega D+1", "Porto Alegre"
- CTA fixo no card: `Pedir este pack no WhatsApp`

## Badge

- Badge sazonal: fundo lima 500 + texto ink 900
- Badge B2B: fundo ink 900 + texto cream 50

## 6) Diretrizes de seção

- Hero com fundo claro e acentos lilás/lima
- Packs em grade com fotos vibrantes e cards claros
- Catálogo de espécies em blocos compactos
- Seção de entrega/condições com visual mais informativo (neutro)
- Rodapé com fundo ink 900 e textos em cream

## 7) Acessibilidade e contraste

- Não usar lima puro para texto longo
- Texto principal sempre em `ink-900` ou `white` com contraste AA
- Tamanho mínimo de texto clicável: 14px
- Área mínima de toque: 44x44px

## 8) Estados de interação

- Hover: escurecer 8% no fundo do componente
- Focus: outline 2px em lilás 800 + offset 2px
- Disabled: opacidade 45%, cursor `not-allowed`
- Loading: spinner simples em linha com label

## 9) Variáveis CSS iniciais

```css
:root {
  --aflora-lilas-600: #A66BEA;
  --aflora-lilas-800: #6D35B3;
  --aflora-lima-500: #D7F05B;
  --aflora-pink-500: #F05FA8;
  --aflora-verde-500: #5C8F3A;
  --aflora-terra-700: #3B2A2A;
  --aflora-cream-50: #FFFDF8;
  --aflora-cream-100: #F8F4EB;
  --aflora-gray-600: #6B6872;
  --aflora-ink-900: #19161F;
  --aflora-white: #FFFFFF;
  --success-whatsapp: #25D366;
}
```

## 10) Menu recomendado (desktop)

- Início
- Packs
- Personalizado
- Espécies
- Entrega
- B2B
- Contato
- Botão destacado: `WhatsApp`

## 11) CTA de pack via WhatsApp

Padrão de mensagem:

`Olá! Quero pedir o pack [NOME DO PACK]. Pode me confirmar disponibilidade e valor da entrega para [BAIRRO]?`
