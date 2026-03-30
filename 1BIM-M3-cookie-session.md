# 1BIM-M3 - Cookies e Sessions

## Integrantes
- Murilo Lazzarini 
- Pedro Gregio Boriero  


## Exercício 1: Diferença entre Cookies e Sessions

Cookies são dados que ficam salvos no navegador do usuário, já as sessions guardam as informações no servidor.  
Cookies são considerandos menos seguros, pois podem ser alterados pelo próprio usuário.  
Por ouro lado as sessions são mais seguras, porque o navegador só recebe um identificador.  
Cookies são mais usados para coisas simples, como preferências ou lembrar informações básicas.  
Sessions são ideais para login e controle de acesso.  
Outra diferença é que cookies podem continuar salvos mesmo depois de fechar o navegador.  
Já as sessions geralmente acabam quando o usuário sai ou fecha o navegador.


## Exercício 2: Aplicação em Loja Virtual

Para manter o usuário logado, o melhor é se ultilizar sessions, porque são mais seguras.  
Os itens do carrinho também podem ficar na session enquanto o usuário navega.  
Assim, essas informações ficam protegidas no servidor.  
Os cookies podem ser usados para guardar preferências, como idioma ou tema do site.  
Também podem servir para lembrar o usuário, mas sem guardar dados importantes.  
Usando os dois juntos, o sistema fica mais completo.  
Cada um é usado naquilo que faz melhor.


## Exercício 3: Teste com Cookies

Quando executamos pela primeira vez, o cookie ainda não aparece porque ele só funciona na próxima requisição.  
Depois que atualizamos a página, o navegador já envia o cookie e ele aparece.  
Nas ferramentas do navegador, dá pra ver o cookie salvo.  
Quando apagamos os cookies e atualizamos, tudo começa de novo.  
Ou seja, o cookie é criado, mas só aparece depois de atualizar.  
Isso acontece por causa do funcionamento entre navegador e servidor.  
É um processo de envio e resposta.


## Exercício 4: Uso de Sessions na Autenticação

Sessions são mais usadas em login porque são mais seguras.  
Os dados ficam armazenados no servidor, o que impede o usuário de alterar diretamente essas informações.  
O navegador recebe apenas um ID de sessão, que serve para identificar o usuário.  
Isso reduz muito o risco de manipulação de dados.  
Já os cookies podem ser modificados, roubados ou até falsificados, o que pode causar problemas de segurança.  
Outro ponto importante é que, com sessions, o sistema consegue encerrar o acesso facilmente no logout.  
Também é possível definir tempo de expiração e controlar melhor o acesso do usuário.  
Por isso, em sistemas com dados sensíveis, como login e informações pessoais, sessions são muito mais confiáveis.  


## Referências

- https://www.php.net/manual/pt_BR/  
- https://www.php.net/manual/pt_BR/function.setcookie.php
- https://www.php.net/manual/pt_BR/book.session.php  
- https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Cookies
- https://www.w3schools.com/php/php_sessions.asp  
- https://www.w3schools.com/php/php_cookies.asp  
