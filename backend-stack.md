## Stack tecnológico

### Back-end

#### Spring Boot
O Spring Boot facilita a criação de aplicações, onde é possível criar um projeto apenas com os componentes necessários, com pouca ou nenhuma configuração e simplesmente executar. "Just run".
Principais características:

- Criar aplicativos Spring stand-alone;
- é possível incorporar Tomcat, Jetty ou Undertow diretamente (sem necessidade de implantar arquivos WAR);
- Fornece dependências ‘iniciais’ opinativas para simplificar sua configuração de compilação;
- Possibilita configurar automaticamente o Spring com bibliotecas de terceiros sempre que possível;
- Fornece recursos prontos para produção, como métricas, verificações de integridade e configuração externalizada;
- Absolutamente não é necessário nenhuma geração de código ou configuração em XML.

https://gist.github.com/frekele/42387c97838b6e173ff9e10cdc61935e


#### Spring Data
A missão do Spring Data é fornecer um modelo de programação baseado em Spring que seja familiar e consistente para acesso a dados, enquanto ainda retém as características especiais do armazenamento de dados subjacente.
Ele facilita o uso de tecnologias de acesso a dados, bancos de dados relacionais e não relacionais, estruturas de redução de mapa e serviços de dados baseados em nuvem. Este é um projeto abrangente que contém muitos subprojetos que são específicos para um determinado banco de dados.
Os subprojetos são desenvolvidos com trabalho em conjunto com muitas empresas e desenvolvedores que estão por trás dessas tecnologias interessantes.
Principais características:
- Repositório poderoso e abstrações de mapeamento de objeto personalizadas;
- Derivação de consulta dinâmica de nomes de métodos de repositório;
- Classes de base de domínio de implementação que fornecem propriedades básicas;
- Suporte para auditoria transparente (created, last changed);
- Possibilidade de integrar código de repositório personalizado;
- Fácil integração Spring via JavaConfig e namespaces XML personalizados;
- Integração avançada com controladores Spring MVC.

https://gist.github.com/frekele/249f63d202be189ffd349c675b8949ff

#### Lombok
O Lombok é uma biblioteca Java focada em produtividade e redução de código boilerplate que por meio de anotações adicionadas ao nosso código ensinamos o compilador (maven ou gradle) durante o processo de compilação a criar código Java.

https://gist.github.com/frekele/0223441d0d30ee455bdf18ff7775256c

#### Hibernate Validator
O Hibernate Validator permite expressar e validar as restrições da aplicação. A fonte de metadados padrão são anotações, com a capacidade de substituir e estender por meio do uso de XML. Ele não está vinculado a uma camada de aplicativo ou modelo de programação específico e está disponível para programação de aplicativo de servidor e cliente.

https://gist.github.com/frekele/fb299752273c2ccb160ecb784b65a4eb

#### JUnit 5
JUnit é um framework open-source que possibilita a criação de testes unitários em Java. A maioria das IDEs do mercado incorporam o JUnit dentro de seu ambiente de desenvolvimento, facilitando assim o uso desse framework.
O JUnit possibilita a criação das classes de testes. Estas classes contêm um ou mais métodos para que sejam realizados os testes, podendo ser organizados de forma hierárquica, de forma que o sistema seja testado em partes separadas, algumas integradas ou até mesmo todas de uma só vez. Além disso, este framework tem como objetivo, facilitar a criação de casos de teste, além de permitir escrever testes que retenham seu valor ao longo do tempo, ou seja, que possam ser reutilizáveis.

https://gist.github.com/frekele/43494cb87b2b3433f0adbe06cbadf161

#### Mockito
Uma das características fundamentais de um bom teste unitário é ser isolado. Para que ele execute rápido, fornecendo feedback ao desenvolvedor, ele deve ser isolado. Quando digo isolado é que ele deve ser isolado de dependências externas: acesso à rede, ao sistema de arquivos, a banco de dados etc. É aí que os mocks podem nos ajudar e que o Mockito entra em ação.
O Mockito é um framework de mocking para uso em testes de unidade na linguagem Java. Ele possui uma API clara e simples. A curva de aprendizado é suave e ele possui uma documentação bastante útil, recheada de exemplos.
Principais características:
- O setup para a criação de um mock, diferentemente de outros frameworks, é bastante simples;
- Possibilidade de criar mocks tanto de classes concretas como de interfaces;
- Criação de mocks por meio de anotações: @Mock;
- Facilidade na verificação de erros: a verificação de testes que falham é simples, bastando olhar o stack trace disponibilizado;
- Permite verificar a quantidade de vezes que um método foi chamado;
- Permite a verificação por meio de matchers de argumentos (any(), anyObject(), anyString() …);
- Permite a verificação da ordem das chamadas de um método.

https://gist.github.com/frekele/cbb9c1e6daf9507a5d449d1c32908a8c

#### JaCoCo
JaCoCo é uma biblioteca de cobertura de código gratuita para Java, que foi criada pela equipe EclEmma com base nas lições aprendidas com o uso e integração de bibliotecas existentes por muitos anos.
Com JaCoCo é possível obter analise de cobertura de código detalhado.

#### Apache Maven
O Apache Maven é uma ferramenta de automação e gerenciamento de projetos Java, embora também possa ser utilizada com outras linguagens. Ela fornece às equipes de desenvolvimento uma forma padronizada de automação, construção e publicação de suas aplicações, agregando agilidade e qualidade ao produto final. Por ser extremamente flexível, permite que sejam adicionados plugins a si, para estender suas funcionalidades nativas.

#### SpringDoc
A biblioteca java springdoc-openapi ajuda a automatizar a geração de documentação API Swagger-UI usado em projetos com Spring Boot . springdoc-openapi funciona examinando a app em tempo de execução para inferir a semântica da API com base nas configurações do spring, estrutura de classe e várias anotações.

#### MongoDB
O MongoDB é um banco de dados orientado a documentos (document database) no formato JSON, ou seja, diferente de um banco de dados relacional, ele não possui como restrição a necessidade de ter as tabelas e colunas criadas previamente, permitindo que um documento represente toda a informação necessária, com todos os dados que você queira, no formato de um JSON.
Assim como em um JSON utilizado em comunicações HTTP entre aplicações, no documento do MongoDB podem existir valores simples, como números, strings e datas, assim como também podem existir listas de valores e listas de objetos.
Os documentos são agrupados em collections. E um conjunto de collections forma um database (banco de dados). O MongoDB permite que seu database seja replicado para outros servidores, aumentando assim a disponibilidade de suas informações, sendo esse recurso conhecido por replica set. Dessa forma, cada servidor terá uma cópia dos dados.

