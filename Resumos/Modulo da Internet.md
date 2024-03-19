# Sumário

## Estrutura da Internet

A definição da internet por si só é algo complexo, pois a sua crescente mudança tanto nos componentes de hardware e software tornam esse conceito muito amplo.

Nesse contexto surgem o ISP (Internet Service Provider) que são empresas que fornecem acesso a internet, como exemplo temos a Vivo, Claro, Tim, Oi, entre outras.

### ISP

Um ISP pode possuir algumas estruturas, tais como: 

- ISP Local: Aquela que fornece serviços de internet em uma área geográfica muito restrita, como cidade ou bairro

- ISP Regional: Aquele que opera em uma área geográfica mais ampla, abrangendo várias cidades e ate paises. 

- ISP de Rede Corporativa: Nesse caso o ISP atende a demanda exclusiva de uma empresa, fornecendo serviços de internet para a mesma.

O que determina o tipo de ISP no geral são

- Escopo Geográfico conforme visto anteriormente

- Serviços oferecidos

- Segmento do mercado 

### Redes de Comutação de Circuitos

Este modelo de rede é baseado na ideia de que a comunicação entre dois pontos é feita por um caminho dedicado, ou seja, um circuito é estabelecido entre os dois pontos e a comunicação é feita por esse circuito.

O paradigma envolvido aqui é que a conexão entre o remetente e o destinatário é estabelecida antes da transmissão de dados.

Envolve três etapas:

- Estabelecimento do circuito - Os recursos necessários para a comunicação são reservados ao longo do caminho entre os dois pontos; Um caminho físico é estabelecido entre os dois pontos; Ocorre a negociação entre os nós intermediários para a criação do circuito.

- Transferência de informação - Após o estabelecimento do circuito onde é feito um caminho fisico entre os dois pontos, os dados são transmitidos ao longo deste caminho fisico dedicado de forma continua; Durante essa fase não há interrupção dos dados já que o caminho fisico é reservado para a comunicação.

- Desconexão do circuito - Após a transmissão dos dados, o circuito é desconectado e os recursos são liberados; Os recursos alocados para a comunicação são liberados e podem ser utilizados por outras comunicações.

#### Problemas

- Ineficiência: Os recursos podem permanecer subutilizados durante os períodos de inatividade, isso implica que há um desperdício de recursos.

- Dificuldade de lidar com mudanças de tráfego: Uma vez que os circuitos são estabelecidos, é difícil lidar com mudanças no tráfego, necessidades dinâmicas podem resultar em problemas e súbitas alterações na rota podem causar ainda mais devido a necessidade de reestabelecer o circuito.

Enlances -> Links de comunicação entre os nós da rede

Comutadores -> Troca de pacotes entre os enlaces

Um protocolo de redes de computadores nada mais é do que uma solicitação de uma comunicação entre dois ou mais dispositivos, onde é estabelecido um conjunto de regras que determinam a forma como a comunicação será realizada. Primeiro é feito o estabelecimento da comunicação (Solicitação de conexão TCP), depois a resposta a solicitação (Resposta de conexão TCP), que nem sempre é aceita, e por fim a comunicação em si.

HFC (Hybrid Fiber-Coaxial) é um tipo de arquitetura de rede de comunicação utilizada principalmente para fornecer serviços de televisão a cabo, acesso à internet e telefonia. Esta tecnologia combina fibras ópticas e cabos coaxiais para transmitir dados de forma eficiente.

DSL (Digital Subscriber Line) é uma tecnologia de comunicação que fornece conexão de internet de alta velocidade através das linhas telefônicas convencionais de cobre. Ela utiliza uma porção da banda de frequência da linha telefônica para transmitir dados de forma digital, permitindo que os usuários acessem a internet enquanto ainda usam a linha telefônica para chamadas de voz. Essa possibilidade se da através da passagem das informaçõe estarem em frequências diferentes.

óptica que utilizam componentes ópticos passivos para fornecer serviços de telecomunicações, como acesso à internet, televisão por assinatura e telefonia.

Essas redes são chamadas de "passivas" porque não requerem energia ou eletrônicos ativos entre o provedor de serviços e o assinante. Em vez disso, os sinais ópticos são transmitidos de forma passiva ao longo da rede, utilizando divisores ópticos passivos e componentes de multiplexação.


Os terminais de rede óptica, também conhecidos como ONTs (Optical Network Terminals), são dispositivos utilizados em redes ópticas passivas (PONs - Passive Optical Networks) para fornecer serviços de comunicação, como acesso à internet, televisão por assinatura e telefonia, aos assinantes finais.