# Tekoá Impacto

**Calculadora de retorno social (SROI) para Soluções baseadas na Natureza.**

[Abrir a calculadora](https://gustavo-marques-da-silva.github.io/tekoa-impacto/) | [Metodologia](metodologia.md) | [Portfólio](https://gustavo-marques-da-silva.github.io/Portfolio/)

---

## O problema

A [Tekoá](#sobre-a-tekoá) constrói jardins filtrantes, sistemas que tratam água com plantas. O benefício é real: menos esgoto a céu aberto, mais área verde e menos doenças de veiculação hídrica. Mas construtoras e prefeituras decidem com números, e impacto ambiental raramente chega a elas em reais.

## A solução

Uma ferramenta que transforma as características de um projeto em uma estimativa de **SROI** (Social Return on Investment), ou seja, quantos reais de valor social cada real investido gera.

| Entrada | Saída |
|---|---|
| Área do jardim (m²) | Valor social por categoria de benefício |
| Pessoas atendidas | Valor social total, a valor presente |
| Horizonte (anos) | Razão SROI, por exemplo 4,1 : 1 |
| Investimento (R$) | |

## Teoria da Mudança

```
Recursos  →  Atividades  →  Entregas  →  Resultados  →  Impacto
investimento   projeto e     m² de jardim   menos esgoto,   território mais
plantas,       construção    litros         mais área       saudável e
mão de obra                  tratados/dia   verde, menos    resiliente
local                                       doenças
```

## Status

| Versão | O que tem | Situação |
|---|---|---|
| v0.1 | Calculadora com proxies ilustrativas | Publicada |
| v0.2 | Proxies validadas com fontes públicas | Próxima |
| v0.3 | IA que sugere proxies com fonte e monta a Teoria da Mudança | Planejada |
| v0.4 | Relatório de impacto em PDF alinhado aos ODS | Planejada |

> **Atenção:** os valores da v0.1 são ilustrativos e servem só para demonstração. Veja [metodologia.md](metodologia.md).

## Onde entra a IA

- Sugerir proxies financeiras e a fonte pública de cada uma.
- Montar a Teoria da Mudança a partir de uma descrição do projeto em texto livre.
- Escrever o relatório de impacto alinhado aos ODS.

Princípio: **a IA não inventa números.** Toda proxy vem com fonte e passa pela validação de uma pessoa.

## Tecnologia

Um único `index.html` com HTML, CSS e JavaScript, sem dependências e sem servidor. Publicado com GitHub Pages.

Para rodar localmente, basta abrir o `index.html` no navegador.

## Sobre a Tekoá

Negócio de impacto que desenvolve Soluções baseadas na Natureza para água, saneamento e resiliência territorial, a partir de Florianópolis (SC). O produto principal é o jardim filtrante, reconhecido por dois anos seguidos no Prêmio Inovação Social WASH Amanco Wavin.

## Autor

**Gustavo Marques**, fundador da Tekoá e administrador pela UFSC.
[Portfólio](https://gustavo-marques-da-silva.github.io/Portfolio/) | [GitHub](https://github.com/gustavo-marques-da-silva)

## Licença

[MIT](LICENSE)
