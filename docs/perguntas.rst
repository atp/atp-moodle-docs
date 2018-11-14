Perguntas Frequentes
====================
	(Respostas atualizadas em setembro de 2016)

.. contents:: Conteúdo

------------------------

Sou ingressante, como acesso o Moodle da USP?
---------------------------------------------
Veja `Cadastro`_ para mais informações. 

Por que não consigo me inscrever ou acessar uma disciplina?
-----------------------------------------------------------
Existem algumas possibilidades que podem causar este problema:

    1. O aluno não está matriculado no Júpiter na respectiva disciplina.
    2. A sua turma do Júpiter não está configurada para ser inscrita neste ambiente de apoio online.
    3. O docente responsável pela disciplina não criou o ambiente virtual.
    4. Houve algum erro na criação do ambiente. 

Como proceder: entre em contato com o docente responsável pela disciplina, informando-o sobre o problema, para que ela ou ele possa corrigir o problema. 

É preciso ter uma conta no Stoa para usar o Moodle da USP?
----------------------------------------------------------
A partir de 9/9/2016: Não. O Moodle da USP usa a "Senha Única da USP". Veja `Cadastro`_ para mais informações. 

Trocar a senha
--------------
A partir do setembro de 2016, é possível usar a Senha Única da USP para se logar no Moodle. Veja os links "Esqueci a senha" e "Alterar senha" nos `Sistemas USP`_.

Estou logado no Moodle da USP?
------------------------------
Verifique o canto superior direito da tela. Se estiver logado, o seu nome deveria aparecer.

Não quero que visitantes ou não-logados possam acessar o conteúdo da minha disciplina
-------------------------------------------------------------------------------------
`Veja aqui`_

Migrar / Importar / Restaurar conteúdo de outros sistemas
---------------------------------------------------------
Uma vez criado o curso, é possível "restaurar" um curso inteiro a partir do backup de um outro Moodle. Porém, somente conteúdo pode ser importado (não é possível transferir usuários e suas atividades de outros Moodles para o Moodle da USP).

Para mais informações, veja `Dicas`_

Os alunos não estão aparecendo como Participantes na disciplina
---------------------------------------------------------------
Antes de mais nada: o sistema não "puxa" todos os alunos matriculados do Júpiter todos de uma vez. Mesmo se tudo estiver configurado corretamente, os seus alunos aparecerão no seu ambiente somente quando acessarem o Moodle da USP pelo menos uma vez (e o aluno deve se logar: não é suficiente somente acessar a página como visitante).

As `inscrições dos alunos matriculados no Júpiter/Janus no ambiente de apoio no Moodle da USP`_ pode não funcionar corretamente por alguns motivos:

    1. O campo "Turmas da USP" (nas configurações do ambiente) não está configurado com o código correto. Este campo deve conter um código do tipo codigo-jupiter.versão.turma.
    2. A sincronização das turmas e matriculados no Júpiter ou Janus com o Moodle da USP é feita somente uma vez por dia, de madrugada.
    3. Talvez um determinado aluno simplesmente não esteja matriculado corretamente na disciplina no Júpiter ou Janus. Neste caso, `faça a inscrição manual`_. 

Qualquer dúvida, `entrar em contato com o nosso Helpdesk`_ poderá ajudá-lo com as configurações. 

Tenho duas turmas no Júpiter mas quero ter somente um curso no Moodle
---------------------------------------------------------------------

É possível juntar alunos de duas turmas (do diurno e do noturno, por exemplo) num único ambiente no Moodle da USP. A maneira mais fácil de resolver isto é `entrar em contato com o nosso Helpdesk`_, mencionando o código da disciplina (do tipo NNN01234) e os números das turmas (do tipo 2009101 e 2009102). Nós juntaremos as turmas.

O próprio docente também pode fazê-lo: nas "Configurações" do ambiente em questão, há um campo chamado de "Turmas da USP". Este campo deve estar preenchido com um código do tipo LAN0500.3.2009101 (por exemplo). Se quiser juntar aqui uma outra turma, acrescente uma vírgula e o código da outra turma. O campo ficaria LAN0500.3.2009101,LAN0500.3.2009102

Se você já criou os dois ambientes no Moodle, agora deve pedir que os administradores apaguem o outro que não usará mais (docentes não podem remover cursos totalmente, mas podem remover todo conteúdo e avisar os administradores (suporte@edisciplinas.usp.br), que removerão o curso).

Alunos estranhos aparecem na minha disciplina!
----------------------------------------------
Verifique nas configurações da disciplina se as inscrições estão abertas ("Administração" > "Usuários" > "Métodos de inscrição": se o botão "Auto-inscrição" não estiver oculto, qualquer usuário do Moodle da USP poderá se inscrever). Se está usando as inscrições automáticas via Júpiter ou Janus (ou seja, existe o código da disciplina e turma no campo "Turmas da USP" nas configurações do ambiente), não é necessário abrir inscrições, os seus alunos matriculados serão inscritos automaticamente.

