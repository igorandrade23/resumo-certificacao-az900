# Lab2 Módulo 1 - Criando Máquinas Virtuais na Azure

Neste laboratório, foi demonstrado o processo de criação de uma máquina virtual (VM) no Azure, detalhando as principais opções de configuração disponíveis durante a implantação do recurso. A criação de uma VM envolve a definição de diversos parâmetros importantes para garantir que o recurso atenda às necessidades da aplicação e esteja em conformidade com as melhores práticas de nuvem.

Durante a configuração da VM, é necessário especificar:

1. **Assinatura**  
   Seleção da assinatura do Azure à qual a VM estará vinculada, determinando onde os custos serão alocados.

2. **Nome da VM**  
   Definição de um nome único para identificar a máquina virtual dentro do ambiente.

3. **Região e Zona de Disponibilidade**  
   Escolha da região geográfica e, se aplicável, da zona de disponibilidade onde a VM será provisionada. Essa decisão impacta diretamente a latência, a conformidade com requisitos legais e os níveis de SLA (Service Level Agreement) oferecidos pelo Azure.

4. **Tipo de Segurança, Imagem e Arquitetura**  
   Seleção da imagem do sistema operacional (Windows, Linux, etc.), arquitetura (x64, ARM) e configurações de segurança, como habilitação de recursos de proteção avançada.

5. **Tamanho da VM**  
   Escolha do tamanho da VM, que determina a quantidade de CPU, memória e armazenamento disponíveis. Essa escolha deve ser feita com base no perfil de carga de trabalho, influenciando diretamente o custo mensal do recurso.

6. **Usuário e Autenticação**  
   Definição do nome do usuário administrador e do método de autenticação (senha ou chave SSH) para acesso seguro à VM.

Além dessas configurações básicas, o Azure permite ajustes avançados, como a adição de discos de dados, configuração de redes virtuais, definição de regras de firewall (NSG), habilitação de monitoramento e backup, entre outros.

Durante as aulas, também foram discutidos os principais benefícios da computação em nuvem, que incluem:

- **Alta disponibilidade:** Garantia de que os serviços permaneçam acessíveis mesmo diante de falhas.
- **Escalabilidade:** Capacidade de aumentar ou reduzir recursos conforme a demanda.
- **Elasticidade:** Ajuste automático dos recursos de acordo com as necessidades do momento.
- **Confiabilidade:** Infraestrutura robusta e redundante, minimizando riscos de indisponibilidade.
- **Previsibilidade:** Facilidade para estimar custos e desempenho.
- **Segurança:** Recursos avançados de proteção de dados e controle de acesso.
- **Governança:** Ferramentas para gerenciamento, auditoria e conformidade.
- **Gerenciabilidade:** Facilidade de administração e automação dos recursos.
