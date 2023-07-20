## Exercícios de GitHub - Nível Básico:

1.  Como criar um novo repositório no GitHub?
**Resposta**: Faça login no GitHub, clique no botão "+" no canto superior direito e selecione "New repository". Siga as instruções para configurar o novo repositório.
    
2.  Como clonar um repositório do GitHub para o seu computador?
**Resposta**: No repositório no GitHub, clique no botão "Code" e copie o URL do repositório. No seu computador, abra o terminal, navegue até o diretório desejado e use o comando `git clone URL-do-repositorio` para clonar o repositório.
    
3.  Como adicionar colaboradores a um repositório no GitHub?
**Resposta**: No repositório no GitHub, vá para "Settings" > "Manage access" e clique em "Invite a collaborator". Digite o nome do colaborador ou o nome de usuário do GitHub e clique em "Add collaborator".
    
4.  Explique a diferença entre um repositório público e privado no GitHub.
**Resposta**: Um repositório público é visível para qualquer pessoa na internet, enquanto um repositório privado é visível apenas para os colaboradores do repositório.
    
5.  Como criar e fechar problemas (issues) no GitHub?
**Resposta**: No repositório no GitHub, clique na aba "Issues" e, em seguida, clique no botão "New issue" para criar um novo problema. Para fechar um problema, clique no botão "Close issue" na página do problema.
    
6.  Como fazer um fork de um repositório no GitHub?
**Resposta**: No repositório que deseja fazer o fork, clique no botão "Fork" no canto superior direito da página. Isso criará uma cópia do repositório no seu perfil do GitHub.
    
7.  Como criar um arquivo README.md usando a sintaxe do Markdown?
**Resposta**: Crie um arquivo chamado "README.md" no repositório e use a sintaxe do Markdown para adicionar conteúdo ao arquivo. O Markdown é uma linguagem de marcação leve que permite formatar o texto com facilidade.
    
8.  Como criar um Pull Request (PR) para contribuir com um repositório?
**Resposta**: Após fazer um fork e fazer alterações no seu fork, vá para a página do repositório original e clique no botão "Pull Request". Selecione a branch com suas alterações e clique em "Create Pull Request".
    
9.  Como usar as Actions do GitHub para criar um fluxo de trabalho automatizado?
**Resposta**: Crie um arquivo de configuração chamado "workflow.yml" na pasta ".github/workflows/" do repositório. Defina os eventos que acionarão a execução da ação e especifique as etapas que deseja automatizar.
    
10.  Como usar o GitHub Pages para hospedar um site estático?
**Resposta**: Crie um branch chamado "gh-pages" no repositório e coloque o conteúdo do site estático nesse branch. O GitHub Pages irá automaticamente hospedar o site em um URL específico.
    

## Exercícios de GitHub - Nível Intermediário:

1.  Descreva o processo de revisão de código (code review) em um Pull Request no GitHub.
**Resposta**: No Pull Request, os revisores podem visualizar as alterações propostas, fazer comentários e sugerir melhorias. Os revisores e o autor do Pull Request podem discutir as alterações antes que o PR seja mesclado (merged) no repositório original.
    
2.  Como usar as GitHub Actions para executar testes automatizados em seu código?
**Resposta**: Configure uma GitHub Action que seja acionada por eventos específicos (por exemplo, um push para uma branch). Use essa Action para executar os testes automatizados no código e relatar os resultados.
    
3.  Explique a diferença entre "git fetch" e "git pull" ao trabalhar com repositórios remotos.
**Resposta**: `git fetch` busca as informações mais recentes do repositório remoto, mas não faz merge com a branch atual. Já `git pull` busca as informações mais recentes e faz o merge automático com a branch atual.

4.  Como criar e gerenciar um projeto no GitHub?
**Resposta**: No repositório, vá para a aba "Projects" e clique em "Create a project". Você pode adicionar colunas para representar diferentes estágios do projeto e adicionar cartões para representar tarefas específicas.
    
5.  Como usar os templates de problemas (issue templates) para padronizar os problemas relatados?
**Resposta**: Crie um diretório chamado ".github/ISSUE_TEMPLATE/" no repositório e adicione arquivos de modelo de problemas (por exemplo, bug_report.md e feature_request.md). Quando os usuários criarem um novo problema, eles poderão escolher um dos modelos para padronizar o relatório.
