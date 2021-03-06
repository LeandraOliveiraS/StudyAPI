# :link: API RESTFUL

## :pencil: API

Uma ótima analogia para se entender como se dá o funcionamento de uma API é a da logística adotada pelos restaurantes. Onde se tem, clientes, garçons e uma cozinha. Em uma API não é diferente, tem-se o cliente (Client), a (API) que é responsável por levar os pedidos até o servidor e o servidor(Server) que representa a cozinha e que por sua vez faz a entrega das requisições realizadas pelos cliente(browser) e levados pela API.

O Acrônimo API já foi bastante citado, mas qual o seu significado? 

**API** - **A**pplication **P**rogramming **I**nterface.

Pode-se definir como uma ***Interface de Programação de Aplicações***, basicamente é um conjunto de rotinas e padrões estabelecidos por uma aplicação, possibilitando que outras aplicações façam uso de suas funcionalidades. Além disso, realiza as seguintes funções.

:heavy_check_mark: É responsável por estabelecer a comunicação entre diferentes tipos de serviços.

:heavy_check_mark: Realiza a intermediação entre as tecnologias utilizadas nas aplicações e assim, possilita também a troca de informações.

## :left_right_arrow: REST

**R**epresentational **S**tate **T**ransfer. 
Realiza a transferência de estado representativo, onde são realizadas transferências de dados, geralmente, utilizando o protocolo HTTP de forma:

- [X] Símbolica
- [X] Figurativa
- [X] Representativa
- [X] Maneira Didática

Desse modo, o REST realiza a delimitação de algumas obrigações nas transferências de dados, essas por sua vez, são chamadas de *Resources* que pode ser uma entidade ou um objeto.

## :pushpin:	 Constrainsts para ser uma API RESTful

 :clipboard:	**Uniform Interface:** 
 - [X] Uniformidade
 - [X] Constância
 - [X] Padrão na construção da interface.

  A API precisa ser coerente para quem vai consumi-lá. Precisa fazer sentido para o cliente.
   Logo, precisam possuir: 

   :heavy_check_mark: Uso correto dos verbos HTTP; 

   :heavy_check_mark: Endpoints coerentes (todos os endpoints no plural, por exemplo);

   :heavy_check_mark: Utilização somente uma linguagem de comunicação (json); 

   :heavy_check_mark: Realizar envio de respostas aos clientes.

:computer: **Client-server:** Separação do cliente e do armazenamento de dados (servidor), dessa forma, é possível ter portabilidade no sistema.
Por exemplo, utilizando React para WEB e React Native para aplicações no smartphone.

:memo: **Stateless:** Cada requisição que o cliente faz para o servidor, deverá conter todas as informações necessárias para o servidor entender e responder (RESPONSE) a requisição (REQUEST).

  - Exemplo: A sessão do usuário deverá ser enviada em todas as requisições, para saber se aquele usuário está autenticado e apto a usar os serviços, e o servidor     não pode lembrar que o cliente foi autenticado na requisição anterior, para isso é interessante o uso de tokens.

:arrows_clockwise: **Cacheable:** As respostas para uma requisição, deverão ser explicitas ao dizer se aquela requisição, pode ou não ser cacheada pelo cliente.

:mag_right: **Layered System:** O cliente acessa a um endpoint, sem precisar saber de questões como: 

 - Complexidade
 - Passos estão sendo necessários para o servidor responder a requisição
 - Quais outras camadas o servidor estará lidando, para que a requisição seja respondida.

:wrench: **Code on demand (optional):** Dá a possibilidade da aplicação captar códigos, como o javascript, por exemplo, e executar no cliente.


# :notebook: RESTFUL

RESTful, é a aplicação dos padrões REST.






