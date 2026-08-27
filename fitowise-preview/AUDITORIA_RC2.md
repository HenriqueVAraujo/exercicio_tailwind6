# FITOWISE — Auditoria da Landing RC2

## Escopo
Auditoria visual, UX, copy científica/comercial, acessibilidade, SEO de homologação e governança de manutenção.

## Fontes usadas
- Brandbook FITOWISE 2026.
- Briefing da landing page FITOWISE.
- Projeto PIPE-JT Agro — FAPESP, processo 2026/09080-7.
- MVP interno FITOWISE como referência de linguagem visual de dashboard.

## Correções aplicadas

### P0 — Claims e confiança
- Removida a aparência de que métricas do dashboard fossem dados reais.
- Todo mockup operacional foi identificado como demonstrativo.
- Separados: capacidade em validação, arquitetura proposta e visão futura.
- A Fase 1 é apresentada como validação científica, tecnológica e operacional.
- Não foram inventadas métricas de precisão, ROI, clientes, pilotos ou resultados de campo.

### P1 — Identidade e UX
- Removido o “F” genérico da RC1.
- Aplicada a forma do símbolo oficial FITOWISE como base do mark visual.
- Hero reestruturado com o slogan do Brandbook: “Decisões inteligentes começam com dados.”
- Hierarquia, espaçamento, cards, CTA, dashboard e narrativa refinados.
- Responsividade reorganizada para desktop, tablet e celular.

### P1 — Acessibilidade
- Skip link.
- Estados `:focus-visible`.
- Menu móvel com `aria-expanded`, `aria-controls` e `aria-hidden`.
- Respeito a `prefers-reduced-motion`.
- Formulário com labels e validação nativa.

### P1 — Privacidade / homologação
- `noindex,nofollow`.
- Formulário não envia nem persiste dados.
- Aviso visível de homologação.

### P2 — Pendente para produção
- Domínio oficial e canonical.
- Imagem Open Graph final.
- Sitemap/robots de produção.
- Canal real do formulário (CRM/API/e-mail corporativo).
- Política de privacidade/LGPD.
- Repositório dedicado `fitowise-site` e pipeline definitivo de deploy.

## Parecer
**GO para homologação visual e de conteúdo.**

**NO-GO para produção**, exclusivamente porque domínio, canal real de leads, LGPD e pipeline definitivo ainda não foram definidos.