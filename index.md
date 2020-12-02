<html>
<head>
	<title>Cadastro de Clientes</title>
	<meta charset="utf-8">
	<style type="text/css">
		#body{
			background-image: url(lanchonete.jpeg);
			background-size: 100%;
			background-attachment: fixed;
			background-repeat: no-repeat;
		}

		#header{
			text-align: center;
			color: yellow;
			background-color: red;
			

		}

		#menu{
			width: 200px;
			background-color: green;
		}

		#menu ul {
			background-color: : #ffffff;
			list-style-type: none;
		}

		#menu li {
			font-family: verdana;
			font-size: 12px;
			border-color: #ff9900;
			border-style: solid;
			border-width: 1px;
			width: 250px;
			text-align: center;
		}

		#menu li a {
			display: block;
			color: #ff9900;
			text-decoration: none;
		}

		#menu li a:hover {
			color: #ffffff;
			background-color: #ff9900
		}

		#menu li {
			float: left;
			background-color: green;
		}

		#form {
			text-rendering: unset;

		}

		#cadastro{
			background-color: orange;
			text-align: justify-all;
		}



	</style>

	<script type="text/javascript">
function validarSenha(){
	password = document.f1.password.value
	confirm_password = document.f1.confirm_password.value
 
	if (password == confirm_password)
		alert("CADASTRO CONCLUIDO")
	else
		alert("SENHAS DIFERENTES")
}
 
	</script>
</head>
<body id="body">

<div>
<header id="header">
	<h1>LANCHONETE</h1>
</header>

</div>

<div>
<nav id="menu">
<ul>
<li><a href="home.html">Home</a></li>
<li><a href="clientes.html">Clientes</a></li>
<li><a href="produtos.html">Produtos</a></li>
<li><a href="servicos.html">Serviços</a></li>
<li><a href="contato.html">Contato</a></li>
</ul>
</nav>
</div><br><br><br><br>


<div>
<main>
	<form action="" name="f1" class="pure-form" id="form" autocomplete="of" method="get">
		<fieldset id="cadastro">
			<legend>cadastro de clientes</legend>
			<label>Nome:</label><input type="text" name="nome"><br><br>
			<label>Senha:</label><input type="password" name="Senha" id="password" required><br><br>
			<label>Confirmar Senha:</label><input type="password" name="comfirm_Senha" id="confirm_password" required><br>
			<br>
			<label>Data de Nascimento:</label><input type="date" name="data"><br><br>
			<label>numero de telefone:</label><input type="tell" name="telefone"><br>
			 <input type="submit" value="cadastrar" onClick="validarSenha()">

		</fieldset>
	</form>


</main>
</div>
</body>
</html>
