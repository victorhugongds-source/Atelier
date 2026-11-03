# Atelier — Organizador com Supabase

## Instalação rápida
1. Extraia o ZIP e abra a pasta `atelier-supabase` no VS Code.
2. No Supabase, abra SQL Editor, crie uma consulta, copie `supabase/schema.sql` inteiro e clique em Run.
3. Em Project Settings > API Keys, copie Project URL e Publishable key.
4. Cole os valores em `js/config.js`. Use somente a Publishable key. Nunca use Secret key/service_role no navegador.
5. Abra `index.html` com a extensão Live Server.

## Recursos
- Cadastro/login por e-mail e senha.
- Contas independentes: cada pessoa vê apenas seus próprios dados.
- Matérias, anotações e tarefas com status e prazos.
- Upload, abertura e exclusão de arquivos.
- Pastas para organização.
- Painel com contagem e progresso de tarefas.
- Arquivos em bucket privado, limite de 20 MB.

## Importante
Se a confirmação de e-mail estiver ativa no Supabase, confirme o endereço recebido antes do primeiro login. Configure a URL local em Authentication > URL Configuration.
Este projeto usa HTML, CSS e JavaScript com a biblioteca Supabase carregada por CDN. Não publique a Secret key nem desative RLS.
