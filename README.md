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
 1. Requisitos funcionais:
    Cadastrar alunos 
    Cadastrar funcionarios 
    Cadastrar cursos
    Listar alunos
    Listar cursos
    Listar funcionarios
    Mostrar os dados dos alunos
    Mostrar os dados dos funcionarios
    Mostrar os dados do curso
    Realizar as matriculas
    Editar os dados do aluno
    Editar os dados do funcionario
    Editar os dados do curso
    Excluir os alunos
    Excluir os funcionarios
    Excluir os cursos
    Excluir as matriculas
    Carga horaria
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
    Pesquisar alunos
    Pesquisar funcionários
    Pesquisar cursos
    Pesquisar turmas
    Pesquisar disciplinas
    Consultar matrículas
    Cancelar matrícula
    Cadastrar responsáveis pelos alunos
    Consultar responsáveis
    Cadastrar salas
    Associar professores às disciplinas
    Associar alunos às turmas
    Alterar notas dos alunos
    Alterar faltas dos alunos
    Consultar o calendário escolar
    

2. Requisitos não funcionais:
    Autenticação
    Interface com navegação padronizada e consistente entre as telas
    Interface responsaveis e adaptativa e diversas reluções de tela e dispopsitivos diferentes,como computador ,celular e tablet
    Interface deve ser computavel com os principios navegadores web
    Criptografar as senhas antes de salva-las no banco de dados
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
    Ser compatível com diferentes navegadores.
    Ter cores agradáveis
    Ter textos fáceis de ler
    Ter botões fáceis de encontrar
    Ter telas bem organizadas
    Ter menus simples
    Permitir recuperação de senha
    Mostrar mensagens de confirmação
    Mostrar mensagens de erro
    Ter boa qualidade visual
    Ser compatível com diferentes tamanhos de tela
    Permitir manutenção do sistema
    Evitar dados duplicados
    Manter os dados atualizados
    Permitir vários usuários ao mesmo tempo