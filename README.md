# nerd de aluguel — landing page

Landing page estática, mobile-first e acessível para apresentar os serviços do Nerd de Aluguel. O projeto foi criado para funcionar diretamente no GitHub Pages, sem servidor, banco de dados ou dependência de framework.

## arquivos

- `index.html`: página completa, com HTML semântico, CSS local e JavaScript mínimo.
- `assets/`: lugar reservado para imagens, áudios e vídeos autorizados. O site foi mantido sem logotipo nesta versão.
- `CNAME`: domínio personalizado planejado: `cuidadosdigitais.com.br`.

## executar localmente

Abra `index.html` no navegador. Para uma prévia mais próxima do GitHub Pages, rode um servidor estático simples a partir desta pasta, por exemplo `python3 -m http.server 8000`, e acesse `http://localhost:8000`.

## publicar no GitHub Pages

1. Crie um repositório público ou privado no GitHub.
2. Copie estes arquivos para a raiz do repositório.
3. Faça um commit e envie para a branch principal.
4. Em **Settings → Pages**, escolha a branch principal e a pasta `/ (root)`.
5. Antes de divulgar, substitua os contatos provisórios e faça uma visita completa pelo celular.

## conteúdo que precisa ser preenchido

Antes da publicação, revisar o e-mail, o WhatsApp, a identidade visual definitiva, área de atendimento, formas de pagamento, política de privacidade e os valores. Os preços presentes são a referência documentada em `56 CLIENTES/NERD DE ALUGUEL/TABELA_PRECOS.md`, ainda sujeitos a confirmação de Ramires.

Depoimentos, fotos, áudios e vídeos devem ser adicionados somente após autorização. A seção de depoimentos está temporariamente oculta com o atributo `hidden` no HTML; para reativá-la, remova esse atributo e recrie o link de navegação quando os materiais estiverem prontos. Para cada áudio ou vídeo, incluir transcrição ou descrição equivalente. Não inserir senhas, códigos, documentos pessoais ou outros dados sensíveis.

## decisões de estilo

- **linguagem:** minúsculas predominantes, direta, acolhedora e concreta; a página fala com a pessoa e não usa jargão para criar distância.
- **paleta:** petróleo `#173b3f` para estrutura e legibilidade; creme `#fffaf0` e areia `#f2e7d5` para acolhimento; terracota `#c65d43` para ação; amarelo `#f3b544` para destaque; verde `#52745f` para apoio.
- **layout:** uma coluna no celular, grades fluidas em telas maiores, bastante espaço em branco e tabela com rolagem horizontal controlada.
- **conteúdo:** a jornada segue problema concreto → serviços → valores → processo → confiança → contato.
- **decisão de honestidade:** não há depoimentos, clientes ou resultados inventados. Placeholders indicam exatamente o que precisa ser substituído.

## acessibilidade

A página usa idioma declarado, um único `h1`, títulos hierárquicos, landmarks semânticos, link para pular ao conteúdo, foco visível, contraste alto, navegação por teclado, `caption` e escopos na tabela, FAQ com `details`, áreas de toque confortáveis e suporte a `prefers-reduced-motion`. Áudio e vídeo futuros precisam de controles, transcrição e descrição.

O texto evita prometer autonomia completa ou resultados garantidos. O orçamento final depende do escopo confirmado, do tempo total, do deslocamento e de custos diretos aprovados.

## revisão antes de publicar

- [x] substituir o e-mail pelo contato profissional confirmado: `ramires@cuidadosdigitais.com.br`;
- [ ] adicionar WhatsApp somente quando houver um número público confirmado;
- [ ] confirmar preços, faixas e área de atendimento;
- [ ] adicionar logo somente se houver arquivo autorizado;
- [ ] revisar todos os textos com a voz atual do Nerd de Aluguel;
- [ ] testar zoom, teclado, leitor de tela e celular;
- [ ] confirmar links e ausência de erros no console;
- [ ] adicionar somente depoimentos autorizados, com transcrição quando necessário.
