# Portal Médico Metropolitano Lapa — demonstração

Este repositório contém apenas uma interface estática de demonstração, sem dados reais, sem consulta a planilhas e sem autenticação.

## Publicar no GitHub Pages
1. Crie um repositório público chamado `portal-medicos-lapa` em https://github.com/new.
2. Envie o arquivo `index.html` para a raiz do repositório (Add file > Upload files > Commit changes).
3. Em Settings > Pages, escolha Deploy from a branch, branch `main`, pasta `/ (root)` e Save.
4. Após a publicação, abra https://danielpicoli.github.io/portal-medicos-lapa/ (se o usuário for Danielpicoli).

**Segurança:** nunca publique a planilha original, CPFs, senhas, arquivos `.env`, banco de dados ou códigos de acesso no GitHub Pages. Para um sistema real, é necessário autenticação forte e backend privado; idealmente, substituir a exibição de senhas por um fluxo de redefinição.
