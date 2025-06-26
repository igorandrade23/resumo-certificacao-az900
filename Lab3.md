# Lab3 Módulo 1 - Configurando uma Instância de Banco de Dados no Azure

No Azure, um dos principais recursos disponíveis é o SQL Database. Durante o processo de criação desse serviço, é possível configurar diversos parâmetros importantes:

1. **Assinatura, nome e servidor**  
   Definição da assinatura responsável pelo recurso, escolha do nome do banco de dados e seleção do servidor onde ele será hospedado (caso não exista, é necessário criar um novo servidor no portal do Azure).

2. **Rede**  
   Configuração das regras de firewall, políticas de acesso ao banco de dados e definição sobre a necessidade de acesso criptografado, garantindo segurança nas conexões.

3. **Segurança**  
   Opções como ativação do Microsoft Defender, configuração da identidade do servidor e gerenciamento das chaves de criptografia dos dados podem ser ajustadas conforme a necessidade do ambiente.

4. **Fonte e ordenação dos dados**  
   Escolha da origem dos dados e definição das regras de ordenação (collation) para o banco.

Após a configuração, a calculadora do Azure exibe o valor mensal estimado para o uso do banco de dados criado, permitindo o planejamento financeiro do ambiente.

### Aula

Durante as aulas, foram explicados os diferentes modelos de serviço em nuvem: Infrastructure as a Service (IaaS), Platform as a Service (PaaS) e Software as a Service (SaaS).  
Cada modelo define uma divisão específica de responsabilidades entre o cliente e a Microsoft. De modo geral, a Microsoft é sempre responsável pela infraestrutura física, como hosts, rede e datacenters, enquanto o usuário é responsável por contas, identidades, dispositivos e pelos próprios dados e informações.
