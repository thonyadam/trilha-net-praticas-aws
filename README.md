# trilha-net-praticas-aws

# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 24/08/2025
Empresa: Abstergo Industries
Responsável: Anthony Adam

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na AWS para a Abstergo Industries, realizado por Anthony Adam. O objetivo do projeto foi selecionar 3 serviços AWS para melhorar sistemas críticos e reduzir custos operacionais imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos especí­ficos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Nome da ferramenta: Amazon S3 Intelligent-Tiering
- Foco da ferramenta: Armazenamento inteligente e econômico de dados.
- Descrição de caso de uso:
A Abstergo armazena grandes volumes de dados de pesquisas clínicas, imagens médicas e registros de pacientes. O S3 Intelligent-Tiering automatiza a movimentação de dados entre camadas de acesso (frequente, infrequente e arquivamento) com base no padrão de uso. Isso reduz custos pois evita taxas de recuperação desnecessárias e elimina a complexidade de gerenciamento manual de camadas. Dados críticos são mantidos em camadas de acesso rápido, enquanto dados antigos são automaticamente arquivados. A segurança é garantida com criptografia padrão.

Etapa 2: 
- Nome da ferramenta: AWS Lambda 
- Foco da ferramenta: Processamento sob demanda sem custos de ociosidade.
- Descrição de caso de uso:
Substituiu servidores EC2 ociosos usados para processar relatórios de ensaios clínicos e análises de dados. Com o Lambda, a execução de código é acionada apenas quando novos dados chegam. Isso reduziu custos pois a empresa paga apenas pelo tempo de execução. Além disso, a escalabilidade automática permite lidar com picos de demanda durante lançamentos de novos medicamentos sem provisionamento prévio.

Etapa 3:
- Nome da ferramenta: Amazon RDS
- Foco da ferramenta: Banco de dados gerenciado com alta disponibilidade.
- Descrição de caso de uso:
Migração de bancos de dados locais para o Amazon RDS com motor PostgreSQL. O RDS automatiza backups e patches de segurança, isso reduziu custos com licenças de software, hardware e DBA. A empresa também beneficia de recuperação de desastres integrada.


## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado:
- Redução de custos imediata de armazenamento, processamento e banco de dados.
- Maior agilidade em pesquisas e cadastros no sistema devido à escalabilidade sob demanda.
O que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos
https://aws.amazon.com/pt/pm/lambda
https://aws.amazon.com/pt/s3
https://aws.amazon.com/pt/rds


Assinatura do Responsável pelo Projeto:

Anthony Adam
