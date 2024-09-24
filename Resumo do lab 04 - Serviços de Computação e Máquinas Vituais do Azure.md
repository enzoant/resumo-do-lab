# Serviços de Computação e Máquinas Vituais do Azure

A computação do Azure oferece recursos de computação sob demanda, como armazenamento, processamento, memória, rede e sistemas operacionais, acessíveis pela nuvem. Esses serviços são escaláveis e flexíveis, permitindo que as empresas ajustem os recursos conforme necessário.

## Máquinas Virtuais do Azure

As máquinas virtuais (VMs) são emulações de computadores físicos, oferecendo recursos como processador virtual, memória, armazenamento e rede. Essa solução é classificada como IaaS (Infraestrutura como Serviço), pois fornece controle completo e personalização do ambiente, ideal para cenários onde é necessário gerenciar diretamente o sistema operacional e o software.

## Conjuntos de Disponibilidade de VMs

Para garantir alta disponibilidade, as VMs devem ser distribuídas entre diferentes racks dentro de um datacenter. Se todas as VMs estiverem em um único rack, uma falha ou atualização pode afetar todas elas ao mesmo tempo, interrompendo o serviço. Ao distribuir as VMs entre Domínios de Falha e Domínios de Atualização, o sistema continua operando mesmo em caso de falhas ou atualizações. Essa configuração não afeta os custos, sendo uma prática recomendada.

## Conjuntos de Dimensionamento de VMs

Conjuntos de dimensionamento de máquinas virtuais permitem criar e gerenciar várias VMs para diferentes funções. O dimensionamento automático ajusta os recursos conforme a demanda, garantindo que a carga de trabalho seja bem distribuída e o desempenho mantido. Isso é especialmente útil em cenários onde a carga varia, como sites de e-commerce em períodos de alta demanda.

## Área de Trabalho Virtual do Azure

A Área de Trabalho Virtual do Azure é um serviço de virtualização que permite criar e acessar uma versão do Windows na nuvem com aplicações e configurações personalizadas. Esse ambiente pode ser replicado para toda uma organização, permitindo que os funcionários utilizem um ambiente corporativo seguro em seus dispositivos pessoais. Oferece suporte à autenticação multifator e aplicativos como o Office 365.

---

## Serviços de Contêineres do Azure

Contêineres são ambientes virtualizados leves que não exigem gerenciamento de sistema operacional, facilitando o desenvolvimento, a execução e a escalabilidade de aplicativos.

- **Instâncias de Contêineres do Azure**: Serviço PaaS que executa um contêiner ou pod de contêineres sem a necessidade de gerenciar infraestrutura.
- **Aplicativos de Contêiner do Azure**: Semelhante a instâncias de contêineres, mas com funcionalidades adicionais, como balanceamento de carga e escalonamento automático, ideal para microserviços.
- **Serviço de Kubernetes do Azure (AKS)**: Um serviço de orquestração para gerenciar contêineres em larga escala, facilitando a automação de tarefas como distribuição de atualizações, balanceamento de carga e recuperação de falhas.

---

## Azure Functions

O Azure Functions é um serviço PaaS que permite computação sem servidor (serverless). O código baseado em eventos é executado sob demanda, sem a necessidade de manter infraestrutura ativa durante períodos ociosos. Ideal para automações e tarefas pontuais, como responder a eventos ou processar dados.

---

## Comparação entre Modelos de Computação no Azure

### Máquinas Virtuais (VMs)

- Suporta sistemas operacionais Windows e Linux.
- Ideal para migrações para a nuvem através de um modelo automatizado.
- Fornece um pacote de sistema operacional completo com controle total sobre o host.

### Área de Trabalho Virtual

- Experiência personalizável e segura para o usuário final.
- Acessível de qualquer navegador moderno.
- Permite múltiplos logins simultâneos no mesmo ambiente.

### Contêineres

- Projetados para serem altamente escaláveis.
- Executam microserviços em ambientes leves.
- Resilientes e auto-recuperáveis quando orquestrados (via AKS).
- Aplicativos e serviços são empacotados e executados sob demanda.

### Serviços de Aplicativo do Azure

- Plataforma totalmente gerenciada para criar, implantar e dimensionar aplicativos Web e APIs rapidamente.
- Suporta várias linguagens de programação, como .NET, .NET Core, Node.js, Java, Python e PHP.
- Ideal para requisitos corporativos de desempenho, segurança e conformidade.

---

## Serviços de Rede do Azure

- **VNet**: Permite que os recursos do Azure se comuniquem entre si, com a Internet e redes locais.
- **Pontos de Extremidade Públicos**: Acessíveis de qualquer lugar na Internet.
- **Pontos de Extremidade Privados**: Acessíveis apenas dentro da rede privada da empresa.
- **Sub-redes Virtuais**: Segmentam a rede virtual para melhor organização e segurança.
- **Emparelhamento de Rede**: Conecta redes privadas diretamente, facilitando a comunicação entre diferentes ambientes.
- **Gateway de VPN**: Utilizado para enviar tráfego criptografado entre redes privadas e públicas.
- **ExpressRoute**: Proporciona uma conexão privada e dedicada entre a infraestrutura da empresa e o Azure, com maior segurança e baixa latência.

## DNS do Azure

O DNS do Azure gerencia a tradução de nomes de domínio em endereços IP, facilitando o acesso a recursos na web. Permite o uso de domínios personalizados com fácil gerenciamento, integrando-se perfeitamente ao ecossistema do Azure. Ideal para empresas que precisam gerenciar seus próprios nomes de domínio.
