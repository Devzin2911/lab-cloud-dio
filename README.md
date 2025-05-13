# lab-cloud-dio
Repositório que conterá informações para as aulas do bootcamp DIO, referente ao módulo de Cloud


Aprendi sobre os modelos de nuvem, os modelos de cobrança, o que é de fato a computação em nuvem
como funcionam os datacenters que estão alocados ao redor do mundo.

Aprendenmos também como funcionam os custos de capital e os custos de operação

e essencialmente que o melhor dos dois mundos é modelo de nuvem híbrida e que o extremo de um ou 
de outro depende de como está a situação de cada empresa

## Benefícios da Nuvem

Os benefícios da nuvem são diversos para cada tipo de aplicação que você deseja inserir.
Aprendemos muito como é facil de gerenciar e aprender sobre as funções e recursos que 
você irá implementar.

Aprendi sobre Alta disponibilidade, Elasticidade, Confiabilidade, Previsibilidade e Segurança

Com a Alta disponibilidade, você garante que sua aplicação vai estar disponível quando e onde
precisar, mesmo com falhas de sistema e entre outras coisas.

A Elasticidade permite você fazer um balanceamento da quantidade de recursos que utiliza na
medida em que eles são requisitados

A Confiabilidade garante a consistência dos seus dados quando e onde eles forem acessados

A Previsibilidade ajuda você a gerenciar seus recursos, custos para que se tenha um aproveitamento
melhor do ambiente Cloud



## Criando Máquinas Virtuais na Azure

IaaS - Infraestrutura como Serviço

IaaS → Servidores e Armazenamento, Firewalls e Segurança de Rede e prédio físico do data center

Exemplo: Crie uma infraestrutura de TI de pagamento conforme o uso alugando servidores, máquinas virtuais, armazenamento, redes e sistemas operacionais de um provedor de nuvem.

PaaS - Plataforma como Serviço

PaaS → Servidores e Armazenamento, Firewalls e Segurança de Rede,  prédio físico do data center, Sistemas operacionais, Ferramentas de desenvolvimento, análise de negócios de 
gerenciamento de banco de dados.

Exemplo: Fornece um ambiente para criação, o teste e a implantação de aplicativos de software, sem focar no gerenciamento de infraestrutura subjacente.

SaaS - Software como Serviço

SaaS→ Servidores e Armazenamento, Firewalls e Segurança de Rede,  prédio físico do data center, Sistemas operacionais, Ferramentas de desenvolvimento, análise de negócios de 
gerenciamento de banco de dados, aplicativos/apps hospedados.

 Exemplo: Os usuários se conectam e usam aplicativos com base em nuvem pela internet, tipo: Microsoft Office 365, email e calendários.

Modelo de Responsabilidade Compartilhada

Comparação de Serviço em Nuvem

IaaS:

O serviço de nuvem mais flexível.
Você confiura e gerencia o hardware para seu aplicativo.

PaaS

Focado no desenvolvimento de aplicativos
O gerenciamento de plataforma é realizado pelo provedor de nuvem.

SaaS

Modelo de preço de pagamento conforme o uso.
Os usuários pagam pelo software que utilizam em um modelo de assinatura.

A Segurança garante a defesa completa contra todo tipo de ataque cibernético que possa sofrer

## Componentes de Arquitetura da Azure

IaaS - Infraestrutura como Serviço

IaaS → Servidores e Armazenamento, Firewalls e Segurança de Rede e prédio físico do data center

Exemplo: Crie uma infraestrutura de TI de pagamento conforme o uso alugando servidores, máquinas virtuais, armazenamento, redes e sistemas operacionais de um provedor de nuvem.

PaaS - Plataforma como Serviço

PaaS → Servidores e Armazenamento, Firewalls e Segurança de Rede,  prédio físico do data center, Sistemas operacionais, Ferramentas de desenvolvimento, análise de negócios de 
gerenciamento de banco de dados.

Exemplo: Fornece um ambiente para criação, o teste e a implantação de aplicativos de software, sem focar no gerenciamento de infraestrutura subjacente.

SaaS - Software como Serviço

SaaS→ Servidores e Armazenamento, Firewalls e Segurança de Rede,  prédio físico do data center, Sistemas operacionais, Ferramentas de desenvolvimento, análise de negócios de 
gerenciamento de banco de dados, aplicativos/apps hospedados.

 Exemplo: Os usuários se conectam e usam aplicativos com base em nuvem pela internet, tipo: Microsoft Office 365, email e calendários.

Modelo de Responsabilidade Compartilhada

Pra cada modalidade existe um equilibrio entre as responsabilidades que são do exclusivas do cliente, exclusivas do provedor e de ambos os lados

Comparação de Serviço em Nuvem

IaaS:

O serviço de nuvem mais flexível.
Você confiura e gerencia o hardware para seu aplicativo.

PaaS

Focado no desenvolvimento de aplicativos
O gerenciamento de plataforma é realizado pelo provedor de nuvem.

SaaS

Modelo de preço de pagamento conforme o uso.
Os usuários pagam pelo software que utilizam em um modelo de assinatura.

Componentes de Arquitetura do Azure

Regiões, pares de regiões e regiões soberanas do Azure

Zonas de Disponibilidade

Datacenters do Azure

Regiões

As regiões são compostas de um ou mais datacenters muito próximos.

Eles fornecem flexibilidade e escala para reduzir a latência do cliente

As regiões preservam a residência dos dados com uma oferta abrangente de conformidade

Zonas de Disponibilidade

Fornece proteção contra tempo de inatividade devido a falhas do datacenter

Separe fisicamente os datacenters dentro da mesma região

Cada datacenter é equipado com alimentação, resfriamento e rede independentes.

Conectadas por meio de redes privadas de fibra óptica.

Pares de Regiões

