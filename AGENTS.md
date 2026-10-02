# AGENTS.md — Borborema Engenharia

## 1. Finalidade e escopo

Este arquivo orienta agentes de IA e colaboradores na criação e manutenção do site institucional da **Borborema Engenharia em WordPress**. Coloque-o na raiz do projeto para que as orientações sejam consideradas nas tarefas realizadas nesse diretório e em seus subdiretórios.

A fonte de requisitos é `Referencias_Sites_Borborema_Engenharia.md`; preserve seu conteúdo original. Este arquivo transforma o briefing em instruções executáveis, sem converter propostas em fatos aprovados.

Documentos de trabalho:
- `design/REFERENCIAS-E-BRIEFING.md`: observações das referências, evidências e cobertura de cada tópico.
- `design/DESIGN-SYSTEM.md`: sistema visual próprio, tokens propostos e regras de componentes.
- `wordpress/preparacao-online/LEIA-ME.md`: configuração observada do ambiente de homologação.

Leia os documentos pertinentes antes de alterar a interface. Em conflito, prevalecem as instruções atuais do usuário e os fatos confirmados sobre o briefing e as propostas de design. A versão anterior deste AGENTS.md foi preservada em `design/arquivo/`.

Atue como colaborador de desenvolvimento WordPress, design de interfaces e conteúdo institucional. Entregue soluções que a equipe consiga editar e manter pelo painel administrativo.

## 2. Objetivo do site

Apresentar a Borborema Engenharia com uma linguagem corporativa e sofisticada, orientada à construção e reforma de espaços comerciais, lojas, franquias e ambientes em shopping centers.

Prioridades, nesta ordem:

1. Comunicar com clareza o posicionamento e os serviços efetivamente prestados.
2. Demonstrar capacidade técnica por meio de obras reais e informações verificadas.
3. Gerar contatos comerciais pelo WhatsApp e formulário de orçamento.
4. Facilitar a solicitação de visita técnica, sujeita à disponibilidade da empresa.
5. Permitir a atualização de serviços, portfólio e contatos sem depender de alterações no código.

Público pretendido: responsáveis por lojas, marcas, franquias, empreendimentos comerciais e espaços em shopping centers.

## 3. Informações confirmadas e pendentes

Confirmado pelo briefing:

- Nome de apresentação: Borborema Engenharia.
- Plataforma definida pelo usuário: WordPress.
- Direção visual: corporativa, sofisticada e orientada a obras comerciais.
- Paleta de referência: azul institucional, branco e tons neutros.
- Foco de conteúdo: institucional, serviços, portfólio, clientes/parceiros e contato.
- Ambiente de homologação instalado: `https://borboremaeng.freepage.cc/`.
- Editor escolhido: Elementor gratuito; não pressupor Elementor Pro.
- Estado observado em 02/10/2026: WordPress 7.0.2, Elementor 4.3.3, tema Twenty Twenty-Five; plugins Borborema — Conteúdo e Borborema — Homologação ativos. Reinspecione antes de trabalhar no servidor, pois versões e estado podem mudar.
- `modelo-site/` é uma prévia local autorizada pelo usuário, em HTML/CSS/JavaScript. Ela é referência de apresentação para o WordPress, não sua substituição.

A confirmar antes de usar como informação definitiva:

- Logotipo oficial, códigos das cores e eventual manual de marca.
- História, anos de atuação, diferenciais, números e qualificações.
- Lista exata dos serviços prestados e abrangência geográfica.
- Obras, clientes, shopping centers, imagens e permissões de divulgação.
- Telefone, WhatsApp, e-mail, endereço, redes sociais e dados cadastrais.
- Domínio definitivo, hospedagem de produção, adequação do tema e eventuais licenças adicionais.
- Responsável por receber os contatos e destino dos formulários.

Não invente clientes, depoimentos, certificações, registros profissionais, prazos, garantias ou estatísticas. Use marcadores como `[WHATSAPP A CONFIRMAR]` apenas em rascunhos. Não publique conteúdo com esses marcadores.

## 4. Referências de linguagem e estrutura

