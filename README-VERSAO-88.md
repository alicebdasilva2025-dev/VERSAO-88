# LiDire — Versão 88

Base: versão 87.

## Alterações
- O nome do remetente e a data/hora aparecem em linhas separadas nas notificações LD.
- Data e hora exibidas no formato brasileiro (`dd/mm/aaaa às HH:mm:ss`).
- A tela inicial exibe somente notificações não lidas; notificações lidas continuam disponíveis na área LD/Família.
- O título “Notificações da família” foi substituído por “LD”.

## Segurança e compatibilidade
- Não foram adicionadas migrações nem alterado o esquema do banco D1.
- A exclusão e as respostas implementadas na versão 87 foram preservadas.
- Esta versão precisa ser validada em Worker de teste; não foi publicada nem testada contra o banco D1 de produção.
