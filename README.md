# ProjetoIndividualM4
Banco de Dados
# :desktop_computer: A Resilia está pensando em lançar um novo sistema de acompanhamento e para isso precisa de ajuda para modelar um banco de dados que vai armazenar seus cursos, turmas e alunos. 



# Diagrama de relacionamento: 

![Diagrama](https://user-images.githubusercontent.com/113558275/215584206-9758f203-11f6-4a5c-b0fb-d9a8abf13fe1.png)

# 1 - Existem outras entidades além dessas três?
R: Sim, será necessário mais entidades  para completar o modelo, além de CURSOS, ALUNOS e TURMAS, adicionei DISCIPLINAS E PROFESSORES.

# 2 - Quais são os principais campos e tipos?

R:  Os principais campos são ID, NOME, EMAIL e N_MATRICULA.  Os tipos são eles respectivamente  INT e VARCHAR. 

# 3 - Como essas entidades são relacionadas? 




    ALUNOS matriculam-se em CURSOS

    CURSOS geram TURMAS
    
    TURMAS possuem ALUNOS
    
    TURMAS contem PROFESSORES
    
    PROFESSORES ensinam DISCIPLINAS
    


# EXTRAS

Script com o código na pasta SQLScript. 
