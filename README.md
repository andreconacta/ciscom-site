# Site institucional da Ciscom

Site estático (HTML puro, sem framework) publicado no Cloudflare Workers
por meio do recurso de static assets.

## Estrutura

- `public/` contém todas as páginas do site e o logo
- `public/solucoes/` contém as páginas de solução e de tema
- `wrangler.jsonc` diz ao Cloudflare onde estão os arquivos

## Como publicar uma alteração

Substituir o arquivo dentro de `public/` e confirmar a alteração (commit).
O Cloudflare republica sozinho em cerca de um minuto.

## Formulário de contato

O formulário da página `public/contato.html` usa o Formspree.
O endereço de envio está na linha que contém `formspree.io`.
