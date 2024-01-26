# Responda cada pergunta abaixo com suas palavras.
## As respostas estão [aqui](https://github.com/heathcliff-akihiko/perguntas-github/blob/main/respostas.md)

# **NÃO ESQUEÇA**
#### VOCÊ PODE OLHAR AS RESPOSTAS A QUALQUER MOMENTO MAS SE VOCÊ DESEJA REALMENTE TESTAR SEUS CONHECIMENTOS RESPONDA COM SUAS PALAVRAS
#### CASO NÃO SAIBA RESPONDER UMA DAS PERGUNTAS PESQUISE, REVEJA SUAS ANOTAÇÕES, TESTE NO SEU CONSOLE, CONSULTE A DOCUMENTAÇÃO, SEMPRE BUSCANDO APRENDER E NÃO DECORAR
#### LEMBRANDO QUE O QUE IMPORTA É QUE AS REPOSTA ESTEJA CERTA, NÃO COM AS MESMAS PALAVRAS.

# BOA SORTE

# Introdução ao GitHub

O GitHub é uma plataforma web baseada em Git que facilita o armazenamento, colaboração e rastreamento de projetos de software. Ele fornece uma interface amigável para interação com repositórios Git, além de oferecer recursos adicionais para facilitar o trabalho em equipe.

## Principais Recursos do GitHub

1. **Repositórios:**
   - São containers onde seu projeto, seus commits e seus arquivos vivem.

2. **Forks:**
   - Permite que você faça uma cópia de um repositório para sua própria conta, facilitando a contribuição para projetos de código aberto.

3. **Pull Requests:**
   - É uma proposta de mudança. Você sugere alterações e solicita que o proprietário original do repositório as incorpore.

4. **Issues:**
   - São usadas para rastrear tarefas, melhorias, bugs e discussões no projeto.

5. **Branches:**
   - Possibilitam o desenvolvimento paralelo de recursos sem afetar o código principal.

6. **Actions:**
   - Permite a automação de tarefas, como testes, build e deploy, diretamente no GitHub.

7. **GitHub Pages:**
   - Permite hospedar sites estáticos diretamente de um repositório.

8. **Gists:**
   - São repositórios pequenos para armazenar e compartilhar trechos de código.

## Colaboração no GitHub

1. **Clone:**
   - Clone um repositório para começar a trabalhar localmente.

git clone <URL do repositório>

2. **Branch e Commit:**
- Crie branches para desenvolver recursos e faça commits regularmente.

git branch <nome do branch>
git checkout <nome do branch>

3. **Pull Request:**
- Crie uma pull request para propor suas alterações.

4. **Issues:**
- Reporte bugs ou sugira melhorias através de issues.

## Conclusão

O GitHub é mais do que apenas uma plataforma de hospedagem Git. Ele oferece ferramentas colaborativas poderosas que facilitam o desenvolvimento de software em equipe e o gerenciamento eficiente de projetos.


## Exercícios de GitHub - Nível Básico:

1.  Como criar um novo repositório no GitHub?
	Logado no github clicar em "new repository", nomeie seu repositório e defina se será public ou private e clicar em create repository.

2.  Como clonar um repositório do GitHub para o seu computador?
	Acesse o repositório que deseja clonar, no botão Code do github copie a url do repositório. O comando utilizado no terminal é git clone url do repositório.
 
3.  Como adicionar colaboradores a um repositório no GitHub?
	Na sessão meus repositórios, escollha um repositório e acesse, ir na aba settings e no menu lateral escolha manage access, no botão verde clique em convidar colaborador, incluimos o id desse usuário e clique no botão para confirmar.
  
4.  Explique a diferença entre um repositório público e privado no GitHub.
	Um repositório público, o próprio nome diz, o projeto fica aberto a qualquer pessoa que queira ter acesso e o privado só terá acesso o dono do projeto ou alguma pessoa que ele adicionar como colaborador.

