# Diagramas de Sequência do Programa de Indicadores de Fluxo

Estes diagramas foram feitos de acordo com a linguagem de modelagem de software UML. A mesma contém um tipo de diagrama chamada diagrama de sequências, que foi utilizado nesse projeto.

As funções que não tem a palavra plota são as mais importantes pois elas realizam os cálculos e passam o resultado para função que plotam.

## 1 - Funções para um CURSO

### 1.1 - Funções que fazem os cálculos: 

Função (TAP) calcular_taxas_de_permanencia_de_varios_anos_para_um_CURSO_VERSAO_2

Função (TCA) calcular_taxas_de_conclusao_acumulada_de_varios_anos_para_um_CURSO

Função (TDA) calcular_taxas_de_desistencia_acumulada_de_varios_anos_para_um_CURSO


### 1.2 - Funções que utilizam as funções de cálculos para plotar o gráfico

Função (TAP) calcular_e_plotar_grafico_de_taxas_de_permanencia_de_varios_anos_para_um_CURSO

Função (TCA) calcular_e_plotar_grafico_de_taxas_de_conclusao_acumulada_de_varios_anos_para_um_CURSO

Função (TDA) calcular_e_plotar_grafico_de_taxas_de_desistencia_acumulada_de_varios_anos_para_um_CURSO

calcular_e_plotar_grafico_de_indicadores_de_fluxo_de_varios_anos_para_um_CURSO

## 2 - Funções para uma UNIDADE

### 2.1 - Funções que fazem os cálculos: 

Função (TAP) calcular_taxas_de_permanencia_de_varios_anos_para_uma_UNIDADE_VERSAO_2

Função (TCA) calcular_taxas_de_conclusao_acumulada_de_varios_anos_para_uma_UNIDADE

Função (TDA) calcular_taxas_de_desistencia_acumulada_de_varios_anos_para_uma_UNIDADE


### 2.2 - Funções que utilizam as funções de cálculos para plotar o gráfico

Função (TAP) calcular_e_plotar_grafico_de_taxas_de_permanencia_de_varios_anos_para_uma_UNIDADE

Função (TCA) calcular_e_plotar_grafico_de_taxas_de_conclusao_acumulada_de_varios_anos_para_uma_UNIDADE

Função (TDA) calcular_e_plotar_grafico_de_taxas_de_desistencia_acumulada_de_varios_anos_para_uma_UNIDADE

calcular_e_plotar_grafico_de_indicadores_de_fluxo_de_varios_anos_para_uma_UNIDADE


## 3 - Funções Auxiliares

São funções que são usadas pelas outras para realizar uma tarefa:

Função retornar_alunos_ingressados_em_T_para_um_CURSO

Função retornar_alunos_ingressados_em_T_para_uma_UNIDADE
