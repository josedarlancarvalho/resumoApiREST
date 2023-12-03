# resumoApiREST

## Api REST e RESTFUL


API REST, essa arquitetura foi criada pelo cientista da computação Roy Fielding. Uma API REST é um conjunto de padrões 
arquiteturais que facilitam a comunicação entre sistemas na web. Utilizando métodos HTTP padrão, como GET, POST e DELETE, 
uma API REST permite a transferência de dados de maneira eficiente e consistente. 
Você pode pensar em uma API na web como um gateway entre clientes e recursos na Web.
Ela opera com base no princípio de representação  de recursos, onde cada recurso é identificado por uma URI única e pode ser manipulado através das operações definidas pelos métodos HTTP. 
Essa abordagem simplifica a integração entre diferentes sistemas, promovendo a escalabilidade e a interoperabilidade em aplicações web modernas.


## Restful

A API REST é uma interface que possibilita a troca segura de informações entre dois sistemas computacionais pela internet. A grande maioria das aplicações 
empresariais necessita interagir com outras aplicações internas e externas para realizar diversas tarefas.
Alguns benefícios das APIs RESTful são: escalabilidade, flexibilidade e independência.

Ao adotar a API RESTful, as aplicações podem atingir maior interoperabilidade, pois a comunicação ocorre por meio de padrões amplamente reconhecidos. 
Além disso, a simplicidade e a flexibilidade dessa abordagem tornam mais fácil a integração entre sistemas.

## Diferencas entre REST e RESTFul

"API REST" e "RESTful" são muitas vezes usados quase como sinônimos, mas existem diferenças subtis entre eles:
API REST:

Princípios do Estado Representacional de Transferência (REST): Referem-se ao estilo arquitetural que estabelece diretrizes para o design de sistemas.
API (Interface de Programação de Aplicações): Consiste em um conjunto de normas e definições que facilita a interação entre diferentes softwares.

RESTful:
Implementação Prática do REST: Uma API que adere aos princípios e práticas da arquitetura REST é considerada RESTful.
Conformidade com os Princípios REST: Isso envolve a utilização semântica dos métodos HTTP (GET, POST, PUT, DELETE), o correto emprego de URIs para 
identificação de recursos, a representação adequada de tais recursos e a ausência de estado na comunicação.

Resumimindo, uma "API RESTful" é uma concretização específica de uma "API REST". Uma API pode ser chamada de RESTful quando segue os princípios e práticas da arquitetura REST. 
O termo "RESTful" é normalmente empregado para descrever APIs que adotam esses princípios, assegurando uma comunicação eficiente, escalável e consistente entre sistemas distribuídos na web.


## HTTP verbs

Os HTTP verbs, ou métoodos HTTP, são comandos utilizados em requisições HTTP para indicar a ação que deve ser realizada sobre um recurso. Os principais métodos:

GET: Solicita a recuperação de dados de um recurso especificado.

POST: Submete dados para serem processados a um recurso especificado, criando um novo recurso ou realizando uma ação.

PUT: Atualiza um recurso existente com os dados fornecidos.

DELETE: Remove um recurso especificado.

PATCH: Aplica modificações parciais a um recurso.

Esses métodos desempenham um papel importantissimo na comunicação entre clientes e servidores na web, permitindo operações diversas como obter informações, criar, modificar ou excluir recursos em conformidade com os princípios RESTful.


## HTTP Status Code

Os códigos de status HTTP são códigos numéricos que indicam o resultado de uma solicitação HTTP entre um cliente (geralmente um navegador da web) e um servidor. Eles são divididos em cinco classes, cada uma representando uma categoria específica de resposta. Alguns exemplos notáveis incluem:
Essas categorias iniciam com um número, e esse número tem um significado.

1xx- Informativo: Indica que a solicitação foi recebida, continuará processando ou está sendo processada.
Exemplo: 100 Continue - O servidor recebeu os cabeçalhos da solicitação e indica que o cliente pode continuar com o restante da requisição ou descartá-la, dependendo das condições.

2xx- Sucesso: Indica que a solicitação foi recebida, compreendida e aceita com sucesso.
Exemplo: 200 OK - Indica que a solicitação foi bem-sucedida.

3xx- Redirecionamento: Indica que mais ações são necessárias para completar a solicitação.

Exemplo: 301 Moved Permanently - Indica que o recurso solicitado foi permanentemente movido para uma nova localização.

4xx- Erro do Cliente: Indica que o cliente parece ter cometido um erro.

Exemplo: 404 Not Found - Indica que o recurso solicitado não foi encontrado no servidor.

5xx- Erro do Servidor: Indica que o servidor falhou ao cumprir uma solicitação válida.

Exemplo: 500 Internal Server Error - Indica que ocorreu um erro interno no servidor.

Os códigos de status são essenciais para diagnosticar problemas na comunicação entre clientes e servidores, fornecendo informações sobre o resultado de uma solicitação específica.

## Autor
José Darlan de Lima Carvalho - 01466857
