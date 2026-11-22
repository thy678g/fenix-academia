FÊNIX ACADEMIA — pacote de desenvolvimento.
Inclui interface PWA, cadastro e primeiro acesso, treinos, mensalidades, mensagens, orientações, notificações e avaliação física.
Avaliações: peso, altura, percentual de gordura, massa gorda, massa muscular e circunferências bilaterais; histórico com gráficos; edição e exclusão pela professora.
Não publicar ainda: faltam teste ponta a ponta, recuperação de senha, habilitar proteção contra senhas vazadas e revisar acessos.

Atualização desta revisão: a programação semanal agora inclui domingo (segunda a domingo), mantendo a estrutura existente do banco de dados.

Atenção: esta revisão ainda não deve ser publicada. Antes da liberação, testar login real, primeiro acesso, recuperação de senha, cadastro de aluno, upload de mídia, montagem e visualização de treinos, permissões por perfil e funcionamento em celular. Não compartilhar chaves secretas; a chave publishable presente no frontend é pública por projeto.

Atualização desta revisão: mensagens revisadas para validar conteúdo antes do envio, evitar cliques repetidos, marcar mensagens recebidas como lidas e gerar notificação ao aluno quando a professora responde. A criação da notificação depende das políticas RLS existentes e deve ser confirmada em teste com contas reais.

Atualização desta revisão: painel de mensagens da professora com indicador de mensagens não lidas por aluno, carregamento em estado de espera, tratamento de falhas ao carregar lista/conversa e atualização da conversa após resposta. Nenhuma alteração no banco de dados ou nas funções do servidor.

Revisão consolidada: orientações da professora agora validam título e conteúdo, evitam envios duplicados, diferenciam publicação de rascunho e permitem exclusão com tratamento de falhas. A área da aluna mostra estado de carregamento, data de publicação, conteúdo formatado e opção de tentar novamente quando houver erro. Cache PWA atualizado.

Limitação importante: esta é uma revisão do pacote frontend; não substitui testes de ponta a ponta com contas reais nem revisão de segurança das políticas RLS e das Edge Functions. Não publicar em produção antes dessas verificações.
