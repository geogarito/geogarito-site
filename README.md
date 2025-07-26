<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>GEOGARITO - Questões Comentadas de Geografia</title>
<style>
  /* Reset básico */
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }
  body {
    background: #f0f3f8;
    color: #333;
    line-height: 1.6;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
  }
  header {
    background-color: #1e3a8a;
    color: white;
    padding: 20px 10%;
    text-align: center;
    box-shadow: 0 2px 5px rgba(0,0,0,0.2);
  }
  header h1 {
    font-weight: 700;
    font-size: 2.5rem;
    letter-spacing: 3px;
  }
  nav {
    margin-top: 10px;
  }
  nav a {
    color: #a5b4fc;
    text-decoration: none;
    margin: 0 15px;
    font-weight: 600;
    transition: color 0.3s ease;
  }
  nav a:hover {
    color: #6366f1;
  }
  main {
    flex: 1;
    padding: 40px 10%;
  }
  section#sobre {
    margin-bottom: 40px;
  }
  section#sobre h2 {
    font-size: 2rem;
    margin-bottom: 15px;
    color: #1e3a8a;
  }
  section#sobre p {
    font-size: 1.15rem;
    max-width: 800px;
  }
  section#ebooks {
    background-color: #e0e7ff;
    padding: 30px;
    border-radius: 8px;
    max-width: 900px;
    margin: 40px auto;
    box-shadow: 0 2px 8px rgba(99,102,241,0.3);
  }
  section#ebooks h2 {
    color: #1e3a8a;
    margin-bottom: 25px;
    text-align: center;
  }
  .ebook-list {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
    justify-content: center;
  }
  .ebook {
    background: white;
    padding: 20px;
    border-radius: 8px;
    width: 250px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    text-align: center;
  }
  .ebook h3 {
    margin-bottom: 12px;
    color: #334155;
  }
  .ebook p {
    font-size: 0.95rem;
    color: #555;
    margin-bottom: 15px;
  }
  .ebook a {
    display: inline-block;
    text-decoration: none;
    background-color: #6366f1;
    color: white;
    padding: 10px 15px;
    border-radius: 5px;
    font-weight: 600;
    transition: background-color 0.3s ease;
  }
  .ebook a:hover {
    background-color: #4f46e5;
  }
  section#contato {
    background-color: #e0e7ff;
    padding: 30px;
    border-radius: 8px;
    max-width: 600px;
    margin: 40px auto 60px;
    box-shadow: 0 2px 8px rgba(99,102,241,0.3);
  }
  section#contato h2 {
    color: #1e3a8a;
    margin-bottom: 20px;
    text-align: center;
  }
  iframe {
    width: 100%;
    height: 600px;
    border: none;
  }
  footer {
    background-color: #1e3a8a;
    color: white;
    text-align: center;
    padding: 20px 10%;
  }
  footer p {
    margin-bottom: 8px;
  }
  .social-links {
    margin-top: 10px;
  }
  .social-links a {
    color: white;
    margin: 0 15px;
    font-size: 1.8rem;
    text-decoration: none;
    transition: color 0.3s ease;
  }
  .social-links a:hover {
    color: #a5b4fc;
  }
  @import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css');
  @media (max-width: 600px) {
    header h1 {
      font-size: 1.8rem;
    }
    nav a {
      margin: 0 8px;
      font-size: 0.9rem;
    }
    main {
      padding: 20px 5%;
    }
    section#ebooks .ebook {
      width: 100%;
    }
    section#contato {
      max-width: 100%;
    }
  }
</style>
</head>
<body>

<header>
  <h1>GEOGARITO</h1>
  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#ebooks">E-books</a>
    <a href="#contato">Contato</a>
  </nav>
</header>

<main>
  <section id="sobre">
    <h2>Sobre o GEOGARITO</h2>
    <p>
      O GEOGARITO é um projeto educacional focado em fornecer questões comentadas de Geografia para estudantes que buscam aprimorar seus conhecimentos para concursos e vestibulares. Idealizado pelo Prof. Coimbra, nosso objetivo é facilitar o aprendizado por meio de materiais didáticos acessíveis e atualizados, com um toque prático e direto.
    </p>
  </section>

  <section id="ebooks">
    <h2>E-books e Cursos Disponíveis</h2>
    <div class="ebook-list">
      <div class="ebook">
        <h3>Simulados de Geografia</h3>
        <p>Conjunto com 100 questões comentadas para fixar o conteúdo.</p>
        <a href="https://link-para-download-simulados.com" target="_blank" rel="noopener">Baixar agora</a>
      </div>
      <div class="ebook">
        <h3>Guia Completo de Geopolítica</h3>
        <p>Material detalhado com mapas, conceitos e questões comentadas.</p>
        <a href="https://link-para-download-geopolitica.com" target="_blank" rel="noopener">Baixar agora</a>
      </div>
      <div class="ebook">
        <h3>Curso Online de Regionalização</h3>
        <p>Aulas em vídeo + material de apoio para estudo completo.</p>
        <a href="https://link-para-curso-online.com" target="_blank" rel="noopener">Saiba mais</a>
      </div>
    </div>
  </section>

  <section id="contato">
    <h2>Fale conosco</h2>
    <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSfWZag9slKJfjPMIXF2Jpm7dFTZBUG62sJrvAeuCtey3_oYJQ/viewform?embedded=true" loading="lazy" title="Formulário de contato GEOGARITO">Carregando…</iframe>
  </section>
</main>

<footer>
  <p>© 2025 GEOGARITO - Todos os direitos reservados</p>
  <p>Contato: mestrewanderson59@gmail.com | Tel: (94) 98125-4279</p>
  <div class="social-links">
    <a href="https://instagram.com/geogarito" target="_blank" aria-label="Instagram"><i class="fab fa-instagram"></i></a>
    <a href="https://tiktok.com/@geogarito" target="_blank" aria-label="TikTok"><i class="fab fa-tiktok"></i></a>
  </div>
</footer>

</body>
</html>
