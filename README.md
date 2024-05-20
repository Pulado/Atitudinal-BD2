# Atitudinal-BD2
1) SELECT aluno_id, nota_prova_bimestral FROM materias_alunos
   WHERE nota_prova_bimestral>7

2) SELECT (nota_atitudinal*0.1+nota_licoes*0.1+nota_prova_bimestral*0.5+nota_prova_mensal*0.3)
  AS media_final FROM materias_alunos WHERE
  (nota_atitudinal*0.1+nota_licoes*0.1+nota_prova_bimestral*0.5+nota_prova_mensal*0.3) > 7

3) SELECT aluno_id FROM materias_alunos WHERE curso_tecnico=2 AND
  (nota_atitudinal*0.1+nota_licoes*0.1+nota_prova_bimestral*0.5+nota_prova_mensal*0.3)> 7
   AND nota_prova_bimestral>7
