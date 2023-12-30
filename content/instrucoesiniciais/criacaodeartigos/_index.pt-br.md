---
title: Criação de Artigos
linkTitle: Criação de Artigos
type: docs
nav_icon:
  vendor: tabler
  name: article
  color: green
nav_weight: 3
---
## Pensando em criar um tópico novo?

Primeiro precisaremos criar uma pasta dentro da pasta:

ProductCommunity/content/blog/

1. Insira o nome do assunto na pasta sem espaços e sem acentuações.
2. Crie um arquivo _index.pt-br.md
3. crie o cabeçalho do arquivo como o modelo abaixo

```markdown
title: "Tutorial"
# linkTitle:
date: 2024-01-01T13:00:00-03:00
description:  ss
nav_weight: 1000
# nav_icon:
#   vendor: bootstrap
#   name: toggles
#   color: '#e24d0e'
series:
  - Tutorial  
categories:
  - Content  
tags: 
  - Shortcode 
  - Code Block
  - KaTex
  - Mermaid
  - Math
  - Diagram
images:
authors:
  - diogoguilhen
```

Depois de ter criado você já pode escrever o seu artigo com o suporte do pluging para VS code relatado na [página](../requisitosiniciais)

| parametro   | descrição                                                                                                                                                           |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| date        | data e hora, utilizar o formato disponibilizado                                                                                                                       |
| description | Descrição da sua página, utilizado também pelo GA                                                                                                                 |
| nav_weight  | Tamanho do navegador a esquerda, deixar valor default                                                                                                                 |
| nav_icon    | Icons utilizados caso o artigo seja promovido para algum menu                                                                                                         |
| series      | As séries são frequentemente usadas para agrupar artigos que estão relacionados sequencialmente                                                                    |
| categories  | categorias são usadas para classificar o conteúdo com base em temas mais amplos. Um artigo pode pertencer a uma série e ter categorias atribuídas ao mesmo tempo. |
| tags        | Utilizadas para classificar os artigos                                                                                                                                |
| images      | utiliza-se para colocar todas as imagens utilizadas no seu artigo, colocar por tópico : "Imagens:`<enter> -"/img/imagem1.jpg"<enter> `-"/img/imagem1.jpg"``"       |
| authors     | Colocar o nome dos autores, se tiver mais de um so seguir o mesmo esquema da images.                                                                                  |

Se precisar de inspirações para escrita e dicas utilize o site abaixo:

{{< bs/btn-link url="https://hugomods.com/bootstrap/examples/hero/" size=lg class="p-3" >}}Hugo Hero Exemple{{< /bs/btn-link >}}
