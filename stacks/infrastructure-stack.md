## Stack tecnológico - Infraestrutura

#### GitHub.com
GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git. Ele permite que programadores, utilitários ou qualquer usuário cadastrado na plataforma contribuam em projetos privados e/ou Open Source de qualquer lugar do mundo. GitHub é amplamente utilizado por programadores para divulgação de seus trabalhos ou para que outros programadores contribuam com o projeto, além de promover fácil comunicação através de recursos que relatam problemas ou mesclam repositórios remotos (issues, pull request).
O GitHub é mundialmente usado e chega a ter mais de 36 milhões de usuários ativos mundialmente contribuindo em projetos comerciais ou pessoais. Hoje o GitHub abriga mais de 100 milhões de projetos,[2] alguns deles que são conhecidos mundialmente. WordPress, GNU/Linux, Atom, Electron. GitHub também oferece suporte ao recurso de organizacão que é amplamente utilizado por aqueles que querem uma escala maior para seus projetos. Na maioria das vezes, o recurso é usado por empresas já existentes como a Google, Microsoft e WordPress. Conforme Wikipedia.

#### Github Action (CI&CD)
O GitHub Actions ajuda a automatizar os fluxos de trabalho de desenvolvimento de software de dentro do GitHub. Você pode implantar fluxos de trabalho no mesmo local em que armazena código e colabora em solicitações de pull e problemas.
No GitHub Actions, um fluxo de trabalho é um processo automatizado que você configura no repositório do GitHub. Você pode criar, testar, empacotar, lançar ou implantar qualquer projeto no GitHub com um fluxo de trabalho.
Cada fluxo de trabalho é composto por ações individuais que são executadas após ocorrer um evento específico (como uma solicitação de pull). As ações individuais são scripts empacotados que automatizam tarefas de desenvolvimento de software.

#### AWS ECS (Elastic Container Service)
O Amazon Elastic Container Service (Amazon ECS) é um serviço gerenciado de orquestração de contêineres. Clientes como Duolingo, Samsung, GE e Cookpad usam o ECS para executar seus aplicativos mais confidenciais e essenciais à missão devido à segurança, confiabilidade e escalabilidade.
O ECS é uma ótima opção para executar contêineres por vários motivos. Primeiro, você pode optar por executar seus clusters do ECS usando o AWS Fargate, que é computação sem servidor para contêineres. O Fargate elimina a necessidade de provisionar e gerenciar servidores, permite que você especifique e pague pelos recursos por aplicativo, além de aumentar a segurança ao conceber aplicativos isolados. Segundo, o ECS é amplamente utilizado na Amazon para fornecer serviços como o Amazon SageMaker, AWS Batch, Amazon Lex e o mecanismo de recomendação da Amazon.com, garantindo que o ECS seja testado extensivamente em termos de segurança, confiabilidade e disponibilidade

#### AWS ECR (Elastic Container Registry)
O Amazon Elastic Container Registry (ECR) é um registro de contêineres do Docker totalmente gerenciado que permite que desenvolvedores armazenem, gerenciem e implantem facilmente imagens de contêineres do Docker. O Amazon ECR é integrado ao Amazon Elastic Container Service (ECS), o que simplifica o seu desenvolvimento para o fluxo de trabalho de produção. O Amazon ECR elimina a necessidade de operar os seus próprios repositórios de contêiner ou de preocupar-se sobre a escalabilidade da infraestrutura subjacente. O Amazon ECR hospeda suas imagens em uma arquitetura altamente disponível e escalável, o que permite que você implante de forma confiável contêineres para aplicativos.

#### AWS Fargate (SERVERLESS)
O AWS Fargate é um mecanismo de computação sem servidor para contêineres que funciona com o Amazon Elastic Container Service (ECS) e com o Amazon Elastic Kubernetes Service (EKS). O Fargate facilita a sua concentração no desenvolvimento de aplicativos. O Fargate elimina a necessidade de provisionar e gerenciar servidores, permite que você especifique e pague pelos recursos por aplicativo, além de aumentar a segurança ao conceber aplicativos isolados.
O Fargate aloca a quantidade certa de computação, eliminando a necessidade de escolher instâncias e ajustar a escala da capacidade do cluster. Você só paga pelos recursos exigidos para a execução dos contêineres, por isso não há excesso de provisionamento nem pagamento por servidores adicionais. O Fargate executa cada tarefa ou pod no próprio kernel do serviço, disponibilizando às tarefas e aos pods ambientes próprios isolados de computação. Isso permite que o aplicativo seja concebido para oferecer isolamento da carga de trabalho e segurança otimizada. É por isso que clientes, como Vanguard, Accenture, Foursquare e Ancestry, escolheram executar aplicativos de missão crítica no Fargate.

