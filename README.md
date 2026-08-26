# sistema de gestao escolar

## Sistema para gerenciar funcionarios, alunos, cursos e matriculas

1. Quem utilizará o sistema (usuários)?

Os principais usuários são:

Funcionários

2. Quais são os usuários e o que cada tipo consegue fazer?

- Colaboradores:
Cadastrar Alunos,
Cadastrar cursos editar e excluir dados dos alunos e dos cursos,
listar alunos, 
listar cursos, 
matricular alunos nos cursos e desmantricular alunos do cursos 
e a tualizar os proprios dados
- Admin: todas as funções acima, mais:
cadastrar outros funcionarios,
listar outros funcionarios,
editar dados dos outros funcionarios 
e excluir outros funcionarios


3. Quais informações iremos armazenar?

- Funcionários:
Nome
Email
Cargo
data de nascimento
CPF
Login e senha
Contato
endereço

- Alunos:
Nome
matricula
Data de nascimento
CPF
telefone
Email
enderço

- Cursos:
Descrição
Carga horária
Nome do curso

Matrículas:
Quais alunos estão cadastrados em quais cursos

Notas e Frequência:
Nota por disciplina
Presenças e faltas

4. Quais regras ou restrições são necessárias?

- Apenas administradores podem criar/deletar outros funcionarios;
- Funcionarios colaboradores não podem editar dados de outros funcionarios;
- CPF não pode repetir, email não pode repetir 
- nome, email, cpf, senha, carga horaria, matricula são dados obrigatorios
- Um aluno não pode ser matriculado duas ou mais vezes no mesmo curso 
- o sistema deve validar as informações 

## PROBLEMA:
- Esse sistema é direcionado a funbcionarios de escolas 
- Permite cadstrar, editar, listar e deletra alunos, matriculas e funcionarios 

## Modelo de Negócio:
 ![Business Model Canvas](image/bussiness-model-canva.png) 

 ## REQUISITOS
 1. Requisitos Funcionais:
 - Cadastrar alunos
 - Cadastrar cursos
 - Cadastrar funcionarios
 - Listar alunos
 - Listar cursos
 - Listar funcionarios 
 - Mostrar os dados do aluno
 - Mostrar os dados do curso
 - Mostrar os dados do funcionario
 - Editar os dados do aluno 
 - Editar os dados do cursos 
 - Editar os dados do funcionarios 
 - Excluir os alunos
 - Excluir os cursos
 - Excluir os funcionarios
 - Excluir as matriculas
 - realizar as matriculas 
 -
 - O sistema deve permitir pesquisar alunos por nome, CPF ou matrícula
 - O sistema deve permitir ativar/desativar cursos
 - O sistema deve permitir definir limite máximo de alunos por curso
 - O sistema deve permitir exportar relatórios em PDF ou Excel
 - O sistema deve permitir redefinição de senha pelo usuário
 - O sistema deve permitir bloquear usuários inativos
 - O sistema deve permitir lançamento de notas por disciplina
 - O sistema deve permitir visualizar o histórico escolar do aluno
 - O sistema deve permitir definir horários das aulas
 - O sistema deve permitir encerrar automaticamente cursos após a data final
 - O sistema deve permitir anexar documentos ao cadastro do aluno
 - O sistema deve permitir definir períodos de início e fim dos cursos
 - O sistema deve gerar relatórios de alunos matriculados por curso
 - O sistema deve gerar relatórios de desempenho (notas) dos alunos
 - O sistema deve calcular automaticamente a média final do aluno
 - O sistema deve indicar se o aluno foi aprovado ou reprovado
 - O sistema deve emitir comprovante de matrícula
 - O sistema deve enviar notificações (email ou sistema) sobre matrícula
 - O sistema deve impedir matrícula fora do período do curso
 - O sistema deve impedir matrícula em cursos já encerrados



2. Requisitos não funcionais:
- Autenticação
- Interface com navegação padronizada e consistente entre as telas 
- Interface responsiva e adaptativa e diversas resoluções de tela e dispositivos diferentes, como computador, celular e tablet
- Interface deve ser compatível com os principais navegadores web 
- Criptografar as senhas antes de salvá-las no banco de dados
- 
- O sistema deve possuir autenticação de usuários (login e senha)
- O sistema deve garantir que CPF e e-mail sejam únicos no sistema
- O sistema deve validar os dados obrigatórios antes de salvar
- O sistema deve possuir tempo de resposta rápido
- O sistema deve manter backup periódico dos dados
- O sistema deve possuir navegação padronizada e fácil de usar
- O sistema deve possuir disponibilidade mínima de 99%
- O sistema deve permitir manutenção e atualização sem parar o sistema
- O sistema deve proteger os dados contra acessos não autorizados
- O sistema deve ser compatível com diferentes sistemas operacionais (Windows, Android, iOS)

