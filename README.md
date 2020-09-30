<h1 align="center">
    <img src="./.github/level-up.svg" width="150px" >
</h1>

<h1 align="center">
    Plataforma LevelUp
</h1>

<h2 align="center">
    Plataform de cursos online, onde o aluno se cadastra em um curso, e tem acesso os módulos e aulas daquele determindo curso
</h2>


## Descrições da plataforma

- A plataforma deve ser uma plataforma web, posteriormente adaptar para mobile
- Uma área para o aluno poder acessar as aulas e ver seu desempenho e uma para o gestor controlar a aplicação
- Teremos três tipos de cursos(ou dois), um gratuíto e dois pagos, sendo um básico e outro avançando

### Aluno

`Aqui será onde o aluno poderá acessar a plataforma e ver de acordo com a assinatura, todas aulas que estão dispostas a ele, seja aula em vídeo ou PDF`

### Gestor

`Aqui será onde o gestor poderá controlar os alunos cadastrados em cada curso, as aulas de cada módulo de um curso, o desempenho dos alunos e ter relatórios gerais`


## Observações de regras de negócio (Observação inicial)

### Aluno

- Precisará ter uma conta na plataforma para navegar pelos curso;
- Um aluno só poderá acessar um curso em que esteja mátriculado e devidamente em dias;
- O aluno poderá acessar o curso gratuíto a qualquer momento, independente do curso que ele estiver matriculado;

### Gestor

- Só poderá acessar a plataforma se tiver uma `role` de *Adim* ou *Gestor*;


## Observações finais

- O projeto será feito em duas pastas (Aluno/Admin)
- Conforme formos trabalhado em cada parte, os requisitos irão sendo implementados
- Teremos 3 branchs (master/dev-rennan/dev-fabiano), cada dev trabalha na sua brach e depois de um pull request será jogado para a master,
- Em cada uma das parte dos projeto(Aluno/Admin), será criado um README detalhado com os requisitos daquela área do sistema