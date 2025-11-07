<!--
Projeto: Site completo para tráfego orgânico (template universal)
Arquivos inclusos (cole e salve cada bloco em arquivos separados):
- index.html
- style.css
- script.js
- /posts/pagina-pilar.html
- /posts/artigo-exemplo-1.html
- /posts/artigo-exemplo-2.html
- sitemap.xml
- robots.txt
- README (instruções de deploy e 30 dias)

INSTRUÇÕES:
1) Copie cada bloco abaixo e salve no arquivo com o nome indicado.
2) Abra index.html no navegador para ver o site localmente.
3) Para colocar online: siga as instruções em README (GitHub Pages recomendado).
-->


==================== index.html ====================

<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>EcomBoost — Estratégias para Tráfego Orgânico</title>
  <meta name="description" content="Site template universal otimizado para tráfego orgânico: SEO, blog, página pilar, captura de leads e deploy fácil.">
  <meta name="keywords" content="tráfego orgânico, SEO, site, blog">
  <link rel="canonical" href="https://seu-dominio-aqui.com/">
  <link rel="stylesheet" href="style.css">
  <script type="application/ld+json">
  {
    "@context":"https://schema.org",
    "@type":"WebSite",
    "name":"EcomBoost",
    "url":"https://seu-dominio-aqui.com/",
    "potentialAction":{
      "@type":"SearchAction",
      "target":"https://seu-dominio-aqui.com/?s={search_term_string}",
      "query-input":"required name=search_term_string"
    }
  }
  </script>
</head>
<body>
  <header class="site-header">
    <div class="container header-inner">
      <a class="brand" href="/">EcomBoost</a>
      <nav class="main-nav" id="mainNav">
        <a href="/">Home</a>
        <a href="/posts/pagina-pilar.html">Guia</a>
        <a href="#blog">Blog</a>
        <a href="#sobre">Sobre</a>
        <a href="#contato">Contato</a>
      </nav>
      <button class="nav-toggle" id="navToggle" aria-label="Abrir menu">☰</button>
    </div>
  </header>

  <main>
    <section class="hero">
      <div class="container">
        <h1>Construa um site que atrai visitantes sem pagar por anúncios</h1>
        <p class="lead">Template universal pronto para qualquer nicho: SEO técnico, páginas otimizadas e plano de conteúdo para 90 dias.</p>
        <div class="hero-cta">
          <a class="btn" href="/posts/pagina-pilar.html">Ver Guia Completo</a>
          <a class="btn ghost" href="#contato">Peça seu site</a>
        </div>
      </div>
    </section>

    <section class="features container">
      <article>
        <h2>Página Pilar + Cluster</h2>
        <p>Estrutura comprovada: 1 página pilar que centraliza conhecimento e 6–10 artigos cluster com links internos.</p>
      </article>
      <article>
        <h2>SEO Técnico</h2>
        <p>Meta tags, sitemap, robots, schema e performance para rankear melhor nos mecanismos de busca.</p>
      </article>
      <article>
        <h2>Captura de Leads</h2>
        <p>Isca digital (e-book) + formulário para aumentar sua lista e trazer tráfego recorrente.</p>
      </article>
    </section>

    <section id="blog" class="container blog-preview">
      <h2>Últimos artigos</h2>
      <div class="posts">
        <article class="post">
          <h3><a href="/posts/artigo-exemplo-1.html">Como escolher palavras-chave para começar</a></h3>
          <p>Aprenda passo a passo a identificar termos de busca com intenção real e baixa concorrência.</p>
        </article>
        <article class="post">
          <h3><a href="/posts/artigo-exemplo-2.html">SEO on-page rápido: checklist</a></h3>
          <p>Checklist simples para deixar suas páginas prontas para ser encontradas.</p>
        </article>
      </div>
    </section>

    <section id="sobre" class="container about">
      <h2>Sobre este template</h2>
      <p>Template universal criado para ser facilmente adaptado a qualquer nicho. Edite textos, imagens e publique usando GitHub Pages ou outra hospedagem.</p>
    </section>

    <section id="contato" class="container contact">
      <h2>Fale comigo</h2>
      <p>Peça personalização ou o site completo pronto para publicar.</p>
      <form id="contactForm" action="#" onsubmit="return submitForm(event)">
        <label for="name">Nome</label>
        <input id="name" name="name" required>
        <label for="email">E-mail</label>
        <input id="email" name="email" type="email" required>
        <label for="message">Mensagem</label>
        <textarea id="message" name="message" rows="4"></textarea>
        <button class="btn" type="submit">Enviar</button>
      </form>
    </section>

  </main>

  <footer class="site-footer">
    <div class="container footer-inner">
      <div>
        <strong>EcomBoost</strong>
        <p>Template para tráfego orgânico — pronto para qualquer nicho.</p>
      </div>
      <nav>
        <a href="/">Home</a> |
        <a href="/posts/pagina-pilar.html">Guia</a> |
        <a href="#contato">Contato</a>
      </nav>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>


