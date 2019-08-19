# Agamer
<!DOCTYPE ...>
<head>
  <style>
    body{
      text-align: center;
    }
        .heart {
       background-color: red;
       display: inline-block;
       height: 50px;
       margin: 50px 10px;
       position: relative;
       top: 0;
       transform: rotate(-45deg);
       /*position: absolute;
       left: 45%; top: 45%;*/
       width: 50px;
     }
     
     .heart:before,
     .heart:after {
       content: "";
       background-color: red;
       border-radius: 50%;
       height: 50px;
       position: absolute;
       width: 50px;
     }
     
     .heart:before {
       top: -25px;
       left: 0;
     }
     
     .heart:after {
       left: 25px;
       top: 0;
     }
     @keyframes heartbeat {
       0% {
         transform: scale( 1 );    
       }
       20% {
         transform: scale( 1.25 ) 
           translateX(5%) 
           translateY(5%);
       } 
       40% {
         transform: scale( 1.5 ) 
           translateX(9%) 
           translateY(10%);
       }
     }
     .heart {
       animation: heartbeat 1s infinite; // our heart has infinite heartbeat :)
     }

     #opener {
      color:gold;
    }
      #treesome{
       color: aquamarine;
     }
      #freedom{
       color: chartreuse;
     }
      #lovely{
       color: rgb(135, 21, 170);
     }
      #Button{
      color: forestgreen;
    }
      .cool{
      color: magenta; 
    }
      .nice{
      color: beige;
    }
  </style>
</head>

<body>
  <main>
    <h1 id = 'opener'>Welcome to my website.Hello,I am Agamer. I am a very POPULAR YOUTUBER</h1>
    <h2 id="treesome">Would you want to see my kitten named Hope. Well here he is.</h2>
    <a href='#'><img src="https://bit.ly/fcc-relaxing-cat"  alt="My cat Fluffy."></a>
    <h2 id="freedom">How do you think he looks and do you have a kitten or cat.</h2>
      <label for="Cat">
        <input type="text" placeholder="He looks cool.">
        <button type="submit" id="Button">Submit</button>
        <input id="Cat" type="radio" name="Cat-Kitten">Cat
      </label>
      <label for="Kitten">
          <input id="Kitten" type="radio" name="Cat-Kitten">Kitten
      </label>
    <div id="lovely">
    To show my love to my veiwers,here is my heart.
    </div>
    <div class="heart"></div>
  </main>
</body>
