<!DOCTYPE HTML> <!-- Declara o tipo de documento como HTML5 -->

<html> <!-- Inicia o elemento <html>  -->

<head><!-- Início do elemento <head>, que contém metadados e informações importantes sobre a página -->
	<title>Currinculum by HTML5 UP</title>
	<!-- Define o título da página como "Miniport by HTML5 UP", que aparece na aba do navegador -->
	<meta charset="utf-8" />
	<!-- Define a codificação de caracteres para UTF-8, que suporta acentos e caracteres especiais -->
	<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no" />
	<!-- Define as configurações da viewport para dispositivos móveis. "width=device-width" ajusta a largura da página para corresponder à largura da tela do dispositivo, "initial-scale=1" define o nível de zoom inicial como 1 (sem zoom), e "user-scalable=no" desativa a possibilidade do usuário dar zoom na página. -->
	<link rel="stylesheet" href="assets/css/main.css" />
	<!-- Link para o arquivo de estilo externo (CSS) localizado em "assets/css/main.css" -->
</head><!-- Inicia o elemento <html>  -->

<body class="is-preload"><!-- inicia a tag body (corpo) que representa o conteúdo de uma página e contém uma class -->

	<!-- Nav -->
	<nav id="nav">
		<!-- Inicia o elemento <nav>, que representa uma seção de navegação na página. O atributo id="nav" é usado para identificar e estilizar essa seção. -->
		<ul class="container">
			<!-- Inicia uma lista não ordenada <ul> que contém os itens de navegação. O atributo class="container" pode ser usado para estilizar a lista com CSS. -->
			<li><a href="#top">Topo</a></li>
			<!-- Cria um item de lista <li> com um link <a> que, quando clicado, leva o usuário para a seção com o id="top" na mesma página. O texto exibido é "Top". -->
			<li><a href="#work">Trabalhos</a></li>
			<!-- Cria outro item de lista <li> com um link <a> para a seção com o id="work". O texto exibido é "Work". -->
			<li><a href="#portfolio">Portfolio</a></li>
			<!-- Cria um item de lista <li> com um link <a> para a seção com o id="portfolio". O texto exibido é "Portfolio". -->
			<li><a href="#contact">Contatos</a></li>
			<!-- Cria um item de lista <li> com um link <a> para a seção com o id="contact". O texto exibido é "Contact". -->
		</ul><!-- Finaliza a lista não ordenada -->
	</nav> <!-- Finaliza o elemento <nav> de navegação -->
	<!-- Home -->
	<article id="top" class="wrapper style1">
		<!-- Inicia o elemento <article>, que é usado para representar uma seção independente ou um conteúdo autossuficiente. O id "top" é dado à seção para identificá-la, enquanto as classes "wrapper" e "style1" são aplicadas para estilizar a seção, provavelmente com regras CSS. -->
		<div class="container">
			<!-- Cria uma <div> com a classe "container", geralmente usada para centralizar o conteúdo e adicionar espaçamento. -->
			<div class="row">
				<!-- Inicia uma <div> com a classe "row", que é utilizada para organizar colunas dentro de uma linha (método comum de layout em frameworks CSS como Bootstrap). -->
				<div class="col-4 col-5-large col-12-medium">
					<!-- Inicia uma coluna com diferentes larguras para diferentes tamanhos de tela: "col-4" para telas pequenas, "col-5-large" para telas grandes e "col-12-medium" para dispositivos médios. -->
					<span class="image fit">
						<!-- A tag <span> com a classe "image fit" é usada para ajustar a imagem ao tamanho do contêiner. -->
						<img src="images/eu1.jfif" alt="" />
						<!-- Exibe uma imagem localizada em "images/pic00.jpg". O atributo "alt" está vazio, mas normalmente é usado para descrever a imagem. -->
					</span>
				</div>
				<div class="col-8 col-7-large col-12-medium">
					<!-- Inicia uma outra coluna com larguras adaptativas para diferentes tamanhos de tela, sendo 8 partes da largura para telas pequenas, 7 partes para grandes e 12 partes para médias. -->
					<header> <!-- Inicia o cabeçalho da seção com o nome "header". -->
						<h1> <strong>Gabriel Marcos</strong>.</h1>
						<!-- Exibe um título principal "Hi. I'm Jane Doe", com o nome "Jane Doe" em negrito. -->
					</header>
					<p>
						<!-- Exibe um parágrafo que descreve brevemente o projeto e menciona os criadores do template. -->
						Sou estudante de <strong><a class="noLink" color: #43B3E0;
								href="https://www.iesp.edu.br/cursos/graduacao/sistemas-para-internet">Sistemas para
								Internet</a></strong>, apaixonado por
						tecnologia e em constante busca por aprimoramento pessoal e profissional. Seja bem vindo!
						<!-- Descrição sobre o template Miniport, com links para o criador AJ, o site HTML5 UP e a licença CCA. -->
					</p>
					<a href="#work" class="button large scrolly">Saiba mais sobre mim.</a>
					<!-- Cria um link (botão) que, quando clicado, leva o usuário para a seção com o id "work". O texto exibido é "Learn about what I do". -->
				</div>
			</div>
		</div>
	</article>
	<!-- Finaliza o elemento <article>, que encapsula um conteúdo autossuficiente, como uma introdução ao projeto. -->

	<!-- Work --> <!-- Comentário indicando que a seção seguinte é sobre "Trabalho" ou "Work" -->

	<article id="work" class="wrapper style2">
		<!-- Inicia a seção <article> com o id "work", usado para identificar essa seção. As classes "wrapper" e "style2" são aplicadas para definir estilos e estrutura da seção. -->
		<div class="container">
			<!-- Inicia uma <div> com a classe "container", que ajuda a centralizar e envolver o conteúdo da seção com margens e espaçamentos. -->

			<header> <!-- Inicia o cabeçalho da seção. -->
				<h2>Isso, sou eu.</h2> <!-- Título principal da seção, que descreve o que a pessoa faz. -->
				<p>Veja meus trabalhos, siga-me nas redes sociais.</p>
				<!-- Descrição da seção, fornecendo um contexto geral sobre o trabalho. -->
			</header>

			<div class="row aln-center">
				<!-- Inicia uma linha para organizar o conteúdo em colunas, com a classe "aln-center" para centralizar o conteúdo dentro da linha. -->

				<!-- Primeira coluna com um item de trabalho -->
				<div class="col-4 col-6-medium col-12-small">
					<!-- Define uma coluna que ocupa 4 partes em telas grandes, 6 partes em telas médias e 12 partes em telas pequenas. -->
					<section class="box style1">
						<!-- Inicia um item de trabalho dentro da coluna, com a classe "box" e "style1" para aplicar o estilo. -->
						<span class="icon featured fa-comments"></span>
						<!-- Exibe um ícone com a classe "fa-comments", usado para representar um ícone de conversa ou comentários. -->
						<h3>Comenta</h3> <!-- Título do item de trabalho. -->
						<p>Sementem ut feceris, ita metes.</p>
						<!-- Descrição do item de trabalho, explicando mais sobre o que é feito. -->
					</section>
				</div>

				<!-- Segunda coluna com outro item de trabalho -->
				<div class="col-4 col-6-medium col-12-small">
					<!-- Define outra coluna, com o mesmo comportamento responsivo. -->
					<section class="box style1">
						<!-- Inicia o segundo item de trabalho dentro da coluna, com as mesmas classes para aplicar estilo. -->
						<span class="icon solid featured fa-camera-retro"></span>
						<!-- Exibe um ícone de câmera retro, representando a fotografia ou vídeos. -->
						<h3>Poste</h3> <!-- Título do segundo item de trabalho. -->
						<p>Omnia in Bonum</p>
						<!-- Descrição do segundo item de trabalho. -->
					</section>
				</div>

				<!-- Terceira coluna com mais um item de trabalho -->
				<div class="col-4 col-6-medium col-12-small">
					<!-- Cria a terceira coluna com o mesmo comportamento responsivo. -->
					<section class="box style1"> <!-- Inicia o terceiro item de trabalho dentro da coluna. -->
						<span class="icon featured fa-thumbs-up"></span>
						<!-- Exibe um ícone de "curtir" (thumbs-up), representando aprovação ou gostei. -->
						<h3>Curte</h3> <!-- Título do terceiro item de trabalho. -->
						<p>Omnia vincit amor</p> <!-- Descrição do terceiro item de trabalho. -->
					</section>
				</div>
			</div> <!-- Fecha a linha "row" que agrupa as colunas do trabalho. -->

			<footer> <!-- Inicia o rodapé da seção de trabalho. -->
				<p>Experientia praestantior arte</p>
				<!-- Texto genérico ou uma pergunta que pode incentivar a interação. -->
				<a href="#portfolio" class="button large scrolly">Veja meus trabalhos mais recentes</a>
				<!-- Um botão grande que, ao ser clicado, rola para a seção de portfólio. -->
			</footer>
		</div> <!-- Fecha a "div" com a classe "container" que envolve o conteúdo da seção. -->
	</article> <!-- Fecha o <article> com id "work" -->

	<!-- Portfolio --> <!-- Comentário indicando que a seção seguinte é sobre "Portfólio" -->

	<article id="portfolio" class="wrapper style3">
		<!-- Inicia a seção <article> com o id "portfolio", que será usado para identificá-la. As classes "wrapper" e "style3" são aplicadas para estilizá-la de acordo com as regras CSS definidas. -->
		<div class="container">
			<!-- Inicia uma <div> com a classe "container", que ajuda a centralizar o conteúdo e aplica espaçamentos adequados ao redor do conteúdo. -->

			<header> <!-- Inicia o cabeçalho da seção do portfólio. -->
				<h2>Deixe-me fazer coisas para você.</h2>
				<!-- Título da seção, que sugere que o portfólio exibe trabalhos recentes. -->
				<p>Hoc non pereo habebo fortior me</p>
				<!-- Descrição adicional ou texto de apoio sobre o que o portfólio apresenta. -->
			</header>

			<div class="row">
				<!-- Inicia uma linha (row), que será usada para organizar os itens do portfólio em colunas. -->

				<!-- Primeira coluna com um item do portfólio -->
				<div class="col-4 col-6-medium col-12-small">
					<!-- Define uma coluna que ocupa 4 partes em telas grandes, 6 partes em telas médias e 12 partes em telas pequenas. -->
					<article class="box style2">
						<!-- Inicia um item de portfólio dentro da coluna, com as classes "box" e "style2" para aplicar estilo. -->
						<a href="#" class="image featured"><img src="images/html.png" alt="" /></a>
						<!-- Link (a) que envolve a imagem, tornando-a clicável. O atributo "class='image featured'" pode aplicar estilos para exibir a imagem adequadamente. -->
						<h3><a href="#">HTML</a></h3>
						<!-- Título do item do portfólio, que é um link que pode redirecionar para mais informações. -->
						<p>Ornare nulla proin odio consequat.</p> <!-- Descrição do item do portfólio. -->
					</article>
				</div>

				<!-- Segunda coluna com outro item do portfólio -->
				<div class="col-4 col-6-medium col-12-small">
					<!-- Definição da segunda coluna, com comportamento responsivo similar ao anterior. -->
					<article class="box style2">
						<!-- Outro item do portfólio com a mesma estrutura de "box" e "style2". -->
						<a href="#" class="image featured"><img src="images/css.png" alt="" /></a>
						<!-- Imagem do item do portfólio com link. -->
						<h3><a href="#">CSS</a></h3> <!-- Título do segundo item. -->
						<p>Ornare nulla proin odio consequat.</p> <!-- Descrição do segundo item. -->
					</article>
				</div>

				<!-- Terceira coluna com outro item do portfólio -->
				<div class="col-4 col-6-medium col-12-small">
					<!-- Definição da terceira coluna, com a mesma lógica de responsividade. -->
					<article class="box style2"> <!-- Terceiro item de portfólio. -->
						<a href="#" class="image featured"><img src="images/js11.png" alt="" /></a>
						<!-- Imagem do terceiro item com link. -->
						<h3><a href="#">JavaScript</a></h3> <!-- Título do terceiro item. -->
						<p>Ornare nulla proin odio consequat.</p> <!-- Descrição do terceiro item. -->
					</article>
				</div>

				<!-- Quarta coluna com outro item do portfólio -->
				<div class="col-4 col-6-medium col-12-small">
					<!-- Definição da quarta coluna, seguindo o mesmo padrão de colunas responsivas. -->
					<article class="box style2"> <!-- Quarto item do portfólio. -->
						<a href="#" class="image featured"><img src="images/java13.png" alt="" /></a>
						<!-- Imagem do quarto item com link. -->
						<h3><a href="#">Java</a></h3> <!-- Título do quarto item. -->
						<p>Ornare nulla proin odio consequat.</p> <!-- Descrição do quarto item. -->
					</article>
				</div>

				<!-- Quinta coluna com outro item do portfólio -->
				<div class="col-4 col-6-medium col-12-small">
					<!-- Quinta coluna, mesma estrutura de colunas responsivas. -->
					<article class="box style2"> <!-- Quinto item do portfólio. -->
						<a href="#" class="image featured"><img src="images/c++.png" alt="" /></a>
						<!-- Imagem do quinto item com link. -->
						<h3><a href="#">C++</a></h3> <!-- Título do quinto item. -->
						<p>Ornare nulla proin odio consequat.</p> <!-- Descrição do quinto item. -->
					</article>
				</div>

				<!-- Sexta coluna com outro item do portfólio -->
				<div class="col-4 col-6-medium col-12-small">
					<!-- Sexta e última coluna, seguindo o mesmo padrão de responsividade. -->
					<article class="box style2"> <!-- Sexto item do portfólio. -->
						<a href="#" class="image featured"><img src="images/python.jfif" alt="" /></a>
						<!-- Imagem do sexto item com link. -->
						<h3><a href="#">Python</a></h3> <!-- Título do sexto item. -->
						<p>Ornare nulla proin odio consequat.</p> <!-- Descrição do sexto item. -->
					</article>
				</div>
			</div> <!-- Fecha a linha (row) que contém todos os itens de portfólio. -->

			<footer> <!-- Inicia o rodapé da seção do portfólio. -->
				<p>Amicus certus in re incerta cernitur</p>
				<!-- Texto genérico de exemplo ou pergunta. -->
				<a href="#contact" class="button large scrolly">Entre em contato comigo.</a>
				<!-- Um botão grande que, quando clicado, leva o usuário à seção de contato da página. -->
			</footer>
		</div> <!-- Fecha a <div> com a classe "container", que envolve o conteúdo do portfólio. -->
	</article> <!-- Fecha o <article> com o id "portfolio" -->


	<!-- Contact --> <!-- Comentário indicando que a seção seguinte é a de "Contato" -->

	<article id="contact" class="wrapper style4">
		<!-- Inicia a seção <article> com o id "contact". As classes "wrapper" e "style4" são usadas para aplicar o estilo da seção. -->
		<div class="container medium">
			<!-- Inicia a <div> com a classe "container medium", que organiza o conteúdo e aplica a largura definida para a seção. -->

			<header> <!-- Inicia o cabeçalho da seção de contato. -->
				<h2>Peça-me </h2>
				<!-- Título da seção de contato, convidando o visitante a solicitar serviços. -->
				<p>Industriam adjuvat Deus</p>
				<!-- Descrição breve ou mensagem de introdução à seção de contato. -->
			</header>

			<div class="row"> <!-- Inicia uma linha (row) para organizar os elementos em colunas. -->
				<div class="col-12">
					<!-- Define uma coluna que ocupa toda a largura da linha. Aqui, o formulário ocupa a largura completa. -->
					<form method="post" action="#">
						<!-- Inicia um formulário que será enviado via método POST para o URL especificado (neste caso, um placeholder "#"). -->
						<div class="row"> <!-- Inicia uma linha para organizar os campos do formulário. -->

							<!-- Campo para nome -->
							<div class="col-6 col-12-small">
								<!-- Define uma coluna que ocupa metade da largura em telas grandes e toda a largura em telas pequenas. -->
								<input type="text" name="name" id="name" placeholder="Name" />
								<!-- Campo de entrada para o nome do usuário. -->
							</div>

							<!-- Campo para e-mail -->
							<div class="col-6 col-12-small"> <!-- Define uma coluna para o campo de e-mail. -->
								<input type="text" name="email" id="email" placeholder="Email" />
								<!-- Campo de entrada para o e-mail do usuário. -->
							</div>

							<!-- Campo para assunto -->
							<div class="col-12">
								<!-- Define uma coluna que ocupa toda a largura da linha para o campo de assunto. -->
								<input type="text" name="subject" id="subject" placeholder="Subject" />
								<!-- Campo de entrada para o assunto da mensagem. -->
							</div>

							<!-- Campo para mensagem -->
							<div class="col-12"> <!-- Define uma coluna para o campo de mensagem. -->
								<textarea name="message" id="message" placeholder="Message"></textarea>
								<!-- Área de texto para a mensagem do usuário. -->
							</div>

							<!-- Botões de envio e reset -->
							<div class="col-12"> <!-- Define uma coluna para os botões de envio e reset. -->
								<ul class="actions"> <!-- Lista de ações (botões). -->
									<li><input type="submit" value="ENVIAR" /></li>
									<!-- Botão de envio do formulário. -->
									<li><input type="reset" value="LIMPAR" class="alt" /></li>
									<!-- Botão para limpar os campos do formulário. -->
								</ul>
							</div>
						</div>
					</form> <!-- Fim do formulário -->
				</div>

				<!-- Seção para redes sociais -->
				<div class="col-12"> <!-- Define uma coluna para a seção de redes sociais. -->
					<hr /> <!-- Linha horizontal para separar as seções. -->
					<h3>Encontre-me em ...</h3> <!-- Título para a seção de links para redes sociais. -->
					<ul class="social"> <!-- Lista de redes sociais. -->
						<!-- Links para as redes sociais, com ícones e texto alternativo para cada uma -->
						<li><a href="#" class="icon brands fa-twitter"><span class="label">Twitter</span></a></li>
						<!-- Link para o Twitter com ícone correspondente. -->
						<li><a href="https://www.facebook.com/gabrielmarcosbr" class="icon brands fa-facebook-f"><span
									class="label">Facebook</span></a></li>
						<!-- Link para o Facebook com ícone correspondente. -->
						<li><a href="https://www.instagram.com/marcosoliverpb/" class="icon brands fa-instagram"><span
									class="label">instagram</span></a></li>
						<!-- Link para o Dribbble com ícone correspondente. -->
						<li><a href="#" class="icon brands fa-linkedin-in"><span class="label">LinkedIn</span></a></li>
						<!-- Link para o LinkedIn com ícone correspondente. -->
						<li><a href="#" class="icon brands fa-tumblr"><span class="label">Tumblr</span></a></li>
						<!-- Link para o Tumblr com ícone correspondente. -->
						<li><a href="#" class="icon brands fa-google-plus"><span class="label">Google+</span></a></li>
						<!-- Link para o Google+ com ícone correspondente. -->
						<li><a href="https://github.com/gabrieljp" class="icon brands fa-github"><span
									class="label">Github</span></a></li>
						<!-- Link para o GitHub com ícone correspondente. -->
					</ul>
					<hr /> <!-- Linha horizontal para separar as redes sociais do rodapé. -->
				</div>
			</div> <!-- Fim da linha de conteúdo (row) -->

			<footer> <!-- Inicia o rodapé da seção de contato. -->
				<ul id="copyright"> <!-- Lista para informações de copyright. -->
					<li>&copy; By Gabriel. All rights reserved.</li> <!-- Texto de copyright. -->
					<li>Design: <a href="http://html5up.net">HTML5 UP</a></li>
					<!-- Créditos para o design do site (HTML5 UP). -->
				</ul>
			</footer> <!-- Fim do rodapé -->
		</div> <!-- Fim da <div> com a classe "container medium" -->
	</article> <!-- Fim da seção de contato -->

	<!-- Scripts -->
	<!-- Comentário indicando que as linhas a seguir contêm os scripts JavaScript necessários para o funcionamento do site -->

	<!-- Inclusão do jQuery, uma biblioteca JavaScript popular que facilita manipulação do DOM, animações, etc. -->
	<script src="assets/js/jquery.min.js"></script>

	<!-- Inclusão do jQuery Scrolly, uma extensão do jQuery para animações ao rolar a página -->
	<script src="assets/js/jquery.scrolly.min.js"></script>

	<!-- Inclusão do script "browser.min.js", provavelmente utilizado para detectar ou corrigir problemas de compatibilidade entre diferentes navegadores -->
	<script src="assets/js/browser.min.js"></script>

	<!-- Inclusão do script "breakpoints.min.js", geralmente usado para definir pontos de interrupção (breakpoints) em designs responsivos -->
	<script src="assets/js/breakpoints.min.js"></script>

	<!-- Inclusão do script "util.js", que pode conter funções utilitárias genéricas que são usadas em várias partes do site -->
	<script src="assets/js/util.js"></script>

	<!-- Inclusão do script "main.js", provavelmente o script principal que contém o comportamento e funcionalidades personalizadas do site -->
	<script src="assets/js/main.js"></script>
</body>

</html>