5.  Como criar e fechar problemas (issues) no GitHub?
	Para criar uma issue acessar o repositório desejado, clicar em new issue, digitar a pergunta, escrever um pequeno texto explicando a dúvida e clique em submit. Para fechar entramos na issue, respondemos a issue, clico em comment e em seguida em closed para fechar a issue, clico no menu lateral em lock conversation, escolho a opção resolved, por exemplo e clico em lock, pronto issue finalizada.
    
6.  Como fazer um fork de um repositório no GitHub?
	Dentro do projeto clico em fork, no menu lateral clico em meus repositórios e pronto o projeto que fiz o fork já estará lá. 	Desta forma posso agora fazer modificações nesse projeto sem interferir no projeto principal da outra pessoa.

7.  Como criar um arquivo README.md usando a sintaxe do Markdown?    	Crie um arquivo README.md no VSCode e escreva o conteúdo com a linguagem de marcação markdown.

8.  Como criar um Pull Request (PR) para contribuir com um repositório?
Fazendo qualquer alteração no código que agora tem uma versão no meu github através do fork que já foi realizado anteriormente, vou criar o commit, incluindo a mensagem sobre a alteração realizada, neste momento ele mostra que tem mais de um contribuidor para este projeto, no caso, eu e o dono do projeto. Para sugerir esta alteração no projeto original, preciso criar um pull request, clicando no botão pull request dentro do referido repositório, o github vai verificar se não tem nenhum conflito, mostrar o detalhe da alteração realizada e clicamos em create pull request. Nesse momento o dono do projeto vai ser sinalizado sobre esta solicitação de recebimento e ele pode alterar ou não o projeto original.

9.  Como usar as Actions do GitHub para criar um fluxo de trabalho automatizado?
NÃO CONSEGUI ENTENDER ESSE TÓPICO.
  
  
10.  Como usar o GitHub Pages para hospedar um site estático?
Logada na minha conta do github, defina qual repositório voce vai utilizar para hospedar o projeto no github pages ou crie um novo repositório.Agora dentro do repositório clicar em settings, no menu lateral esquerdo clicar em pages, em source escollha a opção main e save. Neste momento ele vai informar a url criada para ser divulgada.

## Exercícios de GitHub - Nível Intermediário:

1.  Descreva o processo de revisão de código (code review) em um Pull Request no GitHub.  
Pelo que entendi o pull request envia as alterações ou colaborações no código que podem ou não ser aceitas para fazerem parte do código original e na code review essas ações ção discutidas para um melhor entendimento e alinhamento entre todos os colaboradores do código em questão.
  
2.  Como usar as GitHub Actions para executar testes automatizados em seu código? 
NÃO CONSEGUI ENTENDER ESSE TÓPICO.
   
3.  Explique a diferença entre "git fetch" e "git pull" ao trabalhar com repositórios remotos.
O git fetch baixa o conteúdo remoto e não altera o estado do repositório local. Já o git pull baixa o conteúdo remoto e, de imediato, tenta alterar o estado local para que ele corresponda aquele conteúdo.

4.  Como criar e gerenciar um projeto no GitHub?
Na foto do perfil do github clicar em your profile, projects, new project, digite um nome para o projeto, escolha um modelo ou um projeto vazio e clique em create.Agora dentro do projeto adicionamos tarefas e informações importantes do projeto.
    
5.  Como usar os templates de problemas (issue templates) para padronizar os problemas relatados?
Na página principal do repositório, clicar em configurações, na seção recursos, em problemas clique em configurar modelos. No menu Adicionar modelo e clique no tipo de modelo que deseja criar. Voce pode visualizar e editar o modelo antes de comitar, depois clique em propor alterações, digite a mensagem de commit. Clique em fazer commit das alterações. Desta forma o modelo será disponibilizado para os contribuidores usarem quando abrirem os novos problemas no repositório.
