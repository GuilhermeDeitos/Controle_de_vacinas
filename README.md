## Controle de vacinação

Desenvolva um sistema que consiste no registro e busca de informações em carteiras de vacina de pessoas. O sistema deve possuir um menu com cadastro de pessoa, registro de vacina, busca e relatório.

O sistema deve possibilitar:
- cadastro de pessoas, com:
    - nome (*string*)
    - RG (*string*)
- referente a cada pessoa, deve possuir o registro de vacinas específicas, com registro de:
    - doença que a vacina protege (*string*)
    - data de aplicação da vacina (*string* dd/mm/aaaa)
    - dose tomada (inteiro)
- busca por:
    - nome da pessoa
    - RG
- relatórios com:
    - total de pessoas vacinadas para cada doença
    - total de pessoas vacinadas por mês


O sistema deve possibilitar salvar dados cadastrados em arquivo, e recuperar o arquivo durante a abertura do sistema. 

No desenvolvimento, arquivos, listas e dicionários devem ser utilizados. Os arquivos podem ser de qualquer tipo (texto, csv, json ou outros)

Deve ser entregue:
- O projeto (Jupyter ou Colaboratory);
- Um arquivo, com dados a serem carregados quando a execução do sistema for iniciada.
