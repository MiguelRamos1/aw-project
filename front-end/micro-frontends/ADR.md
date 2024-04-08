# Contexto e Problema
A aplicação em questão é uma app que permite aos utilizadores scannear embalagens de carne para visualizar as suas informações antes de comprar. Além disso, oferece outras funcionalidades como a visualização de produtos, notícias, estatísticas ambientais, entre outras. Esta app dá assim a oportunidade aos utilizadores de tomarem uma decisão consciente e informada acerca da compra que irão fazer. Diante deste contexto, surge a necessidade de evitar a complexidade no sistema em construção, garantindo uma arquitetura que promova a escalabilidade, flexibilidade e modularidade.

# Direcionadores da Decisão
Para obtermos as 3 características anteriormente descritas, temos a necessidade de dividir o sistema global em blocos lógicos, facilitando o desenvolvimento independente das diversas partes do sistema. Garantir a capacidade de alterar partes do sistema sem afetar outras, aproveitando a arquitetura em camadas para promover a coesão e a separação de responsabilidades será um dos grandes objetivos

# Opções Consideradas
- Camadas;
- Componentes;
- Workflow.

# Decisão Tomada
Considerando a natureza da aplicação, decidimos adotar a abordagem de Camadas. Essa decisão baseia-se na estrutura da app, que sugere uma organização em camadas e na necessidade de introduzir micro frontends para permitir uma maior modularidade e flexibilidade.

# Consequências Boas
- Arquitetura altamente modular, permitindo o desenvolvimento, teste e implementações independentes de diferentes partes do sistema;
- Flexibilidade na seleção de tecnologias para cada camada, possibilitando que as equipas trabalhem em paralelo em diferentes partes do sistema, promovendo a eficiência no desenvolvimento.

# Consequências Más
- Pode haver uma penalidade no desempenho para cada nível de indireção;
- Aumento da complexidade, exigindo uma cuidadosa definição e gestão. 





