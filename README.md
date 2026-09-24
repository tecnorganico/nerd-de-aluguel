# nerd de aluguel — landing page

Landing page estática, mobile-first e acessível para apresentar os serviços do Nerd de Aluguel. O projeto foi criado para funcionar diretamente no GitHub Pages, sem servidor, banco de dados ou dependência de framework.

## arquivos

- `index.html`: página completa, com HTML semântico, CSS local e JavaScript mínimo.
- `suporte.html`: página completa de suporte remoto, alinhada visualmente à `index.html` e com downloads oficiais do RustDesk para Windows, macOS, Android e iOS.
- `assets/`: lugar reservado para imagens, áudios e vídeos autorizados. O site foi mantido sem logotipo nesta versão.
- `CNAME`: domínio personalizado planejado: `cuidadosdigitais.com.br`.

## contato

- E-mail: `ramires@cuidadosdigitais.com.br`
- WhatsApp: [+55 21 97722-9377](https://wa.me/5521977229377)

O site apresenta suporte tecnológico, aulas e orientação, organização digital e pequenos projetos para pessoas, profissionais autônomos, coletivos e negócios locais. Os valores exibidos são referências por faixa e o escopo final é combinado antes de cada atendimento.

Depoimentos, fotos, áudios e vídeos só devem ser publicados com autorização. A seção de depoimentos está temporariamente oculta e todo áudio ou vídeo futuro deve ter transcrição ou descrição equivalente. Não inserir senhas, códigos, documentos pessoais ou outros dados sensíveis.

## decisões de estilo

- **linguagem:** minúsculas predominantes, direta, acolhedora e concreta; a página fala com a pessoa e não usa jargão para criar distância.
- **paleta:** petróleo `#173b3f` para estrutura e legibilidade; creme `#fffaf0` e areia `#f2e7d5` para acolhimento; terracota `#c65d43` para ação; amarelo `#f3b544` para destaque; verde `#52745f` para apoio.
- **layout:** uma coluna no celular, grades fluidas em telas maiores, bastante espaço em branco e tabela com rolagem horizontal controlada.
- **conteúdo:** a jornada segue problema concreto → serviços → valores → processo → confiança → contato.
- **decisão de honestidade:** não há depoimentos, clientes ou resultados inventados. Placeholders indicam exatamente o que precisa ser substituído.
- **temas:** `index.html` alterna entre modo dia (`☀`), modo tarde (`🌇`) e modo noite (`☾`), com escolha restaurada pelo `localStorage`.
- **suporte:** `suporte.html` usa o mesmo sistema visual, tokens de cor, navegação, acessibilidade e comportamento mobile-first da página principal. A identificação automática do sistema apenas destaca o card recomendado e não esconde as outras opções.
- **depoimentos:** a seção de depoimentos permanece oculta até existirem materiais reais e autorização de uso.
- **dependências:** nenhuma dependência externa nova foi adicionada; o site continua sendo HTML, CSS e JavaScript locais, compatível com GitHub Pages.

## acessibilidade

A página usa idioma declarado, um único `h1`, títulos hierárquicos, landmarks semânticos, link para pular ao conteúdo, foco visível, contraste alto, navegação por teclado, `caption` e escopos na tabela, FAQ com `details`, áreas de toque confortáveis e suporte a `prefers-reduced-motion`. Áudio e vídeo futuros precisam de controles, transcrição e descrição.

O texto evita prometer autonomia completa ou resultados garantidos. O orçamento final depende do escopo confirmado, do tempo total, do deslocamento e de custos diretos aprovados.
