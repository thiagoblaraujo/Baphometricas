# Baphometricas

Nome do trabalho: Baphométricas

Minimundo: 

Descrição da aplicação
O Baphométricas consiste de um sistema de informação para uma empresa de consultoria que visa melhorar a interação com um grupo de 
consultores americanos. Esta melhoria na interação será feita agilizando o processo de cadastro de formulários para geração de 
relatórios. Por exemplo, V&A utiliza determinados formulários com seus clientes que são preenchidos manualmente por cada participante 
do processo. Cada um destes formulários eram enviados por correio e serão agora digitados através deste software permitindo que o mesmo 
gere um arquivo no formato txt que o grupo Symlog definiu como aceitável pelo seu sistema.
Para funcionar, o sistema guardará informações referentes aos usuários com suas permissões e formulários cadastrados com respostas de 
cada cliente entrevistado.

Identificação das entidades e suas características
Operador: Usuário com acesso ao sistema para gerenciamento de formulários. Possui atributos de nome, login, senha e email.
Administrador: Atributos e funções de operador com privilégios de cadastro de operadores e geração de arquivos de exportação.
Formulário:  Entidade responsável por registrar todos os formulários cadastrados no sistema. Cada registro possui um identificador, um grupo e um número visível pelo usuário.
Subformulário: Cada formulário preenchido possui 4 perguntas. Esta entidade representa cada uma destas perguntas e são caracterizadas por pertencer a um formulário e possuir uma pergunta referente ao subformulário.
Resposta: Entidade que registra as respostas a cada um dos itens do subformulário. Atributos são o subformulário a qual se refere e o código inserido como resposta (1, 2 ou 3).
Grupo: Entidade que define os diferentes grupos existentes no sistema. Cada grupo possui somente um nome e um identificador.

Relacionamento entre as Entidades

Um operador cadastra, edita e remove formulários;
Um administrador cadastra, edita e remove operadores;
Um administrador cadastra, edita e remove administradores;
Um formulário possui subformulários;
Um subformulário possui várias respostas;
Um grupo possui vários formulários.

Nome do grupo: Thiago Batista Lemos de Araújo

Pitch:
