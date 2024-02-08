### Passo a passo para criar um repositório no GitHub <h3>

#### Primeiro cria-se uma conta GitHub (https://github.com/) 
#### Instale GitHub Desktop (https://desktop.github.com/)
#### Instale o Visual Studio Code (https://code.visualstudio.com/download)
#

1. Após as devidas instalações, no GitHub Web, na página "home" clicaremos no botão verde indicado como "new" ao lado de "Top Repositories", criando assim um novo repositório
2. Coloque o nome de seu repositório em: Repository Name. exemplo: laura-dw
3. Deixe seu repositório público, para que seus colegas e professores tenham acesso, caso não queira que outras pessoas acessem, coloque na opção "private"
4. Então aperte novamente no botão verde nomeado de "Create Repository"
5. Você será direcionado a uma página, ao identificar um quadro azul, clique no botão "Set up in Desktop"

##### GitHub Desktop <h5>

1. Certifique-se de que foi enviado para o desktop na opção "URL", então clone.
2. Depois de clonado, você será redirecionado para uma página do desktop "No local changes", então apertará no botão "Opne in visual studio code"

##### VSCODE <h5>

1. Agora no Visual Studio, aperte no botão azul "Yes, a trust the authors"
2. Sua pasta está criada, no meu exemplo nomeada de laura-dw-teste, ao lado desse nome, crie um novo arquivo e nomeie de "README"
3. Digite uma frase de teste, ex: "###NOME DO PROJETO"

##### GitHub Desktop <h5>

1. No GitHub Desktop, adicione a descrição no quadro localizado no canto inferior direito, dê _*commit to main*_.
2. Para localizar o que foi salvo no passo anterior, vá em *"history" e aperte no botão "Pushing Branch"
3. Percebemos um erro, então vamos voltar no *VISUAL STUDIO CODE* para editar, dando espaço após uma das hastags, para fazer um título, ex: "### NOMEDOPROJETO"
3. Como seu repositório está público e alguém tenha feito algum tipo de alteração, você poderá fazer o "pull", que é trazer essas alterações para seu desktop e estudá-las.
4. Para isso, abra o GitHub Desktop, no canto superior esquerdo, clique em "repository" e depois em "pull"; ou faça "Ctrl+shift+P"

### Pronto, agora você tem um repositório no GitHub!!

#### No dia 08/02 demos continuidade ao conteúdo, aprendendo sobre o branch com os seguintes passos: 

1. Abrimos os **GitHub Web**, **GitHub Desktop** e o **VSC**;
2. Abrimos a pasta que criamos na primeira aula para testar os códigos, no meu caso a pasta "Laura-aula4-dw"
3. No **GitHub Desktop** selecionamos os diretório que está sendo executado no **VSC**;
4. Criamos um branch no campo __"Branch"__ e nomeamos da forma que quisermos, no meu casos "new_branch";
5. Voltamos pro **VSC** fizemos um novo file chamado __"teste.txt"__ e adicionamos uma frase de teste;
6. Voltamos no **GitHub Desktop** e damos commit dentro da branch sobre o __"teste.txt"__
7. Selecionamos o __"main"__ em **Current Branch** e voltamos ao **VSC** e criamos um novo file de teste 2, resultando agora em dois files testes, um na branch nova e outro no main;
8. Fazemos a unificação da branch ao main apertando em __"Marge into current branch..."__;
9. Agora não se tem mais necessidade de se ter a branch __"new_branch"__ já que unificamos ela em main, então clicamos nela com o botão direito e vamos excluí-la.