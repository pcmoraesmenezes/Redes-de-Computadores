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