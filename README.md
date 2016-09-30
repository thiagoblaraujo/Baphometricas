# Baphometricas

##Nome do trabalho: 

Baphométricas

##Minimundo: 

Descrição da aplicação
O Baphométricas consiste de um sistema de informação para um empresa que presta serviço de software com sua remununeração baseada em 
ponto de função. Este sistema será feito para facilitar a contagem de ponto de função pela equipe de análise e desenvolvimento da empresa. Por exemplo, a equipe tem para cada projeto gerar uma planilha de contagem para o projeto em que está atuando, contudo devido a 
imaturidade da equipe para estar utilizando a técnica de contagem, há divergências entre as contagens de um para outro analista ou mesmo entre duas contagens realizadas pelo mesmo analista. O sistema irá permitir o cadastro dos projetos e de sua contagem para manter um baseline, facilitando a consulta dos dados para novas contagens, além de automatizar o relatório de contagem em um formato aceito pelo contrato.

##Identificação das entidades e suas características

Usuário: Pessoa que irá utilizar o sistema. Possui atributos de nome e senha.

Analista: Analista/Desenvolvedor que está realizando o projeto. Possui atributos de nome, login, senha e email.

Administrador: Atributos e funções de operador com privilégios de cadastro de operadores e geração de arquivos de exportação.

Formulário:  Entidade responsável por registrar todos os formulários cadastrados no sistema. Cada registro possui um identificador, um grupo e um número visível pelo usuário.

Subformulário: Cada formulário preenchido possui 4 perguntas. Esta entidade representa cada uma destas perguntas e são caracterizadas por pertencer a um formulário e possuir uma pergunta referente ao subformulário.

Resposta: Entidade que registra as respostas a cada um dos itens do subformulário. Atributos são o subformulário a qual se refere e o código inserido como resposta (1, 2 ou 3).

Grupo: Entidade que define os diferentes grupos existentes no sistema. Cada grupo possui somente um nome e um identificador.

##Relacionamento entre as Entidades

Um operador cadastra, edita e remove formulários;
Um administrador cadastra, edita e remove operadores;
Um administrador cadastra, edita e remove administradores;
Um formulário possui subformulários;
Um subformulário possui várias respostas;
Um grupo possui vários formulários.

##Nome do grupo: 

Thiago Batista Lemos de Araújo

##Pitch:
