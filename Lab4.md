# Lab4 Módulo 2 - Construindo Arquiteturas no Azure

Neste laboratório, foram explorados os principais tipos de computação disponíveis no Azure, as opções de hospedagem de aplicativos e os conceitos fundamentais de redes virtuais. O objetivo foi compreender como escolher e configurar recursos de computação e rede de acordo com as necessidades de diferentes cenários em nuvem.

---

## Tipos de Computação no Azure

- **Máquinas Virtuais (VMs):**  
  Permitem a execução de sistemas operacionais completos e aplicações personalizadas, oferecendo flexibilidade para diferentes cargas de trabalho. O usuário pode escolher o tamanho, sistema operacional, armazenamento e configurações de rede.

- **Instâncias de Contêiner:**  
  Facilitam a implantação e gerenciamento de aplicações em contêineres, como Docker, proporcionando portabilidade, escalabilidade e isolamento de ambientes. O Azure Container Instances (ACI) permite executar contêineres sem necessidade de gerenciar servidores.

- **Funções (Azure Functions):**  
  Serviço de computação serverless que executa código sob demanda, ideal para automação, processamento de eventos e integração entre sistemas, sem a necessidade de provisionar ou gerenciar infraestrutura.

---

## Opções de Hospedagem de Aplicativos

- **Aplicativos Web do Azure (App Service):**  
  Plataforma gerenciada para hospedagem de aplicações web, APIs e backends móveis, com suporte a várias linguagens e integração com CI/CD. Oferece escalabilidade automática, SSL, autenticação e monitoramento integrado.

- **Contêineres:**  
  Possibilidade de hospedar aplicações empacotadas em contêineres, utilizando serviços como Azure App Service for Containers, Azure Kubernetes Service (AKS) ou Azure Container Instances.

- **Máquinas Virtuais:**  
  Utilizadas para hospedar aplicações que exigem controle total do ambiente, customizações específicas ou dependências de sistemas legados.

---

## Redes Virtuais no Azure

- **Redes Virtuais (VNet):**  
  Permitem a criação de ambientes de rede isolados e seguros dentro do Azure, possibilitando a comunicação entre recursos, segmentação por sub-redes e configuração de regras de segurança.

- **Sub-redes:**  
  Dividem a rede virtual em segmentos menores, facilitando a organização, controle de acesso e aplicação de políticas específicas para diferentes grupos de recursos.

- **Emparelhamento de Redes (VNet Peering):**  
  Permite a comunicação entre redes virtuais distintas, seja na mesma região ou em regiões diferentes, de forma segura e eficiente.

- **DNS:**  
  O Azure oferece serviços de DNS para resolução de nomes internos e externos, facilitando o acesso e gerenciamento dos recursos.

- **Gateway de VPN:**  
  Permite a conexão segura entre a rede local (on-premises) e a rede virtual do Azure por meio de túneis VPN criptografados.

- **ExpressRoute:**  
  Solução para conexão privada e dedicada entre o ambiente local e o Azure, oferecendo maior largura de banda, menor latência e maior confiabilidade em comparação com conexões via internet pública.
