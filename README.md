# Um projeto simples de final de curso

## Passo a passo
git init
git config user.name luiz
git config user.email lpdossj@gmail.com

// cria o arquivo readme.md
git add readme.md
git commit -m "um comentário"

// Cria projeto no github

// Conectar o repositório local com o remoto
git remote add origin https://github.com/lpdossj/projeto-livro-scifi.git

- para listar os repositório que estão sincronizados.
git remote 

- Para enviar as alterações para originm contudo...
git push origin master

- Podemos padronizar também para que nos próximos push as alterações sejam enviadas para origin 
git push -u origin master