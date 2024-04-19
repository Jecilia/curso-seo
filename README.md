[# Certificado](https://app.rocketseat.com.br/certificates/08370cca-a23d-47a3-a4ce-4b7a52690c91)

[# SEO](https://developers.google.com/search/docs?hl=pt-br)

(Search Engine Optimization), que é a otimização para motores de busca. O SEO é um conjunto de técnicas e práticas que melhoram o posicionamento de um site ou conteúdo na internet.

Isso é importante para aumentar o tráfego do seu site, garantindo que as pessoas encontrem as informações relacionadas ao seu negócio. Um site bem posicionado nos resultados de busca é mais visível para os clientes e pode aumentar as vendas. 

O SEO é essencial para os desenvolvedores, pois mesmo que o site esteja bem construído, se não for encontrado, não adianta. É importante estudar profundamente o SEO para obter resultados efetivos.


 [# Core Web Vitals](https://developers.google.com/search/docs?hl=pt-br)

Core Web Vitals, que são três métricas que medem a experiência do usuário em sites. O Google criou essas métricas para ajudar até mesmo pessoas sem conhecimento técnico a entender como o desempenho de seus sites está afetando a experiência do usuário.

As três principais métricas são: 

- **Largest Contentful Paint (LCP)**, que mede o tempo de carregamento da página; 
- **First Input Delay (FID)**, que mede a interatividade da página;
- **Cumulative Layout Shift (CLS)**, que mede a estabilidade visual da página. Vamos explorar cada uma delas ao longo das aulas.

## Três estágios do Google 

Os três estágios do Google:

O **Crawling** é quando o robô do Google procura na internet por textos, imagens e vídeos. Ele começa procurando por novas páginas que estão entrando na internet. 

O **Indexing** é quando o algoritmo do Google observa o conteúdo das páginas, como título, imagens e vídeos, e decide se a página será indexada. 

O **Serving** é quando o Google entrega os resultados da pesquisa para o usuário, levando em consideração fatores como localização e tipo de dispositivo. É importante entender esses estágios para compreender como o robô e o algoritmo do Google trabalham.

## Crawling-Indexing

  [# Rendering](https://developers.google.com/search/docs/crawling-indexing/javascript/dynamic-rendering)

Rendering, que é o processo de transformar o JavaScript em HTML. O robô precisa interpretar o JavaScript como se fosse HTML para entender o conteúdo da página. O Crawler pode encontrar páginas que não estão completamente renderizadas, ou seja, construídas principalmente com JavaScript.

Isso requer uma fila de renderização antes que o conteúdo possa ser indexado. Vou mostrar duas estratégias para entender melhor o Rendering. Também vou falar sobre frameworks como Vue, Angular e React, que são usados para criar aplicações SPA. Além disso, vou mencionar ferramentas como Next.js, Astro e Wordpress, que ajudam na renderização prévia no servidor. Essas estratégias podem ser úteis para melhorar o processo de indexação pelo Google.

  [# URL](https://developers.google.com/search/docs/crawling-indexing/url-structure)

Melhores práticas de URLs, uma URL é um localizador de recursos único, como uma página HTML, um arquivo JavaScript, uma imagem ou um vídeo. É importante entender que as URLs não devem conter caracteres especiais ou espaços, sendo convertidas para o formato ASCII válido. 

Ao criar uma URL, é recomendado que ela seja simples, descritiva e contenha palavras relevantes. Além disso, é importante considerar a transformação para UTF-8 e evitar práticas ruins, como o uso de caracteres especiais, underscores e espaços. Problemas comuns podem surgir quando não há um padrão na estrutura da URL, como a presença de muitos parâmetros de pesquisa. 

Para resolver esses problemas, é necessário criar uma estrutura de URL organizada e inteligível, bloquear o acesso a URLs problemáticas no arquivo robots.txt e evitar o uso de IDs de sessão nas URLs. Também é importante considerar o uso de certificados SSL para encriptar os dados e transformar o HTTP em HTTPS. O Google considera URLs com e sem www como diferentes, portanto, é recomendado adicionar todas as versões no Search Console e trabalhar com redirecionamentos canônicos para evitar conteúdo duplicado

  [# links](https://developers.google.com/search/docs/crawling-indexing/links-crawlable)

A importância dos links em SEO, os links devem ser claros e explicativos, utilizando o atributo "title" ou o texto alternativo da imagem para fornecer informações sobre a página de destino. É recomendado usar textos simples e concisos, evitando frases genéricas como "clique aqui". 

Além disso, discutimos sobre links internos, que ajudam o Google a entender a estrutura do seu site, e links externos, que estabelecem confiança e relevância. Também mencionamos a tag "nofollow" para qualificar links externos e evitar que sejam seguidos pelo robô do Google.

  [# Sitemap](https://developers.google.com/search/docs/crawling-indexing/sitemaps/overview)

 Sitemap, que é um arquivo que lista todas as páginas do seu site. Ele ajuda os mecanismos de busca a encontrar e indexar seu site de forma eficiente. O Sitemap é útil para comunicar páginas novas, fornecer informações detalhadas sobre o conteúdo do site e é especialmente recomendado para sites grandes e complexos.

Existem várias maneiras de criar um Sitemap, incluindo o uso de geradores online ou ferramentas como o Screaming Frog. Recomendamos o uso do **xml-sitemaps.com** se você não tiver uma ferramenta que já crie o Sitemap para você

  [# robots.txt](https://developers.google.com/search/docs/crawling-indexing/robots/intro)

Sobre o arquivo robots.txt e entender como ele é usado para gerenciar o tráfego do crawler. O robots.txt permite definir permissões e restrições para os bots de busca. 

É importante ressaltar que o robots.txt não impede que as páginas sejam indexadas pelo Google, mas pode ser usado para bloquear arquivos específicos, como áudio, imagem, vídeo, scripts ou CSS. No entanto, é preciso ter cuidado ao bloquear esses arquivos para não afetar a funcionalidade das páginas. 

O arquivo robots.txt deve ser criado na raiz do site, seguindo algumas regras simples. É possível definir diretivas para diferentes user-agents, como o Googlebot, e especificar quais URLs são permitidas ou negadas. É importante lembrar que o robots.txt funciona apenas no domínio principal e não nos subdomínios. Além disso, pode haver uma demora de até 24 horas para que as alterações no arquivo sejam refletidas.

  [# block indexing](https://developers.google.com/search/docs/crawling-indexing/block-indexing)

 sobre como bloquear a indexação do Google usando a estratégia "noindex". Essa estratégia permite que solicitemos ao Google que remova uma página dos resultados de busca. No entanto, é importante lembrar que essa estratégia não funcionará se a página estiver bloqueada no arquivo "robots.txt". A implementação é simples, basta adicionar uma meta tag com o nome "robots" e o conteúdo "noindex". Isso funciona para todos os crawlers. Também é possível adicionar outras estratégias, como "nofollow", para evitar que os links dentro da página sejam seguidos.


[# canonicalization](https://developers.google.com/search/docs/crawling-indexing/canonicalization)

Canonicalização e URLs canônicas, a canonicalização é o processo de determinar qual é a URL verdadeira para o Google, quando há páginas duplicadas ou conteúdo duplicado. Isso pode acontecer quando há páginas com argumentos de filtro de busca, páginas com HTTP e HTTPS, ou versões de teste que ficaram online. O Google determina a URL canônica, mas podemos ajudar indicando qual é a página verdadeira. 

Podemos fazer isso através de redirecionamentos e do uso do atributo "relation canonical" no HTML. É importante sempre referenciar a URL canônica ao compartilhar conteúdo e evitar informações divergentes. O Google dará preferência ao HTTPS e considerará as páginas sugeridas no sitemap como canônicas.


  [# redirects](https://developers.google.com/search/docs/crawling-indexing/301-redirects)

 O redirecionamento é uma forma de informar ao Google que uma determinada URL não está mais disponível e foi movida para outro local. 
 
 Existem três etapas para configurar o redirecionamento: **via servidor**, através de respostas HTTP; através de **meta tags** no código HTML da página;  **via JavaScript**. Recomenda-se utilizar o redirecionamento via servidor, pois é mais eficiente. Dependendo da ferramenta que você está utilizando, existem outras opções disponíveis. Como programadores, é importante entendermos essas técnicas para implementar o redirecionamento corretamente

## Feature Guides 

  [# Structured Data](https://developers.google.com/search/docs/appearance/structured-data/search-gallery)

Structured Data, ou dados estruturados do Google. Essa é uma forma de ajudar o Google a entender o tipo de conteúdo do seu site e como ele deve ser apresentado nos resultados de pesquisa. 

Você pode criar dados estruturados usando ferramentas como **WebCode.tools** e **search.google.com/test/rich-results**. O **schema.org** é uma comunidade aberta que fornece diretrizes e documentação para ajudar na criação desses dados. Você pode testar seus dados estruturados usando a URL ou o snippet de código no schema.org. Lembre-se de sempre atualizar-se sobre as melhores práticas e usar as ferramentas disponíveis para facilitar o processo.

## Ranking  systems

 [# Sitelinks](https://developers.google.com/search/docs/appearance/sitelinks)

Os Sitelinks são links agrupados que aparecem nos resultados de busca do Google para ajudar os usuários a encontrar informações com mais eficiência. O Google utiliza um algoritmo de agrupamento de links para exibir esses Sitelinks. Eles são indexados e aparecem quando são úteis para o usuário. 

Algumas melhores práticas para ter Sitelinks incluem ter títulos e cabeçalhos relevantes e compactos, uma estrutura lógica de fácil navegação e evitar conteúdo repetitivo. O Google também dá a dica de que é possível remover um Sitelink removendo a página ou utilizando a estratégia de noindex. Durante a aula, analisaremos um exemplo de Sitelinks na página da Rocketseat para entender melhor como eles funcionam.

## OTIMIZAÇÃO

  [# metatags](https://developers.google.com/search/docs/crawling-indexing/special-tags)

Falar sobre metatags e como elas podem ajudar a melhorar a visibilidade do seu site nos mecanismos de busca, como o Google. As metatags são tags que ficam dentro do elemento <head> do seu documento HTML e fornecem informações sobre o conteúdo da página. 

Algumas das metatags que o Google considera são: a definição do conjunto de caracteres utilizado, a indicação de que o site é responsivo para dispositivos móveis, uma descrição da página, a autoridade do site e a configuração do Safe Search. Vamos explorar mais metatags em aulas futuras.

# Title e Description 
[# verificando o title e description](https://mangools.com/?utm_source=google&utm_medium=cpc&utm_campaign=mangools-brand-main-landing-europe&gad_source=1&gclid=Cj0KCQjwiYOxBhC5ARIsAIvdH50ErBFIDmI69TmoiKaW_jSFuO11yzLEsgjmgHwpS7w12VwXuP9KL4saAtAyEALw_wcB)

Title e do Description para o SEO. O Title deve ser único para cada página e definir claramente o objetivo da página. Evite repetir títulos em outras páginas do seu site, pois isso diminui a relevância para o SEO. 

O Description não afeta o ranqueamento nas pesquisas, mas é útil para explicar o conteúdo da página. Use a ferramenta mangools.com para verificar se o título e a descrição estão adequados. O Title e o Description são metatags que devem ser colocadas no cabeçalho da página.

o Google faz modificações nos títulos e descrições das páginas de pesquisa. O Google pode alterar títulos que sejam clickbaits, ou seja, títulos que não correspondem ao conteúdo da página. Ele também pode modificar títulos que sejam muito longos ou que contenham apenas palavras-chave. 

Além disso, o Google pode alterar as descrições das páginas para melhor atender aos usuários. É importante entender essas modificações e criar títulos coerentes para melhorar o SEO. O Google também pode usar links internos da página para gerar títulos relevantes. Por fim, discutimos a importância de criar uma Meta Description para ajudar os usuários a entenderem o conteúdo da página


  [# Open Graph](https://webcode.tools/open-graph-generator)

Open Graph, que são as meta-tags para as mídias sociais. Essas tags são importantes para controlar a aparência de um link compartilhado nas redes sociais, como Facebook, LinkedIn e Twitter. 

O objetivo é tornar o conteúdo mais atrativo e explicativo, gerando engajamento e mais cliques para a página. Existem várias meta-tags disponíveis, mas as principais são og:title, og:url e og:description. Além disso, também temos o Twitter Card, que funciona de forma semelhante ao Open Graph. É importante testar as tags usando ferramentas como o Facebook Debugger e o Post Inspector do LinkedIn para garantir que o compartilhamento esteja correto


# Tags de Texto

As tags de texto são como a organização de um livro, e é importante estruturá-las corretamente para que o motor de busca entenda o conteúdo da página. 

O **H1** é o título principal da página e deve ser semelhante ao título do head. Os **H2** são subtítulos e podem ter sub-blocos com **H3**. Os parágrafos são marcados com a tag P e a tag Strong é usada para dar ênfase ao texto. A tag A é usada para criar links internos e externos. Quanto mais links e menos dependência de estilos, melhor para o SEO.


# Navegação 

É fundamental que os visitantes consigam se encontrar facilmente e que o robô de busca também entenda a relevância das páginas. Vou mostrar um desenho para ilustrar como a navegação pode ser organizada de forma eficiente. 

Além disso, vou explicar sobre outros tipos de navegação, como os **breadcrumbs**, que ajudam tanto os usuários quanto os motores de busca. Também abordaremos a importância de uma navegação mobile friendly e de uma página 404 coerente

  # Otimização de imagens

Existem estratégias de otimização de imagens para melhorar a performance do seu site. Imagens são pesadas e podem deixar o site lento, então é importante trabalhar com tamanhos adequados e responsivos. Além disso, é recomendado utilizar formatos mais modernos, como **avif** e **webp**, que reduzem o tamanho da imagem sem perder qualidade. 

A estratégia de **Lazy Loading** também é útil, carregando as imagens apenas quando são visíveis na página. Definir largura e altura da imagem ajuda a evitar problemas de layout. Atributos como source, alt, source set, sizes, loading, decoding e fetch priority também são importantes para otimizar as imagens.


# Lazy Load Third Party Content  

Lazy Load, uma estratégia para carregar e ler conteúdos de terceiros, como embeds do YouTube ou integrações com redes sociais. A ideia é usar uma fachada, um elemento estático que se parece com o conteúdo desejado, mas sem as funcionalidades completas. 

Isso adia o carregamento e permite identificar e tratar o tipo de conteúdo. Para identificar, podemos usar o pagespeed.web.dev. Ao aplicar o Lazy Load, podemos melhorar o desempenho do site e a pontuação de performance.

# Mobile Friendly  

Discutimos a importância de ter um site amigável para dispositivos móveis, também conhecido como Mobile Friendly. O Google dá grande importância ao conteúdo otimizado para dispositivos móveis, através da iniciativa Mobile First Indexing. 

Recomenda-se o uso de estratégias como responsividade e AMP (Accelerated Mobile Pages) para melhorar a experiência do usuário em dispositivos móveis. É essencial ter uma meta tag viewport e evitar bloqueios de recursos no robots.txt. A ferramenta  [# Lighthouse](https://pagespeed.web.dev/) pode ser usada para analisar e melhorar a performance do site em dispositivos móveis. Ao implementar essas estratégias, seu site estará mais amigável para dispositivos móveis e será melhor indexado pelo Google

## FERRAMENTAS

  [# Google Search Console]( https://search.google.com/search-console/welcome?utm_source=about-page)

Google Search Console, uma ferramenta importante para trabalhar com SEO. Através dela, podemos analisar vários fatores, como a indexação de páginas, problemas com vídeos, criação de sitemaps e remoção de URLs indesejadas. 

Também podemos verificar a experiência do usuário, como os Core Web Vitals e a usabilidade no mobile. A ferramenta oferece relatórios detalhados e permite que você aprofunde seu conhecimento sobre o desempenho do seu site. Além disso, mostraremos como verificar a propriedade do seu site e explorar as diferentes funcionalidades do Search Console


  [# Pagespeed Insights](https://pagespeed.web.dev/)

 ferramenta Lighthouse e como utilizá-la para analisar a performance de um site. O Mayk mencionou a importância de utilizar o HTTP2 para reduzir o tempo de carregamento das imagens. Ele também mostrou como acessar a ferramenta Pagespeed Insights através do site pagespeed.web.dev ou diretamente no DevTools do navegador. O Mayk explicou como interpretar os resultados da análise, destacando a sugestão de utilizar formatos de imagem mais eficientes, como WebP e AVIF, para reduzir o tamanho dos arquivos e melhorar a velocidade do site


  [# Keyword Planner - Planejamento de conteúdo](https://answerthepublic.com/)

O SEO (Search Engine Optimization) é importante para apresentar um bom conteúdo aos usuários. É fundamental ter conteúdos únicos e informativos. Existem várias ferramentas para planejar palavras-chave e criar conteúdo relevante. 

É importante pensar no seu nicho e pesquisar as palavras-chave relacionadas a ele. O planejamento de conteúdo e palavras-chave é essencial para atrair tráfego e gerar relevância para o seu site. 

Algumas ferramentas úteis são o [ Moz Explorer](https://moz.com/explorer ) e o [# Keywords Sheeter](https://keywordsheeter.com/). Essas ferramentas fornecem informações sobre o volume de pesquisa, dificuldade de classificação e sugestões de palavras-chave

  [# Screaming Frog](https://www.screamingfrog.co.uk/seo-spider/)

 A ferramenta Screaming Frog, que é muito útil para encontrar links quebrados, gerar Sitemap XML e auditar redirecionamentos em nosso site. A versão gratuita permite até 500 URLs, enquanto a versão paga é ilimitada. 

 A ferramenta oferece uma ampla gama de informações, como links internos e externos, segurança, códigos de resposta, títulos de página, descrições e palavras-chave meta, cabeçalhos, conteúdo, imagens, links canônicos e muito mais. 
 Além disso, ela também identifica problemas, como links faltando títulos de página. O Screaming Frog é uma ferramenta completa e amplamente utilizada por profissionais de SEO