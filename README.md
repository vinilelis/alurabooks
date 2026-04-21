# Alura Books
https://vinilelis.github.io/alurabooks/
## Sobre o projeto

Este projeto consiste em um site responsivo da **Alura Books**, desenvolvido para apresentar livros, categorias e conteúdos ligados ao universo da tecnologia e da educação digital. A proposta da página é simular uma vitrine online de livros e materiais de estudo, com foco em áreas como:

- Programação
- Front-end
- Back-end
- Infraestrutura
- UX e Design
- Business e carreira

O objetivo principal do projeto foi praticar a construção de uma interface moderna, organizada e adaptável a diferentes tamanhos de tela, aplicando conceitos de **HTML**, **CSS** e **responsividade**.

## Objetivo do desenvolvimento

Durante a construção do projeto, a prioridade foi desenvolver uma experiência agradável para quem acessa o site em qualquer dispositivo. Por isso, a estrutura foi pensada para funcionar primeiro em telas menores e depois evoluir para telas maiores.

O projeto foi desenvolvido com a abordagem **mobile first**, ou seja:

1. Primeiro foi criada a versão para celulares.
2. Depois foram adicionadas adaptações para tablets.
3. Por fim, a interface foi refinada para desktops e telas maiores.

Essa estratégia ajuda a manter o layout mais organizado, melhora a legibilidade do código e facilita a escalabilidade da interface.

## Estrutura do projeto

O projeto está dividido em um arquivo principal HTML e vários arquivos CSS separados por responsabilidade visual:

- `index.html`: estrutura principal da página.
- `style.css`: arquivo central que importa os estilos das seções.
- `styles/header.css`: estilos do cabeçalho e navegação.
- `styles/banner.css`: estilos do banner principal e campo de busca.
- `styles/carrossel.css`: estilos dos carrosséis e cartões de destaque.
- `styles/topicos.css`: estilos da área de tópicos visitados.
- `styles/contato.css`: estilos da seção de contato e newsletter.
- `styles/rodape.css`: estilos do rodapé.
- `reset.css`: redefinição de estilos padrão do navegador.
- `assents/`: pasta com ícones, logos e imagens dos livros.

Essa separação foi importante para manter o projeto mais limpo, facilitando a manutenção e a identificação de cada parte da interface.

## Conteúdo apresentado no site

O site foi estruturado com várias áreas visuais que simulam uma página inicial de catálogo digital:

### Cabeçalho

O cabeçalho reúne navegação, menu de categorias, logo, favoritos, sacola e acesso ao perfil. Em telas menores, a navegação aparece por meio de um menu hambúrguer. Em telas maiores, os links ficam visíveis de forma mais completa.

### Banner principal

Logo abaixo do cabeçalho, o banner apresenta uma mensagem de boas-vindas e um campo de pesquisa para incentivar o usuário a procurar sua próxima leitura.

### Carrosséis de livros

O projeto possui seções com livros em destaque, como:

- Novos lançamentos
- Mais vendidos

Esses blocos ajudam a destacar conteúdos de forma mais dinâmica e visual.

### Cards de destaque

Além dos carrosséis, também foram incluídos cartões com informações complementares, como indicação de livro e autora do mês.

### Tópicos visitados recentemente

Essa seção mostra tags relacionadas a temas populares de estudo, como HTML, CSS, Python, Java, Marketing Digital, Agile e Startups.

### Área de contato

A seção de contato foi criada para simular um espaço de cadastro de e-mail, permitindo que o usuário receba novidades, promoções e atualizações sobre novos conteúdos.

### Rodapé

O rodapé apresenta links institucionais e educacionais relacionados ao ecossistema Alura, organizados em colunas para facilitar a navegação em telas maiores.

## Processo de responsividade

O ponto central do projeto foi a construção de uma interface responsiva. A seguir está o detalhamento de como esse processo foi pensado e aplicado.

## Etapa 1: desenvolvimento com Mobile First

O desenvolvimento começou pela versão mobile, considerando que telas menores exigem mais organização, objetividade e clareza visual.

Nesta fase, foram realizados os seguintes passos:

### 1. Estrutura base da página

Foi montada a estrutura principal em HTML com todas as seções do site:

- Cabeçalho
- Banner
- Carrosséis
- Tópicos
- Contato
- Rodapé

Essa base permitiu organizar o conteúdo antes dos ajustes para telas maiores.

### 2. Definição das variáveis globais

No arquivo `style.css`, foram definidas variáveis CSS para:

- Cores principais
- Gradientes
- Fontes
- Tons auxiliares

Isso ajudou a manter consistência visual em todo o projeto.

### 3. Layout adaptado para celular

Na versão inicial para mobile, a interface foi construída com foco em simplicidade:

- Cabeçalho compacto
- Menu hambúrguer para economizar espaço
- Campo de busca ocupando praticamente toda a largura
- Carrosséis com imagens ajustadas ao tamanho da tela
- Cards com espaçamento reduzido e leitura confortável
- Seções empilhadas verticalmente

