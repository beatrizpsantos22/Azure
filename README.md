# Azure
O que é Azure? Plataforma de computação em nuvem da Microsoft. O Azure permite que você “alugue” recursos de computação sob demanda, pagando apenas pelo que utiliza.
Computação em Nuvem: acesso e uso de recursos computacionais como um serviço, sem a necessidade de construir uma infraestrutura física própria. 

Modelos de Serviço:
-IaaS (Infraestrutura como Serviço): Máquinas virtuais, redes, armazenamento.
-PaaS (Plataforma como Serviço): Serviços gerenciados (Azure SQL, App Services).
-SaaS (Software como Serviço): Aplicativos prontos (Office 365, Dynamics 365).

Serviços Pincipias:
1. COMPUTAÇÃO
   Azure Virtual Machines (VMs): Máquinas virtuais Windows/Linux.
   Azure Kubernetes Service (AKS): Orquestração de contêineres.
   Azure Functions: Serverless para execução de código sob demanda.
2. ARMAZENTAMENTO
   Blob Storage: Armazenamento de arquivos (imagens, vídeos).
   Azure SQL Database: Banco de dados relacional gerenciado.
   Cosmos DB: Banco de dados NoSQL global.
3. REDES
   Virtual Network (VNet): Rede privada na nuvem.
   Azure Load Balancer: Distribui tráfego entre VMs.
   Azure CDN: Entrega rápida de conteúdo estático.
4. SEGURANÇA
   Azure Active Directory (AD): Gerenciamento de identidade.
   Azure Key Vault: Armazenamento seguro de segredos (senhas, certificados).
   Azure Security Center: Monitoramento de segurança unificado.
5. MONITORAMENTO
   Azure Monitor: Coleta e analisa logs e métricas.
   Application Insights: Monitoramento de aplicações em tempo real.

O PaaS é um modelo de serviço em nuvem que fornece uma plataforma completa para criar, gerenciar e implantar aplicativos sem precisar lidar com a complexidade da infraestrutura, como servidores ou redes. Já o SaaS é um modelo de serviço em nuvem em que você acessa aplicativos prontos para uso diretamente pela internet, sem a necessidade de instalar, manter ou atualizar software em seus dispositivos.

![imagem_2025-04-25_144852401](https://github.com/user-attachments/assets/16e5a223-76cc-43a5-8608-85abd20b8be0)


Sobre a Segurança: A empresa compartilha uma documentação com padrões e práticas recomendadas para ajudar os clientes a protegerem seus dados e recursos na nuvem. Manter a segurança em uma estrutura local exige atualizações manuais e monitoramento constante. No Azure, a segurança é contínua, com certificações que facilitam seguir as regras de segurança.


How does Microsoft Azure work?: https://www.youtube.com/watch?v=KXkBZCe699A


COMO CRIAR UMA MÁQUINA VIRTUAL?
1. Entrar no Azure
2. Digite máquinas virtuais na pesquisa.
3. Em Serviços, selecione Máquinas virtuais.
4. Na página Máquinas virtuais, clique em Criar e selecione Máquina virtual do Azure. A página Criar uma máquina virtual é aberta.
5. Em Detalhes da instância, insira myVM no Nome da máquina virtual e escolha Windows Server 2022 Datacenter: Azure Edition - x64 Gen 2 na Imagem. Deixe os outros padrões.
6. Em Conta de administrador, forneça um nome de usuário, como azureuser e uma senha. A senha deve ter no mínimo 12 caracteres e atender a requisitos de complexidade definidos.
7. Em Regras de porta de entrada, escolha Permitir portas selecionadas e, em seguida, selecione RDP (3389) e HTTP (80) na lista suspensa.
8. Deixe os padrões restantes e, em seguida, selecione o botão Examinar + criar na parte inferior da página.
9. Após a execução da validação, selecione o botão Criar na parte inferior da página.
10. Após a conclusão da implantação, selecione Ir para o recurso.
   
