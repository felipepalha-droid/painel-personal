# Painel do Personal

Página onde o personal monta o treino do aluno e envia direto para o app Caderno de Treino.
Os dados ficam no Supabase do Felipe (tabelas `vinculos`, `planos`, `treinos_feitos`, protegidas por RLS).
A chave no `index.html` é a publicável do Supabase, feita para ficar no navegador.
