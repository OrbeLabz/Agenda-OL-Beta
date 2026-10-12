# Agenda OL Beta — OrbeLabz

Interface beta de gestão de serviços, recuperada da versão Agenda-OL escolhida por John. Preserva as telas Agenda, Cobranças, Comandas, Mensagens, Clientes, Serviços, Estoque, Despesas, Equipe, Performance, Financeiro, Fidelidade e Configurações.

## Estado
Demonstração frontend em HTML/CSS/JavaScript. Dados fictícios iniciais e persistência em localStorage específica deste beta. Sem servidor de aplicação, login seguro, sincronização entre dispositivos, WhatsApp real ou processamento de pagamentos. Algumas telas e controles são demonstrativos. A troca gestor/cliente é visual e não autenticação. Não inserir dados pessoais sensíveis.

## Publicação
Repositório pretendido: OrbeLabz/Agenda-OL-Beta. Em Settings > Pages, selecionar GitHub Actions. O workflow publica a raiz em GitHub Pages após push em main. Endereço pretendido: https://orbelabz.com/Agenda-OL-Beta/ (a confirmar após publicação). Não adicionar CNAME: o domínio pertence ao site institucional.

## Desenvolvimento
Editar index.html, styles.css e app.js, revisar alterações e publicar commits em main. Referências de pesquisa/capturas/vídeos não foram incluídas no site público. Código original preservado no segundo cérebro; este pacote representa nova versão beta, não copia dados do navegador anterior.

## Mudanças desta preparação
Identificação Beta/OrbeLabz, retorno ao site institucional, chave de armazenamento isolada, carregamento tolerante a JSON inválido, data local atual para a agenda e agendamentos fictícios remapeados para hoje/amanhã.

## Próximas etapas
Validar cada fluxo com John, persistência das configurações, autenticação, backend, permissões, backup e integrações; importar conversa original de criação.

## Acesso ao serviço beta
Após a publicação concluir, abra https://orbelabz.com/Agenda-OL-Beta/ . O status da publicação aparece na aba Actions deste repositório.
