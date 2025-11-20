Projeto de Análise de Dados: Pesquisa de Sono

Mini Apresentação

Este projeto demonstra uma etapa fundamental no pré-processamento de dados: a transformação de variáveis textuais em numéricas para viabilizar análises quantitativas.

Objetivo Principal

Converter a coluna de faixa etária (idade), que continha dados textuais (ex: "Entre 18 e 40"), em uma nova coluna numérica (idade_numerica), utilizando o ponto médio de cada faixa.

Solução Técnica

Desenvolvemos a função em Python transformar_idade que utiliza lógica condicional (if/elif/else) e expressões regulares para:

1.
Identificar as faixas etárias.

2.
Extrair os limites numéricos.

3.
Calcular o ponto médio (valor representativo).

4.
Aplicar a transformação em todo o dataset usando Series.apply.

Impacto da Transformação

A nova coluna idade_numerica permitiu realizar análises que antes eram impossíveis, como:

•
Cálculo de Correlação: Medir a relação linear entre a idade e as horas de sono (horaSono).

•
Visualização Quantitativa: Gerar gráficos de dispersão (Scatter Plots) para observar tendências.

O resultado completo da análise, incluindo a função e os gráficos, pode ser encontrado no Notebook_Analise_Pesquisa_Sono_Final.ipynb.

