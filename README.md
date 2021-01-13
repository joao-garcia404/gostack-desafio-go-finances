<img alt="GoStack" src="https://i.imgur.com/pHg9Or3.png" />

<h1 align="center">
  Desafio 07: GoFinances GoStack
</h1>

## Sobre o desafio

Desafio de uma aplicação de gestão de finanças, com Typescript, utilizando rotas e envio de arquivos por formulário.
Essa aplicação utiliza o back-end do <a href="https://github.com/joao-garcia404/gostack-desafio-database-upload/tree/master">Desafio 06<a/>, exibindo as transações criadas e importando arquivos .csv para a criação de uma transação.
  
---------------------------------------------------------------------------------------------------------------------------------------------------------------

## Layout da aplicação

Essa aplicação possui um layout no figma que pode ser acessado por esse <a href="https://www.figma.com/file/EgOhyj1Inz14dhWGVhRlhr/GoFinances?node-id=0:1">link.<a/>
  
<img src="https://i.imgur.com/wKbEhze.png">
  
------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Funcionalidades

- `Listagem das transações da API`: A página `dashboard` exibe uma listagem através de uma tabela, contendo os campos `title`, `value`, `type`, `category` de todas as
transações que estão cadastradas na API.

- `Exibir o balance da API`: A página `dashboard` exibe exibi o balance da conta, que é retornado do <a href="https://github.com/joao-garcia404/gostack-desafio-database-upload/tree/master">BackEnd<a/>, contendo o total geral, junto ao total de entradas e saídas. 
  
- `Importação de arquivos .csv`: A página `import` permite a importação de um arquivo .csv para o cadastro de uma nova transação, o arquivo deve conter o seguinte
<a href="https://github.com/rocketseat-education/bootcamp-gostack-desafios/blob/master/desafio-database-upload/assets/file.csv">modelo<a/>.
  
----------------------------------------------------------------------------------------------------------------------------------------------------------------
  
## Testes da aplicação
  
- `should be able to list the total balance inside the cards`: Para que esse teste passe, sua aplicação deve permitir que seja exibido na sua Dashboard, cards contendo o total de `income`, `outcome` e o total da subtração de `income - outcome` que são retornados pelo balance do seu backend.

- `should be able to list the transactions`: Para que esse teste passe, sua aplicação deve permitir que sejam listados dentro de uma tabela, toda as transações que são retornadas do seu backend.

- `should be able to navigate to the import page`: Para que esse teste passe, você deve permitir a troca de página através do Header, pelo botão que contém o nome `Importar`.

- `should be able to upload a file`: Para que esse teste passe, você deve permitir que um arquivo seja enviado através do componente de drag-n-drop na página de `import`, e que seja possível exibir o nome do arquivo enviado para o input.

----------------------------------------------------------------------------------------------------------------------------------------------------------------

## :memo: Licença

Esse projeto está sob a licença MIT. Veja a página [LICENSE](https://opensource.org/licenses/MIT) para mais detalhes.
