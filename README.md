# Resumo sobre a atividade

Você está iniciando o desenvolvimento de um sistema WEB para uma pequena lanchonete. • O projeto ainda está no início, mas a equipe decidiu utilizar Git para controlar o histórico do desenvolvimento e GitHub para armazenar o repositório
remoto. 
• A partir do repositório criado na aula, você deverá evoluir o projeto em etapas, realizando commits pequenos, organizados e descritivos. 
• Nosso objetivo é praticar o ciclo de versionamento local e remoto, compreendendo a diferença entre alterações nos arquivos, commits e push. 
## • Etapa 1 — Estrutura inicial do projeto
• Crie a seguinte estrutura de diretórios e arquivos:
MeuPrimeiroGit/
README.md
docs/

requisitos.md

src/

index.html 
• Ajuste a estrutura inicial, inclua qualquer conteúdo nos arquivos, nosso foco é com o git. 
• Através do add, organize os arquivos e diretórios. 
• Crie um ponto de versão, devendo ser utilizada a seguinte mensagem de commit: Adiciona estrutura inicial do projeto. • Suba as alterações para o remoto.

LABORATÓRIO PRÁTICO

## Etapa 2 — Documentando os produtos
• Crie e inclua um texto de documentação da funcionalidade de produto:
docs/produtos.md

• Crie um ponto de versão, devendo ser utilizada a seguinte mensagem de commit: Adiciona documentação dos
produtos.

## Etapa 3 — Criando a página de produtos
• Crie a página html de produtos:
src/produtos.html • Através do add, organize os arquivos e diretórios. • Crie um ponto de versão, devendo ser utilizada a seguinte mensagem de commit: Adiciona página de produtos. • Verifique com o git status, quantos commits estão confirmados
• Suba as alterações para o remoto.

## Etapa 4 — Adicionando um arquivo CSS
• Crie:
src/style.css

• Altere o src/index.html para referenciar o CSS:
<link rel="stylesheet" href="style.css">

• Inclua qualquer conteúdo nos arquivos, nosso foco é com o git. 
• Utilize os comandos git status, git diff. 
• Através do add, organize os arquivos e diretórios. 
• Crie um ponto de versão, devendo ser utilizada a seguinte mensagem de commit: Adiciona estilização inicial. 
• Suba as alterações para o remoto.

## Etapa 5 — Criando a página de pedidos
• Crie os arquivos:
src/pedidos.html
docs/pedidos.md

• Inclua qualquer conteúdo nos arquivos, nosso foco é com o git. • Através do add, organize os arquivos e diretórios. • Crie um ponto de versão, devendo ser utilizada a seguinte mensagem de commit: Adiciona documentação e página
inicial de pedidos. • Suba as alterações para o remoto.

## Etapa 6 — Atualizando a documentação
• Altere o README.md, acrescentando a documentação do que foi feito até aqui. • Inclua qualquer conteúdo nos arquivos, nosso foco é com o git. 
• Utilize o git diff 
• Através do add, organize os arquivos e diretórios. • Crie um ponto de versão, devendo ser utilizada a seguinte mensagem de commit: Atualiza documentação do
projeto. 
• Suba as alterações para o remoto.

## Etapa 7 — Contato
• Crie uma nova funcionalidade chamada Contato, composta por um arquivo HTML e um arquivo CSS específico.
src/contato.html
src/contato.css

• Inclua qualquer conteúdo nos arquivos, nosso foco é com o git. 
• Através do add, organize os arquivos e diretórios, preparando eles para um único commit. 
• Crie um ponto de versão, devendo ser utilizada a seguinte mensagem de commit: Adiciona documentação e página
inicial de contato. 
• Suba as alterações para o remoto.

## • Etapa 8 — Atualizando a documentação
• Altere o README.md, respondendo as perguntas abaixo: 
### Qual é a diferença entre Working Directory, Staging Area e Repository?
Working Directory: É a pasta do projeto
Staging Area: É o espaço entre o git add, onde adicionamos as modificações até fazer o git commit
Repository: É onde fica os git commits, dentro de uma pasta oculta chamada ".git"
### Qual é a diferença entre git commit e git push? 
O git commit fica localmente, e quando fazemos um git push subimos os commits para o repositorio remoto (github)
### É possível realizar vários commits antes de executar um git push? Explique. 
Sim, é possivel sim todos iram subir separadamente no repositorio remoto
### Por que é interessante realizar commits pequenos e descritivos? 
Pois fica mais fácil de localizar e caso algum erro aconteça durante a criação da aplicação retorna na versão mais recente antes do erro
### O que acontece com os commits locais quando ainda não executamos o git push? 
Ficam apenas na pasta ".git", e não é possivel fazer o acesso remoto 
### Como verificar, pelo GitHub, se os commits foram enviados corretamente?
Pela url do repositorio 

• Utilize o git diff 
• Organize os arquivos e diretórios. 
• Crie um ponto de versão, devendo ser utilizada a seguinte mensagem de commit: Questionário.