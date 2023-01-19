# Modelagem_Bd_Sistema_Resilia


Um banco de dados SQL de uma platafoma de cursos.

## MODELO CONCEITUAL

<div align="center">
<img src="https://user-images.githubusercontent.com/112680379/213394028-11e24b49-c4ab-4f51-9054-8018c480a3c6.png" width="700px"/>
</div>

## MODELO LÓGICO
<div align="center">
<img src="https://user-images.githubusercontent.com/112680379/213394122-7322cb04-2b8f-4541-ab6f-59af98466fff.png" width="700px"/>
</div>

### Perguntas sobre modelo

##### Existem outras entidades além dessas três?

   Sim, foram identificadas duas novas entidades para o BD: professor e matéria 
 
##### Quais são os principais campos e tipos?

   O campo que mais apareceu no BD foi campo de nome ,e o tipo mais comum foi Varchar.
 
##### Como essas entidades estão relacionadas?

      As entidades estão relacionadas através de chaves estrangeiras. A tabela aluno tem uma chave estrangeira id_turma, que se relaciona com a tabela turma através da coluna id_turma. A tabela matéria tem uma chave estrangeira id_professor, que se relaciona com a tabela professor através da coluna id_prof. A tabela aluno_matricula tem chaves estrangeiras id_aluno e id_curso, que se relacionam com as tabelas aluno e curso, respectivamente. A tabela turma_curso tem chaves estrangeiras id_turma e id_curso, que se relacionam com as tabelas turma e curso, respectivamente. A tabela prof_curso tem chaves estrangeiras id_prof e id_curso, que se relacionam com as tabelas professor e curso, respectivamente.


 