==================== style.css ====================

/* style.css - básico e responsivo */

:root{
  --accent:#007bff;
  --dark:#0b1320;
  --muted:#6b7280;
  --max-width:1100px;
}
*{box-sizing:border-box}
body{font-family:Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial; margin:0; color:var(--dark); background:#fff}
.container{max-width:var(--max-width); margin:0 auto; padding:20px}
.header-inner{display:flex; align-items:center; justify-content:space-between}
.brand{font-weight:700; text-decoration:none; color:var(--dark)}
.main-nav a{margin-left:18px; text-decoration:none; color:var(--muted)}
.nav-toggle{display:none; background:none; border:none; font-size:20px}

.hero{background:linear-gradient(90deg, rgba(0,123,255,0.08), rgba(255,255,255,0)); padding:60px 0}
.hero h1{font-size:28px; margin:0 0 10px}
.lead{color:var(--muted); margin-bottom:18px}
.btn{display:inline-block; padding:10px 16px; background:var(--accent); color:#fff; text-decoration:none; border-radius:8px}
.btn.ghost{background:transparent; border:2px solid var(--accent); color:var(--accent); margin-left:10px}

.features{display:grid; grid-template-columns:repeat(3,1fr); gap:20px; margin:40px 0}
.features article{background:#fafafa; padding:18px; border-radius:10px}

.blog-preview .posts{display:grid; grid-template-columns:repeat(2,1fr); gap:16px}
.post h3{margin:0 0 6px}

.about, .contact{margin:36px 0}
.contact form{display:grid; gap:8px}
input, textarea{padding:10px; border:1px solid #e5e7eb; border-radius:6px}
.site-footer{background:#f8fafc; padding:20px 0; margin-top:36px}
.footer-inner{display:flex; justify-content:space-between; align-items:center}

/* Responsivo */
@media(max-width:800px){
  .features{grid-template-columns:1fr}
  .blog-preview .posts{grid-template-columns:1fr}
  .main-nav{display:none}
  .nav-toggle{display:block}
}


==================== script.js ====================

// script.js - menu mobile e submit fake
const navToggle = document.getElementById('navToggle')
const mainNav = document.getElementById('mainNav')
navToggle && navToggle.addEventListener('click', ()=>{
  if(mainNav.style.display === 'block') mainNav.style.display = ''
  else mainNav.style.display = 'block'
})

function submitForm(e){
  e.preventDefault();
  const name = document.getElementById('name').value || 'Amigo';
  alert('Obrigado, ' + name + '! Recebi sua mensagem. Vou te responder em breve.');
  e.target.reset();
  return false;
}


==================== /posts/pagina-pilar.html ====================

<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Guia Completo: Como Gerar Tráfego Orgânico | EcomBoost</title>
  <meta name="description" content="Guia pilar: passo a passo para atrair tráfego orgânico com SEO, conteúdo e estratégias de autoridade.">
  <link rel="stylesheet" href="../style.css">
</head>
<body>
  <main class="container">
    <h1>Guia Completo: Como Gerar Tráfego Orgânico</h1>
    <p class="lead">Este é o seu hub — a página pilar que organiza o tema e liga todos os artigos do cluster.</p>

    <section>
      <h2>Índice</h2>
      <ol>
        <li>O que é tráfego orgânico</li>
        <li>Pesquisa de palavras-chave</li>
        <li>SEO on-page</li>
        <li>Conteúdo pilar + artigos cluster</li>
        <li>Backlinks e autoridade</li>
        <li>Plano de 30/60/90 dias</li>
      </ol>
    </section>

    <section>
      <h2>Pesquisa de Palavras-Chave</h2>
      <p>Comece listando pesquisas reais, depois use ferramentas para estimar volume e dificuldade. Priorize intenção.</p>
    </section>

    <section>
      <h2>Conteúdo recomendado (cluster)</h2>
      <ul>
        <li><a href="artigo-exemplo-1.html">Como escolher palavras-chave</a></li>
        <li><a href="artigo-exemplo-2.html">SEO on-page: checklist</a></li>
        <li>Como conseguir backlinks</li>
      </ul>
    </section>

    <section>
      <h2>Lead Magnet</h2>
      <p>Crie um e-book simples com 7 táticas e ofereça em troca do e-mail.</p>
    </section>

    <section>
      <h2>Conclusão</h2>
      <p>Implemente, meça e otimize. SEO é esforço consistente — bons resultados vêm com tempo.</p>
    </section>

  </main>
</body>
</html>


==================== /posts/artigo-exemplo-1.html ====================

<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Como escolher palavras-chave — Guia rápido</title>
  <meta name="description" content="Passo a passo para escolher palavras-chave com intenção e baixa concorrência.">
  <link rel="stylesheet" href="../style.css">
</head>
<body>
  <main class="container">
    <h1>Como escolher palavras-chave: 6 passos rápidos</h1>
    <p class="lead">Uma metodologia simples para começar a gerar tráfego orgânico.</p>
    <h2>1. Liste perguntas reais</h2>
    <p>Faça uma lista de 20 perguntas que seu público faria sobre o tema.</p>
    <h2>2. Classifique por intenção</h2>
    <p>Informativa, navegacional, comercial.</p>
    <h2>3. Use ferramentas gratuitas</h2>
    <p>Google Search, Ubersuggest e o autocompletar.</p>
    <h2>Conclusão</h2>
    <p>Escolha 5 palavras para os seus primeiros 3 meses e foque nelas.</p>
  </main>
</body>
</html>


==================== /posts/artigo-exemplo-2.html ====================

<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>SEO on-page: checklist rápido</title>
  <meta name="description" content="Checklist prático de SEO on-page para aplicar hoje nas suas páginas.">
  <link rel="stylesheet" href="../style.css">
</head>
<body>
  <main class="container">
    <h1>SEO on-page: checklist prático</h1>
    <ul>
      <li>Título (H1) com palavra-chave</li>
      <li>Meta description persuasiva</li>
      <li>URLs curtas e amigáveis</li>
      <li>Imagens otimizadas (alt e compressão)</li>
      <li>Links internos para a página pilar</li>
    </ul>
  </main>
</body>
</html>


==================== sitemap.xml ====================

<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <url>
    <loc>https://seu-dominio-aqui.com/</loc>
    <changefreq>weekly</changefreq>
    <priority>1.0</priority>
  </url>
  <url>
    <loc>https://seu-dominio-aqui.com/posts/pagina-pilar.html</loc>
    <changefreq>monthly</changefreq>
    <priority>0.9</priority>
  </url>
  <url>
    <loc>https://seu-dominio-aqui.com/posts/artigo-exemplo-1.html</loc>
    <changefreq>monthly</changefreq>
    <priority>0.6</priority>
  </url>
</urlset>


==================== robots.txt ====================

User-agent: *
Allow: /
Sitemap: https://seu-dominio-aqui.com/sitemap.xml


==================== README + 30-day plan + deploy ====================

README - Como usar este projeto

1) Criar estrutura de pastas
- Coloque index.html, style.css e script.js na raiz do projeto.
- Crie a pasta posts/ e coloque os arquivos de exemplo dentro.
- Coloque sitemap.xml e robots.txt na raiz.

2) Visualizar localmente
- Abra index.html no navegador.

3) Publicar com GitHub Pages (rápido e grátis)
- Crie conta no github.com (se não tiver).
- Crie novo repositório (ex: meusite).
- Faça upload de todos os arquivos (arrastar e soltar funciona).
- Vá em Settings > Pages > Source > branch: main > / (root) > Save.
- Após alguns minutos o site estará disponível em: https://seuusuario.github.io/meusite

4) Substituir "https://seu-dominio-aqui.com/" pelas URLs reais nos arquivos sitemap.xml, canonical e schema.

5) Checklist SEO inicial
- Criar conta no Google Search Console e adicionar o site.
- Enviar sitemap.xml pelo Search Console.
- Criar propriedade no Google Analytics (GA4).
- Verificar Core Web Vitals com PageSpeed Insights.

