# :rocket: Guia de SEO (Search Engine Optimization)

- Este é um check-list pessoal que criei de links úteis e lembretes de tags a serem adicionadas na criação de sites HTML estáticos (na unha ✍️😂 - sem nenhum framework como Wordpress, React :react:, Next, etc) para que os motores de busca façam a indexação do site de forma orgânica.

# Significado das siglas

- SEO: Search Engine Optimization
- SERP: Search Engine Results Page

# Head

- [x]  Charset `utf-8`
- [x]  Viewport `width=device-width, initial-scale=1.0`
- [x]  Theme color
- [x]  Link canonical

# Metatags

[https://metatags.io/](https://metatags.io/)

- [x]  Title
- [x]  Description
- [x]  Author
- [x]  Copyrigth
- [x]  Keywords
- [x]  Meta Robots (por página)
    - [x]  index, follow (Permite a indexação da página)
    - [x]  noindex, nofollow (Bloqueia a indexação da página)

# Open Graph (General/Facebook)

[https://freecodetools.org/ogp/](https://freecodetools.org/ogp/)

- [x]  og:type
- [x]  og:url
- [x]  og:title
- [x]  og:description
- [x]  og:image

# Open Graph (Twitter)

[https://freecodetools.org/twitter-card-generator/](https://freecodetools.org/twitter-card-generator/)

- [x]  twitter:card
- [x]  twitter:url
- [x]  twitter:title
- [x]  twitter:description
- [x]  twitter:image

# Favicon

[https://www.favicon-generator.org/](https://www.favicon-generator.org/)

- [x]  Default (16x16)
- [x]  Tamanhos para iOS
- [x]  Tamanhos para Android
- [x]  manifest.json

# Schema (JSON-LD)

[https://technicalseo.com/tools/schema-markup-generator/](https://technicalseo.com/tools/schema-markup-generator/)

- [ ]  Article
- [ ]  Localização
- [ ]  Carrossel
- [ ]  Perguntas frequentes
- [ ]  Empresa local
- [ ]  Logo
- [ ]  Perguntas e respostas
- [ ]  Caixa de pesquisa de sitelinks

# Sitemap

[https://www.xml-sitemaps.com/](https://www.xml-sitemaps.com/)

- [ ]  Gerar XML com links de todas as páginas e data da ultima atualização do site

# Robots.txt

- [ ]  Gerar arquivo txt, com referencia ao Sitemap

[https://en.ryte.com/free-tools/robots-txt-generator/](https://en.ryte.com/free-tools/robots-txt-generator/)

# HTML Semântico (Principais tags)

- `<header>`
- `<nav>`
- `<main>`
- `<section>`
    - `<div>`
    - `<blockquote>`
    - `<cite>`
    - `<adrress>`
    - `<time>`
- `<article>`
- `<aside>`
- `<footer>`

# Títulos e Parágrafos

- `<h1>`
- `<h2>`
- `<h3>`
- `<h4>`
- `<h5>`
- `<h6>`
- `<p>`

# Dicas

- [ ]  H1: 1 por página
- [ ]  H2: 1 por sessão
- [ ]  H3: Pode repetir
- [ ]  Todas imagens do site devem ter o atributo `alt`
- [ ]  Links externos `target="_blank"` devem ter os atributos: `rel=”noopener”` e `rel=”noreferrer”`

# Hospedagem

- [ ]  Site deve estar com certificado SSL/HTTPS
- [ ]  URL amigável
- [ ]  Remover extensões de arquivos `.html` no final
- [ ]  Página 404 personalizada
- [ ]  Habilitar compressão Gzip
- [ ]  Habilitar cache control
- [ ]  Habilitar keep alive

# Testar velocidade:

- PageSpeed: [https://developers.google.com/speed/pagespeed/insights/?hl=pt-BR](https://developers.google.com/speed/pagespeed/insights/?hl=pt-BR)
- GTMetrix: [https://gtmetrix.com/](https://gtmetrix.com/)
- Lighthouse: [https://developers.google.com/web/tools/lighthouse/](https://developers.google.com/web/tools/lighthouse/)

# SEO Analyzer's

- Seobility: [https://www.seobility.net/en/seocheck/](https://www.seobility.net/en/seocheck/)
- SEO Site Checkup: [https://seositecheckup.com/](https://seositecheckup.com/)
- Sitechecker: [https://sitechecker.pro/pt/](https://sitechecker.pro/pt/)

# Planejadores de palavras-chave

- Google Ads: [https://ads.google.com/aw/keywordplanner/home](https://ads.google.com/aw/keywordplanner/home)
- Keyword Tool: [https://keywordtool.io/](https://keywordtool.io/)

# Official Debuggers

- [https://developers.facebook.com/tools/debug/](https://developers.facebook.com/tools/debug/)
- [https://cards-dev.twitter.com/validator](https://cards-dev.twitter.com/validator)
- [https://www.linkedin.com/post-inspector/inspect/](https://www.linkedin.com/post-inspector/inspect/)
- [https://search.google.com/structured-data/testing-tool/u/0/](https://search.google.com/structured-data/testing-tool/u/0/)
- [https://search.google.com/test/rich-results](https://search.google.com/test/rich-results)

# Links

- O que é SEO: [https://resultadosdigitais.com.br/especiais/o-que-e-seo/](https://resultadosdigitais.com.br/especiais/o-que-e-seo/)
- Dados estruturados: [https://developers.google.com/search/docs/advanced/structured-data/intro-structured-data](https://developers.google.com/search/docs/advanced/structured-data/intro-structured-data#search-appearance)
- Google Meu Negócio: [https://www.google.com/intl/pt-BR_br/business/](https://www.google.com/intl/pt-BR_br/business/)
- Google Search Console: [https://search.google.com/search-console](https://search.google.com/search-console)
- Sitelinks: [https://developers.google.com/search/docs/data-types/sitelinks-searchbox](https://developers.google.com/search/docs/data-types/sitelinks-searchbox)
- Tipos de dados estruturados: [https://developers.google.com/search/docs/advanced/structured-data/search-gallery](https://developers.google.com/search/docs/advanced/structured-data/search-gallery)
- Cursos Google: [https://skillshop.exceedlms.com/student/catalog/browse](https://skillshop.exceedlms.com/student/catalog/browse)

# Documentações Oficiais

- Developers Google Webmaster: [https://developers.google.com/search/](https://developers.google.com/search/)
- Microsoft Bing Webmaster Tools: [https://www.bing.com/webmasters/help/home-05a5a164](https://www.bing.com/webmasters/help/home-05a5a164)