As associações abaixo vêm do briefing. A pesquisa de 02/10/2026 está em `design/REFERENCIAS-E-BRIEFING.md`, com capturas em `design/referencias/`. Separe sempre intenção do briefing, observação real e decisão para a Borborema. Não descreva as referências como se fornecessem um design system oficial: a análise identifica padrões públicos e o sistema da Borborema é original.



### Cobertura fiel do briefing

Cada entrega deve relacionar os tópicos 1–6 do briefing à solução implementada ou à pendência concreta. Não omita um tópico silenciosamente para simplificar o layout.

- Objetivo da pesquisa: atender marcas, lojas, franquias e operações comerciais com posicionamento claro e contato fácil.
- Referências: justificar a contribuição de cada uma das seis referências; registrar falhas de acesso e limites da análise visual.
- Estrutura: contemplar início, institucional, serviços, portfólio, clientes/parceiros e contato.
- Serviços propostos no briefing: execução de obras, reformas, projetos complementares, instalações e gerenciamento. Os cinco devem aparecer na preparação como propostas explícitas; a publicação depende da confirmação de cada serviço.
- Portfólio: prever foto principal, projeto/cliente, empreendimento, localização, segmento, escopo, galeria e desafios/soluções. Não deduzir escopo, conclusão, área ou prazo por uma fotografia.
- Posicionamento: usar no rascunho “Sua obra comercial, do projeto à entrega.” e o texto de apoio sugerido. Ajustar só quando o escopo real ou uma instrução do usuário justificar.
- Direção visual: azul, branco, neutros, fotos próprias, tipografia limpa, títulos fortes, CTAs de orçamento e WhatsApp e organização do portfólio.

A fidelidade ao briefing exige distinguir conteúdo proposto e confirmado. Na prévia, reservar a seção de clientes/parceiros com indicação de validação; não preencher com marcas da concorrência ou fingir autorização. Em produção, mostrar a seção somente com dados e permissões aprovados.

## 5. Estrutura de páginas

Adote a estrutura abaixo como ponto de partida. Ajustes podem ser feitos conforme o conteúdo real disponível.

| Página | Caminho sugerido | Conteúdo principal |
| --- | --- | --- |
| Início | `/` | Posicionamento, serviços em resumo, obras em destaque e chamadas para contato. |
| A Borborema | `/a-borborema/` | História, experiência, área de atuação e diferenciais comprovados. |
| Serviços | `/servicos/` | Serviços confirmados, escopo e orientação para orçamento. |
| Obras | `/obras/` | Portfólio com imagens reais e informações objetivas. |
| Detalhe de obra | `/obras/nome-da-obra/` | Ficha, galeria, escopo, desafios e soluções documentados. |
| Contato | `/contato/` | WhatsApp, formulário e solicitação de visita técnica. |
| Política de privacidade | `/politica-de-privacidade/` | Texto validado e compatível com o tratamento real de dados do site. |

Clientes e parceiros podem aparecer como seção na página inicial ou institucional. Crie página própria apenas se houver conteúdo suficiente. Não inclua blog, área de cliente ou funcionalidades adicionais sem necessidade definida.

### Página inicial

Ordem inicial sugerida:

1. Cabeçalho com logotipo, navegação enxuta e botão “Solicitar orçamento”.
2. Abertura com foto real de obra concluída, título claro e chamada principal.
3. Apresentação breve da empresa.
4. Resumo dos serviços confirmados.
5. Obras em destaque com acesso aos detalhes.
6. Processo de trabalho, se validado pela equipe.
7. Clientes e parceiros autorizados.
8. Chamada final para orçamento ou solicitação de visita técnica.
9. Rodapé com contatos, navegação e política de privacidade.

O briefing sugere o título **“Sua obra comercial, do projeto à entrega.”** e o apoio **“Execução e gerenciamento de obras comerciais com experiência em lojas, franquias e espaços em shopping centers.”** Trate-os como propostas: valide a experiência e a abrangência do serviço antes de publicar.

## 6. Direção visual e experiência

