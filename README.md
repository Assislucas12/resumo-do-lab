# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO sobre Azure
estamos sendo introduzidos no tema do AZURE atualmente aprendemos a diferença ente CapEx e OpEx assim como as 
caracteristicas da computação em nuvem, privada e hibrida

#Beneficios da Nuvem:
no modulo atual aprendemos sobre os princiapais beneficios da Nuvem como por exemplo(Gerenciabilidade, Governança, Segurança, Confiabilidade, Escalabilidade...)
tambem foi destacado Tema(SLA -> Service Level Agreement) na qual foi apresentados os tipos de SLA.
Dica: quanto Mais 9 no tipo de SLA mais Caro porem com tempo de inatividalide reduzido draticamente) ex:(99%, 99,9%, 99,95%, 99,99% e 99,999%)

#Tipos de Serviço
Foi apresentado os tipos de Serviços disponiveis(IaaS,PaaS e SaaS) e suas caracteristicas.
PaaS (Plataforma como Serviço): fornece infraestrutura e ferramentas para desenvolvimento de aplicativos.
IaaS (Infraestrutura como Serviço): oferece servidores, armazenamento e rede sob demanda.
SaaS (Software como Serviço): disponibiliza software pronto para uso via internet.

# Arquitetura Azure
Regiões do Azure: Áreas geográficas onde os datacenters do Azure estão localizados, permitindo proximidade e menor latência.
Zona de Disponibilidade: Locais físicos dentro de uma região, garantindo alta disponibilidade com redundância.
Pares de Região: Regiões emparelhadas para replicação de dados e recuperação de desastres.
Região Soberana: Regiões isoladas que atendem a requisitos específicos de conformidade, como China e Alemanha.
Recursos: Instâncias de serviços do Azure, como máquinas virtuais, bancos de dados ou redes.
Grupo de Recursos: Contêiner lógico para gerenciar e organizar recursos relacionados.
Tipos de Assinatura: Planos que definem acesso, limites e cobrança de serviços no Azure, como Gratuito, Pay-As-You-Go ou Enterprise.

# Maquina Virtual
O processo de criação de uma máquina virtual envolve algumas etapas principais. Primeiro, escolhe-se um software de virtualização, como VMware, VirtualBox ou Hyper-V, que permite criar e gerenciar máquinas virtuais. Em seguida, configura-se os parâmetros da máquina, como a alocação de memória RAM, armazenamento em disco, número de CPUs e rede. Após isso, é necessário instalar o sistema operacional na máquina virtual, utilizando uma imagem ISO do SO desejado. Durante a configuração, pode-se ajustar dispositivos virtuais, como adaptadores de rede, drives de CD/DVD e portas USB. Uma vez instalada, a máquina virtual funciona como um computador físico, mas dentro de um ambiente isolado, permitindo a execução de testes, desenvolvimento ou operação de sistemas diferentes sem interferir no host. Por fim, as máquinas virtuais podem ser iniciadas, pausadas, clonadas e gerenciadas conforme necessário, otimizando recursos e garantindo flexibilidade no uso do hardware.

# Segurança do Azure
O Microsoft Entra ID (anteriormente Azure Active Directory) é um serviço de gerenciamento de identidade e acesso baseado em nuvem, que oferece autenticação segura, gerenciamento de usuários, SSO (Single Sign-On) e suporte a políticas como MFA (Multi-Factor Authentication) e autenticação sem senha, incluindo métodos como Windows Hello e FIDO2. Complementando, o Microsoft Entra Domain Services fornece serviços gerenciados de domínio no Azure, como autenticação Kerberos e políticas de grupo, facilitando a migração de aplicativos tradicionais para a nuvem.

O Azure também permite a colaboração com identidades externas, oferecendo acesso de convidado para parceiros, fornecedores e clientes, com controle granular sobre permissões. Além disso, o Acesso Condicional do Entra é uma ferramenta que aplica políticas de segurança baseadas em condições específicas, como localização, tipo de dispositivo e risco de login, permitindo ações como exigir MFA, bloquear acessos suspeitos ou garantir a conformidade de dispositivos antes de autorizar o acesso.


# Definição de Preço e Azure Marketplace
A Calculadora de Preço do Azure é uma ferramenta online que permite estimar os custos de serviços no Azure, personalizando configurações como tipo de serviço, região e consumo esperado. Ajuda a planejar orçamentos com base em cenários de uso específicos.

O TCO (Total Cost of Ownership) é um recurso que compara os custos de infraestrutura local com a migração para o Azure. Ele considera fatores como despesas operacionais, manutenção e economia proporcionada pela nuvem, ajudando na tomada de decisão sobre investimentos.

O Azure Marketplace é uma plataforma que oferece soluções prontas de parceiros e da Microsoft, incluindo aplicativos, serviços e integrações. Facilita a implementação de ferramentas diretamente no Azure, economizando tempo e aumentando a produtividade.

