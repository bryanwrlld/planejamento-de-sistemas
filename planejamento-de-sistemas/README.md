# Sistema de Gestão Escolar

## Sistema para gerenciar funcionarios, alunos, cursos e matriculas

1. Quem utilizara o sistema (usuarios)?
alunos ,professores 

2. quais os tipos de usuarios e o que cada tipo consegue fazer?
estudantes que podem se matricular para começar a trabalhar
funcionarios q querem uma oprtundade de emprego fazer uma oferta de trabalho para receber tal quantia de dinheiro e alguns beneficios 
funcionarios que trabalham bem em grupo
e pessoas que possam contratalos

3. quais informações podemos armazenar?
 FUNCIONARIOS:nome ,cpf ,telefone ,email ,data de nascimento , senha ,endereço
 
 ALUNOS:matricula ,data de nascimento ,email ,telefone ,cpf ,nome
 
 CURSOS:descrição ,carga horaria ,nome 

 MATRICULAS:quais alunos estão cadastrados em quais cursos

4. quais regras ou restrições são necessarias?
apenas funcionarios adms podem criar/deletar outros funcionarios,

funcionarios colaboradorem não podem editar dados de outros dados,

(horario de entrada ,nome ,senha ,matricula)dados obrigatorios
(cpf e email)nunca se repetem
um aluno não pode ser matriculado mais de uma vez no mesmo curso
o sistema deve validar as informações

## POIBLEMA:
    esse sistema é direcionado a funcionarios de escolas
    permite cadstrar ,editar ,listar e deletar alunos ,cursos ,matriculas e funcionarios

## modelo de negocio:
 ![Business Model Canva](image/bussines-model-canvas.png)

 ## REQUISITOS:
 1. requisitos funcionais:
    cadastrar alunos 
    cadastrar funcionarios 
    cadastrar cursos
    listar alunos
    listar cursos
    listar funcionarios
    mostrar os dados dos alunos
    mostrar os dados dos funcionarios
    mostrar os dados do curso
    realizar as matriculas
    editar os dados do aluno
    editar os dados do funcionario
    editar os dados do curso
    excluir os alunos
    excluir os funcionarios
    excluir os cursos
    excluir as matriculas
    carga horaria
    Alterar cadastro
    Excluir cadastro
    Cadastrar turmas
    Cadastrar disciplinas
    Registrar notas
    Registrar faltas
    Consultar notas
    Consultar faltas
    Emitir boletim
    Cadastrar horários
    Fazer relatórios
    

2. requisitos não funcionais:
    autenticação
    interface com navegação padronizada e consistente entre as telas
    interface responsaveis e adaptativa e diversas reluções de tela e dispopsitivos diferentes,como computador ,celular e tablet
    interface deve ser computavel com os principios navegadores web
    criptografar as senhas antes de salva-las no banco de dados
    Ser fácil de usar
    Ser rápido
    Ser seguro
    Ter uma interface simples
    Funcionar no computador
    Funcionar no celular
    Proteger os dados
    Ter senha segura
    Evitar perda de dados
    Fazer backup
    Ter poucos erros
    Carregar rapidamente
    Ser organizado
    Funcionar todos os dias
    Ser fácil de atualizar