No mínimo 300 milhas de separação entre pares de regiões.

Replicação automática para alguns serviços

Recuperação de região priorizada em casos de interrupção.

As atualizações são distribuidas sequenciamente para minimizar o tempo de inatividade

Regiões Soberanas do Azure

Serviços Governamentais dos EUA

Atende as necessidades de segurança e conformidade das agências federais, governos estaduais e locais dos EUA e seus provedores de soluções.

Recursos do Azure

- Maquinas Virtuais
- Contas de Armazenamento
- Redes Virtuais
- Serviços de aplicativos
- Banco de Dados
- Funções

Grupo de Recursos
(Web mais BD, VM, armazenamento) em um grupo 

OU

Grupo de Recursos de Web e banco de dados
Grupo de Recursos de Máquina Virtual
Grupo de Recursos de Armazenamento

Os recursos podem ser movidos para diferentes grupos de recursos

Os aplicativos podem utilizar vários grupos de recursos

Assinaturas do Azure

Uma assinatura do Azure fornece a você acesso autenticado e autorizado as contas do Azure

Limite de Cobrança: Gere relatórios de cobrança e faturas separados para cada assinatura

Limite de Controle de Acesso: Gerenciar e controlar o acesso aos recursos que os usuários podem provisionar com assinaturas específicas.

Grupos de Gerenciamento

1º - Grupos de Gerenciamento
2º - Assinaturas
3º - grupo de recursos
4º - Voltar



## Computação e Rede na Azure

A Computação do Azure é um serviço sob demanda que fornece recursos de computação, como discos, processadores, memória, rede e sistemas operacionais.

Máquinas Virtuais

As máquinas virtuais do Azure são emulações de software de computadores físicos
Inclui processador virtual, memória, armazenamento e rede.
Ofertas de IaaS que oferece personalização e controle total.

Conjunto de Dimensionamento de VMs

Os conjuntos de dimensionamento oferecem uma oportunidade de balanceamento de carga para dimensionar os recursos automaticamente.

Conjuntos de Disponibilidade de VM

A ideia de um padrão correto de um conjunto de disponibilidade, seria organizar pelo menos 3 domínio de falha, que seriam onde suas máquinas estariam localizadas e distribuídas.

Área de Trabalho Virtual do Azure

Crie um ambiente completo de virtualização da área de trabalho sem precisar executar outros serviços de gateway

Reduza o risco de que o recurso seja deixado para trás

Implantações reais de várias sessões.

Serviços de Containeres do Azure

Os contêineres do Azure fornecem um ambiente leve e virtualizado que não exige o gerenciamento do sistema operacional e pode responder a alterações sob demanda.

Instâncias de Contêiner do Azure: Uma oferta de PaaS que executa um contêiner ou pod de contêineres no Azure

Aplicativos de Contêiner do Azure: Uma oferta de PaaS, como instâncias de contêineres, que pode balancear a carga e escalar.

Serviço de Kubernetes do Azure: Um serviço de orquestração para contêineres com arquiteturas distribuidas e grandes volumes de contêineres.

Azure Functions

Uma oferta de PaaS que dá suporte a operações de computação sem servidor.
O código baseado em eventos é executado quando chamado, sem exigir uma infraestrutura de servidor durante períodos inativos.

Comparando opções de Computação do Azure

Máquinas Virtuais:

Servidor baseado em nuvem que dá suporte de lift-and-shift para a nuvem.
Útil para migrações de lift-and-shift para a nuvem.
Pacote do sistema operacional completo, incluindo o sistema operacional do host.

Área de Trabalho Virtual

Fornece uma experiência de área de trabalho do Windows baseada em nuvem.
Aplicativos dedicados para conexão e uso ou acessíveis de qualquer navegador moderno.
O logon de vários clientes permite que vários usuários façam logon no mesmo computador ao mesmo tempo.

Contêineres

Ambiente leve e em miniatura adequado para a execução de microsserviços.
Projetado para escalabilidade e resiliência por meio da orquestração.
Os aplicativos e serviços são empacotados em um contêiner que fica na parte superior do sistema operacional do host. Vários contêineres podem ficar em um sistema operacional do host.

Serviços de Aplicativos 

Os serviços de aplicativos do Azure consistem em uma plataforma totalmente gerenciada para criar, implantar e dimensionar aplicativos Web e APIs rapidamente.
Trabalha com .NET, .NET Core, Node.js, Java, Python ou php.
Oferta de PaaS com requisitos de nível corporativo de desempenho, segurança e conformidade.

Serviços de Rede do Azure

A Rede Virtual do Azure (VNet) permite que os recursos do Azure se comuniquem uns com os outros, com a Internet e com as Redes Locais.
Pontos de extremidade públicos, acessíveis de qualquer lugar na internet.
Pontos de extremidade privados, acessíveis somente de dentro da sua rede.
As sub-redes virtuais segmentam sua rede para atender às suas necessidades
O emparelhamento de rede conecta suas redes privadas diretamente.

Gateway de VPN

O Gateway de VPN é usado para enviar tráfego criptografado entre uma rede virtual do Azure e uma no local pela Internet pública.

Express Route

O ExpressRoute estende as redes locais para o Azure por meio de uma conexão privada facilitada por um provedor de conectividade.

DNS do Azure

Confiabilidade e desempenho aproveitando uma rede global de servidores de nome DNS usando a rede Anycast.
A segurança do DNS do Azure baseia-se no gerenciador de recursos do Azure, habilitando o controle de acesso baseado em função e o monitoramento e o registro em log.
Facilidade de uso para gerenciar seus recursos externos e do Azure com um único serviço DNS.
As redes.
As redes virtuais personalizáveis permitem que você use nomes de domínio privados e totalmente personalizados em suas redes virtuais privadas.




