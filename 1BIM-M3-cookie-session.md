# 📘 1BIM-M3 - Cookies e Sessions

## 👨‍💻 Integrantes
- Murilo Lazzarini 
- Pedro Gregio Boriero  


## 📝 Exercício 1 — Diferença entre Cookies e Sessions

Cookies são dados que ficam salvos no navegador do usuário, enquanto sessions guardam as informações no servidor.  
Por isso, cookies são menos seguros, já que podem ser alterados pelo próprio usuário.  
Já as sessions são mais seguras, porque o navegador só recebe um identificador.  
Cookies são mais usados para coisas simples, como preferências ou lembrar informações básicas.  
Sessions são ideais para login e controle de acesso.  
Outra diferença é que cookies podem continuar salvos mesmo depois de fechar o navegador.  
Já as sessions geralmente acabam quando o usuário sai ou fecha o navegador.


## 📝 Exercício 2 — Aplicação em Loja Virtual

Para manter o usuário logado, o melhor é usar sessions, porque são mais seguras.  
Os itens do carrinho também podem ficar na session enquanto o usuário navega.  
Assim, essas informações ficam protegidas no servidor.  
Os cookies podem ser usados para guardar preferências, como idioma ou tema do site.  
Também podem servir para lembrar o usuário, mas sem guardar dados importantes.  
Usando os dois juntos, o sistema fica mais completo.  
Cada um é usado naquilo que faz melhor.


## 📝 Exercício 3 — Teste com Cookies

Quando executamos pela primeira vez, o cookie ainda não aparece porque ele só funciona na próxima requisição.  
Depois que atualizamos a página, o navegador já envia o cookie e ele aparece.  
Nas ferramentas do navegador, dá pra ver o cookie salvo.  
Quando apagamos os cookies e atualizamos, tudo começa de novo.  
Ou seja, o cookie é criado, mas só aparece depois de atualizar.  
Isso acontece por causa do funcionamento entre navegador e servidor.  
É um processo de envio e resposta.


## 📝 Exercício 4 — Uso de Sessions na Autenticação

Sessions são mais usadas em login porque são mais seguras.  
Os dados ficam no servidor e não podem ser alterados pelo usuário.  
O navegador recebe só um identificador da sessão.  
Já os cookies podem ser modificados ou até roubados.  
Com sessions, fica mais fácil controlar quem está logado.  
Também dá pra encerrar o acesso com mais segurança no logout.  
Por isso, elas são melhores para sistemas com dados importantes.


## 📚 Referências

- https://www.php.net/manual/pt_BR/  
- https://www.php.net/manual/pt_BR/function.setcookie.php  
