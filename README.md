# Aula 06 - Materialize CSS

## Estrutura do projeto:

```
MeuWebsite/
  |--css/
  |  |--materialize.css
  |
  |--fonts/
  |  |--roboto/
  |
  |--js/
  |  |--materialize.js
  |
  |--index.html
```
<br>

## Configuração do projeto:

Na tag `<head>` do arquivo `index.html`, importar a fonte, a lib css do Materialize, e a metatag viewport:<br>
```
<head>
    <link href="fonts/material-icons.css" rel="stylesheet">
    <link type="text/css" rel="stylesheet" href="css/materialize.min.css" media="screen,projection" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
<head/>
```
no final da tag `<body>`, antes de fechar importe a lib js do Materialize:
```
    ...
    <script type="text/javascript" src="js/materialize.min.js"></script>
</body>
```
Os arquivos das libs e fontes estão presentes neste repositório.

Agora basta acessa a documentação do [Materialize CSS](https://materializecss.com/) e começar a usar seus recursos.
<br><br>

## Atividades da aula

Crie o layout de um site onde seja possível efetuar um CRUD, ou seja, um formulário de cadastro e uma listagem (listagem com ações de editar e excluir). Por enquanto preocupe-se apenas com layout(parte visual), não é necessário que o CRUD funcione de fato.