- Use o azul oficial da Borborema como cor principal. Enquanto o código não for fornecido, identifique qualquer azul usado no protótipo como provisório.
- Combine branco e neutros para dar destaque às fotografias e à informação técnica.
- Trabalhe com tipografia limpa, títulos fortes, parágrafos curtos e espaçamento consistente.
- Defina estilos globais para cores, tipografia, botões, cartões, largura de conteúdo e espaçamentos.
- Priorize fotografias reais, com boa iluminação e enquadramento. Não apresente imagens de banco ou geradas como obras executadas pela empresa.
- Mantenha uma chamada principal por seção e contraste suficiente para leitura.
- Evite carrosséis automáticos, excesso de animações, vídeos pesados na abertura e elementos decorativos que disputem atenção com as obras.
- Projete primeiro para telas pequenas e refine para tablet e desktop.
- Garanta que menus, botões flutuantes e avisos não cubram conteúdo ou campos de formulário.
- Não use dimensões fixas que provoquem corte de texto ou rolagem horizontal.

### Sistema visual próprio

Use `design/DESIGN-SYSTEM.md` como contrato visual do modelo. Os tokens são uma proposta para revisão e não um manual de marca oficial.

- Centralize cores, tipografia, espaçamento, largura de conteúdo, bordas e estados em variáveis `--be-*`; não espalhe valores concorrentes.
- Use títulos sem serifa com peso forte, fotografias amplas e composição alinhada a uma grade. Evite misturar famílias e estilos sem uma função definida.
- Use azul profundo, branco e neutros como base. Restrinja a cor de acento a detalhes funcionais; preserve contraste em textos, controles e estados.
- Componentes mínimos: cabeçalho/menu móvel, botão primário e secundário, abertura fotográfica, serviço, cartão de obra, ficha/galeria, etapas de processo, clientes/parceiros, formulário e rodapé.
- Defina estados normal, hover, foco, aberto, inválido, desativado e demonstração onde pertinentes. Diferencie visualmente CTAs de contato ainda indisponíveis.
- Use os padrões das referências como princípios: clareza de especialidade, prova fotográfica, ficha objetiva, processo legível e caminho curto até contato. Não reutilize sua identidade ou reproduza literalmente seu layout.
- Mantenha fotos e marca existentes em `modelo-site/`; imagens geradas podem explorar layout, mas nunca comprovar uma obra da empresa.

## 7. Arquitetura WordPress

### Antes de implementar

Inspecione a estrutura existente e identifique tema ativo, editor, plugins, versões e ambiente de execução. Preserve as convenções e funcionalidades já presentes. Não invente comandos de instalação, build ou teste: consulte os arquivos e ferramentas realmente disponíveis.

WordPress é a plataforma deste projeto. Não substitua a implementação por uma aplicação independente em React, Next.js ou outro framework sem uma solicitação explícita.

### Editor e tema

- Reutilize o editor já adotado no projeto.
- Se houver Elementor, use estilos globais, estruturas reutilizáveis e recursos disponíveis na versão instalada. Não pressuponha licença Pro.
- Se houver editor de blocos, use blocos, padrões e templates coerentes com o tema ativo.
- Se ainda não houver editor definido, proponha uma opção adequada à edição pela equipe e confirme essa escolha antes de criar estruturas que dependam dela.
- Nunca altere arquivos do núcleo do WordPress, de plugins de terceiros ou do tema pai.
- Para customizações de apresentação que exijam código, utilize um tema filho quando apropriado à arquitetura existente.
- Mantenha funcionalidades de conteúdo independentes do tema, preferencialmente em plugin específico do projeto quando houver desenvolvimento personalizado.
- Evite instalar plugins com funções duplicadas. Não presuma compra de licenças nem adicione dependências sem necessidade.

### Conteúdo e portfólio

Mantenha textos, imagens, serviços e contatos editáveis pelo painel. Para um portfólio com atualização recorrente, prefira um tipo de conteúdo “Obras” com template único de listagem e detalhe. Reutilize uma estrutura existente se ela já atender à necessidade.

Campos previstos para cada obra:

- Nome do projeto ou cliente autorizado.
- Foto principal.
- Shopping ou empreendimento, quando aplicável e autorizado.
- Cidade e estado.
- Segmento e tipo de serviço.
- Escopo executado.
- Galeria do processo e do resultado final.
- Desafios e soluções, quando documentados.
- Ano, área e prazo somente quando fornecidos e aprovados.

