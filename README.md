Aula de JavaScript (Alura) - Validação de formulários e HTML5

Então nós mexemos primeiro no formulário de cadastro de pessoa no site da doguito pet shop, e aprendemos logo no começo maneiras de validar o formulário usando apenas HTML. No campo de nome nós usamos o atributo required, para poder dizer que nós queremos que o campo seja preenchido antes de ser enviado para o servidor.

No campo de e-mail nós colocamos o atributo type passando o tipo de e-mail, que já faz uma pré-validação, e checando a estrutura do e-mail.

E no campo de senha, nós começamos a apimentar um pouco mais as coisas, com mensagens customizadas no tittle e também uma validação mais fina do que nós poderíamos colocar no campo de senha utilizando atributo Pattern e passando uma expressão regular, ou “regex” dentro desse pattern. Então nós conseguimos ver o quão poderoso já é validação HTML por si só, o quanto que nós já conseguimos fazer.

E depois, no data de nascimento, nós começamos a criar a nossa própria validação. Então nós criamos um Java Script, que pode importado inclusive por outras aplicações, nós formamos nossa própria aplicação de validação que é super genérica, que nós podemos usar em qualquer campo utilizando o “Data Attribute Tipo” passando um tipo. E temos mensagens customizadas, nós temos validações customizadas em funções que validam, por exemplo, data de nascimento se a pessoa menor de idade.

No campo de CPF também fizemos a validação utilizando contas matemáticas para poder descobrir se o CPF está pelo menos no formato válido, escrita válida.

E também colocamos um pouco mais de integração com outras aplicações, outras APIs, no campo de CEP. Onde nós fazemos uma pequena validação do CEP para saber se a estrutura dele está correta, e depois fazemos uma requisição para a API do Via CEP. E nós pegamos as informações que são voltadas com o CEP, e preenchemos com essas informações os campos de logradouro, cidade e estado.

E depois de tudo isso, nós terminamos o formulário de cadastro e seguimos depois para outro formulário que vai ser cadastro de produto, onde nós vimos como importar a nossa aplicação, reutilizar ela em outras páginas. E também nós vimos a utilização da máscara, máscara monetária, como foi implementado, como foi a configuração, e como foi a utilização dessa máscara. Com tudo isso, nós fechamos esse curso.
