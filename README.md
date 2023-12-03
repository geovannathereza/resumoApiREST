# ApiREST e RESTFul
A princípio, REST é um agrupamento de restrições arquitetônicas e não um padrão ou protocolo, como muitas pessoas pensam. Os desenvolvedores de API podem implementar estas restrições de inúmeras maneiras. A API REST é uma interface de programação de aplicativos que está de acordo com as restrições do estilo arquitetural REST e permite a interação com serviços web RESTful.

Quando é feita uma solicitação do cliente utilizando a API RESTful, é transferida uma representação do estado do recurso para quem solicita ou para o endpoint. Esta informação, é entregue em um dos vários formatos via HTTP.

## Diferenças entre REST e RESTFUL
Enquanto a API REST trata-se de uma Interface de Programação de Aplicações que segue os princípios arquiteturais Representational State Transfer, o RESTful descreve uma API que adere estritamente aos princípios REST. Portanto, todas as APIs RESTful são APIs REST, porém nem todas as APIs REST são necessariamente RESTful.

## HTTP verbs
Os HTTP Verbs são métodos que permitem que os clientes e servidores possam interagir, assim facilitando a comunicação na web. Cada método tem um objetivo específico, contribuindo para a funcionalidade mais dinâmica em um sistema HTTP.
Alguns métodos são:

GET - Este método solicita os dados de um recurso especificado.

HEAD - Este método solicita uma resposta idêntica a uma solicitação GET, porém sem o corpo da resposta.

POST - Este método envia dados para ser processado em um recurso específico.

PUT - Este método substitui todas as representações atuais do recurso de destino pela carga útil da solicitação.

DELETE - Este método exclui um recurso especificado.

CONNECT - Este método estabelece um túnel para um servidor identificado pelo recurso destinado.

OPTIONS - Este método irá descrever as opções de comunicação para o recurso destinado.

TRACE - Este método serve para executar um teste de loopback de mensagem durante o caminho para o recurso de destino.

PATCH - Este método irá aplicar modificações parciais em um recurso.

## HTTP status code

Os códigos de status HTTP são retornados por um servidor em resposta a uma solicitação. Apresentam o resultado da tentativa de realizar uma ação solicitada. Alguns exemplos comuns incluem:

200 OK - A solicitação foi bem-sucedida. O servidor atendeu à solicitação com êxito.

201 Created - A solicitação foi bem-sucedida, e foi criado um novo recurso como resultado.

400 Bad Request - Indica que a solicitação não pôde ser processada pelo servidor.

401 Unauthorized - O cliente deve se autenticar para obter a resposta solicitada. Significa que a autenticação é necessária e falhou.

404 Not Found - Indica que o servidor não encontrou um recurso solicitado.

500 Internal Server Error - Indica que algo deu errado no servidor, por uma condição imprevista que o impediu de cumprir a solicitação.

---

Autor do resumo: Geovanna Thereza Tavares da Silva - 01523550
