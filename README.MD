# Projeto do Recesso - Programa��o Orientada a Objetos

## Escopo Do projeto

O sistema consistem em um gerenciador de tarefas que segue as seguintes condi��es:

- Existem apenas dois v�nculos: tech leader e desenvolvedores;

- Teach leader podem ver as tarefas de todos, podem criar tarefas e tamb�m assumir tarefas,
possuem tamb�m acesso a estat�sticas como: tarefas em atraso, tarefas conclu�das, tarefas
abandonadas, tarefas com impedimento, tarefas em an�lise (se foram mesmo conclu�das ou
se retornam - o tech leader que decide) e tarefas a serem aprovadas para inicio (tarefas que
n�o foram feitas pelo tech leader e precisam de autoriza��o para come�ar). Al�m disso,
apenas o tech leader pode colocar um respons�vel pela tarefa que n�o seja o criador dela, ou
mudar o respons�vel pela tarefa;

- Os desenvolvedores podem criar tarefas (e automaticamente s�o os respons�veis por ela), o
tempo da tarefa fica em aberto a ser definido pelo tech leader. Os desenvolvedores veem
apenas suas tarefas ou tarefas que tenham rela��o com a sua. A tarefa s� pode ser iniciada
com a autoriza��o do tech leader;

- As tarefas podem ter rela��o quando fazem fun��es diferentes mas no mesmo local, como:
cria��o da classe de produtos e cria��o do formul�rio de cria��o de produtos (mesmo que
n�o tenham o mesmo respons�vel) - essa correla��o � feita pelo tech leader;

- Os desenvolvedores podem ser adicionados atrav�s de um txt ou json (que pode ser
atualizado pelo tech leader) ou manualmente;
Para entrar no sistema, todos precisam de uma chave de acesso;