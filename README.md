# Guia Definitivo Git e GitHub
- Gi => Sofware de Versionamento Loca => Faz o controçe de Versões de Arquivo e Pastas de um Projeto de Foma Local,(Git Commit)     
---------------------------------------------------------------


- GitHub => Site de Versionamento na Nuvem => Faz o controle de versões na Nuvem (Internet)  (Git  Push)

## Passo para Criar um Versionamento 

- 1º Passo - Instalar o Git no Comptador 
----------------------------------------------------------------
- 2º Passo - Configurar o Git com Email e Usucario do GitHub
  - git cofig --global user.name "NomeUsuario"
  - git cofig --global user.email "meu@email.com"
----------------------------------------------------------------
- 3º Passo - Inicar Giot na Pasta do Projeto
   - git init (vai criar a pasta oculta .git dentro do Projeto)
   - git remote add origin "o endereço do repostp´sorio  onlinde"
----------------------------------------------------------------
- 4º Passo - Fazer o Controle de Versão 
   - git add . (vai adiconar todos os arquivos parao versionamento )
   -git commit -m "Adicionar o Comentario" (faz o versionamento Local )
   - git push -u oringin (fazer o versionemento na nuvem )
------------------------------------------------------------------
- 5º Passso - atualizar Repstiorio Local 
  - git pull (pega as informações do GitHub(nuvem) e atualizar localmene(computador) )
------------------------------------------------------------------
- 6º Passo - Copiar meu repositório oara outor Computador 
 - git vlone "endereç do repositorio na nuvem "