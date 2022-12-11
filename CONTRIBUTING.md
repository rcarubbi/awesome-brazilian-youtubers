# Diretrizes de contribuição

Por favor siga o [código de conduta](https://github.com/rcarubbi/awesome-brazilian-youtubers/blob/main/CODE_OF_CONDUCT.md).

Apenas adicione YouTubers que sejam realmente **awesome**! _"Afinal, é uma curadoria, não uma coleção"_. [O que é awesome?](https://github.com/sindresorhus/awesome/blob/main/awesome.md#only-awesome-is-awesome)

<details>
  <summary>Guia para novos usuários do GitHub</summary>
  <ol>
    <li>Va até o arquivo <a href="https://github.com/rcarubbi/awesome-brazilian-youtubers/blob/main/README.md">readme.md</a> neste repositório.</li>
    <li>Clique no botão "editar" (com o ícone de um lápis).</li>
    <li>Adicione o novo YouTuber (seguindo o formato abaixo e no final da seção apropriada) e clique em "Commit".</li>
    <li>Clique no botão verde "Criar um pull request", preencha o template e clique no botão verde "Criar um pull request" novamente.</li>
    <p>E é isso... fácil assim!</p>
  </ol>
</details>

## Adicione o YouTuber seguindo este formato

```html
[<img align="left" height="94px" width="94px" alt="Avatar do canal" src="LINK_PARA_O_AVATAR_DO_CANAL_DO_YOUTUBE"/>](LINK_A_PAGINA_PRINCIPAL_DO_CANAL) 

[**NOME_DO_CANAL**](LINK_A_PAGINA_PRINCIPAL_DO_CANAL) [<img height="16px" width="16px" alt="Distintivo para canais do YouTube verificados" src="badges/badge-verificado.svg" title="É um canal do YouTube verificado"/>](badges/README.md#canal-do-youtube-verificado) [<img height="16px" width="16px" alt="Distintivo para YouTubers que postam videos semanalmente" src="badges/badge-semanal.svg" title="Posta videos semanalmente"/>](badges/README.md#post-de-videos-semanais) \ 
Conteúdo sobre: EXEMPLO, EXEMPLO, EXEMPLO \ 
Playlists em destaque: `PLAYLIST 1`, `PLAYLIST 2`, `PLAYLIST 3`,`PLAYLIST 4`. \
<br />
```

<details>
  <summary>Exemplo:</summary>

[<img align="left" height="94px" width="94px" alt="Avatar do canal do GitHub" src="https://yt3.ggpht.com/a/AATXAJzVBGU-QyENevFp8etYX1iEak8Y7KEjUPsucWAvAA=s100-c-k-c0xffffffff-no-rj-mo"/>](https://www.youtube.com/user/github)

[**GitHub**](https://www.youtube.com/user/github) [<img height="16px" width="16px" alt="Distintivo para YouTubers que postam videos semanalmente" src="badges/badge-semanal.svg" title="Posta videos semanalmente"/>](badges/README.md#post-de-videos-semanais) \
Conteúdo sobre: Código livre, Segurança, Desenvolvimento de Aplicativos \
Playlists em destaque: `Open Source Friday`, `GitHub Satellite 2020 - Work`, `Public Roadmap`, `GitHub Artic Code Vault`.

</details>

**Apenas edite as palavras que estão TOTALMENTE EM CAIXA ALTA. Deixe todas as outras coisas como estão. Considerações abaixo.**

- No exemplo, você vê que dois distintivos foram adicionados (Distintivos de Canal do YouTube verificado e posts semanais). Se o canal não satisfizer um destes requerimentos, remova o distintivo. Mais informações no [arquivo de distintivos](badges/README.md).
- Se a seção "Playlists em destaque" for mais curta do que 124 caracteres, adicione um símbolo `\` e uma tag `<br/>` na linha abaixo. Caso contrário, não adicione nada.
- Preste atenção a todos os outros caracteres: pontos, vírgulas, asteríscos, etc.
- Antes de abir um pull request, tenha certeza que o layout esteja correto.

## Crie o conteúdo do pull request seguindo este formato

_Aparece automaticamente quando você criar um pull request._

```markdown
- **Nome do YouTuber:**
- **Sobre o que é este canal? (ex. desenvolvimento web, design, ...)**:
- **Em que seção está este canal? (Se você criar uma nova seção, por favor especifique o motivo)**:
- **Por que você considera que este YouTuber merece um lugar nesta lista? _O que faz dele awesome?_**:
```

<details>
  <summary>Exemplo:</summary>

- **Nome do YouTuber**: GitHub
- **Sobre o que é este canal? (ex. desenvolvimento web, design, ...)**: Plataforma de desenvolvimento de software para armazenagem de repositórios.
- **Em que seção está este canal? (Se você criar uma nova seção, por favor especifique o motivo)**: Código Livre.
- **Por que você considera que este YouTuber merece um lugar nesta lista? _O que faz dele awesome?_**: O youtuber posta videos diariamente com tutoriais de tecnologia em geral. Estes tutoriais incluem proteção à sua empresa, busca de vulnerabilidades, uso de GitHub actions, e mais. Também tem playlists muito úteis aonde você pode encontrar palestras de profissionais que te ensinam diversos tópicos.
</details>
