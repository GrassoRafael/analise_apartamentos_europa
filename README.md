# Case 1 data analysis escola DNC

Este projeto visa desenvolver um sistema de apoio à decisão para o setor imobiliário, com foco em duas cidades europeias específicas. O sistema será uma ferramenta abrangente para auxiliar compradores, vendedores e investidores na tomada de decisões informadas relacionadas a propriedades imobiliárias.

Premissas de negócio:
As premissas foram sendo desenvolvidas o longo do case, para responder perguntas variads que vinham surgindo, trazendo representações em formas de gráficos e tabelas. 

Métricas:
Foi definido que o range da avaliação seria feito em imóveis que o preço do aluguel seria maior ou igual a €4000.00, precisaria ter pelo menos 2 quartos, mas 3 quartos também seria aceito e que fossem permitidos animais. Após realizar os tratamento e a limpeza dos dados, chegamos as seguintes conclusões:

1. Quantidade de quartos - A diferença de preço médio dos imóveis com 2 e 3 quartos foi de mais ou menos €500 a mais. Levando em consideração a diferença de preço com o valor médio dos apartamentos (€2556) um quarto a mais representa cerca de 20% a mais no valor.
2. Quantidade de banheiros - A quantidade de banheiros terá impacto direto no valor dos imóveis onde de 1 até 4 banheiros temos um aumento constante no valor, a partir de 5 ganheiros começamos a notar uma redução nos preços do aluguel.
3. Quantidade de imóveis/m² - A maioria dos imóveis da base tem as áreas de 60m² e 70m².
4. Comparação por cidade - Nota-se que, a cidade do Porto possui os imóveis mais baratos em consideração, a cidade de Barcelona possui mais que o dobro da quantidade de imóveis de alto valor, representando uma parcela baixíssima de valores entre €1000 e €1500. A melhor opção para que está procurando um local mais barato, é a cidade do Porto para quem precisa mais opções idenpentente do preço, a cidade de Barcelona é a escolha certa, dada sua quantidade elevada.
5. Análise de preço/andar - Partindo da premissa que os apartamento em andares mais altos são mais valorizados, nosso cliente gostaria de adquirir o imóvel em um andar de número 10 para cima, tendo em vista essa questão, analisamos que os andares mais baratos são os andares, 10, 16 e 19.
6. Procurando o apartamento do gosto do cliente - Seguindo todas as métricas passadas pelo cliente: Valor menor ou igual a €4000, 2 ou 3 quartos, na cidade do Porto, aceitando animais, e em um andar alto e barato (16º andar foi o mais barato dos andares altos analisados) temos dois apatamentos que são perfeitos a escola do cliente

![image](https://github.com/GrassoRafael/case1_da_dnc/assets/150485894/86e4005a-b7d9-46e3-bb51-231374b8c047)

# Bibliotecas usadas:
  1. Pandas
  2. Seaborn
