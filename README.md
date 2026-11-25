# Estoque 360 · BYD — publicação

Site público de revisão: https://lucasvdlk10.github.io/estoque360-byd/

Este repositório contém somente o artefato estático gerado do frontend. O código-fonte, fixtures de demonstração, imagens locais e migrations permanecem fora deste repositório. `site/` é publicado pelo workflow do GitHub Pages a cada push em `main`.

A versão usa Supabase Auth com chave publishable de navegador; não contém service-role nem segredo privilegiado. Acesso aos dados depende de conta Supabase ativa e RLS. O login está disponível, mas a validação autenticada/persistência ponta a ponta e a configuração final de redirects ainda não equivalem a aceite operacional.

Para atualizar, substitua `site/` por uma nova build `supabase` validada com base `/estoque360-byd/` e envie o commit para `main`. Não adicione `.env.local`, imagens, seeds de demonstração ou credenciais privilegiadas.