#### AWS Route53 (DNS)
O Amazon Route 53 é um Domain Name System (DNS) na nuvem AWS altamente disponível e escalável. Ele foi projetado para oferecer aos desenvolvedores e empresas uma maneira altamente confiável e econômica de direcionar os usuários finais aos aplicativos de Internet, convertendo nomes como www.example.com para endereços IP numéricos como 192.0.2.1, usados pelos computadores para se conectarem entre si.

#### AWS CloudFront (CDN)
O Amazon CloudFront é um serviço rápido de rede de entrega de conteúdo (CDN) que entrega dados, vídeos, aplicativos e APIs a clientes em todo o mundo com segurança, baixa latência e altas velocidades de transferência em um ambiente de uso facilitado para desenvolvedores. O CloudFront é integrado com a AWS; ambos são locais físicos conectados diretamente à infraestrutura global da AWS, bem como a outros serviços da AWS. O CloudFront funciona de forma transparente com serviços como AWS Shield para mitigação de ataques DDoS; Amazon S3, Elastic Load Balancing ou Amazon EC2 como origens para os aplicativos; e Lambda@Edge para executar código personalizado mais perto dos usuários dos clientes e personalizar a experiência dos usuários.

#### AWS VPC (Virtual Private Cloud)
A Amazon Virtual Private Cloud (Amazon VPC) permite provisionar uma seção da Nuvem AWS isolada logicamente na qual é possível executar recursos da AWS em uma rede virtual que você mesmo define. Você tem controle total sobre seu ambiente de redes virtuais, incluindo a seleção do seu próprio intervalo de endereços IP, a criação de sub-redes e a configuração de tabelas de rotas e gateways de rede. Você pode usar IPv4 e IPv6 na VPC para acessar recursos e aplicativos com segurança e facilidade.

#### AWS ELB (Elastic Load Balancing)
O Elastic Load Balancing distribui automaticamente o tráfego de entrada de aplicativos entre diversos destinos, como instâncias do Amazon EC2, contêineres, endereços IP e funções Lambda. O serviço pode lidar com a carga variável de tráfego dos aplicativos em uma única zona de disponibilidade ou em diversas zonas de disponibilidade. O Elastic Load Balancing oferece três tipos de load balancers, todos eles com a alta disponibilidade, a escalabilidade automática e a segurança robusta necessárias para tornar os aplicativos tolerantes a falhas.

#### AWS S3 (Simple Storage Service)
O Amazon Simple Storage Service (Amazon S3) é um serviço de armazenamento de objetos que oferece escalabilidade, disponibilidade de dados, segurança e performance líderes do setor. Isso significa que clientes de todos os tamanhos e setores podem usá-lo para armazenar qualquer volume de dados em vários casos de uso, como data lakes, sites, aplicativos para dispositivos móveis, backup e restauração, arquivamento, aplicações empresariais, dispositivos IoT e análises de big data. O Amazon S3 fornece recursos de gerenciamento fáceis de usar, de maneira que você possa organizar os dados e configurar os controles de acesso refinados para atender a requisitos específicos comerciais, organizacionais e de conformidade. O Amazon S3 foi projetado para 99,999999999% (11 9s) de durabilidade e armazena dados para milhões de aplicações para empresas de todo o mundo.

#### Docker
Docker é uma plataforma open source para desenvolvedores e administradores possam criar, testar e implantar aplicações distribuídas.
Docker é uma plataforma que permite criar e executar "conteiners". Com o Docker podemos colocar as aplicações em um contêiner que possui todos os recursos necessários e que permite e testar, implantar e publicar mais rapidamente. Isso acaba com aquele velho problema onde o desenvolvedor cria uma aplicação em sua maquina, ou em uma maquina virtual, mas no momento da publicação ela não se comporta da maneira esperada.

#### SonarCloud (SonarQube)
O SonarCloud é um serviço em nuvem oferecido pela SonarSource e baseado no SonarQube. O SonarQube é uma plataforma open source amplamente adotada para inspecionar continuamente a qualidade do código-fonte e detectar bugs, vulnerabilidades e "code smells" em mais de 20 linguagens de programação.
O SonarCloud lê métricas do código fonte da aplicação enviadas para o serviço para montar um painel para expor as métricas daquele código e através de um mínimo aceitável (Quality Gates) ele te diz onde estão possíveis bugs, "code smells" e outras variáveis.

#### Codecov e Codacy (Cobertura de Código)
Codecov e Codacy fornecem ferramentas altamente integradas para agrupar, mesclar, arquivar e comparar relatórios de cobertura de código.

#### MongoDB Atlas
MongoDB Atlas é o serviço de banco de dados em nuvem global para aplicativos modernos. Implante MongoDB totalmente gerenciado em AWS, Google Cloud e Azure com a melhor automação e práticas comprovadas que garantem disponibilidade, escalabilidade e conformidade com os padrões de privacidade e segurança de dados mais exigentes.
