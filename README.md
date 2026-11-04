# Instituto Laços

## CONTEXTUALIZAÇÃO

O Instituto Laços enfrenta dificuldades em sua rotina de atendimentos devido à ausência de um sistema informatizado. O controle manual dos agendamentos e dos registros de pretendentes e crianças tem ocasionado perda de consultas, duplicidade de informações e falhas no armazenamento de dados. Além disso, a ausência de mecanismos adequados de proteção dos dados pessoais dos pretendentes, como o CPF, pode comprometer a segurança dessas informações e resultar no descumprimento das disposições da Lei Geral de Proteção de Dados (LGPD). 

Para resolver essa situação, o gestor do instituto contratou sua equipe para desenvolver uma solução de software que organize o processo de agendamento e gestão de informações. Durante a reunião inicial, o gestor destacou a importância da autenticação dos usuários com tempo de expiração, da proteção dosdados pessoais armazenados e da documentação técnica do sistema, incluindo requisitos funcionais e geração do diagrama entidade relacionamento, a fim de garantir a manutenção futura do sistema.

Após a reunião com o gestor do instituto, foram definidos algumas regras de negócio: 

- No script do banco de dados devem existir pelo menos três registros para todas as tabelas criadas, respeitando os tipos de dados, chaves primárias e estrangeiras.
- Na funcionalidade de login, fazer validação em caso de falha na autenticação.
- O CPF dos pretendentes deve ser armazenado de forma criptografada no banco de dados.
- A funcionalidade principal do sistema deve exibir: nome do usuário logado e uma forma de acessar os demais recursos, assim como uma maneira de sair do sistema.
- A funcionalidade de pretendentes deve conter: um recurso de busca para que o usuário possa inserir o termo, o qual, após inserção e confirmação, deverá exibir para o usuário a atualização da listagem dos valores da tabela com os registros que correspondem. A funcionalidade também deve permitir editar os dados de um pretendente já cadastrado, salvando a alteração no banco de dados.
- A funcionalidade de agendamento deve exibir: Listagem dos agendamentos cadastrados ordenado por dia de agendamento, trazendo todos dados do pretendente e do criança. A funcionalidade também deve permitir atualizar a data de um agendamento já cadastrado, salvando a alteração no banco de dados.
- Ao cadastrar uma nova criança, o usuário deve associá-lo a um pretendente.

## DESAFIO

Você, como desenvolvedor deverá criar um sistema que permita o cadastro e gerenciamento de pretendentes, crianças e agendamentos, com autenticação de usuários e controle seguro de dados.

## RESULTADOS E ENTREGAS ESPERADAS
Crie um diretório compactado na área de trabalho (formato .zip, .rar ou .7zip) nomeado com seu nome completo, contendo os seguintes arquivos:

| Nº | Entrega | Tipo de Entrega | Tempo Estimado (minutos) |
|:--:|:--------|:----------------|:------------------------:|
| 1 | Documentação de software (Anexo 1) | documentacao.pdf | 15 |
| 2 | Diagrama entidade relacionamento | der.png ou der.pdf | 5 |
| 3 | Script de criação e população do banco de dados | saep_db.sql | 20 |
| 4 | Código fonte da funcionalidade do login | Diretório `sistema` contendo os arquivos do código-fonte | 20 |
| 5 | Código fonte da funcionalidade principal do sistema | Diretório `sistema` contendo os arquivos do código-fonte | 20 |
| 6 | Código fonte da funcionalidade de gerenciamento Pretendente | Diretório `sistema` contendo os arquivos do código-fonte | 30 |
| 7 | Código fonte da funcionalidade de gerenciamento Criança | Diretório `sistema` contendo os arquivos do código-fonte | 30 |
| 8 | Código fonte da funcionalidade de gerenciamento de Agendamentos | Diretório `sistema` contendo os arquivos do código-fonte | 40 |
