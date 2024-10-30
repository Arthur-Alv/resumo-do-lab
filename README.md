# RESUMO do Lab Microsoft Azure


Dentro os serviços do Microsoft Azure existe a possibilidade de Localizar os Serviços por categorias, sendo elas:
 - Análises
 - Armazenamento
 - Banco de Dados
 - Computação
 - Contêiners
 - DevOps Híbido + multinuvem
 - IA + Machine Learning
 - Geral
 - Identicade
 - Integração
 - Internet das Coisas
 - Management and governance
 - Migração
 - Monitor
 - Realidade misturada
 - Rede
 - Segurança
 - Web & Mobile.


Cada uma dessas categorias possui um "subtitulo" ou objetivo no qual trás serviços voltados para um assunto especifico, como por exemplo da Categoria `Banco de dados`, há o assunto `Modernizar aplicativos existentes` com os itens:

 - Bancos de dados SQL
 - Azure Cosmos DB for MongoDB (vCore)
 - Instâncias gerenciadas do SQL
 - Azure Managed Instance for Apache Cassandra
 - máquinas virtuais do SQL
 - Oracle Database@Azure
 - Servidores flexíveis do Banco de Dados do Azure para MySQL

 Essa divisão permite com facilidade a localização do serviço dentro da console da Azure. 
 
## SLA E ALTA DISPONIBILIDADE

O  nível de acordo de serviço ou SLA (Service Level Agreement) é o tempo que o Cloud Provider oferece de disponibilidade do serviço. Quando o valor é 99% o tempo de inatividade é de 1,68 hora por semana e 7,2 horas por mês e 3,65 dias por ano. Porem esse valor pode alterar bastante onde, se o SLA é de 99,999% o tempo de inatividade diminui significativamente para 6 segundos por semana, 25,9 segundos por mês e 5,26 minutos por ano.


## Criação de máquina virtual / Imagem e Arquitetura

No painel de criação da máquina virtual é possivel ver o valor estimado que será cobrado pela máquina e sobre a responsabilidade.
É possível configurar itens como:
- Reinicio automática
- Monitoramento
- Discos
- Peças
- Modelo de redundância

## Armazenamento

Parar fazer uma configuração de armazenamento a assinatura já vem configurada e deve ser escolhido o grupo de recursos. O nome da conta de armazenamento deve ter nome único.

- Região - Deve ser escolhida de acordo com os requisitos de latência ou até mesmo custo.
- Desempenho - Pode ser escolhido o `Standard` ou `Premium` que irá determinar a latencia
- Redundância - Pode ser usada LRS (local), GRS (geográfica), ZRS (Zona) e GZRS(Zona geográfica) que determinará o tipo de redundância este armazendo deverá ter.