Essa decisão garantiu boa usabilidade em smartphones.

### 4. Navegação simplificada

No mobile, parte dos elementos de navegação foi ocultada para evitar poluição visual. O menu hambúrguer ficou responsável por abrir e fechar a lista de categorias.

### 5. Rodapé enxuto

Na versão de celular, o rodapé ficou mais simples, mostrando apenas o essencial. As listas completas de links foram escondidas nessa etapa para preservar espaço e legibilidade.

## Etapa 2: adaptação para tablets

Depois da base mobile pronta, foram adicionadas media queries para melhorar a experiência em telas médias, especialmente a partir de `1024px`.

Nessa fase, o projeto passou por uma expansão visual importante.

### 1. Cabeçalho mais completo

Em telas maiores:

- O menu hambúrguer foi ocultado
- O título da marca passou a aparecer
- As opções de navegação ficaram visíveis
- O menu de categorias ganhou comportamento mais adequado ao espaço disponível

Isso deixou a navegação mais clara e mais próxima de uma experiência de loja virtual completa.

### 2. Banner ampliado

No tablet:

- O título do banner ganhou mais destaque
- O campo de busca teve sua largura reduzida para melhor equilíbrio visual
- O conteúdo ficou mais proporcional ao centro da tela

### 3. Melhoria nos carrosséis

Nos carrosséis:

- O título aumentou de tamanho
- As setas de navegação passaram a aparecer
- O componente `swiper` recebeu largura controlada
- Os cards passaram a ocupar uma área central mais equilibrada

Essas mudanças trouxeram mais conforto visual e melhor aproveitamento do espaço.

### 4. Ajustes nas seções de tópicos e contato

As áreas de tópicos e contato também receberam melhorias:

- Fontes maiores
- Melhor distribuição dos elementos
- Organização mais agradável em linha

Na seção de contato, por exemplo, o texto e o campo de e-mail passaram a ficar alinhados lado a lado.

### 5. Rodapé expandido

No tablet, o rodapé deixou de ser compacto e passou a exibir:

- Título principal
- Colunas com links
- Melhor distribuição horizontal dos conteúdos

Isso tornou a página mais rica e mais completa em telas intermediárias.

## Etapa 3: refinamento para desktop

Na etapa final, foram aplicados ajustes para telas grandes, especialmente a partir de `1728px`, aproveitando melhor áreas amplas e trazendo mais sofisticação ao layout.

### 1. Cabeçalho com mais informação

No desktop:

- Os links com ícones passaram a mostrar texto
- A navegação ganhou melhor espaçamento
- O cabeçalho recebeu padding lateral
- O menu ficou mais confortável para leitura e interação

### 2. Banner mais equilibrado em telas largas

O banner foi ajustado para:

- Ter mais respiro vertical
- Manter o campo de busca em largura proporcional
- Posicionar melhor o ícone do placeholder no campo de pesquisa

Esses detalhes ajudam a evitar que o conteúdo fique “solto” em telas muito grandes.

### 3. Carrossel lado a lado com card

Uma das principais evoluções no desktop foi a organização horizontal do conteúdo:

- O carrossel e o card passaram a ficar lado a lado
- O bloco ganhou alinhamento vertical centralizado
- As margens laterais foram ampliadas
- A leitura dos textos ficou mais confortável

Esse ajuste melhora bastante a composição visual em telas amplas.

### 4. Tópicos com área centralizada

Na versão desktop, a seção de tópicos passou a trabalhar com um espaço horizontal mais controlado, evitando excesso de largura e mantendo os botões organizados.

### 5. Contato e rodapé com acabamento final

As seções finais também foram refinadas:

- A área de contato recebeu padding lateral maior
- O rodapé ganhou divisões visuais entre colunas
- A distribuição dos conteúdos ficou mais elegante e bem resolvida

## Técnicas e conceitos aplicados

Durante o desenvolvimento, foram praticados vários conceitos importantes de front-end:

- Estruturação semântica com HTML
- Organização de estilos em arquivos separados
- Uso de variáveis CSS
- Aplicação de `flexbox`
- Uso de `media queries`
- Estratégia `mobile first`
- Ajustes progressivos para tablet e desktop
- Interação visual com menu hambúrguer usando `checkbox`
- Integração de carrossel com Swiper


## Conclusão

O projeto **Alura Books** representa um estudo prático de construção de interface responsiva para uma plataforma de livros voltada à área de tecnologia. A página foi pensada para destacar conteúdos relacionados a programação, front-end, back-end, UX, design, infraestrutura e desenvolvimento profissional.

Mais do que montar uma página visualmente bonita, o projeto teve como foco aplicar uma lógica de desenvolvimento organizada, começando pelo **mobile first**, avançando para **tablets** e finalizando com ajustes para **desktops**. Esse processo permitiu construir uma experiência mais consistente, escalável e agradável para diferentes dispositivos.

