# Api REST e RESTFul

## Introdução

Uma API REST (Interface de Programação de Aplicações baseada em Transferência de Estado Representacional) é um conjunto de regras que define como aplicativos ou dispositivos podem se conectar e comunicar uns com os outros. Projetada para seguir os princípios de design do REST, a API REST se baseia na arquitetura Representacional State Transfer (REST).

## REST vs RESTful

REST refere-se aos princípios de design que compõem uma API, enquanto RESTful é uma abordagem específica para implementar esses princípios em um sistema. Em resumo, todas as APIs REST são baseadas em RESTful, mas nem toda API RESTful é estritamente REST.

## Diferenças entre REST e RESTFul

A diferença chave entre REST e RESTful reside na aderência aos princípios REST. Uma API RESTful adere rigorosamente a esses princípios, incluindo uma interface uniforme, desacoplamento cliente-servidor, ausência de estado, capacidade de armazenamento em cache, arquitetura em camadas e, opcionalmente, código sob demanda.

## HTTP Verbs

Os métodos HTTP (também conhecidos como HTTP verbs) são usados em uma API REST para indicar a ação a ser executada em um recurso. Alguns dos principais métodos incluem:

- **GET:** Recupera a representação de um recurso.
- **POST:** Submete dados a um recurso, causando uma mudança de estado ou efeitos colaterais no servidor.
- **PUT:** Substitui todas as representações atuais do recurso de destino pelos dados da requisição.
- **DELETE:** Remove um recurso específico.
- **PATCH:** Aplica modificações parciais em um recurso.
- E outros, como HEAD, OPTIONS, CONNECT, e TRACE.

## HTTP Status Code

O Status Code HTTP é uma parte essencial da comunicação entre cliente e servidor, indicando o resultado da tentativa de solicitação. Alguns códigos comuns incluem:

- **2xx (Success):** Indica que a ação foi recebida, compreendida e aceita com sucesso.
- **3xx (Redirection):** Indica que mais ações precisam ser tomadas para completar a solicitação.
- **4xx (Client Error):** Indica que a solicitação contém sintaxe incorreta ou não pode ser atendida.
- **5xx (Server Error):** Indica que o servidor falhou em cumprir uma solicitação aparentemente válida.

---

**Autor do resumo:** Mateus Rebêlo Fernandes - 01559114
