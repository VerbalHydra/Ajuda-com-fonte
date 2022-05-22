# Ajuda-com-fonte
Estou tendo dificuldades para colocar uma fonte diferenciada no meu código, tentei de tudo e não consegui.
<!DOCTYPE html>
<html lang="pt-br">
	<head>
		<meta name="viewport" content="width=device-width">
		<meta charset="utf-8">
		<title>Academia</title>	
		<link rel="stylesheet" href="reset.css">
		<link rel="stylesheet" href="style.css">
		<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
		<link href="https: //fonts.googleapis.com/css2? family= Montserrat:wght@100 & display=swap" rel="stylesheet">
		<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
		<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
	</head>
	<body>
		
		<header>

			<div class="caixa">
				<h1> <img class="imagem-titulo" src="fundo1.png" alt="Logo da Academia"></h1>
			<nav>
				<p class="nome">Mestre Totti - Centro Cultural de Artes Marciais</p>
			</nav>
			</div>
	
		</header>
			
		<main>
			<section>
				<div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
				  <div class="carousel-inner">
				    <div class="carousel-item active">
				      <img src="teste1.jpg" class="d-block w-100" alt="...">
				    </div>
				    <div class="carousel-item">
				      <img src="" class="d-block w-100" alt="...">
				    </div>
				    <div class="carousel-item">
				      <img src="" class="d-block w-100" alt="...">
				    </div>
				  </div>
				  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
				    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
				    <span class="visually-hidden">Previous</span>
				  </button>
				  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
				    <span class="carousel-control-next-icon" aria-hidden="true"></span>
				    <span class="visually-hidden">Next</span>
				  </button>
				</div>
			</section>
		    
		    <section>
				<div>
					<h1 class="principal">Sobre a Academia</h1>
					
					<p class="principal">Pratique um novo conceito em artes marciais o Kung Fu, Taichi Chuan, Chikung a Yoga Taoista junto com a meditação.</p>

					<p class="principal">São as únicas artes marciais que, praticadas em conjunto, levam o praticante ao encontro da Excelência do Ser, unificando corpo, mente e alma, equilibrando totalmente a saúde.</p>

				</div>
			</section>

			<section class="mapa">
				<h2 class="titulo-principal">Nossa localização</h2>	
				
			<div class="mapa-conteudo">
				<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3672.2692787404894!2d-45.56559438255614!3d-23.013883099999987!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x94ccf852b66c9c49%3A0xe3b7bb430adbdee6!2sCENTRO%20CULTURAL%20DE%20ARTES%20MARCIAIS%20MESTRE%20TOTTI!5e0!3m2!1spt-BR!2sbr!4v1650896700621!5m2!1spt-BR!2sbr" width="100%" height="400" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
			</div>
			
			</section>

			<section>
				<div class="beneficios">
					<h3 class="titulo-principal">Benefícios de se treinar Kung Fu</h3>
			
					<ul class="lista-beneficios">
						<li class="itens">Controle do peso corporal</li>
						<li class="itens">Melhor mobilidade articular</li>
						<li class="itens">Melhor resistência física</li>
						<li class="itens">Aumento da densidade óssea</li>
						<li class="itens">Melhor força muscular</li>
						<li class="itens">Diminuição da pressão arterial</li>
						<li class="itens">Melhor flexibilidade</li>
					</ul><img class="imagem-beneficios" src="beneficios.jpg" alt="Imagem sobre beneficios do Kung Fu">
				</div>
		    </section>
		</main>

		<footer>
			<p>Também estamos aqui</p>
			<a href="https://www.facebook.com/354048337997302/posts/5080273342041421/"><img class="icone" src="facebook.png"></a>
			<a href="https://instagram.com/mestretotti?igshid=YmMyMTA2M2Y="><img class="icone" src="instagram.jpg"></a>
			<img class="icone" src="tiktok.png">
			<img class="icone" src="whatsApp.jpg">
		</footer>
		












			<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
			<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
		</body>

  
  
  
  
  
  
  
  
  //PARTE CSS
  
  body{
	font-family: 'Montserrat', sans-serif;
}

.caixa{
	position: relative;	
	margin: 0 auto;	
	background: #CCCCCC;
	padding: 0 2em;
}

.imagem-titulo{
	width: 20%;
	margin: 20px auto;
}

.titulo-principal{
	text-align: center;
	font-size: 20px;
	clear: left;
	padding: 1em 0;
}

.nome{
	font-size: 25px;
	font-weight: bold;
	padding: 20px;
	margin-right: 4em;
}

nav{
	position: absolute;
	top: 110px;	
	right: 310px;
}

.principal{
	text-align: center;
	padding: 1em 0 0 0;
	margin: 0 auto;
	background: #FF0000;
}

section h1{
	border-radius: 10px;
	border-style: solid;
	border-width: 5px;
}

main{
	margin: auto;
}

.mapa{
	padding: 3em 0;
	background: linear-gradient(#FF0000,#FFD700); 
	margin: 0 auto;
}

.mapa-conteudo{
	width: 1200px;
	margin: 0 auto;
}

.imagem-beneficios{
	width: 45%;
	opacity: 1;
	box-shadow: 10px 10px 10px #000000;
	margin: 0 auto;
}

.imagem-beneficios:hover{
	opacity: 1;
	transition: 400ms;
}

.lista-beneficios{
	display: inline-block;
	margin: 0 30px 0 0 ;
	vertical-align: top;
}

.beneficios{
	margin: 0 auto;
	padding: 50px 295px;
	background: #FFD700;
}

.itens{
	line-height: 2em;
}

.itens:before{
	content: "★";
}

footer{
	background: #FFFFFF;
}

footer p{
	text-align: center;
	text-transform: uppercase;
	background: #FFD700;
	border-style: solid;
	border-width: 2px;
}

.icone{
	width: 100px;
	height: 100px;
	margin: 0 10px;
	background: #FFFFFF;
	display: block;
}
