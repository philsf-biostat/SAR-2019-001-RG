---
title: "Análise exploratória de associações em dados de pacientes com pubalgia atlética no Brasil"
author: '**De:** Felipe Figueiredo **Para:** Rodrigo Góes'
date: '**Data: ** dd/mm/aaaa'
output:
  html_document:
    fig_caption: yes
    fig_height: 6
    fig_width: 6
    keep_md: yes
    number_sections: yes
    toc: yes
  pdf_document:
    number_sections: yes
    toc: yes
  word_document:
    fig_caption: yes
    fig_height: 6
    fig_width: 6
    reference_docx: misc/style.docx
    toc: yes
subtitle: 'RELATÓRIO: analise_dados_RG_2019-v01'
toc-title: "Sumário"
---



---

**Histórico do documento**


| Versão |   Alterações   |
|:------:|:--------------:|
|   01   | Versão inicial |

---

<!-- # Assinaturas -->

<!-- ```{r, echo=FALSE} -->
<!-- sig.field <- "__________________________" -->
<!-- date.field <- "_____________" -->
<!-- Stat <- c("Elaborador", "Felipe Figueiredo", "Bioestatístico", sig.field, date.field) -->
<!-- Reviewer <- c("Revisado por", "", "", sig.field, date.field) -->
<!-- Approver <- c("Verificado por", "", "", sig.field, date.field) -->
<!-- Final.Approver <- c("Aprovação final", "", "", sig.field, date.field) -->

<!-- sigs <- rbind( -->
<!--   Stat -->
<!--   , Reviewer -->
<!--   , Approver -->
<!--   , Final.Approver -->
<!--   ) -->
<!-- rownames(sigs) <- NULL -->
<!-- colnames(sigs) <- c("Papel", "Nome", "Função", "Assinatura", "Data") -->

<!-- pander(sigs, split.cells = c(9, 14, 14, 16, 8), split.table = Inf) -->
<!-- # kable(sigs) -->
<!-- ``` -->

# Lista de abreviaturas

# Introdução

## Objetivos

## Recepção e tratamento dos dados

# Metodologia



Esta análise foi realizada utilizando-se o software `R` versão 3.4.4.



# Resultados



## Avaliação dos esportes mais praticados pelos atletas com pubalgia

### Associação com desfecho cirúrgico e movimentos em que sente dor


|      &nbsp;       |  FUTEBOL  |  CORRIDA  | MUSCULAÇÃO |  OUTROS   |   p   | test  |
|:-----------------:|:---------:|:---------:|:----------:|:---------:|:-----:|:-----:|
|       **n**       |    148    |    81     |     70     |    114    |       |       |
| **CIRURGIA (%)**  |  8 (5.4)  |  4 (4.9)  | 10 (14.3)  | 19 (16.7) | 0.005 | exact |
|       **n**       |    363    |    90     |     33     |    161    |       |       |
| **MOVIMENTO (%)** |           |           |            |           | 0.007 |       |
|       **1**       | 88 (24.2) | 13 (14.8) |  7 (22.6)  | 42 (26.2) |       |       |
|       **2**       | 52 (14.3) | 28 (31.8) |  8 (25.8)  | 29 (18.1) |       |       |
|       **3**       | 80 (22.0) | 25 (28.4) |  7 (22.6)  | 34 (21.2) |       |       |
|       **4**       | 46 (12.7) | 10 (11.4) |  4 (12.9)  | 26 (16.2) |       |       |
|       **5**       | 97 (26.7) | 12 (13.6) |  5 (16.1)  | 29 (18.1) |       |       |

## Avaliação do tempo até o diagnóstico

### Associação com os exames físicos, nível esportivo e idade


|          &nbsp;           |  <= 90d   |   > 90d   |   p   | test  |
|:-------------------------:|:---------:|:---------:|:-----:|:-----:|
|           **n**           |    118    |    127    |       |       |
|        **EF1 (%)**        | 33 (28.0) | 44 (34.6) | 0.274 | exact |
|        **EF2 (%)**        | 94 (79.7) | 94 (74.0) | 0.364 | exact |
|        **EF3 (%)**        | 83 (70.3) | 83 (65.4) | 0.416 | exact |
|        **EF4 (%)**        | 93 (78.8) | 97 (76.4) | 0.759 | exact |
|        **EF5 (%)**        | 72 (61.0) | 81 (63.8) | 0.693 | exact |
|        **EF6 (%)**        | 44 (37.3) | 58 (45.7) | 0.197 | exact |
|        **EF7 (%)**        | 76 (64.4) | 92 (72.4) | 0.215 | exact |
|        **EF8 (%)**        | 36 (30.5) | 35 (27.6) | 0.673 | exact |
|        **EF9 (%)**        | 13 (11.0) | 24 (18.9) | 0.108 | exact |
|       **EF10 (%)**        | 59 (50.0) | 61 (48.0) | 0.799 | exact |
|           **n**           |    118    |    127    |       |       |
|       **NIVEL (%)**       |           |           | 0.883 | exact |
|     **PROFISSIONAL**      | 20 (16.9) | 24 (18.9) |       |       |
|     **RECREACIONAL**      | 88 (74.6) | 94 (74.0) |       |       |
| **UNIVERSITÁRIO/ESCOLAR** | 10 ( 8.5) | 9 ( 7.1)  |       |       |
|           **n**           |    118    |    127    |       |       |
|       **IDADE (%)**       |           |           | 0.878 | exact |
|       **< 25 anos**       | 20 (16.9) | 25 (19.7) |       |       |
|      **25-40 anos**       | 70 (59.3) | 72 (56.7) |       |       |
|       **> 40 anos**       | 28 (23.7) | 30 (23.6) |       |       |
Table: **Tabela xx** Associação entre o tempo até o diagnóstico e os exames físicos, nível esportivo e idade.

## Avaliação dos locais de dor

### Associação com tempo até o diagnóstico e a modalidade esportiva

<!-- # Exceções e Desvios do teste -->

# Discussão

# Conclusões


# Referências

# Apêndice

