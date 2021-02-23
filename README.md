# Capgemini - Desafio Frontend | Angular

Olá! Esse desafio técnico tem como propósito medir suas habilidades, ver como estuda, pensa e se organiza na prática. O framework utilizado é Angular e versão é de sua escolha (sendo Angular 2+). 

Após finalizar o desafio, de preferencia faça um fork do projeto depois pull request, nos envie um link para repositório do projeto ou um zip com o código o que se sentir mais confortavel.

Existem diversas maneiras e profundidades de solucionar o problema que estamos propondo. Vamos listar algumas sub-tasks que podem guiá-lo(a) em relação a essas possibilidades.

## O desafio

Usuários Bradesco realizam diversos pagamentos pix por todo o Brasil, o desafio é fazer uma aplicação em angular que cadastre os pagamentos pix e listar os pagamentos pix. Na tela de  listagem dos pagamentos deve informar também a porcentagem de cada pagamento em relação o valor montante mensal dos pagamentos feito pela pessoa  X na data dd/mm/yyyy.  Construir um SPA  que por sua vez consumirá umm endPoint "/pagamentos" que terá devolverá para o usuário final um payload em JSON contentando dados dos  pagamento pix.

## Input

Você deve criar uma aplicação para que faça requisições utilizando  json de pagamento pix. 

## Output

Receber lista de pagamentos pix com porcentagem de cada pagamento em relação ao valor montante dos pagamentos pix de uma pessoa X e data dd/mm/yyyy

### Dados a serem coletados do pagamento pix :

* Nome destinatario
* CPF
* Instituição Bancaria
* Chave pix
* Valor
* Data Pagamento
* Descrição
* Logica de porcentagem dos pagametnos (Ex: aplicar uma regra de porcentagem com base no valor do pagamento pix )

## Alguns pontos cruciais para entrega

* Criação de uma API que seja capaz de receber requesições feitas utilizando json e persistindo esses dados. (CRUD)
* Logica da porcentagem dos pagamentos pix

## Alguns pontos que serão bonús:

* Organização do código 
* Organização do repositorio remoto
* Fork e Pull request
* Testes Unitarios (TDD)
* Código bem comentado 
* Facilidade ao rodar o projeto
* Utilização de padrões de projeto 
* Utilização de DDD

## Dúvidas do processo ou enviar zip do projeto

Enviar e-mail para  lucas.reis@capgemini.com , kamila.castelano@capgemini.com , vinicius.pascucci@capgemini.com ou  levi.ferreira@capgemini.com.

**Happy coding! :-)**