Caso a sua disciplina não use as inscrições automáticas, ainda poderá abrir as inscrições, porém sem abrir para todos por meio de um código. Veja o item a seguir. 

Permitir auto-inscrição com código de inscrição
-----------------------------------------------
Há situações em que você gostaria de abrir as inscrições, mas não para que qualquer usuário do Moodle possa se inscrever no seu ambiente (lembre-se de que todos os membros da comunidade USP podem se cadastrar neste Moodle). Este caso pode ser resolvido com um código de inscrição. Em "Administração do ambiente" > "Usuários", habilite o Método de inscrição "Auto-inscrição". Configure o método e coloque um código. Somente quem conhece o código pode se inscrever no curso. 

Inscrever alunos ou monitores manualmente
-----------------------------------------
Qualquer um dos docentes ou monitores responsáveis pelo ambiente no Moodle podem acrescentar qualquer outro usuário do Moodle como aluno, monitor ou docente no seu ambiente (em "Administração do ambiente" > "Usuários" > "Usuários inscritos". Veja `Dicas: Inscrever Monitores e Alunos`_ para mais informações. 

Como colocar dois docentes num único curso?
-------------------------------------------
O próprio responsável (docente) pelo curso pode acrescentar qualquer outro usuário do Moodle com o papel de "Docente". Veja o item acima

É claro que o co-responsável precisa possuir um `cadastro`_ no Moodle da USP 

Alunos não podem usar o Fórum
-----------------------------
Ao ser criado, em cada curso é colocado um "Fórum de notícias". Mas este fórum não permite interação por parte dos alunos. Para criar um fórum de verdade dentro do seu curso, ative a edição e acrescente uma atividade do tipo fórum. Há 4 tipos de fórum, veja `Forum Activity`_.

Quero remover o meu ambiente do sistema
---------------------------------------
Docentes podem "esconder" e deixar inacessível cursos já criados no sistema (veja o item "Visível" nas configurações do ambiente ("Editar configurações" > "Oculto"). O curso estará indisponível para alunos.

Docentes não podem remover ambientes totalmente, mas podem remover todo conteúdo e avisar os administradores (suporte@edisciplinas.usp.br), que removerão o curso.  

Criar cursos de outros semestres ("o meu curso não aparece")
------------------------------------------------------------
O nosso sistema de criação de ambientes automáticos somente oferece essa possibilidade para disciplinas com turmas no semestre atual (ou seja, se houver um "oferecimento" segundo Júpiter). Assim, se um professor não é responsável por pelo menos uma turma no semestre atual, não poderá criar o curso sem intervenção manual dos administradores do Moodle.

Podemos, porém, criar qualquer ambiente manualmente: entre em contato (suporte@edisciplinas.usp.br) e mande o código da disciplina e o seu nome. Por um lado, não queremos criar "cascas" de cursos vazios que nunca serão usados. Mas por outro lado, seria perfeitamente adequado ter um curso no Moodle que não é oferecido neste semestre, desde que haja conteúdo dentro e que seja útil para a comunidade.

Assim, se um dos docentes destas disciplinas quer migrar o conteúdo de um outro Moodle, ou quer se preparar já para o semestre que vem, nós criaremos o curso manualmente com o maior prazer. 

Professores não podem criar outros cursos
-----------------------------------------
Sim, por enquanto a criação de cursos deve ser feita pela integração com Júpiter ou Janus (somente disponível para os responsáveis por turmas no semestre atual, segundo consta no Júpiter ou Janus) ou via um pedido aos administradores do Moodle (pelo e-mail suporte@edisciplinas.usp.br). 

O link "Criar Curso" não aparece
--------------------------------
A `criação de um curso novo`_ normalmente é oferecida aos docentes responsáveis, segundo consta nos sistemas Júpiter e Janus, por meio de um link na página principal. Talvez a seção de alunos ou responsável na sua Unidade ainda não tenha atualizado as informações para este semestre. Verifique no próprio `Júpiter`_ e `Janus`_ quem é o responsável pela sua turma. Se estiver tudo certo lá e ainda não aparecer o link na página principal do Moodle da USP, entre em contato conosco (suporte@edisciplinas.usp.br). 

Criar ambientes que não correspondem a uma disciplina da USP
------------------------------------------------------------
O Moodle pode ser uma plataforma interessante para cursos para funcionários, treinamentos ou outros projetos educativos desenvolvidos pela comunidade USP. É perfeitamente possível hospedar este tipo de ambiente no Moodle da USP. O ambiente terá que ser criado manualmente pelos administradores do Moodle. Mande um e-mail para nós (suporte@edisciplinas.usp.br) com a sua proposta, nome do ambiente, e categoria onde caberia, etc.

No momento, somente membros da comunidade USP (ou seja, quem possui uma Senha Única da USP) pode ter conta no Moodle da USP.

Um espaço para fazer testes
---------------------------
Ao editar o seu curso, às vezes é conveniente fazer testes sem mexer no seu curso original. Provemos agora um `site de testes`_, (que pode ficar fora do ar, não há backup, etc.) cuja finalidade é servir de espaço de testes para os administradores, docentes e outros participantes do Moodle do Stoa. Há `este ambiente`_ onde você poderá fazer testes.  

Não posso "abrir" o meu curso para visitantes por causa de "direito autoral"
----------------------------------------------------------------------------
"Direito Autoral" não é motivo para deixar materiais atrás de um muro fechado.

É perfeitamente possível (e, do nosso ponto de vista, recomendável) compartilhar o seu material didático sem abdicar dos seus direitos autorais. O(a) professor(a) pode indicar no próprio texto ou recurso que ele/ela é o detentor(a) dos direitos autorais. Existem maneiras legais bem estabelecidas de dar um pouco mais de liberdade ao seu público (de re-distribuir, re-usar), indicando explicitamente o que pode e não pode fazer com esta material, mas sem abrir mão dos seus direitos: veja http://www.creativecommons.org.br/

O segundo motivo que poderia levar alguém a não compartilhar o seu trabalho é porque usou material de terceiros, este material sendo protegido por direitos autorais. Porém, em muitos casos é perfeitamente legal usar trechos de obras para fins didáticos. E, na grande maioria dos casos, simplesmente seguir as normas do discurso acadêmico por meio da atribuição correta à fonte original, afasta qualquer mal-estar por parte de todos os envolvidos. Em casos extremos, é simples achar materiais de repositórios livres para substituir materiais que realmente não podem ser reproduzidos.

Acredito que devemos tentar convencer os nossos colegas que compartilhar o seu trabalho é: (1) natural, (2) perfeitamente possível, (3) apropriado a uma instituição financiada com dinheiro público. 

Como criar questões usando um Editor?
-------------------------------------
Para editar / escrever / criar questões para o Banco de Questões do Moodle mas sem usar o próprio Moodle, use o formato `GIFT`_ e veja nesta página `algumas ferramentas`_.

Outra página com boas dicas é: https://wiki.ucl.ac.uk/display/UCLELearning/Building+Moodle+quizzes+quickly mas note que o Moodle do Stoa não possui este plugin instalado http://www.moodle2word.net/ 

No fórum há como se colocar uma data específica para finalizar a discussão do tópico?
-------------------------------------------------------------------------------------
Não, nos fóruns do Moodle não há uma configuração para definir, tecnicamente, um prazo. A ideia é que a discussão sempre deve poder continuar, independente se vai ser avaliada, intermediada ou não.

A solução simples é: o educador entrar no fórum e fazer um post do tipo "encerramos a discussão".

É possível sim, em "Editar configurações" do fórum, definir prazos após do qual não é mais possível um tutor dar notas a um post.

Finalmente, há uma solução técnica: procure no ambiente do fórum pelo link "Permissões", mas é um trabalho manual e não recomendado. Recomendo a solução social e pedagógica acima. 




.. _`Cadastro`: cadastro.html
.. _`Sistemas USP`: https://uspdigital.usp.br/wsusuario/
.. _`Veja aqui`: docentes.html
.. _`Dicas`: dicas.html
.. _`inscrições dos alunos matriculados no Júpiter/Janus no ambiente de apoio no Moodle da USP`: docentes.html#inscricao-automatica-de-alunos-matriculados
.. _`faça a inscrição manual`: dicas.html#inscrever-monitores-e-alunos
.. _`entrar em contato com o nosso Helpdesk`: https://edisciplinas.usp.br/mod/page/view.php?id=12
.. _`Dicas: Inscrever Monitores e Alunos`: dicas.html#inscrever-monitores-e-alunos
.. _`Forum Activity`: https://docs.moodle.org/en/Forum_activity
.. _`criação de um curso novo`: docentes.html#criacao-de-novos-ambientes-de-apoio-as-disciplinas
.. _`Júpiter`: https://sistemas.usp.br/jupiterweb/
.. _`Janus`: https://sistemas.usp.br/janus/
.. _`site de testes`: http://dev.atp.usp.br/stoa2/
.. _`este ambiente`: https://dev.atp.usp.br/stoa2/course/view.php?id=218
.. _`GIFT`: https://docs.moodle.org/en/GIFT_format
.. _`algumas ferramentas`: https://docs.moodle.org/en/GIFT_format#Word_processor_and_spreadsheet_tools_that_create_GIFTs
