---
title: Enviando artigos e alterações
linkTitle: Enviando artigos e alterações
type: docs
nav_icon:
  vendor: feather
  name: git-pull-request
  color: green
nav_weight: 4
---
### Como Gerar um Pull Request no GitHub - Passo a Passo Simples:

1. **Acesse o Repositório:**
   * Abra o navegador e vá para o repositório do projeto no GitHub.
2. **Fork do Repositório:**
   * No canto superior direito da página do repositório, clique no botão "Fork" para criar uma cópia do repositório na sua conta.
3. **Clone o Repositório Forked:**
   * Abra o terminal no seu computador.
   * Execute o comando `git clone URL_DO_SEU_FORK` para baixar uma cópia do repositório para o seu computador.
4. **Crie uma Nova Branch:**
   * Execute o comando `git checkout -b SUA_NOVA_BRANCH` para criar e mudar para uma nova branch onde você fará suas alterações.
5. **Faça Suas Alterações:**
   * Abra os arquivos necessários e faça as alterações desejadas.
6. **Commit das Alterações:**
   * Execute os seguintes comandos:
     * `git add .` para adicionar todas as alterações.
     * `git commit -m "Descrição curta das suas alterações"` para fazer o commit das alterações.
7. **Push para o Repositório Forked:**
   * Execute o comando `git push origin SUA_NOVA_BRANCH` para enviar suas alterações para o seu repositório forked.
8. **Abra um PR no GitHub:**
   * No GitHub, vá até a página do seu repositório forked.
   * Clique no botão "Compare & pull request" ao lado da sua nova branch.
9. **Preencha o Formulário do PR:**
   * Dê um título descritivo ao seu PR.
   * Adicione uma descrição detalhada do que você alterou.
   * Clique no botão "Create pull request" para abrir o PR.
10. **Aguarde a Revisão:**
    * Aguarde a revisão e feedback dos colaboradores do projeto.
11. **Finalize o PR:**
    * Se não houver alterações necessárias, seu PR será mesclado (merged).
12. **Exclua a Branch (Opcional):**
    * Após o PR ser mesclado, você pode excluir a branch, se desejar.
