Spring Boot - Projeto de Gerenciamento de Usuários
Este é um projeto Spring Boot para a criação e gerenciamento de usuários, construído a partir do Spring Initializr usando a ferramenta Maven. O projeto inclui as seguintes dependências essenciais:

Dependências
Spring Boot DevTools: Essa dependência oferece recursos como reinicialização rápida de aplicativos, LiveReload e configurações para uma experiência de desenvolvimento aprimorada.

Lombok: Uma biblioteca de anotações Java que reduz a necessidade de escrever código repetitivo, tornando o código mais conciso e legível.

Spring Web: Esta dependência é fundamental para a criação de aplicativos da web, incluindo serviços RESTful, usando o Spring MVC. O Apache Tomcat é utilizado como o contêiner incorporado padrão para execução do aplicativo.

h2 Database: O H2 é um banco de dados em memória rápido que suporta JDBC e R2DBC APIs. Com uma pegada pequena de apenas 2 MB, ele oferece suporte para modos incorporados e de servidor, bem como uma interface de console baseada em navegador.

Funcionalidades
Neste projeto, foram implementadas as seguintes funcionalidades de gerenciamento de usuários:

Cadastro de Usuários: Um método que permite o cadastro de novos usuários no sistema.

Consulta de Usuários: Um método que retorna todos os usuários cadastrados no sistema.

Exclusão de Usuário: Um método que exclui um usuário com base em seu ID.

O projeto é inicializado com três registros de exemplo no banco de dados H2 para facilitar o teste e o desenvolvimento.

Como Executar
Para executar este projeto localmente, siga estas etapas:

Clone este repositório para o seu ambiente de desenvolvimento.
Abra o projeto em sua IDE preferida.
Execute o aplicativo Spring Boot. Isso inicializará o servidor embutido do Tomcat e disponibilizará os serviços da API.
Acesse a API em seu navegador ou por meio de um cliente REST para testar as funcionalidades disponíveis.
Certifique-se de que todas as dependências do projeto estejam corretamente configuradas no seu ambiente.

Este projeto serve como um exemplo simples de aplicação Spring Boot para gerenciamento de usuários. Sinta-se à vontade para expandir e personalizar conforme suas necessidades.

Espero que este README aprimorado seja útil para você! Se você tiver alguma dúvida ou precisar de mais informações, não hesite em perguntar.
