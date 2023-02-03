# Projeto Desenvolvido no Curso de Lógica de Programação com Java

Definição do Projeto Desenvolvido no Curso de Lógica de Programação com Java

1. - Iniciando um projeto
1.1 - Definição de um projeto básico
1.1.1 - Requisitos do projeto
1.1.2 - Regras de negócio
1.1.3 - Definição da tecnologia 

------------------------------------------------------------------------------------------------
1. - Iniciando um projeto
Nome da aplicação: Todo App
Descrição: Aplicação para o gerenciamento de projetos e as tarefas envolvidas nesses projetos.
Objetivo: Resolver a questão de organização de tarefas de um ou vários projetos.

1.1 - Definição de um projeto básico
- Entidades:
* Projeto;
    Atributos do projeto
	- Nome
	- Descrição
	- Data de Criação
	- Data de Atualização
* Tarefa;
Atributos do projeto
	- Nome
	- Descrição
	- Status
	- Tags
	- Observações
	- Prazo
	- Data de Criação
	- Data de Atualização

1.1.1 - Requisitos do projeto:
* Permitir criar o projetos;
* Permitir alterar o projeto;
* Permitir deletar o projeto; 

* Permitir criar o a tarefa;
* Permitir alterar a tarefa;
* Permitir deletar a tarefa;

1.1.2 - Regras de negócio:
* Não irá conter um sistema de login
* Não haverá o conceito de usuário
* Toda tarefa deve pertencer a um projeto
* Não podem haver tags repetidas numa mesma tarefa
* Deve ser possivel filtrar as tarefas por tag

Tecnologias utilizadas:
* Java
* MySQL
