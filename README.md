# Análise da Inadimplência dos Clientes de Cartão de Crédito

<img src='./cartao.jpeg' width=450>

- **Equipe:**
    - Danilo Pontes;
    - Jonatha Silva;
    - Marcos Antonio;
    - Sanderson Rawan;
    - Saulo Bernardo;
    - Wiliams Alves.


### Contexto

A empresa MBA Data Science e IA está planejando lançar um cartão de crédito com benefícios e vantagens, com foco em consumidores pessoa fisica. Para que o lançamento seja bem-sucedido, é necessário entender o perfil de endividamento dos potenciais clientes e como a população está lidando com o uso de cartões de crédito, especialmente no que diz respeito à inadimplência e ao grau de endividamento.

### Problema

No inicio do ano de 2024 a empresa XYZ planeja lançar um cartão de crédito, para que a empresa tenha sucesso no seu novo produto, precisa entender o cenário de endividamento, inadimplência e o risco de perda de diferentes perfis de clientes, a fim de calibrar suas ofertas e estratégias de mitigação de risco. A análise abaixo foca em três dimensões principais:

1. **Endividamento**: Refere-se ao valor total da carteira de crédito em relação ao valor inadimplente. A empresa precisa entender qual é o nível de endividamento dos clientes com cartão de crédito, especialmente em relação aos tipos de ocupação e porte de cliente.

2. **Inadimplência**: Este indicador é fundamental para a empresa identificar potenciais problemas de crédito e definir limites e condições mais seguras para seu novo produto.

3. **Ativos Problemáticos**: Relacionados à quantidade de crédito que está em risco, representado pela carteira de inadimplência e ativos problemáticos. A empresa deve observar esses valores para não superexpor-se a um volume de crédito com grande risco.

### Objetivo da Análise:

Analisar a base de dados para gerar insights que ajudarão a empresa a tomar decisões informadas sobre o lançamento de seu cartão de crédito, considerando os padrões de endividamento e inadimplência, além de identificar o impacto de fatores como ocupação, porte, região e indexador.

### Insights

- **Aposentados e Pensionistas tem Baixa Inadimplência**

    - Clientes com ocupação "Aposentado/Pensionista", "Servidor ou empregado público" e "Empresário" apresentão uma média de taxas de endividamento abaixo de 9%, indicando que clientes destas ocupações tendem a ter mais estabilidade financeira.

    - Já as demais ocupações apresentam taxas de inadimplência superiores a 10%, destaque para o "MEI" que apresenta a maior taxa média de 11.29%, isso pode ser um sinal de vunerabilidade, pois indica que muitos desses clientes podem não ter fontes de renda regulares.

- **Clientes Sem Renda e com Renda Acima de 20 Salários São Propensos Ativos Problemáticos**

    - Podemos observar que clientes sem renda e com renda acima de 20 salários mínimos, apresentaram as maiores médias de ativos problématicos, isso indica que esses clientes podem esta passando por dificuldades financeiras.

    - As demais faixas de renda se mantem com media de ativos problemáticos entre 4.000 e 4.900.

- **Regiões e Indexadores Influenciam na Taxa de Inadimplência**

    - Região Norte e Sudeste apresenta uma taxa de inadimplência superior em comparação a outras regiões, sugerindo que a empresa deve ser cautelosa ao lançar seu produto nesta localidade.

    - Clientes com indexadores "Pós-fixado" e "Flutuantes" apresentam taxas de inadimplência mais altas, o que pode ser um reflexo de condições de crédito menos flexíveis e resultado da atual economia.

- **É uma Boa Estrategia Lançar o Produto em Regiões com Mais Uso**

    - Se a empresa planeja lançar um cartão de crédito, pode ser útil direcionar campanhas promocionais para as regiões Nordeste, Suldeste e Sul,pois são regiões com uso elevado de cartão de crédito, onde a demanda pode ser mais alta, mas manter o controle da inadimplência nessas regiões.

### Conclusões e Recomendação

Com base na análise dos dados, podemos concluir que:

1. **O segmento de Aposentados/Pensionistas** é um dos menos arriscados devido ao perfil de endividamento e inadimplência. A empresa pode considerar oferecer condições diferenciadas ou taxas de juros mais baixas para este público.

2. **Autônomos, MEI e Empregados de empresas sem fins lucrativos** representam riscos elevados, principalmente em faixas de endividamento de 1 a 5 anos. A empresa pode precisar avaliar a viabilidade de crédito com mais rigor para esses clientes.

3. **A região Norte apresenta maiores taxas de inadimplência** e, portanto, pode ser necessário desenvolver estratégias específicas para mitigar o risco na região, como limites de crédito mais baixos ou taxas de juros mais altas.

4. **O indexador também é um fator relevante**. Para produtos com indexador pós-fixado ou flutuantes, é importante entender a relação entre as condições do mercado e o comportamento dos clientes para ajustar os riscos de inadimplência.

5. **Para o lançamento de um cartão de crédito** deve-se ter cautela e buscar reduzir riscos de inadimplência, é importante avaliar como as políticas de crédito podem ser ajustadas de acordo com os padrões de uso e inadimplência regionais.

A empresa deve focar no desenvolvimento de estratégias de crédito mais personalizadas, levando em consideração as particularidades de ocupação, região e indexador para minimizar os riscos de inadimplência e maximizar a rentabilidade do produto.

