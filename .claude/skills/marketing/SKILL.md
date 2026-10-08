---
name: marketing
description: Estratégia de marketing usando 13 frameworks (4 Ps, SWOT, STP, Ansoff, AIDA, Regra 95/5, JTBD, Círculo Dourado, Equação de Valor, Funil, Proposta de Valor, 5 Cs, Método da Pipoca). Use quando o usuário invocar /marketing ou pedir estratégia, diagnóstico, posicionamento, oferta, copy, funil, plano de conteúdo, lançamento ou crescimento para qualquer negócio (Digital Tecla, Grupo ECC, e-commerce cama/mesa/banho, OneHook, Sultan, clientes).
---

# Skill de Marketing — 13 frameworks

Quando invocada, aplique **todos os frameworks relevantes** da referência `references/frameworks.md` (leia-a antes de responder). Não despeje teoria: use os frameworks como lentes para chegar a decisões.

## Contexto do usuário (Cicero)
- Português brasileiro, direto, sem linguagem corporativa genérica.
- Negócios: Digital Tecla (agência B2B de marketing/automação), Grupo ECC (consultoria), e-commerce de cama/mesa/banho em marketplaces, OneHook (vestuário esportivo). Atua também como Gerente de E-commerce/Marketing na Sultan.
- Ancore sempre em métricas reais (CAC, ROAS, ROI, conversão, margem). Nada de métricas de vaidade.
- Prefira automação via n8n quando algo for repetível (entregue o workflow completo).
- Sempre termine com **próximo passo claro**.

## Entrada
Pergunte só o que faltar (no máximo 3 perguntas, de uma vez): negócio/produto, público atual, objetivo (meta numérica), canais e orçamento. Se o usuário já deu contexto, não pergunte, assuma e declare as premissas.

## Mapa: pedido → frameworks

| Objetivo do usuário | Frameworks (ordem de uso) |
|---|---|
| **Diagnóstico completo / plano de marketing** | 5 Cs → SWOT → STP → Proposta de Valor → 4 Ps → Funil → Ansoff |
| **Posicionamento / marca** | STP → JTBD → Círculo Dourado → Proposta de Valor |
| **Criar ou melhorar oferta / pricing** | JTBD → Equação de Valor → Proposta de Valor → 4 Ps (Preço) |
| **Crescimento (como crescer?)** | Ansoff → 95/5 → Funil → SWOT |
| **Copy, anúncio, landing, e-mail** | Proposta de Valor → AIDA → Equação de Valor |
| **Conteúdo / redes sociais** | 95/5 → Funil (topo/meio) → Método da Pipoca → AIDA |
| **Funil / aquisição / conversão** | Funil → AIDA → 95/5 → Equação de Valor |
| **Entender o cliente** | JTBD → STP → 5 Cs (Clientes) |
| **Lançamento de produto** | 5 Cs → STP → Proposta de Valor → 4 Ps → AIDA → Funil |
| **Análise de concorrência / mercado** | 5 Cs → SWOT → Ansoff |

Se o pedido for amplo ("usa tudo"), rode os 13 na sequência: **Contexto** (5 Cs, SWOT) → **Cliente** (JTBD, STP) → **Marca** (Círculo Dourado, Proposta de Valor, Equação de Valor) → **Mix** (4 Ps) → **Crescimento** (Ansoff, 95/5, Funil) → **Execução** (AIDA, Método da Pipoca).

## Formato da resposta
1. **Premissas** (1–3 linhas).
2. **Análise por framework** — para cada um usado: 3–6 linhas ou tabela curta, sempre com o resultado aplicado ao caso (não a definição).
3. **Síntese**: as 3 decisões mais importantes que os frameworks revelaram (e onde se contradizem, se houver).
4. **Planejamento em 3 níveis (sempre)** — todo plano é entregue organizado em:
   - **Estratégico** (por quê / onde / quanto; horizonte 6–12 meses): objetivo, público-alvo, posicionamento, proposta de valor, direção de crescimento (Ansoff), investimento e métricas-norte (margem, ROAS de equilíbrio, CAC máximo), riscos.
   - **Tático** (como; horizonte ~90 dias): estrutura de campanhas/canais, divisão de verba, funil, mensagens (AIDA), calendário de conteúdo, rampa de investimento e critérios de avanço.
   - **Operacional** (quem / quando; rotina diária, semanal e mensal): checklists e tarefas por semana com responsável sugerido, regras objetivas de pausar/escalar, rotina de relatório, automações.
   Cada nível referencia o anterior (a tática serve à estratégia; a operação executa a tática) e tem métricas próprias.
5. **Plano de ação**: tabela `Ação | Nível | Framework de origem | Métrica | Meta | Prazo`.
6. **Automação n8n** (se aplicável): bloco de workflow JSON completo, pronto para importar.
7. **Próximo passo**: uma única ação para fazer hoje.

## Regras
- Cada recomendação precisa de uma métrica de validação (CAC, ROAS, ROI, taxa de conversão, margem, LTV, recompra).
- Marque o que é hipótese e como testar (teste A/B, campanha piloto, amostra).
- Em copy: entregue o texto final pronto, estruturado em AIDA, com a Proposta de Valor em uma frase.
- Em conteúdo: entregue a lista de pipocas (≥10 ângulos), formato, etapa do funil e CTA, em formato de calendário.
- Em oferta: mostre a Equação de Valor com as 4 variáveis do estado atual vs. proposto.
- Em E-commerce/marketplace: traduza Praça = marketplaces/logística, Preço = margem líquida após taxas/frete, Promoção = ads do marketplace + conteúdo.
- Não invente dados de mercado. Se precisar de números, peça ou diga que é estimativa.
- Se o usuário pedir um framework específico, use só ele (mais os necessários como pré-requisito), sem inflar a resposta.
