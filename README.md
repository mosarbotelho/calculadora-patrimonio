Resumo do Projeto: Calculadora de Patrimônio

O projeto é uma Calculadora de Patrimônio interativa e completa, desenvolvida em um único arquivo HTML com Firebase para salvar os dados do usuário. Ela foi projetada para ajudar o usuário a planejar e monitorar sua jornada rumo à independência financeira.

A aplicação é dividida em várias seções, cada uma com um propósito específico:

Cálculo de Patrimônio: O usuário insere a renda mensal desejada no futuro e a porcentagem que essa renda deve representar de seu patrimônio total (baseada na Regra dos 4%). A calculadora então determina o valor total do patrimônio necessário para atingir essa meta.

Planejamento da Carteira: Com o valor total do patrimônio calculado, o usuário pode distribuir a alocação de ativos entre classes como FIIs, Ações, Renda Fixa e Investimentos Internacionais. A ferramenta mostra a porcentagem e o valor monetário correspondente para cada classe, além de gerar um gráfico de pizza para uma visualização clara da alocação.

Dividendos Projetados: Nesta seção, o usuário projeta os dividendos anuais e mensais com base nas porcentagens de rendimento de cada classe de ativo. O cálculo agora inclui a porcentagem de cada classe em relação ao total de dividendos, fornecendo uma visão mais detalhada da origem da renda passiva.

Cálculo de Investimento Mensal: Com base na taxa de retorno e no tempo de investimento, a calculadora determina o valor de aporte mensal necessário para alcançar o patrimônio desejado. Um gráfico de linha projeta o crescimento do patrimônio ao longo do tempo.

Análise de Inflação: O usuário pode inserir a taxa de inflação para verificar se o retorno de sua carteira está superando a inflação (retorno real). A ferramenta também sugere o aporte necessário em FIIs para manter o poder de compra.

Projeção para o Próximo Ano: Por fim, a calculadora projeta o valor do patrimônio para o ano seguinte, considerando os rendimentos e o impacto da inflação.

Todas as funcionalidades são dinâmicas e interativas, e os dados do usuário são salvos e carregados automaticamente usando o Firestore, garantindo que as informações persistam entre as sessões.
