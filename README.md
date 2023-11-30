# Api Rest 

API (Interface de Programação de Aplicações) REST (Transferência de Estado Representacional) é um estilo arquitetural para o desenvolvimento de serviços web.

* Baseada no conceito de recursos (entidades ou serviços) identificados por URLs.
* Utiliza os princípios do protocolo HTTP para comunicação.
* É stateless, ou seja, cada solicitação do cliente contém toda a informação necessária para entender e processar a requisição.

## APIs 

As APIs são usadas para integrar novas aplicações com sistemas de software existentes. Isso aumenta a velocidade de desenvolvimento porque cada funcionalidade não precisa ser escrita do zero. Você pode usar APIs para aproveitar o código existente.

## O que significa REST?

REST não é um protocolo ou padrão, mas sim um conjunto de restrições de arquitetura. Os desenvolvedores de API podem implementar a arquitetura REST de maneiras variadas.

### Implementação RESTful

* Representam entidades ou serviços específicos que podem ser manipulados.
* Cada recurso é identificado por uma URI (Uniform Resource Identifier).

## HTTP verbs

* GET: Obtém informações sobre um recurso.
* POST: Cria um novo recurso.
* PUT: Atualiza um recurso existente.
* DELETE: Remove um recurso.
* PATCH: Atualiza parcialmente um recurso.

## HTTP Status Code

* São códigos numéricos retornados pelo servidor HTTP para indicar o resultado da solicitação do cliente.
* Esses códigos são divididos em cinco classes, cada uma representando uma categoria específica de resposta. 

    * Exemplos
    
    200 OK: Indica que a solicitação foi bem-sucedida.
    
    201 Created: Usado quando um novo recurso é criado com sucesso.

    204 No Content: A solicitação foi processada com sucesso, mas não há conteúdo a ser retornado.
    
    400 Bad Request:Indica que a solicitação do cliente é inválida ou malformada.
    
    401 Unauthorized: O cliente deve se autenticar para obter a resposta desejada.

    404 Not Found: O recurso solicitado não foi encontrado no servidor.

    500 Internal Server Error: Indica um erro interno no servidor, geralmente algo inesperado.


    ## Concluindo...
    
    As APIs RESTful proporcionam uma abordagem eficaz para desenvolver serviços web interoperáveis e escaláveis. Ao aderir aos princípios REST, como a utilização adequada dos verbos HTTP e códigos de status, os desenvolvedores podem criar sistemas robustos e fáceis de entender, facilitando a integração entre diferentes aplicações e plataformas.

Autora do resumo: Maria Luíza Damião Carvalho- 01601881
