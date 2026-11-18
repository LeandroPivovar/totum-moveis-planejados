# Totum Móveis Planejados

Site institucional estático (HTML/CSS/JS, sem build). Os arquivos publicados ficam em `dist/`.

## Vercel

Importar a raiz do repositório com framework **Other**. O `vercel.json` define a saída `dist`, sem build nem
instalação. `.vercelignore` exclui metadados locais (`.aroe-crm.json`, `.taste-skill/`).

## Dados usados

Fonte: lead do AROE CRM (`.aroe-crm.json`, cadastrado em 18/11/2026).

| Campo | Valor |
|---|---|
| Nome | Totum Móveis Planejados |
| WhatsApp | (48) 9676-3242 (`wa.me/554896763242`, número do CRM sem alteração) |
| Cidade | Santo Amaro da Imperatriz - SC (listagem pública "Totum Planejados" com o mesmo telefone, (48) 9676-3242) |

## PENDENTE antes de considerar o site completo

- **Endereço exato:** o mapa mostra a cidade de Santo Amaro da Imperatriz - SC como área de atendimento; trocar pelo endereço da loja/fábrica quando confirmado.
- Serviços: os textos partem do nome da empresa e convidam a consultar pelo WhatsApp. Confirmar a lista real.
- Horário de atendimento, logo e fotos reais.
- Número para ligação: só o WhatsApp foi informado; não há botão de ligar.

## Direção visual (Taste)

- Direção sorteada: *One motif (paleta Mint and pink; League Spartan + Figtree)*. Ideia: o canto arredondado de uma porta de armário é o único formato da página (fotos, painéis e cartões).
- Hero no padrão obrigatório Aroe (`.agents/skills/aroe-sites/references/hero.md`), com as exceções do Taste
  documentadas só na hero: palavra do título em itálico na cor de acento, contornos no CTA do topo e no botão
  secundário, dois CTAs, barra transparente e camada escura neutra (marcadas com `taste-skill-ignore`).
- Item interativo: montador de pedido (ambiente, fase do imóvel e medidas) em `#contato`.

## Imagens

Fotos ilustrativas do Unsplash (licença Unsplash, uso comercial permitido). Não mostram trabalhos, equipe nem
estabelecimento da empresa; a galeria informa isso. Créditos em `dist/assets/credits.md` e em
`dist/assets/credits.html` (link no rodapé).
