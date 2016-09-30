# Baphometricas

##Nome do trabalho: 

Baphométricas

##Minimundo: 

Descrição da aplicação:
O Baphométricas consiste de um sistema de informação para uma empresa que presta serviço de software com sua remununeração baseada em 
ponto de função. Este sistema será feito para facilitar a contagem de ponto de função pela equipe de análise/desenvolvimento da empresa. Por exemplo, analista/desenvolvidor tem para cada projeto gerar uma planilha de contagem para o projeto em que está atuando, contudo devido a imaturidade da equipe para estar utilizando a técnica de contagem, há divergências entre as contagens de um para outro analista ou mesmo entre duas contagens realizadas pelo mesmo analista. O sistema irá permitir o cadastro dos projetos e de sua contagem para manter um baseline, facilitando a consulta dos dados para novas contagens, além de automatizar o relatório de contagem em um formato aceito pelo contrato.

##Identificação das entidades e suas características:

Usuário: Pessoa que irá utilizar o sistema. Possui atributos de nome e senha.

Analista: Analista/Desenvolvedor que está realizando o projeto. Possui atributos de nome, login, senha e email.

Empresa: Empresa da contratação de software. Possui atributos de nome, status(ativo/inativo), indicador de fornecedor, lista de contratos.

Contrato: Dados do contrato de software da empresa. Possui atributos de codigo, descrição e situação.

Fator de Equivalência: Informação presente no contrato que tem relação de peso para o ponto de funçã, isto é, um percentual aplicado 
por ponto de função para determinado tipo de manutenção de software. Possui atributos de código, tipo de elemento (fixo ou deflator), fator, descrição.

Sistema: Dados do sistema a ser desenvolvido ou alterado por um projeto. Possui atributos de código e descrição.

Entidade: Grupo de dados lógicamente relacionados mantidos pelos sistemas cadastrados. Possui atributos de nome, categoria (dados de código, dados de referência ou dado de negócio), descrição, lista de atributos.

Atributo: Informação atômica reconhecida ou não pelo usuário armazenada em uma entidade. Possui os atributos de nome físico, descrição, formato, tamanho, validade, precisão, indicador de recolhecido pelo usuário.

Projeto: Dados do projeto sendo contado. Possui os atributos de código do projeto, código do subprojeto, título, analista responsável, gestor/analista empresa contratante.

Função de Dados: Grupo de dados lógicamente relacionados reconhecido pelo usuário do sistema (ALI/AIE). Possui os atributos de nome, classificação (ALI/AIE), lista de tipo de registros (Grupo de Entidades) e lista de tipo de dados (atributos das Entidades informadas que são recolhecidas pelo usuário no sistema sendo contado. 

Função de Transação: Menor unidade da tarefa solicitada pelo usuário, recolhecido pelo usuário, representando uma transação completa e que deixa o sistema em estado consistente. Possui os atributos de nome, classificacao (SE/CE/EE), lista de arquivos referênciados (ALI´s e AIE´s cadastrados no sistema) e lista de tipo de dados (dados presentes nos ALI´s e AIE´s que são reconhecidos pelo usuário e atravessam a fronteira da aplicação).

##Relacionamento entre as Entidades:

Um operador cadastra, edita e remove formulários;
Um administrador cadastra, edita e remove operadores;
Um administrador cadastra, edita e remove administradores;
Um formulário possui subformulários;
Um subformulário possui várias respostas;
Um grupo possui vários formulários.

##Nome do grupo: 

Thiago Batista Lemos de Araújo

##Pitch:

