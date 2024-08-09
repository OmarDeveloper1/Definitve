<!DOCTYPE HTML>
<html>
  <head>
    <meta charset="utf-8">
    <link rel="icon" href="https://cdn-icons-png.flaticon.com/512/1092/1092254.png">
    
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Edu+AU+VIC+WA+NT+Hand:wght@400..700&display=swap');
#body{
  font-family: "Edu AU VIC WA NT Hand", cursive;
  font-optical-sizing: auto;
  font-style: normal;
  background-image: url('https://img1.wallspic.com/crops/5/3/4/6/7/176435/176435-tabla-ambiente-ecorregion-afterglow-luz-2250x4872.png');
  background-size: cover;
  background-repeat: no-repeat;
  color: whitesmoke;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body, html{
  width: 100%;
  overflow-x: hidden;
}

#header-div{
  background-image: url("https://wallpapercave.com/wp/wp4566581.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  color: whitesmoke;
  padding: 10px;
  width: 100%;

}

.ul-options{
  display: flex;
  justify-content: space-around;
  align-items: center;
  align-content: center;
  width: 100%;
  
}
.list{
  list-style: none;
  padding: 12px;
  width: 40%;
  margin-left: -15px;
  border-radius: 15px;
}

.list:hover{
  background: purple;
  color: lime;
  transform: scale(1.2);
  transition: 0.3s;
  display: inline;
}

.list a{
  color: whitesmoke;
  text-decoration: none;
}

.tecno{
  display: flex;
  align-items: center;
  justify-content: space-around;
  margin: auto;
  flex-wrap: wrap;
}

.tecno img{
  width: 90px;
  height: 96px;
  text-align: center;
  justify-content: center;
  align-items: center;
  margin-left: 1rem;
}

.tecno div:hover{
  transform: scale(1.2);
  transition: 0.2s;
  box-shadow: 4px 4px 8px cyan;
  color: lightblue;
  border-radius: 0 19px 0 19px;
  padding: 7px;
}

section h2{
  text-align: center;
  margin-bottom: 40px;
  margin-top: 60px;
}

#proyectos{
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  word-break: break-all;
}

.pry{
  width: 30%;
}

.pry img{
  height: 30%;
  width: 100%;
  border-radius: 30px 30px 0 0;
}

#contact{
  margin-top: 50px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-image: url('https://p4.wallpaperbetter.com/wallpaper/647/427/643/landscape-desktop-downloads-wallpaper-preview.jpg');
  background-size: cover;
  background-repeat: no-repeat;
  padding: 18px;
  margin-bottom: 50px;
}
#contact h1{
text-align: center;
backdrop-filter: blur(4px);
}

.aside{
  width: 38%;
  word-break: break-all;
  margin-bottom: 40px;
  backdrop-filter: blur(4px);
}

footer{
  position: fixed;
  bottom: 0;
  left: 0;
  background: black;
  width: 100%;
  text-align: center;
}

#div-cor{
  align-items: center;
  justify-content: center;
  width: 60%;
  backdrop-filter: blur(4px);
}

#div-cor input{
  width: 80%;
  margin-left: 40px;
  margin-bottom: 10px;
  
}

#textarea{
  margin-left: 40px;
  width: 80%;
}

#btn-send{
  text-align: center;
  margin-left: 40%;
  margin-right: 60%;
  font-size: 20px;
  padding: 6px;
  border-radius: 15px;
  width: auto;
}

#btn-send:hover{
  background: black;
  color: whitesmoke;
  border: solid 2px orangered;
}
    </style>
  </head>
  <body id="body">
    <div id="header-div">
      
      <div class="div-name">
        <h1>Omar  Mercado</h1>
      </div>
      
      <div class="options">
        <ul class="ul-options">
          <li class="list">Home</li>
          <li class="list"><a href="#tech">Tecnologies</a></li>
          <li class="list"><a href="#proyectoss">Experience</a></li>
          <li class="list"><a href="#contact">Contact</a></li>
        </ul>
      </div>
      
      <div id="description">
        <p>Welcome to my page 100% responsive</p>
      </div>
    </div>
    
    <section>
      <h2 id="tech">Tecnologies</h2>
      <div class="tecno">
        
         <div>
           <img src="https://cdn.icon-icons.com/icons2/1488/PNG/512/5352-html5_102567.png">
           <h3>HTML5</h3>
           </div>
           
           <div>
             <img src="https://cdn.icon-icons.com/icons2/2107/PNG/512/file_type_css_icon_130661.png">
           <h3>CSS3</h3>
           </div>
           
           <div>
             <img src="https://cdn.icon-icons.com/icons2/2108/PNG/512/javascript_icon_130900.png">
           <h3>Jscript</h3>
         </div>
         
      </div>
      
      <div class="tecno" style="margin-top: 30px;">
      
        <div>
          <img src="https://cdn.icon-icons.com/icons2/2415/PNG/512/bootstrap_plain_logo_icon_146619.png">
          <h3>Bootstrap</h3>
        </div>
        
        <div>
          <img src="https://cdn.icon-icons.com/icons2/2107/PNG/512/file_type_tailwind_icon_130128.png">
          <h3>Tailwind</h3>
        </div>
        
        <div>
          <img src="https://cdn.icon-icons.com/icons2/2415/PNG/512/react_original_logo_icon_146374.png">
          <h3>React Js</h3>
        </div>
        
      </div>
    </section>
    
    <section>
      <h1 style="text-align: center; width: 100%; margin-top: 10rem;" id="proyectoss">Experience</h1>
      <br>
      
      <div id="proyectos">
      <div class="pry">
        <img src="https://ae01.alicdn.com/kf/Sdce6d277dff84d96b71f572d2e8fe1a8E.jpg_640x640Q90.jpg_.webp">
        <h4>Calculator</h4>
      </div>
      <div class="pry">
        <img src="https://i.blogs.es/ae0447/snake/375_375.jpeg">
        <h4>Snake Game</h4>
      </div>
      <div class="pry">
        <img src="https://http2.mlstatic.com/D_NQ_NP_751356-MLA70813155660_082023-O.webp">
        <h4>Instrumental Shop</h4>
      </div>
      </div>
      
    </section>
    
     <h1 style="text-align: center; width: 100%; margin-top: 10rem;">Contact</h1>
    <section id="contact">
     
      
      <div class="aside">
        <h4 >Email</h4>
        <p>omarmercado0112@gmail.com</p>
        
        <h4>Whatsapp</h4>
        <p>(+57) 302 285 9306</p>
        
        <h4>City</h4>
        <p>Barranquilla - Colombia</p>
      </div>
      
      <div id="div-cor">
        <input type="email" name="" id="" value="" placeholder="Write your email adress"/>
        <input type="text" name="" id="" value="" placeholder="topic"/>
        <br>
        <textarea name="" id="textarea" rows="8" cols="20" placeholder="Explain"></textarea>
        <br>
          <button id="btn-send">Send message</button>
      </div>
      
    </section>
    
    <footer>
      <p>Designed by Omar Mercado®</p>
    </footer>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/5.3.0/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
