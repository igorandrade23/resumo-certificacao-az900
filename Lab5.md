# Lab5 Módulo 2 - Computação e Rede

Neste laboratório, foram explorados os principais serviços de computação e rede do Microsoft Azure, com foco em máquinas virtuais, áreas de trabalho virtual e aplicações de funções. O objetivo foi compreender como configurar, escalar e gerenciar recursos de infraestrutura e aplicações, além de boas práticas para ambientes corporativos.

---

## Máquinas Virtuais (VMs)

- **Criação e Configuração:**  
  O laboratório demonstrou o processo de criação de VMs, incluindo definição de nome, região, disponibilidade, tamanho, disco, rede e gerenciamento.
- **Tipos de VMs:**  
  Foram apresentados diferentes tipos e séries de VMs (D5, B, DC, H), cada uma adequada a cenários específicos de desempenho e custo.
- **Instância Spot:**  
  Utilização de recursos não alocados do Azure a um custo reduzido, com a ressalva de que a VM pode ser desalocada caso outro cliente pague o preço cheio.
- **Gerenciamento de Discos:**  
  Destacada a importância de habilitar a opção "Excluir com VM" para evitar custos com discos órfãos.
- **Escalonamento Horizontal:**  
  Configuração de Conjuntos de Dimensionamento (Scale Sets) para aumentar ou reduzir a quantidade de VMs automaticamente, com base em métricas como uso de CPU.

---

## Área de Trabalho Virtual

- **Conceito:**  
  Solução do Azure para oferecer ambientes de trabalho remoto seguros e personalizados.
- **Tipos de Host:**
  - Host pessoal: dedicado a um único usuário.
  - Pool de hosts: compartilhado entre múltiplos usuários.
- **Balanceamento de Carga:**  
  Configuração de limites máximos de sessões e distribuição de usuários entre hosts para otimizar recursos.

---

## Aplicações de Funções (Azure Functions)

- **Criação de Aplicativos de Função:**  
  O laboratório abordou a configuração de nome, pilha de tempo de execução, hospedagem e plano de serviço.
- **Linguagens Suportadas:**  
  Node.js, Java, Python, .NET, entre outras.
- **Serverless:**  
  Introdução ao conceito de computação sem servidor, onde o código é executado sob demanda sem necessidade de gerenciar infraestrutura.
