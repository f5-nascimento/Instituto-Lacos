# Instituto Laços

## CONTEXTUALIZAÇÃO

O Colégio Plural possui um Setor de Inclusão responsável pelo acompanhamento dos alunos que necessitam de atendimento e acompanhamento individualizado no ambiente escolar.
Atualmente, o controle das informações dos responsáveis, alunos e atendimentos realizados pelo setor é feito de forma manual, utilizando anotações e planilhas eletrônicas. Esse processo tem ocasionado dificuldades no acompanhamento dos alunos, perda de informações, duplicidade de registros e dificuldades para localizar rapidamente os dados necessários.

Além disso, o setor trabalha com informações pessoais dos alunos e de seus responsáveis, sendo necessário garantir a segurança dos dados armazenados e o controle de acesso ao sistema.

Para solucionar essa situação, o gestor do Setor de Inclusão do Colégio Plural contratou sua equipe para desenvolver uma solução de software que permita organizar o cadastro dos responsáveis e alunos, bem como o registro e gerenciamento dos atendimentos realizados pelo setor.

Durante a reunião inicial, o gestor destacou a importância da autenticação dos usuários com tempo de expiração, da segurança dos dados sensíveis e da documentação técnica do sistema, incluindo os requisitos funcionais e o Diagrama Entidade-Relacionamento (DER).

Após a reunião com o gestor do Setor de Inclusão do Colégio Plural, foram definidos algumas regras de negócio:
- No script do banco de dados devem existir pelo menos três registros para todas as tabelas criadas, respeitando os tipos de dados, chaves primárias e estrangeiras.
- Na funcionalidade de login, deve ser realizada a validação em caso de falha na autenticação.
- Os dados sensíveis devem ser criptografados no banco de dados.
- A funcionalidade principal do sistema deve exibir o nome do usuário logado, disponibilizar acesso aos demais recursos e apresentar uma forma de sair do sistema.
- A funcionalidade de Responsável deve possuir um recurso de busca, permitindo que o usuário insira um termo e, após sua confirmação, a listagem seja atualizada com os registros correspondentes.
- A funcionalidade de Atendimento deve apresentar a listagem dos atendimentos cadastrados ordenada por data, trazendo os dados relacionados ao responsável e ao aluno.
- Ao cadastrar um novo Aluno, o usuário deverá associá-lo a um Responsável.
- A funcionalidade de Atendimento deverá permitir a atualização da data de um atendimento.

## DESAFIO

Você, como desenvolvedor, deverá criar um sistema que permita o cadastro e gerenciamento de Responsáveis, Alunos e Atendimentos, com autenticação de usuários e controle seguro dos dados.

O sistema deverá atender às necessidades do Setor de Inclusão do Colégio Plural, permitindo organizar os dados dos alunos e responsáveis e controlar os atendimentos realizados pelo setor.
