# Documento Reflexivo - Projeto Landing Page

## Desafios Enfrentados

Durante o processo de estilização e implementação das funcionalidades, alguns desafios foram encontrados:
* **Responsividade Detalhada:** Garantir que o layout se adaptasse perfeitamente a diferentes tamanhos de tela, especialmente em dispositivos móveis com variações de largura, exigiu ajustes finos nas Media Queries. A ordem de alguns elementos (como a imagem na seção de vagas) precisou ser alterada para melhor visualização em telas menores.
* **Menu Mobile Funcional:** Implementar um menu mobile que fosse tanto funcional (abrir e fechar) quanto visualmente integrado ao design exigiu a combinação de CSS para a apresentação e JavaScript para a interatividade do botão de alternância e o comportamento após o clique em um link interno.
* **Rolagem Suave com Offset (Potencial)**: Embora a implementação básica da rolagem suave seja simples deu muitos erros durante o desenvolvimento da aplicação.
* **Validação de Formulário Simples**: A validação implementada para o e-mail é básica (verificar se o campo está preenchido).
* **Animações Sutis:** A escolha de animações simples (hover no botão, fade-in) buscou melhorar a experiência sem sobrecarregar visualmente. O desafio é encontrar o equilíbrio certo entre adicionar interesse visual e manter a usabilidade e o desempenho.
* **Alinhamento das "sections"** o texto junto com as imagens parecia impossivel.

## Recursos Consultados

Para auxiliar no desenvolvimento deste projeto, foram consultados diversos recursos:
* **Documentação MDN Web Docs (Mozilla Developer Network):** Uma fonte essencial para entender as especificações e o uso correto de HTML, CSS e JavaScript. Consultada para relembrar propriedades CSS específicas (como `display: flex`, `grid`, `position`, `transition`, `transform`, `@keyframes`, `scroll-behavior`), seletores CSS e a manipulação do DOM em JavaScript (como `getElementById`, `querySelector`, `classList`, `scrollIntoView`, `addEventListener`).
* **W3Schools:** Utilizado como uma referência rápida e prática para sintaxe e exemplos de HTML, CSS e JavaScript.
* **Stack Overflow:** Para solucionar dúvidas específicas e encontrar soluções para problemas de layout e comportamento inesperados do CSS ou JavaScript. Pesquisas por termos relacionados à responsividade, menus mobile, rolagem suave e validação de formulários foram realizadas.
* **Artigos e Tutoriais Online:** Blogs e sites especializados em desenvolvimento web foram consultados para obter ideias de design, melhores práticas de responsividade, técnicas de animação CSS e tutoriais no YouTube.
* **Ferramentas de Desenvolvedor do Navegador:** As ferramentas de inspeção de elementos (Inspect Element) dos navegadores Chrome e Firefox foram cruciais para testar e ajustar o CSS em tempo real, visualizar o layout em diferentes tamanhos de tela e depurar o JavaScript.
* **Exemplos de Landing Pages:** A análise de diversas landing pages existentes serviu como inspiração para o layout, a organização do conteúdo e os elementos interativos utilizados.

## Justificativas das Escolhas de Layout e Interatividade

As escolhas de layout e interatividade:
O layout foi estruturado para guiar o olhar do usuário através das informações mais importantes, o cabeçalho apresenta a identidade da marca e a navegação principal, as seções subsequentes apresentam os diferenciais, métricas, oportunidades e depoimentos de forma sequencial e com títulos e subtítulos claros.
* **Responsividade:** A prioridade foi garantir que a página fosse acessível e visualmente agradável em diversos dispositivos. O uso de flexbox e media queries permitiu adaptar o layout para telas menores, reorganizando elementos quando necessário para otimizar a visualização em dispositivos móveis. O menu mobile foi implementado para substituir a navegação tradicional em telas menores, oferecendo uma experiência de usuário otimizada para toque.
* **Navegação:** A navegação principal no cabeçalho visa direcionar os usuários para as diferentes seções do site. A implementação da rolagem suave para links internos (embora necessite de IDs nas seções para funcionar plenamente) busca tornar a navegação mais fluida e agradável, proporcionando uma transição suave entre as seções ao invés de um salto abrupto.
* **Interatividade:** As interações implementadas (menu mobile, hover no botão) foram escolhidas para fornecer feedback visual ao usuário e melhorar a usabilidade sem serem intrusivas. O hover no botão indica que ele é clicável, e o menu mobile facilita a navegação em telas menores.
* **Foco na Informação Relevante:** O layout buscou apresentar as informações de forma concisa e direta, destacando os pontos chave sobre a empresa e as oportunidades de carreira. O uso de seções distintas ajuda a organizar o conteúdo e facilita a leitura.
* **Design:** A paleta de cores (branco, cinzas e a cor primária em destaque).
* **Feedback ao Usuário:** A validação básica do formulário de e-mail, mesmo que simples, fornece um feedback imediato ao usuário caso ele tente cadastrar sem preencher o campo. O alerta de boas-vindas após o clique no botão também serve como um feedback da ação.
