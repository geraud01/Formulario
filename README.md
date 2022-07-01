<!DOCTYPE html>
<html lang="pt-br">
	<head>
		<title>Fale conosco</title>
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width, initial-scale=1">

	</head>
	<body>

		<header>
			<h2> Fale Conosco </h2>
		</header>

		<section>

			<nav>
				<ul>
					<li><a href="#home">Home</a></li>
					<li><a href="#sobre">Sobre</a></li>
					<li><a href="./06-formularios.html">Contato</a></li>
               <link rel="stylesheet" type="text/css" href="./STYLE.CSS"> 
				</ul>
			</nav>

			<article>

				<h1>Contato</h1>    
                <p>Preencha os campos Abaixo</p>
                
                <form method="post">
                    <div>
                        <label for="nome">Nome</label><br>
                        <input type="text" name="name" id="nome" placeholder="Digite o seu nome">
                    </div>                    
                    <div>
                        <label for="email">E-mail</label><br>
                        <input type="email" name="email" id="email" placeholder="Digite o seu email">
                    </div>
                    <div>
                        <label for="mensagem">Mensagem</label><br>
                        <textarea type="mensagem" name="mensagem" id="mensagem" rows="5" placeholder="Digite a sua mensagem"></textarea>
                    </div>  
                   
                    <div>
                        <p>
                        <label>Quais linguagens você sabe?</label><br>
                        <input type="radio" name="linguagens"> HTML
                        <input type="radio" name="linguagens"> CSS
                        <input type="radio" name="linguagens"> JavaScript
                        </p>
                    </div>  
                   
                    <div>
                        <p>
                        <label>Qual linguagem você prefere? </label><br>
                        <input type="checkbox" name="linguagens"> HTML
                        <input type="checkbox" name="linguagens"> CSS
                        <input type="checkbox" name="linguagens"> JavaScript
                        </p>
                    </div>                    
                    <div>
                        <label> Qual é a sua cor favorita?</label>
                        <select>
                            <option value="Azul">Azul</option> 
                            <option value="vermelho">Vermelho</option> 
                            <option value="verde">Verde</option> 
                            <option value="escolha"selected>Escolha</option> 
                        </select>
                    </div>
                     <div> 
                     <p>
                        <label>Pronto para enviar?</label>
                        </p>
                        <input type="submit">
                    </div>
                </form>
	
			</article>
		</section>
		<footer>
			<p>Desenvolvido por Geraud</p>
		</footer>
		
	</body>
</html>
