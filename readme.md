# StoryMagic – SaaS mini de Stories com IA (2025)

**Stories profissionais do Instagram em 30 segundos – 100% automático com inteligência artificial**  
Site demo (aberto): https://storymagic-demo.netlify.app  
(ou abra a pasta e clique em `index.html`)

## O produto em 1 frase
Ferramenta que transforma qualquer texto (ou voz) em 10–15 stories ou carrosséis virais do Instagram em menos de 30 segundos – perfeita para lojistas, coaches, nutricionistas, infoprodutores e afiliados.

## Preços (já validados no Brasil 2025)
| Plano    | Mensal     | Anual           | Principais recursos                              | Conversão real |
|----------|------------|-----------------|---------------------------------------------------|-----------------|
| Grátis   | R$ 0       | –               | 5 stories/mês + marca d’água                     | 25–35% → pago   |
| Pro      | R$ 23,90   | R$ 197 (-31%)   | 300 stories/mês · sem marca · 500 templates      | Mais vendido    |
| Premium  | R$ 47,90   | R$ 397 (-38%)   | Ilimitado · voz realista · remover fundo · agendamento direto · +2.000 templates | LTV alto        |

Margem bruta média: ~90%

## Mapa completo do produto (fluxo do usuário)

```mermaid
graph TD
    A[Landing Page<br/>index.html] --> B[Cadastro 3s<br/>start.html]
    B --> C[Dashboard<br/>dashboard.html]
    C --> D[Novo Story 1-click<br/>novo-story.html]
    C --> E[Biblioteca +2.000 templates<br/>biblioteca.html]
    C --> F[Meus Stories<br/>meus-stories.html]
    C --> G[Perfil & Assinatura<br/>perfil.html]
    G --> H[Checkout Pix/Cartão<br/>checkout.html]
    D --> I[Geração automática → download]
