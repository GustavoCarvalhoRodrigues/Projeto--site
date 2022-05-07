# Projeto--site
Um site de notícia 
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon">
    <link rel="shortcut icon" href="imagens/favicon.ico" type="image/x-icon">
    <title>Wireframe</title>
    <style>
        *{
            margin: 0px;
            padding: 0px;
        }
       @font-face {
           font-family: 'BebasNeue';
           src: url('fontes/BebasNeue-Regular.ttf') format('opentype');
       }
        
        @font-face {
            font-family: 'IDroid',sans-serif;
            src: url('fontes/IDroid\ Bold.otf') format('opentype')
        }
        
        body{
             font-family:Arial, Helvetica, sans-serif;
             background-color: #83E1AD;
             font-size: 1em;
             width: 980px;
             
        }
        header{
            background-image: linear-gradient(to bottom  ,#2FA866,#063D1E);
            width: 1980px;
            padding: 20px;
            
            
            
        }
        header > h1{
            font-family: 'BebasNeue',cursive;
            color:rgba(255, 255, 255, 0.938);
            text-align: center;
            text-shadow: 1px 1px 0px  black;
            margin-right: 780px;
            padding: 20px;
        }
        header > p{
            text-align: center;
            color: rgba(255, 255, 255, 0.61);
            margin-right: 770px;
        }
         nav > a{
           margin-right: 0px;
            padding: 15px;
            text-decoration: none;
            color: white;
            text-shadow: 1px 1px 2px black;
            
            
         }
         
         main{
            background-color: white;
            min-width: 400px;
            max-width: 700px; 
            margin-left: 220px;
            padding: 30px;
            
            
         }

         main > article > h1{
             font-family: 'IDroid',sans-serif;
             color: #063D1E;
            
             }
             main > p{
                 padding: 45px;
             }
             img{
                 width: 680px;
             }
             p{color: black;
                 line-height: 1.2em;
                 
             }
              article > h2{
                 font-family: 'IDroid',
                 sans-serif;
                 color: #063D1E;
                 background-color: #83e1ad2c;
                 box-shadow: inset 1px 2px 3px 9px #83E1AD;
                 
             }
             span{
                 color: #063D1E;
                 font-weight: bold;
             }
            div.video{
                 position: relative;
                 background-color: #063D1E;
                 height: 0px;
                 margin-left: -20px;
                 margin-right: -20px;
                 margin-bottom: 15px;
                 padding-bottom: 59%;
                 }
                 div.video > iframe{
                     position: absolute;
                     top: 5%;
                     left: 5%;
                     width: 90%;
                     height: 90%;
                 }
              h4.extra{
                 background-color: #2FA866;
                 padding: 10px;
                 margin: 15px auto 5px auto;
                 color: white;
                 border-radius: 6px;
                 
                }
               section{
                   background-color: #caf8f2;
                   border-radius:6px;
                   height: 350px  ;
                   box-shadow: 1px 1px 1px 0px turquoise;
               }
             
               
               ul{
                  list-style-type: '\2714\0020\0020';
                  columns: 2;
                  list-style-position: inside;
              }

              footer{color: white;
                  text-align: center;
                  background-color: #063D1E;
                  padding: 5px;
                  margin-top: 10px;
                  width: 2020px;
                    
              }
    </style>
</head>
<body>
    <header>
        <h1>CURIOSIDADES DE TECNOLOGIA</h1>
        <p>Tudo aquilo que você sempre quis saber sobre o mundo <br> 
        Tech, em um único lugar. </p>
    
    <nav>
        <a href="#">Home</a>
        <a href="#">Notícias</a>
        <a href="#">Curiosidades</a>
        <a href="#">Fale Conosco</a>
    </nav>
</header>
    <main>
        <article>
        <h1>História do  mascote do android</h1>
        <p>Provavelmente você sabe que o sistema operacional <span>Android</span>, mantido pelo <span>Google</span> é um dos mais utilizados para dispositivos móveis em todo o mundo.Mas talvez você não saiba que o seu simpático mascote tem um nome e uma história muito curiosa?Pois acompanhe esse artigo para aprender muita coisa sobre esse robozinho.</p>
        <h2>a primeira versão</h2>
        <p>A primeira tentativa de criar um mascote surgiu em 2007 e veio de um desenvolvedor chamado<span> Dan Morill</span> &#x003B8;. Ele conta que abriu o <span>Inkscape</span> &#x003B8;(software livre para vetorização de imagens) e criou sua própria versão de robô. O objetivo era apenas personificar o sistema apenas para a a sua equipe, não existia nenhuma solicitação da empresa para a criação de um mascote. </p>
        <img src="imagens/dan-droids.png" alt="dan-droids">
        <p>Essa primeira versão bizarra até foi batizada em homenagem ao seu criador: seriam os Dandroids.</p>
        <h2 class="mascote">Surge um novo mascote</h2>
        <p>A ideia de ter um mascote foi amadurecendo e a missão foi passada para uma profissional da área. A ilustradora Russa <span>Irina Blok</span> &#x003B8;, também funcionária do Google, ficou com a missão de representar o pequeno robô de uma maneira mais agradável.</p>
        <img src="imagens/irina-blok.jpg" alt="irina">
        <p>A ideia principal da Irina era representar tudo graficamente com poucos traços e de forma mais chapada. O desenho também deveria gerar identificação rápida com quem o olha. Surgiu então o <span>Bugdroid</span>, o novo mascote do Android.</p>
        <img src="imagens/bugdroid.png" alt="bugdroid">
        <p>A principal inspiração para os traços do novo Bugdroid veio daqueles bonequinhos que ilustram portas de banheiro para indicar o gênero de cada porta. Conta a lenda que a artista estava criando em sua mesa no escritório do Google e olhou para o lado dos banheiros e a identificação foi imediata: simples, limpo, objetivo.</p>
        <div class="video">
        <iframe  width="695" height="315" src="https://www.youtube.com/embed/l2UDgpLz20M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    </article>
    <section>
    <h4 class="extra">Quer aprender mais?</h4>
    <p>Outro assunto curioso em relação ao Android é que cada versão sempre foi nomeada em homenagem a um doce, em ordem alfabética a partir da versão 1.5 até a 9.0.</p>
    <aside>
    <ul>
        <li> ✔1.5-Cupcake</li> 
        <li> ✔1.6-Donut</li>                              
        <li> ✔3.0-Eclair</li>                             
        <li> ✔2.2-Froyo</li>
        <li> ✔2.3-Gingerbread</li>
        <li> ✔3.0-Honeycomb</li>
            <li> ✔4.0-Ice Cream Sandwich<li>
            <li> ✔4.1-Jelly Bean</li>
            <li> ✔4.4-KitKat</li>
            <li> ✔5.0-Lolipop</li>
            <li> ✔6.0-Marshmallow</li>
            <li> ✔7.0-Nougat</li>
            <li> ✔8.0-Oreo</li>
            <li> ✔9.0-Pie</li>
            
        </ul>
        </aside>
    <p>Infelizmente, o Android Q não existiu, pois o Google resolveu pôr fim a essa divertida prática e começou a usar numerações, o que deu origem ao Android 10.</p>
    <p>Acesse aqui o site <span>Android History</span> &#x003B8; para conhecer a sequência das versões "adocicadas" e o que cada uma trouxe para o sistema Android.</p>
</section>
    <p>Então é isso! Espero que você tenha gostado do nosso artigo com essa curiosidade sobre o sistema Android e seu simpático mascote.</p>
</main>
   <footer>
    Site criado por Gustavo Carvalho estudante do CursoemVideo.
   </footer>
    </body>
</html>
