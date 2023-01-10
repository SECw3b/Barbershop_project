<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="shortcut icon" href="fav.ico" type="image/x-icon">
    <style>
        nav {
            display: flex;
            justify-content: center;
            background-color: #f1f1f1;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            overflow: hidden;
            display: flex;
        }

        nav li {
            float: left;
        }

        nav a {
            display: block;
            color: #000;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }

        nav a:hover {
            background-color: #ddd;
            color: #000;
        }

        h1{
            font-family: sans-serif;
            text-align: center;
        }
        a{
            color: black;
        }
        h2:hover{
            transform: scale(1.1);
        }
        h2{
            font-family: sans-serif;
            text-align: center;
        }
        p{
            font-family: sans-serif;
            text-align: center;
        }
        img:hover {
            transform: scale(1.1); 
        }
        .img-container {
            /*box-shadow: horizontal vertical blur spread color;
            box-shadow: 2px 2px 5px 0px rgba(0, 0, 0, 0.2);
            transition: transform 0.5s ease; 
            filter: drop-shadow(2px 2px 5px rgba(0, 0, 0, 0.2));*/
            margin-left: 140px;
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            grid-gap: 15px; 
            justify-content:end; 
            align-items: center; 
        }
        h3{
            font-family: sans-serif;
            text-align: center;
        }
        h4{
            font-family: sans-serif;
            text-align: center;
        }
        h5{
            font-family: sans-serif;
            text-align: center;
        }
        address{
            text-align: center;
        }
        hr {
            color: #000;
            width: 100%; 
            height: 2px; 
        }
    </style>

</head>
<body>
    <nav>
        <ul>
          <li><a href="file:///C:/Users/Usuario/Desktop/HTML/index5.html">Home</a></li>
          <li><a href="#about">Sobre</a></li>
          <li><a href="#services">Serviços</a></li>
          <li><a href="#contact">Contato</a></li>
        </ul>
      </nav>
      
    <h1><a href="file:///C:/Users/Usuario/Desktop/HTML/index5.html">HOME</a></h1>
    <h2><a href="https://www.google.com" target="_blank">Agende Seu Horário</a></h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet error, sit autem culpa molestiae eligendi eveniet fugit nam nostrum quod,<strong> neque inventore </strong>, hic nesciunt quam nemo odio accusantium optio cum.</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum, illum sunt! Esse, culpa. Error cumque velit minus assumenda aliquid! Nemo saepe eveniet porro amet quidem omnis incidunt, laborum labore ex?</p>

    <div class="img-container">

        <img src="maquinas_barber.jpg" alt="maquinas_barber">
        <img src="navalha.jpg" alt="navalha">
        <img src="twobarbers.jpg" alt="twobarbers">
    </div>
          
    <h3>Sobre</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate eius deleniti suscipit aperiam officiis eaque consequatur dicta consectetur amet repellendus labore deserunt libero sapiente sunt esse iste placeat, atque provident.</p>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Et hic eveniet illo beatae non quam! Ipsa qui atque officiis similique quis illo voluptates, itaque minus explicabo. Beatae voluptatibus in magnam.</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui reiciendis unde vero laudantium tenetur veritatis debitis rem rerum ipsum porro quidem deleniti possimus, fugiat quisquam, maxime voluptatibus dicta nesciunt similique.</p>

    <h4>Serviços</h4>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Optio ut totam nobis atque, beatae consequatur in quos, fugiat amet aliquid voluptates quia nemo recusandae reprehenderit velit est, minima quo consectetur.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eveniet ab fugiat facilis, culpa fugit amet asperiores voluptate nulla perferendis dolore voluptatibus molestiae nobis ipsa accusantium rerum tenetur, dolorum porro incidunt?</p>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Tenetur vel velit saepe earum accusamus quod possimus eveniet explicabo repellendus ipsa blanditiis beatae distinctio non voluptatibus nemo, quia ipsum, eaque totam?</p>

    <h5>Contato</h5>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. A dignissimos quo aperiam quas fugit soluta facilis doloremque voluptates? Exercitationem recusandae laboriosam quae dolorem numquam repellat a iusto provident magni sit?</p>
    <footer>
        <hr>
        <p>Copyright ©2021 Meu Site</p>
        <address> 
            <ol>
                <li>Jacarezinho, PR</li>
                <li>luan12carvalho@gmail.com</li>
            </ol>
    </footer>
    </address>
</body>
</html>
