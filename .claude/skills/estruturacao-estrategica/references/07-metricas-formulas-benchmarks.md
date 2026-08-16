# Métricas, Fórmulas e Benchmarks

Kit matemático da Estruturação Estratégica. Regras de uso:
1. Número calculado é apresentado com a fórmula e os insumos.
2. Benchmark é **faixa de referência para calibrar hipótese**, nunca sentença. Varia por segmento, ticket, região e maturidade — diga isso ao usar. O benchmark que manda é o histórico do próprio cliente evoluindo.
3. Se o dado do cliente estiver muito fora da faixa (para qualquer lado), primeiro desconfie da medição, depois da operação.

---

## 1. Fórmulas essenciais

| Métrica | Fórmula | Leitura de sócio |
|---|---|---|
| **CPC** | Investimento ÷ Cliques | Custo de trazer 1 visitante |
| **CTR** | Cliques ÷ Impressões × 100 | Aderência do anúncio ao público |
| **CPM** | Investimento ÷ Impressões × 1000 | Custo de aparecer; sobe com concorrência e público estreito |
| **Conversão de LP** | Leads ÷ Visitas × 100 | Eficiência do ambiente de conversão |
| **CPL** | Investimento ÷ Leads | Custo de gerar 1 oportunidade |
| **Taxa lead→venda** | Vendas ÷ Leads × 100 | Eficiência comercial (a métrica mais barata de melhorar) |
| **CAC** | (Investimento em mídia + custos de marketing/vendas) ÷ Novos clientes | Custo real de adquirir 1 cliente |
| **Ticket médio** | Receita ÷ Nº de vendas | |
| **ROAS** | Receita atribuída ÷ Investimento em mídia | Retorno bruto da mídia; ROAS mínimo viável = 1 ÷ margem |
| **LTV** | Ticket médio × Compras/ano × Anos de retenção (ou × margem, para LTV de contribuição) | Valor de vida do cliente |
| **LTV:CAC** | LTV ÷ CAC | Saúde do modelo; alvo ≥ 3:1 |
| **Payback de CAC** | CAC ÷ Margem de contribuição mensal do cliente | Em quantos meses o cliente "se paga" |

**ROAS mínimo viável (uso constante):** com margem bruta de 40%, ROAS de equilíbrio = 1 ÷ 0,40 = 2,5. Abaixo disso, cada venda via mídia dá prejuízo — antes de celebrar ROAS 2, confira a margem.

## 2. Funil reverso (referência rápida)

```
Vendas necessárias   = Meta de faturamento ÷ Ticket médio
Leads necessários    = Vendas ÷ Taxa lead→venda
Cliques necessários  = Leads ÷ Conversão da LP
Verba necessária     = Cliques × CPC
Sanidade: CAC implícito (Verba ÷ Vendas) ≤ teto de CAC (30–40% da margem da 1ª venda com recompra; dentro da margem sem recompra)
```

Sempre apresente 3 cenários (conservador/realista/otimista) quando as taxas forem estimadas e não históricas.

## 3. Faixas de benchmark (referência Brasil, PME, para calibrar hipóteses)

### Google Ads (rede de pesquisa)
| Métrica | Faixa típica | Sinal de alerta |
|---|---|---|
| CTR pesquisa | 3–6% | < 2%: anúncio/termo desalinhados |
| Conversão (clique→lead) | 3–10% | < 2%: LP ou oferta com problema |
| Termos irrelevantes | < 10–15% da verba | > 20%: negativação urgente |

### Meta Ads
| Métrica | Faixa típica | Sinal de alerta |
|---|---|---|
| CTR (link) | 0,8–2% | < 0,5%: criativo sem gancho |
| Frequência (aquisição) | 1,5–3 | > 4 com queda de CTR: fadiga, trocar criativo |
| Conversão pós-clique | 2–8% | Depende fortemente do destino (LP vs. WhatsApp) |

### Ambientes de conversão
| Métrica | Faixa típica | Observação |
|---|---|---|
| Conversão LP (lead gen) | 5–15% | Tráfego pago qualificado; < 3% = revisar oferta/página |
| Conversão e-commerce | 1–3% | |
| Abertura de e-mail (base própria) | 20–35% | Régua nova em base engajada fica no topo |
| Clique em e-mail | 2–5% | |
| Resposta a WhatsApp ativo | 30–60% | Base própria, mensagem personalizada |

### Comercial
| Métrica | Referência | Observação |
|---|---|---|
| Tempo de 1ª resposta | ≤ 5–15 min | Após 30 min a chance de contato despenca; responder em minutos multiplica conversão |
| Lead→venda (serviço local) | 10–30% | Ticket alto/consultivo fica na banda baixa |
| Follow-ups até resposta | 3–5 toques | Maioria das vendas sai depois do 2º contato; maioria dos vendedores para no 1º |
| No-show em agendamentos | 20–40% sem confirmação | Confirmação D-1 + 2h antes derruba fortemente |

### Instagram e GMN
| Métrica | Referência | Observação |
|---|---|---|
| Engajamento IG (contas pequenas) | 1–5% por post | Cai com o tamanho da conta; tendência importa mais que o número |
| Avaliações GMN | Superar o concorrente local médio | Volume + recência + resposta a 100% |
| Nota GMN | ≥ 4,5 | Entre 4,0 e 4,5 já perde clique para vizinho melhor avaliado |

## 4. Diagnóstico rápido pelo funil

Sintoma → onde investigar primeiro:
- **Muita impressão, pouco clique** → criativo/anúncio (gancho, oferta) ou público errado.
- **Muito clique, pouco lead** → LP/destino (promessa quebrada, atrito, velocidade) — o anúncio prometeu o que a página não mostra?
- **Muito lead, pouca venda** → comercial (tempo de resposta, qualificação, follow-up) ou lead desqualificado (revisar público e copy do anúncio).
- **Muita venda, pouco lucro** → precificação, margem, CAC alto, mix de produtos.
- **Tudo bom e receita estagnada** → retenção/recompra (V3) e teto de capacidade.
