# Code Education - Curso Git:
## Projeto: Fazendo o Primeiro Push

Método Utilizado:

  
 * __Primeiro Passo__: Criado no Git Bash um novo diretório (local) para Projeto utilizando o seguinte comando: _mkdir projeto-push_.
 * __Segundo Passo__: Inicializado o repositório Git (.git) no diretório "projeto-push"  utilizando o seguinte comando: _git init_.
 * __Terceiro Passo__: Criado um novo arquivo README.md utilizando o seguinte comando: _touch README.md_.
 * __Quarto Passo__: Criado o conteúdo inicial em Markdown do arquivo README pelo [Editor Online - GitHub](https://jbt.github.io/markdown-editor/) e adicionado no arquivo README (local) utilizando o seguinte comando: _vim README.md_.
 *  __Quinto Passo__: Adicionado o arquivo README a lista de arquivos a serem monitorados utilizando o seguinte comando: _git add README.md_ (Agora o arquivo README não está mais em Untracked files, portanto já pode ser commitado).
 *   __Sexto Passo__: Realizado o Commit do arquivo README, utilizando o seguinte comando: _git commit README.md -m 'Primeiro Commit, adicionado arquivo README'_
 * __Sétimo Passo__: Criado novo repositório no GitHub entrando em Profile -> Repositories -> New. Adicionado um nome ao repositório, selecionado Public (para repositório publico) e clicado em "Create repository". 
 * __Oitavo Passo__: Configurado o Git para que possamos enviar e receber modificações do repositório local para o repositório remoto no GitHub. Utilizado o seguinte comando: _git remote add origin https://github.com/pedrolatance/code-education-projeto1.git_.
 * __Nono Passo__: Atualizado o arquivo README com o contéudo completo utilizando o seguinte comando: _vim README.md_.
 * __Décimo Passo__: Adionado as modificações e commitado o README atualizado. Utilizado o seguinte comando: _git commit -a -m 'Segundo Commit, atualizado arquivo README'_.
 * __Passo Final__: Realizado o push para o repositório remoto no GitHub utilizando o seguinte comando: _git push origin master_.

**Autor:** _Pedro Latance_  
**Data:** _12/10/2016_
