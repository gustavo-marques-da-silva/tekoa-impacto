# Metodologia

Como a Tekoá Impacto calcula o SROI na versão 0.1.

> **Todos os valores abaixo são ilustrativos.** Eles servem para demonstrar o funcionamento da ferramenta e ainda serão substituídos por proxies com fonte pública (versão 0.2).

## Fórmula

```
SROI = valor social presente ÷ investimento
```

1. **Benefício anual** = soma dos benefícios de cada categoria em um ano.
2. **Atribuição:** desconta-se 20% do benefício, referente ao que aconteceria de qualquer forma ou se deve a outros atores.
3. **Valor presente:** os benefícios de cada ano são trazidos a valor presente com taxa de desconto de 3,5% ao ano.

```
valor presente = Σ (benefício anual × 0,8) ÷ (1 + 0,035)^t,   para t = 1 até o horizonte
```

## Proxies financeiras

| Categoria | Cálculo | Proxy (ilustrativa) | Fonte |
|---|---|---|---|
| Água tratada | pessoas × 0,1 m³/dia × 365 dias | R$ 5 por m³, custo de tratamento convencional evitado | a definir |
| Saúde | pessoas atendidas | R$ 40 por pessoa ao ano, custos de saúde evitados | a definir |
| Área verde e paisagem | área do jardim em m² | R$ 15 por m² ao ano | a definir |

## Parâmetros

| Parâmetro | Valor | Observação |
|---|---|---|
| Consumo de água por pessoa | 100 L/dia | a validar com dados locais |
| Desconto de atribuição | 20% | a calibrar por projeto |
| Taxa de desconto | 3,5% ao ano | a validar |

## Exemplo

Projeto de 20 m², 40 pessoas, 10 anos e investimento de R$ 15.000:

| Item | Valor |
|---|---|
| Água tratada, custo evitado | R$ 60.711 |
| Saúde, custos evitados | R$ 13.307 |
| Área verde e paisagem | R$ 2.495 |
| Desconto de atribuição (20%) | − R$ 15.303 |
| **Valor social presente** | **R$ 61.210** |
| **SROI** | **4,1 : 1** |

## Limitações conhecidas

- As proxies ainda não têm fonte.
- O modelo não considera deslocamento (benefícios que saem de um lugar e vão para outro) nem queda dos benefícios ao longo do tempo (drop-off).
- O consumo de água por pessoa é uma média e não reflete o projeto real.

## Referências de método

- Social Value International, guia de princípios do SROI.
- Teoria da Mudança aplicada a projetos de impacto.
