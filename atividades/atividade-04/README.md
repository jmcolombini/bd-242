# Atividade 04
1) Criar uma tabela TB_CURSO com os seguintes atributos (ID, NOME);

2) Criar na tabela TB_PROFESSOR um atributo CURSO_ID para relacionar o Professor com o Curso.

3) Criar uma Tabela TB_CURSO_PROFESSOR para implementar um relacionamento N:N onde se consegue obter
   os Professores que ensinam em determinado CURSO e os Cursos com os seus Professores. 

4) Inserir registros na tabela TB_CURSO (Informatica, Telecomunicaçoes, Eletrotécnica, Mecanica,
                                         Edificaçoes, Turismo, Quimica);

5) Inserir registros na tabela TB_PROFESSOR (Cesar Olavo, Davis Macedo, Serra Furtado, Mauricio Jaborandi,
                                             Marcos Lemos, Jose Roberto, Gloria Marinho);

6) Associar os Professores com os Cursos inserindo registros na Tabela TB_CURSO_PROFESSOR.
   Montar os inserts de cada Professor com o Curso usando suas chaves primárias. Na tabela
   TB_CURSO_PROFESSOR haverá os seguintes atributos(ID, CURSO_ID, PROFESSOR_ID). Usar os seguintes registros:

   Cesar Olavo, Informatica;
   Davis Macedo, Informatica;
   Serra Furtado, Informatica;
   Mauricio Jaborandi, Informatica;
   Marcos Lemos,Mecanica;
   Gloria Marinho, Quimica;

7) Fazer uma consulta (select) envolvendo as Tabelas TB_CURSO, TB_PROFESSOR, TB_CURSO_PROFESSOR
   onde é mostrado TB_CURSO.NOME, TB_PROFESSOR.NOME com um Select inner join
   TB_CURSO.ID = TB_CURSO_PROFESSOR.CURSO_ID
   and
   TB_PROFESSOR.ID = TB_CURSO_PROFESSOR.PROFESSOR_ID
