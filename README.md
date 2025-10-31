<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="css/style.css" />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css"
    />
    <title>GreenTech</title>
    <style>
      * {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  text-decoration: none;
  outline: none;
  font-family: sans-serif;
}
body {
  background-color: rgb(255, 255, 255);
}
section,
footer {
  padding: 54px 0;
}
h3 {
  font: 50px;
}
p {
  color: black;
}
.container {
  max-width: 1400px;
  margin: 0 auto;
  padding: 0 5%;
}
.btn {
  background-color: palegoldenrod;
        color: black;
        padding: 12px 20px;
        border-radius: 10px;
        cursor: pointer;
        display: inline-block;
        transition: 0.3s;
        border: none;
        font-weight: bold;
}
.btn:hover {
  background-color: rgb(127, 199, 127);
}
header {
  background-position: center;
  background-size: cover;
  background-attachment: fixed;
  height: 100vh;
}
main{
  flex:1;
}
nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding-top: 30px;
}
nav ul {
  display: flex;
  align-items: center;
}
nav ul a {
  color: white;
  margin: 0 10px;
  text-transform: uppercase;
  font-size: 14px;
  display: block;
}
nav img {
  width: 120px; /* diminui o tamanho da logo */
  top: 20px; /* distância do topo */
}
.banner {
  display: flex;
  justify-content: center;
}
.banner .banner-text {
  margin: 150px;
  text-align: center;
  padding: 0 90px;
}
.banner .banner-text h1 {
  font-size: 96px;
  color: rgb(90, 157, 90);
}
.banner .banner-text p {
  font-size: 20px;
  color: #d4fcd1;
  font-weight: lighter;
  margin: 18px 0;
}

/* === Seção Sobre === */
/* container principal (mantém o fundo verde) */
.sobre {
  background-color: grey;
  padding: 60px 0;
}

.sobre .container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

.sobre-conteudo {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
}

.sobre-texto {
  flex: 1 1 55%;
  color: #fff;
}

.sobre-texto h2 {
  font-size: 2rem;
  margin-bottom: 20px;
  font-weight: bold;
}

.sobre-texto p {
  line-height: 1.6;
  margin-bottom: 40px;
  text-align: justify; /* deixa o parágrafo mais alinhado */
}

.missao-visao {
  display: flex;
  justify-content: flex-start; /* alinha ao canto esquerdo */
  gap: 60px;
}

.info-item {
  flex: 1;
  text-align: left; /* texto alinhado à esquerda */
}

.info-item h3 {
  font-size: 1.4rem;
  margin-bottom: 15px;
  font-weight: bold;
  text-align: center; /* apenas o título centralizado */
}

.info-item p {
  line-height: 1.6;
  text-align: justify; /* texto justificado e alinhado */
}

.sobre-imagem {
  flex: 1 1 40%;
  display: flex;
  justify-content: center;
  margin-left: 40px; /* <-- afasta a imagem do texto */
}

.sobre-imagem img {
  width: 100%;
  max-width: 500px;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
}

/* Centralização vertical */
.sobre-conteudo {
  align-items: center;
}

.rodape {
  background-color: cadetblue;
  color: #ffffff;
  padding: 50px 20px 20px 20px;
  font-family: Arial, sans-serif;
}

.container-rodape {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  max-width: 1200px;
  margin: 0 auto;
  flex-wrap: wrap;
  gap: 30px;
}

.info-rodape h3 {
  font-size: 1.5rem;
  margin-bottom: 15px;
  color: white;
}

.info-rodape p {
  margin: 5px 0;
  font-size: 0.95rem;
}

.social-rodape h4 {
  font-size: 1.2rem;
  margin-bottom: 15px;
}

.icones a {
  font-size: 1.5rem;
  color: #ffffff;
  margin-right: 20px;
  text-decoration: none;
  transition: color 0.3s ease, transform 0.3s ease;
}

.icones a:hover {
  color: #7db881; /* cor de destaque */
  transform: scale(1.2); /* leve aumento no hover */
}

.copy-rodape {
  text-align: center;
  margin-top: 40px;
  font-size: 0.9rem;
  border-top: 1px solid #444;
  padding-top: 15px;
  color: #aaa;
}

@media (max-width: 768px) {
  .container-rodape {
    flex-direction: column;
    text-align: center;
    align-items: center;
  }

  .icones a {
    margin: 0 10px;
  }
}

    </style>
  </head>
  <body>
    <header style="background-image: url('imagens/banner.png')">
      <div class="container">
        <nav style="position: relative">
          <a href="index.html">
            <img
              src="imagens/logolojapng.png"
              alt="Logo"
            />
          </a>
          <ul class="ul">
            <a class="btn" href="produtos.html">Produtos</a>
            <a class="btn" href="sobre.html">sobre</a>
            <a class="btn" href="contato.html">contato</a>
            <a class="btn" href="politica-privacidade.html">Politica-Privacidade</a>
            <a class="btn" href="termos-servico.html">Termos de Serviços</a>
          </ul>
        </nav>
       
      </div>
      <!--final do container-->
    </header>
    <!--final do header-->
    <main>
    <section class="sobre">
      <div class="container">
        <div class="sobre-conteudo">
          <div class="sobre-texto">
            <h2>Bota De Couro Premium “Estilo & Classe”</h2>
            <p>
              Descubra o equilíbrio perfeito entre robustez e sofisticação com a Bota Couro Premium Estilo & Classe.
              Fabricada em couro legítimo de alta durabilidade, ela oferece conforto e elegância em cada passo. Seu design clássico com cadarços metálicos reforçados e solado resistente garante firmeza e estilo, ideal para o homem moderno que valoriza autenticidade e presença.
            </p>

            <div class="missao-visao">
              <div class="info-item">
                <h3>Destaques do produto</h3>
                <p>
                  Material:Couro legítimo premium<br>
                  Solado: Borracha antiderrapante
                  Fechamento: Cadarço reforçado
                  Cor: Marrom rústico elegante
                  Conforto interno com palmilha macia
                  Ideal para looks casuais e urbanos


                </p>
              </div>

              <div class="info-item">
                <h3>Visão</h3>
                <p>
                  Ser reconhecida como referência em sustentabilidade acessível
                  e em práticas que harmonizam crescimento econômico e
                  preservação ambiental.
                </p>
              </div>
            </div>
          </div>

          <div class="sobre-imagem">
            <img
              src="imagens/sapato.jpg"
              alt="Equipe GreenTech em reunião sobre sustentabilidade"
            />
          </div>
        </div>
      </div>
    </section>
  </main>
    <footer class="rodape">
      <div class="container-rodape">
        <div class="info-rodape">
          <h3>Estilo & Classe</h3>
          <p>Elegance 123 - Centro</p>
          <p>Cidade Estilus - BR</p>
          <p>styleclass@gmail.com</p>
        </div>

        <div class="social-rodape">
          <h4>Nos siga</h4>
          <div class="icones">
            <a href="#" aria-label="Facebook"
              ><i class="fa-brands fa-facebook-f"></i
            ></a>
            <a href="#" aria-label="Instagram"
              ><i class="fa-brands fa-instagram"></i
            ></a>
            <a href="#" aria-label="X"
              ><i class="fa-brands fa-x-twitter"></i
            ></a>
            <a href="#" aria-label="LinkedIn"
              ><i class="fa-brands fa-linkedin-in"></i
            ></a>
          </div>
        </div>
      </div>

      <div class="copy-rodape">
        <p>© 2025 Estilo & Classe. Todos os direitos reservados.</p>
      </div>
    </footer>
  </body>
</html>
