# Mídia — Oficina de Ofertas

Repositório público, servido por GitHub Pages, com uma única função: hospedar
os arquivos de imagem e vídeo das campanhas publicadas pela marca **Oficina de
Ofertas** em URLs públicas.

Isso existe porque a API de Publicação de Conteúdo do Instagram (e a opção
`PULL_FROM_URL` do TikTok) exigem que a mídia esteja acessível por URL público
no momento da chamada — não aceitam upload de arquivo local. Este repositório
**não é o projeto do agente de afiliados**: código, banco de dados e
credenciais continuam privados, numa máquina local; aqui só ficam os arquivos
de imagem e vídeo que já seriam publicados de qualquer forma nas redes sociais
da marca.

Estrutura: `campanhas/{ID_DA_CAMPANHA}/arquivo.ext`.

Publicado e mantido com `gh` + `git push` a partir do projeto do agente.