Não exiba rótulos vazios no site. Use filtros por segmento, shopping ou serviço apenas quando houver volume e diversidade suficientes; uma mesma obra pode ter mais de um serviço. Não crie cadastros duplicados para alimentar filtros.

### Código personalizado

- Use HTML semântico, CSS organizado e JavaScript apenas quando necessário.
- Prefixe funções, classes CSS e identificadores próprios para reduzir conflitos, por exemplo `borborema_` no PHP e `be-` no CSS.
- Carregue scripts e estilos pelos mecanismos do WordPress quando trabalhar em arquivos de tema ou plugin.
- Evite CSS global que altere widgets e componentes não relacionados à tarefa.
- Ao criar processamento PHP, valide e sanitize entradas, escape saídas, verifique permissões e use nonces onde aplicável. Nonces não substituem autorização.
- Nunca grave senhas, tokens ou credenciais em código, documentação ou repositório.

## 8. Conteúdo e conversão

Escreva em português do Brasil, com tom profissional, direto e seguro. Explique o serviço e o benefício concreto para quem precisa executar uma obra comercial.

Evite expressões como “a melhor”, “líder”, “excelência comprovada” e “entrega garantida” sem evidências. Não prometa execução de projetos, aprovações ou responsabilidade técnica fora do escopo confirmado da empresa.

Chamadas sugeridas:

- “Solicitar orçamento”.
- “Falar pelo WhatsApp”.
- “Conhecer nossas obras”.
- “Solicitar visita técnica”.

O envio de um formulário não confirma orçamento, prazo ou agendamento. Mostre uma mensagem de recebimento apenas após a confirmação de sucesso do processamento.

### Contato

- Use somente o número de WhatsApp validado, em formato internacional no link.
- Permita mensagem inicial curta, sem dados sensíveis predefinidos.
- No formulário, solicite nome, ao menos um meio de retorno e breve descrição da necessidade. Empresa, cidade e serviço podem ser campos adicionais quando úteis.
- Evite coleta desnecessária de documentos e arquivos no primeiro contato.
- Inclua rótulos visíveis, validação compreensível, estados de envio, sucesso e erro.
- Configure proteção contra spam compatível com o ambiente e com a acessibilidade.
- Verifique o recebimento no destino configurado. Um aviso visual de sucesso não comprova a entrega do e-mail.
- Relacione o formulário à política de privacidade. Não ative inscrição em marketing automaticamente.

## 9. Qualidade técnica

### Acessibilidade

- Organize títulos de forma lógica, com um título principal claro por página.
- Garanta navegação por teclado, foco visível e nomes acessíveis para controles.
- Use texto alternativo contextual nas fotos informativas e alternativa vazia nas imagens puramente decorativas.
- Não dependa apenas de cor, movimento ou passagem do mouse para transmitir informação.
- Respeite preferências de redução de movimento e mantenha texto legível em telas pequenas.

### Desempenho

- Redimensione e comprima fotografias para o tamanho de exibição, usando formatos modernos quando compatíveis.
- Evite carregar a imagem principal com atraso desnecessário; aplique carregamento tardio às imagens fora da primeira tela quando adequado.
- Defina dimensões das imagens para reduzir deslocamentos de layout.
- Reduza variações de fontes, scripts e extensões desnecessárias.
- Avalie cache e otimização conforme a hospedagem e os plugins existentes, sem sobrepor ferramentas equivalentes.

### Busca e compartilhamento

- Defina títulos e descrições específicos, URLs legíveis e links internos úteis.
- Use apenas a solução de SEO já escolhida; evite plugins concorrentes para a mesma função.
- Configure imagem e texto de compartilhamento com dados aprovados.
- Use dados estruturados apenas quando correspondam ao conteúdo real.
- Mantenha homologação fora dos mecanismos de busca e confira a configuração de indexação ao publicar.

### Privacidade e manutenção

- A política de privacidade deve refletir formulários, integrações e coleta efetivamente existentes; não declare conformidade jurídica automática.
- Não adicione rastreamento ou cookies não essenciais por padrão. Defina previamente a necessidade e a configuração de consentimento aplicável.
- Preserve cópias de segurança antes de operações com risco de perda de dados.
- Verifique compatibilidade antes de atualizar tema, plugins ou WordPress.

