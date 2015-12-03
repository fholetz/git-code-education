# Aulas Git da Code Education #

Infos gerais sobre conteúdo das aula sobre Git da Code Education.

### Exemplos práticos ###

 * Criação do repositório principal
 * Criação e adição dos arquivos do projeto
 * Adição e manuseio de Branchs
 * Utilização e manuseio do GutHub - [fholetz](https://github.com/fholetz/) repositório público [git-code-education](https://github.com/fholetz/git-code-education)
 * Criação deste *README*

### Branchs e respectivos exercícios de commits ###

Abaixo todos os branchs criados e histórico dos commits realizados.
**Notas:**
  Todos os commits foram localmente atualizados para o master e este por sua vez salvo no GitHub.
  Na sequência o Branch master foi sincronizado ao novobranch e projeto1.1 via *rebase*.
  Para a produção do *README*, resetei os Branchs com base no respectivo conteúdo do GitHub via *"git checkout -B"* e assim poder criar um histórico de logs coerente via *"git log"* aqui para este *README*.

> *Após diversos mkdir, ls, mv, touch, vim, cat, git, checkout, origin, push, pull, reset, rebase, HEAD
> etc... etc...etc...*

#### Branch master [11 commits](https://github.com/fholetz/git-code-education/commits/master)
```st
exctract from: git log master --pretty=format:" * %h - %ad : %s"
```

 * da051c7 - Wed Dec 2 20:36:11 2015 -0200 : Alterados Testes.txt 2 e 3
 * 66cc538 - Wed Dec 2 20:09:34 2015 -0200 : arquivo novobranch
 * 32b9ca3 - Wed Dec 2 20:01:24 2015 -0200 : Adicionando Olá no teste.php
 * da8e7ef - Tue Dec 1 20:17:36 2015 -0200 : master modificado no arquivo.txt
 * 5d59928 - Tue Dec 1 20:15:27 2015 -0200 : adicionada funcionalidade 1
 * 225c23b - Tue Dec 1 20:10:23 2015 -0200 : adicionados arquivos testes extras e vazios
 * c19c354 - Sun Nov 29 23:19:07 2015 -0200 : adicionando .gitignore
 * 7889cf5 - Sun Nov 29 22:43:25 2015 -0200 : comitando todos os arquivos modificados
 * aa293eb - Sun Nov 29 22:38:15 2015 -0200 :
      - criando um primeiro exemplo de php com git e commit
      - ao mesmo tempo deixando claro o processo
      - aí assim por diante.
 * 1dcfc29 - Sun Nov 29 22:27:29 2015 -0200 : alterado arquivot.txt
 * a5d716b - Sun Nov 29 22:25:00 2015 -0200 : Teste primeiro commit
 
#### Branch novobreanch [10 commits](https://github.com/fholetz/git-code-education/commits/novobranch)
```st
exctract from: git log novobranch --pretty=format:" * %h - %ad : %s"
```

 * 66cc538 - Wed Dec 2 20:09:34 2015 -0200 : arquivo novobranch
 * 32b9ca3 - Wed Dec 2 20:01:24 2015 -0200 : Adicionando Olá no teste.php
 * da8e7ef - Tue Dec 1 20:17:36 2015 -0200 : master modificado no arquivo.txt
 * 5d59928 - Tue Dec 1 20:15:27 2015 -0200 : adicionada funcionalidade 1
 * 225c23b - Tue Dec 1 20:10:23 2015 -0200 : adicionados arquivos testes extras e vazios
 * c19c354 - Sun Nov 29 23:19:07 2015 -0200 : adicionando .gitignore
 * 7889cf5 - Sun Nov 29 22:43:25 2015 -0200 : comitando todos os arquivos modificados
 * aa293eb - Sun Nov 29 22:38:15 2015 -0200 :
      - criando um primeiro exemplo de php com git e commit
      - ao mesmo tempo deixando claro o processo
      - aí assim por diante.
 * 1dcfc29 - Sun Nov 29 22:27:29 2015 -0200 : alterado arquivot.txt
 * a5d716b - Sun Nov 29 22:25:00 2015 -0200 : Teste primeiro commit

#### Branch novobreanch [8 commits](https://github.com/fholetz/git-code-education/commits/nprojeto1.1)
```st
exctract from: git log projeto1.1 --pretty=format:" * %h - %ad : %s"
```

 * da8e7ef - Tue Dec 1 20:17:36 2015 -0200 : master modificado no arquivo.txt
 * 5d59928 - Tue Dec 1 20:15:27 2015 -0200 : adicionada funcionalidade 1
 * 225c23b - Tue Dec 1 20:10:23 2015 -0200 : adicionados arquivos testes extras e vazios
 * c19c354 - Sun Nov 29 23:19:07 2015 -0200 : adicionando .gitignore
 * 7889cf5 - Sun Nov 29 22:43:25 2015 -0200 : comitando todos os arquivos modificados
 * aa293eb - Sun Nov 29 22:38:15 2015 -0200 :
      - criando um primeiro exemplo de php com git e commit
      - ao mesmo tempo deixando claro o processo
      - aí assim por diante.
 * 1dcfc29 - Sun Nov 29 22:27:29 2015 -0200 : alterado arquivot.txt
 * a5d716b - Sun Nov 29 22:25:00 2015 -0200 : Teste primeiro commit

> *Git e GitHub são muito bacanas!*
> *Utilizar* ***Markdown*** *no README é show!!!*

Obrigado!

Fabiano Holetz.