6) Plano de 30 dias (resumido)
Semana 1
- Dia 1: Personalizar nome, logo, e meta tags.
- Dia 2: Escolher 5 palavras-chave iniciais e mapear intenção.
- Dia 3: Criar a página pilar (editar posts/pagina-pilar.html).
- Dia 4: Publicar 2 artigos do cluster (usar os exemplos como base).
- Dia 5: Configurar Google Search Console e Analytics.
- Dia 6: Otimizar imagens e performance.
- Dia 7: Revisar conteúdo e ajustar CTAs.

Semana 2
- Produzir 3 artigos adicionais.
- Começar outreach (contatos para guest posts).
- Criar lead magnet simples (PDF) e integrar a captura de e-mails.

Semana 3
- Reaproveitar conteúdo em redes: 3 short videos / 5 posts no instagram.
- Monitorar posições e CTR no Search Console.

Semana 4
- Atualizar o conteúdo com dados e links internos.
- Planejar próximos 60 dias (mais artigos e backlinks).

7) Se quiser ZIP pronto
- Diga: "Quero o ZIP" e eu crio e disponibilizo para download.

8) Personalização por nicho
- Se me disser seu nicho (ex: contabilidade, culinária, moda), eu adapto títulos, palavras-chave, e exemplos de conteúdo agora.


==================== FIM DO DOCUMENTO ====================
