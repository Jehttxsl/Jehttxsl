<!DOCTYPE html>
<html lang="pt-BR">

<head>
   <meta charset="UTF-8">
   <title>Card de Usuário - @Jehttxsl</title>
   <link rel="stylesheet" href="./style.css">
 <style>
@import url(https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600&display=swap);

body {
  background-color: #212123;
}
.conteudo {
  display: grid;
  font-family: Open Sans, sans-serif;
  height: 100vh;
  place-items: center;
}
.conteudo .card {
  box-shadow: 10px 7px 20px orange;
  justify-content: center ;
  align-items: center ;
  position: absolute;
  font-family: Arial, Helvetica, sans-serif;
  top: 40%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: rgba(255, 255, 255, .1);
  background: linear-gradient(to right,
      rgb(76, 217, 105),
      rgb(52, 170, 220),
      rgb(88, 86, 217),
      rgb(255, 45, 83),
      rgb(255, 45, 83),
      rgb(88, 86, 217),
      rgb(52, 170, 220),
      rgb(76, 217, 105));
  background-size: 400%;
  -webkit-background-clip: text;
  background-clip: text;
  font-weight: 700;
  font-size: 2em; /* Reduzido de 10em para 3em */
  text-align: left;
  animation: sTransition 10s linear infinite;
  
}

@keyframes sTransition {
  0% {
    background-position: 0%;
  }
  100% {
    background-position: 400%;
  }
}

  </style>

.conteudo .card .cabecalho {
  background: #efefef;
  height: 100px;
  border-top-right-radius: 10px;
  border-top-left-radius: 10px;
  background-image: url(/cod/360_F_562024161_tGM4lFlnO0OczLYHFFuNNdMUTG9ekHxb.jpg);
  background-position: center;
  background-size: cover;
}
.conteudo .card .corpo {
  filter: drop-shadow(10px 7px 10px oragen);
  display: flex;
  flex-direction: column;
  font-size: 15px;
}
.conteudo .card .corpo .img__usuario {
  align-self: center;
  border: 5px solid royalblue;
  border-radius: 50%;
  margin-top: -45px;
  max-width: 80px;
}
.conteudo .card .corpo .nome,
.conteudo .card .corpo .tipo {
  align-self: center;
  margin: 0;
}
.conteudo .card .corpo .nome {
  color: #efefef;
}
.conteudo .card .corpo .redes__sociais {
  display: grid;
  grid-template-rows: repeat(3, 35px);
  justify-content: center;
  margin-top: 1rem;
  height: 200px;
  width: 300px;
}
.conteudo .card .corpo .redes__sociais a {
  align-items: center;
  color: #959595;
  display: flex;
  font-size: 0.8rem;
  text-decoration: none;
  transition: all 0.3s ease;
}
.conteudo .card .corpo .redes__sociais a:hover {
  -webkit-transform: scale(1.1);
  transform: scale(1.1);
}
.conteudo .card .corpo .redes__sociais a img {
  margin-right: 5px;
  width: 30px;
}

</head>

<body>
   <div class="conteudo">
      <article class="card">
         <section class="cabecalho"></section>
         <section class="corpo">
            <img src="background.png" alt="Imagem programador.cs"
               class="img__usuario" />
            <h2 class="nome">Dev_Jessi</h2>
            <p class="tipo">Programadora Back-end</p>
            <section class="redes__sociais">
               <a href="https://www.instagram.com/_jessii.xz?igsh=ODZ1Znlsd2dyMHg2">
                  <img src="https://img.icons8.com/3d-fluency/344/instagram-new.png" alt="Logo Instagram" />
                  instagram.com/_jessii.xz
               </a>
               <a href="https://github.com/Jehttxsl">
                  <img src="https://img.icons8.com/3d-fluency/344/github.png" alt="Logo Github" />
                  github.com/Jehttxsl
               </a>
               <a href="https://wa.me/+5581989664642?text=Ol%C3%A1%2C%20tudo%20bem%3F
" target="_blank">
                  <img src="https://img.icons8.com/?size=100&id=16713&format=png&color=000000" alt="Logo Whats" />
                  Whatsapp.com/Jessi
               </a>
            </section>
         </section>
      </article>
   </div>
</body>

</html>