## 10. Forma de trabalhar

1. Leia o briefing, este arquivo e instruções locais aplicáveis.
2. Identifique o estado atual do projeto e os dados disponíveis.
3. Informe brevemente o que será entregue e registre suposições relevantes.
4. Execute a tarefa solicitada em etapas pequenas e verificáveis, preservando alterações alheias.
5. Use conteúdo provisório claramente identificado apenas na preparação.
6. Verifique o resultado de acordo com o alcance da mudança.
7. Entregue um resumo do que mudou, como foi verificado e quais pendências permanecem.

Não interrompa o trabalho por decisões rotineiras de espaçamento, organização ou implementação reversível. Pergunte quando faltar uma definição que altere substancialmente a arquitetura, um dado real indispensável ou autorização para uma ação fora do escopo.

Quando a tarefa depender de ação manual no painel, forneça instruções compatíveis com o editor e a versão observados. Ao entregar código para inserção manual, indique arquivo ou área de destino, dependências e forma de verificar o resultado. Não afirme ter alterado o WordPress se apenas produziu um trecho de código.

### Preservação e limites da entrega

Antes de refazer o modelo local, preserve seus arquivos atuais em um arquivo de revisão datado. Atualize HTML, CSS, JavaScript, documentação e mapeamento de ativos de forma coerente. Pacotes WordPress não sincronizam automaticamente com o HTML: registre quando o importador ainda representar uma versão anterior.

Não publique o redesign, importe imagens para serviço externo, altere tema ou remova as proteções de homologação apenas porque a prévia local foi aprovada. Execute no WordPress somente o escopo autorizado. A criação de uma conta de colaborador foi adiada pelo usuário; não retome sem novo pedido.

## 11. Verificação e critérios de entrega

Aplique os itens pertinentes à mudança. Antes de concluir o site, verifique:

- [ ] Cada tópico do briefing mapeado a implementação ou pendência explícita.
- [ ] Evidências das referências separadas das propostas para a Borborema.
- [ ] Tokens e componentes consistentes entre telas pequenas, médias e grandes.
- [ ] Identidade visual consistente e cores oficiais confirmadas.
- [ ] Conteúdo institucional e serviços validados pela Borborema.
- [ ] Nenhum dado inventado, marcador provisório ou demonstração apresentado como conteúdo real.
- [ ] Uso autorizado de fotos, marcas e logotipos.
- [ ] Navegação e páginas funcionando em celular, tablet e desktop.
- [ ] Portfólio editável, com listagem e detalhes coerentes.
- [ ] Links de orçamento, WhatsApp e contato apontando para destinos corretos.
- [ ] Formulário validado, com tratamento de falhas e recebimento verificado.
- [ ] Acesso por teclado, foco, rótulos e contraste revisados.
- [ ] Imagens otimizadas e ausência de rolagem horizontal indevida.
- [ ] Ausência de erros relevantes de navegador e PHP nas alterações implementadas.
- [ ] Metadados, compartilhamento, indexação e privacidade revisados.
- [ ] Edição dos principais conteúdos possível pelo painel administrativo.

Registre verificações não realizadas e o motivo. Não declare um teste bem-sucedido sem executá-lo. O pedido de preparar arquivos ou um protótipo não autoriza, por si só, publicar em produção; publique quando isso fizer parte do escopo autorizado e após validar o conteúdo necessário.

## 12. Estado do Modelo 02 (02/10/2026)

- A prévia atual em `modelo-site/` implementa o sistema de `design/DESIGN-SYSTEM.md`.
- A correspondência entre briefing, referências e seções está em `design/REFERENCIAS-E-BRIEFING.md`.
- Versão anterior arquivada em `design/arquivo/modelo-antes-da-revisao-2026-10-02.zip`.
- Fotos originais preservadas; derivados WebP e dimensões em `modelo-site/assets-otimizados.json`.
- O formulário é demonstrativo; não envia nem armazena. WhatsApp inativo até validação.
- Informações provisórias não autorizam publicação. Não tratar o pacote Elementor anterior como sincronizado com o Modelo 02.
- Resultado dos testes e limites em `design/VERIFICACAO-MODELO-02.md`.
