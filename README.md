# Amigo Edu - BI Challenge

Esse é um desafio destinado aos candidatos à vaga de analista de Business Intelligence na Amigo Edu. 

## Contexto

No contexto de vendas e marketing online, muitas vezes os usuários são direcionados ao site por diferentes canais (ads em redes sociais, email marketing, Google, etc). Também é comum que os usuários visitem diversas vezes o site antes de realizar uma compra. Nesse desafio você deve analisar os registros de conversões (vendas) de um e-commerce hipotético.

## Dataset

É disponibilizado um database SQLite "*amigoedu_bi_challenge.sqlite*" que contém 2 tabelas com as seguintes colunas:

**table_A**: lista de conversões
* *convId* - ID da transação
* *userId* - ID do cliente
* *revenue* - Valor da transação
* *createdAt* - Data da trasação


**table_B**: atribuições de canais para as conversões
* *convId* - id da transação
* *channel* - canal de marketing
* *contribution* - contribuição do canal para a conversão

Note que a fração de contribuição do canal (*contribution*) representa o quanto um canal de marketing foi responsável por uma venda, e naturalmente soma 1.0 para cada conversão.

## Tarefa

O objetivo é bem direto: queremos que você analise os dados e mostre o que é possível aprender com eles. 

Obviamente não esperamos que sejam criadas soluções ou relatórios extensos. A intenção é avaliar como o problema é abordado e ter uma idéia das suas habilidades técnicas e analíticas. 

Sinta-se a vontade para utilizar quaisquer linguagens e/ou tecnologias de sua preferência para esse desafio, mas a utilização de Python e o pacote Pandas para carregar e tratar os dados devem facilitar bastante a tarefa.

### Algumas dicas de coisas interessantes para analisar:
* Visão geral de KPIs ao longo do tempo (por exemplo: receita, número de clientes, proporção de clientes que retornam)
* Performance e impacto de diferentes canais ao longo do tempo
* Canais mais importantes para segmentos de clientes


### Entregáveis:
* PDF com as análises executadas
* Descrição dos passos tomados para construção do conteúdo acima

### Boa sorte! Estamos à disposição para tirar qualquer dúvida :)