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