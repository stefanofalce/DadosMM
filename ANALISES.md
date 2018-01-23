# Teste MaxMilhas - Analista de Dados
*Candidato: Stefano Guimarães Falce*


----------


**Análise #1: Preços atrativos na MaxMilhas**

1) Observando a massa de dados nas colunas de melhores preços na MaxMilhas ou na própria companhia área, observa-se que cerca de dois 66% das buscas indica que a MaxMilhas possui os melhores preços.
2) MaxMilhas possui melhores preços em dois terços das buscas e muitas pessoas ainda desconhecem, realizando buscas em outros sites, inclusive diretamente nas próprias companhias. Ou seja, é possível trazer estes usuários para realizar buscas no portal MaxMilhas.
3) Basta gerar um gráfico de Pizza no PowerBI adicionando ao grupo de Valores as colunas "qtd_melhores_precos_cias" e "qtd_melhores_precos_mm" e observar a proporção entre as duas áreas do gráfico.


----------


**Análise #2: Duração média da viagem (intervalo de ida e volta)**

1) Observando a quantidade de viagens por intervalo de dias entre ida e volta, nota-se que uma parcela significativa das buscar são bate-e-volta (ida e volta no mesmo dia) ou de 7 dias (uma semana) de diferença.
2) Passageiros no geral acreditam que o intervalo de dias entre ida e volta impactam no preço total das passagens. Além disso, é comum viagens de "bate-e-volta" no mesmo dia no ambiente corporativo para tratamento de negócios.
3) Basta gerar um gráfico de Pizza no PowerBI adicionando em Valores a contagem da coluna ID Distintos e em legenda a coluna "dias em viagem".


----------


**Análise #3: Buscas por passagens de ida e volta e por apenas ida**
1) Observando a proporção de buscas por passagens de ida e volta e de buscas por passagens de apenas ida, nota-se que cerca de 55% das buscas são de passagens de ida e volta.
2) Há correntes que afirmam que compras de passagens de ida e volta em conjunto resultam em menores valores por trecho do que comprar trechos de apenas ida isoladamente.
3) Basta gerar um gráfico de pizza adicionando a coluna "tipo_de_voo" à legenda e a coluna ID (soma) aos Valores