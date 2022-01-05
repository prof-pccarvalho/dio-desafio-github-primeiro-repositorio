# dio-desafio-github-primeiro-repositorio
Reforce seu conhecimento em Git com um desafio de projeto totalmente prático, onde você executará todos os passos para a criação, atualização e sincronização de um repositório no GitHub. Para isso, tenha em mente todas as dicas e direcionamentos apresentados pelo expert nas aulas. Dessa forma, você poderá compartilhar suas anotações e exercícios em seu próprio repositório. Criando assim, o primeiro (de muitos) projetos do seu portfólio ;

* Link para download do Git: https://git-scm.com/downloads
* O Git Bash é um terminal extendido para otimizar o uso do Git.

# Vinculando sua pasta local ao repositório
* Alternativa 1: Clonando o link do seu repositório à sua pasta local

--> git clone "URL obtida no github"
  
  
  *** Isso irá criar uma pasta na sua máquina de mesmo nome do repositório do Github (isso é bacana pq facilita muito) e, a partir daí você já poderá trabalhar. 
Além disso, há uma pasta .git, dentro da sua pasta, responsável por armazenar todas as informações do seu projeto.


* Alternativa 2: Criando sua pasta local e associando-a ao repositório

Após criar a sua pasta (com o nome que você quiser), você precisa dos seguintes comandos:

--> git init

--> git remote add origin "URL obtida no github"  

Observação: Se você criou seu projeto no GITHUB e ele já está com um README na sua estrutura, é necessário, antes de mais nada, você obter na sua máquina local,
 tudo o que tiver no seu repositório (antes de colocar seus próprios arquivos). 
 Faça um PULL do seu repositório na sua máquina (veremos esse comando mais a frente)

--> git pull origin master
  
  Pronto, já está associada a pasta local ao repositório remoto.
> “Boas Práticas” para seu dia-a-dia
  
  Lembre-se: cada commit é uma efetivação de elementos relevantes, ou seja, mudanças que podem afetar seu software de forma efetiva.

--> git pull origin master   // obtenho as útlimas alterações feitas pelos outros  

--> git add .                // adiciono meus novos arquivos  

--> git commit -m "mensagem" // efetivo as alterações  

--> git push origin master   // faço o upload para o repositório  

  
  Claro que, sempre entre um comando e outro, vale um git status para acompanhar o que acontece.

## Links Úteis
[Sintaxe Basica Markdown](https://www.markdownguide.org/basic-syntax/)
