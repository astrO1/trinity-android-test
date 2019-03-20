Trinity - Teste para desenvolvimento Android

Objetivo 1 ( Android )
Criação de uma tela para autenticação do usuário, contendo os seguintes elementos:
Ícone aleatório do aplicativo;
2 inputs sendo 1 de text do tipo e-mail e outro de password;
Botão com a informação: Logar;
(Bônus) - animação da validação dos dados inseridos;

Criação de validações para os 2 inputs, as seguintes validações devem acontecer com uma mensagem associada a cada input:
Todos os campos devem ser preenchidos;
Digite um E-mail válido;

Criação de uma tela Home, onde o usuário só poderá ter acesso após concluir com sucesso a sua autenticação, contendo os seguintes elementos:
Texto com a seguinte informação : Logado como email_do_usuario_logado;
Botão com a seguinte informação : Deslogar;


Logo após logar no sistema os dados do usuário devem ser persistidos através da interface Shared Preferences;


Objetivo 2 ( API )
Desenvolva uma API utilizando uma linguagem da sua preferência para o desenvolvimento da API.
Criar um serviço de autenticação onde irá ser consumido pela aplicação Android após o usuário clicar em Logar.
Crie um banco de dados para a comunicação entre a Aplicação e a API com as seguintes colunas e nomenclaturas:
Banco de dados : db_android_teste
Tabela: android_user
Colunas:user_id, user_email, user_password

Tela Login


 
 
 
 
 
 
Tela Home



Requisitos
Use Java para o desenvolvimento, utilizar um padrão de projeto MVC ou MVP será tratado como um Bônus.





A comunicação entre a Aplicação e a API deve ser utilizado o formato JSON, a resposta da API para a Aplicação deve seguir o padrão como no exemplo abaixo, lembrando caso exista token de autenticação na resposta será considerado bônus:
O Ícone do projeto pode ser encontrado ou feito por você mesmo através do link:
https://www.flaticon.com/search?word=app

Padrões de código
Ao trabalhar no projeto, use um estilo de codificação consistente. Será tratado como um bônus a utilização do padrão de projeto MVC ou MVP.
Garantia da Qualidade
O que você precisa fazer para obter uma pontuação alta? Basta atender todas as questões abaixo:
Geral
São cumpridos todos os requisitos definidos acima?
O aplicativo está funcionando sem erros? Todas as validações estão sendo bem tratadas?
Padrões de codificação
A página está usando um estilo de codificação JAVA consistente?
O desenvolvimento da API está possuindo uma organização e uma codificação consistente?
