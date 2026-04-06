Este projeto é um serviço simples desenvolvido com Spring Boot que tem como objetivo retornar uma 
saudação personalizada. A aplicação recebe um nome como parâmetro, podendo ser informado tanto via 
PathVariable quanto via RequestParam, e retorna uma mensagem de saudação de forma dinâmica.

O serviço também utiliza configurações externalizadas para definir a mensagem padrão e o nome padrão, 
permitindo fácil customização através de arquivos .properties. Além disso, há suporte a 
internacionalização básica, com diferentes perfis configurados (como espanhol e inglês), possibilitando 
alterar o idioma da saudação conforme o ambiente ativo.
