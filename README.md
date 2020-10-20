index.php

<link href="//maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" rel="stylesheet" id="bootstrap-css">
<script src="//maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>

<!DOCTYPE html><html lang='en' class=''>
<head><script src='//production-assets.codepen.io/assets/editor/live/console_runner-079c09a0e3b9ff743e39ee2d5637b9216b3545af0de366d4b9aad9dc87e26bfd.js'></script><script src='//production-assets.codepen.io/assets/editor/live/events_runner-73716630c22bbc8cff4bd0f07b135f00a0bdc5d14629260c3ec49e5606f98fdd.js'></script><script src='//production-assets.codepen.io/assets/editor/live/css_live_reload_init-2c0dc5167d60a5af3ee189d570b1835129687ea2a61bee3513dee3a50c115a77.js'></script><meta charset='UTF-8'><meta name="robots" content="noindex"><link rel="shortcut icon" type="image/x-icon" href="//production-assets.codepen.io/assets/favicon/favicon-8ea04875e70c4b0bb41da869e81236e54394d63638a1ef12fa558a4a835f1164.ico" /><link rel="mask-icon" type="" href="//production-assets.codepen.io/assets/favicon/logo-pin-f2d2b6d2c61838f7e76325261b7195c27224080bc099486ddd6dccb469b8e8e6.svg" color="#111" /><link rel="canonical" href="https://codepen.io/frytyler/pen/EGdtg" />

<link rel='stylesheet prefetch' href='https://cdnjs.cloudflare.com/ajax/libs/normalize/5.0.0/normalize.min.css'><script src='https://cdnjs.cloudflare.com/ajax/libs/prefixfree/1.0.7/prefixfree.min.js'></script>
<style class="cp-pen-styles">@import url(https://fonts.googleapis.com/css?family=Open+Sans);
.btn { display: inline-block; *display: inline; *zoom: 1; padding: 4px 10px 4px; margin-bottom: 0; font-size: 13px; line-height: 18px; color: #333333; text-align: center;text-shadow: 0 1px 1px rgba(255, 255, 255, 0.75); vertical-align: middle; background-color: #f5f5f5; background-image: -moz-linear-gradient(top, #ffffff, #e6e6e6); background-image: -ms-linear-gradient(top, #ffffff, #e6e6e6); background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#ffffff), to(#e6e6e6)); background-image: -webkit-linear-gradient(top, #ffffff, #e6e6e6); background-image: -o-linear-gradient(top, #ffffff, #e6e6e6); background-image: linear-gradient(top, #ffffff, #e6e6e6); background-repeat: repeat-x; filter: progid:dximagetransform.microsoft.gradient(startColorstr=#ffffff, endColorstr=#e6e6e6, GradientType=0); border-color: #e6e6e6 #e6e6e6 #e6e6e6; border-color: rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.25); border: 1px solid #e6e6e6; -webkit-border-radius: 4px; -moz-border-radius: 4px; border-radius: 4px; -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.2), 0 1px 2px rgba(0, 0, 0, 0.05); -moz-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.2), 0 1px 2px rgba(0, 0, 0, 0.05); box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.2), 0 1px 2px rgba(0, 0, 0, 0.05); cursor: pointer; *margin-left: .3em; }
.btn:hover, .btn:active, .btn.active, .btn.disabled, .btn[disabled] { background-color: #e6e6e6; }
.btn-large { padding: 9px 14px; font-size: 15px; line-height: normal; -webkit-border-radius: 5px; -moz-border-radius: 5px; border-radius: 5px; }
.btn:hover { color: #333333; text-decoration: none; background-color: #e6e6e6; background-position: 0 -15px; -webkit-transition: background-position 0.1s linear; -moz-transition: background-position 0.1s linear; -ms-transition: background-position 0.1s linear; -o-transition: background-position 0.1s linear; transition: background-position 0.1s linear; }
.btn-primary, .btn-primary:hover { text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.25); color: #ffffff; }
.btn-primary.active { color: rgba(255, 255, 255, 0.75); }
.btn-primary { background-color: #4a77d4; background-image: -moz-linear-gradient(top, #6eb6de, #4a77d4); background-image: -ms-linear-gradient(top, #6eb6de, #4a77d4); background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#6eb6de), to(#4a77d4)); background-image: -webkit-linear-gradient(top, #6eb6de, #4a77d4); background-image: -o-linear-gradient(top, #6eb6de, #4a77d4); background-image: linear-gradient(top, #6eb6de, #4a77d4); background-repeat: repeat-x; filter: progid:dximagetransform.microsoft.gradient(startColorstr=#6eb6de, endColorstr=#4a77d4, GradientType=0);  border: 1px solid #3762bc; text-shadow: 1px 1px 1px rgba(0,0,0,0.4); box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.2), 0 1px 2px rgba(0, 0, 0, 0.5); }
.btn-primary:hover, .btn-primary:active, .btn-primary.active, .btn-primary.disabled, .btn-primary[disabled] { filter: none; background-color: #4a77d4; }
.btn-block { width: 100%; display:block; }

* { -webkit-box-sizing:border-box; -moz-box-sizing:border-box; -ms-box-sizing:border-box; -o-box-sizing:border-box; box-sizing:border-box; }

html { width: 100%; height:100%; overflow:hidden; }

body { 
	width: 100%;
	height:100%;
	font-family: 'Open Sans', sans-serif;
	background: #092756;
	background: -moz-radial-gradient(0% 100%, ellipse cover, rgba(104,128,138,.4) 10%,rgba(138,114,76,0) 40%),-moz-linear-gradient(top,  rgba(57,173,219,.25) 0%, rgba(42,60,87,.4) 100%), -moz-linear-gradient(-45deg,  #670d10 0%, #092756 100%);
	background: -webkit-radial-gradient(0% 100%, ellipse cover, rgba(104,128,138,.4) 10%,rgba(138,114,76,0) 40%), -webkit-linear-gradient(top,  rgba(57,173,219,.25) 0%,rgba(42,60,87,.4) 100%), -webkit-linear-gradient(-45deg,  #670d10 0%,#092756 100%);
	background: -o-radial-gradient(0% 100%, ellipse cover, rgba(104,128,138,.4) 10%,rgba(138,114,76,0) 40%), -o-linear-gradient(top,  rgba(57,173,219,.25) 0%,rgba(42,60,87,.4) 100%), -o-linear-gradient(-45deg,  #670d10 0%,#092756 100%);
	background: -ms-radial-gradient(0% 100%, ellipse cover, rgba(104,128,138,.4) 10%,rgba(138,114,76,0) 40%), -ms-linear-gradient(top,  rgba(57,173,219,.25) 0%,rgba(42,60,87,.4) 100%), -ms-linear-gradient(-45deg,  #670d10 0%,#092756 100%);
	background: -webkit-radial-gradient(0% 100%, ellipse cover, rgba(104,128,138,.4) 10%,rgba(138,114,76,0) 40%), linear-gradient(to bottom,  rgba(57,173,219,.25) 0%,rgba(42,60,87,.4) 100%), linear-gradient(135deg,  #670d10 0%,#092756 100%);
	filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#3E1D6D', endColorstr='#092756',GradientType=1 );
}
.login { 
	position: absolute;
	top: 50%;
	left: 50%;
	margin: -150px 0 0 -150px;
	width:300px;
	height:300px;
}
.login h1 { color: #fff; text-shadow: 0 0 10px rgba(0,0,0,0.3); letter-spacing:1px; text-align:center; }

input { 
	width: 100%; 
	margin-bottom: 10px; 
	background: rgba(0,0,0,0.3);
	border: none;
	outline: none;
	padding: 10px;
	font-size: 13px;
	color: #fff;
	text-shadow: 1px 1px 1px rgba(0,0,0,0.3);
	border: 1px solid rgba(0,0,0,0.3);
	border-radius: 4px;
	box-shadow: inset 0 -5px 45px rgba(100,100,100,0.2), 0 1px 1px rgba(255,255,255,0.2);
	-webkit-transition: box-shadow .5s ease;
	-moz-transition: box-shadow .5s ease;
	-o-transition: box-shadow .5s ease;
	-ms-transition: box-shadow .5s ease;
	transition: box-shadow .5s ease;
}
input:focus { box-shadow: inset 0 -5px 45px rgba(100,100,100,0.4), 0 1px 1px rgba(255,255,255,0.2); }
</style></head><body>
<div class="login">
	<h1>Login</h1>
    <form method="post" action = "Validacaologin.php">
    	<input type="text" name="nome" placeholder="Username" required="required" />
        <input type="password" name="senha" placeholder="Password" required="required" />
        <button type="submit" class="btn btn-primary btn-block btn-large">Entrar</button>
        <a href="Cadastro.php" class="btn btn-primary btn-block btn-large">Cadastrar Usuário</a>
    </form>
</div>
<script src='//production-assets.codepen.io/assets/common/stopExecutionOnTimeout-b2a7b3fe212eaa732349046d8416e00a9dec26eb7fd347590fbced3ab38af52e.js'></script>
<script >
</script>
</body>
</html>


Validacaologin.php


<?php
session_start();
    $login = $_POST['nome'];
    $senha = $_POST['senha'];

    $conexao = mysqli_connect('localhost', 'root','', 'controle_vendas') or die ("Sem conexão com o servidor");
    $select = mysqli_select_db ($conexao,"controle_vendas") or die ("Sem acesso ao DB, entre em contato com o Administrador, nathanxavier84@gmail.com");
    $result = mysqli_query($conexao, "SELECT * FROM `cadastro` WHERE `nome` = '$login' AND `senha` = '$senha'");
        if(mysqli_num_rows ($result)){
        $_SESSION['nome'] = $login;
        $_SESSION['senha'] = $senha;
        header ('location:sistema.php');
        }
        else {
            unset ($_SESSION['nome']);
            unset ($_SESSION['senha']);
            header ('location:index.php');
        }
?>

Cadastro.php

<?php  include_once 'conexao.php' ?>
<link href="//maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" rel="stylesheet" id="bootstrap-css">
<script src="//maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>


<link href="//maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" rel="stylesheet" id="bootstrap-css">
<script src="//maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>

<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>


<style type="text/css">
  
body{
  background-image: url(http://www.joburgchiropractor.co.za/images/background.jpg);
}







</style>



</head>
<body>

<div class="container" style="margin-top: 5%;">
  <div class="row">
    <div class="col-sm-4"> </div>
<div class="col-md-4">
  
<h1 class="text-center text-success"> Página de Cadastro</h1>
<br/>

<div class="col-sm-12">

  <ul class="nav nav-pills" >



  </ul>

<br/>


  <div class="tab-content">
    <div id="home" class="tab-pane fade in active">
      
<form method = POST action = "cadastrar.php">

  <div class="form-group">
    <label for="UserName">Usuário</label>
    <input type="text" class="form-control" name="nome">
  </div>
  
  <div class="form-group">
    <label for="email">Email:</label>
    <input type="email" class="form-control" name="email">
  </div>

  <div class="form-group">
    <label for="senha">Senha:</label>
    <input type="password" class="form-control" name="senha">
  </div>

  <div class="form-group">
    <label for="confirmar">Confirmar Senha:</label>
    <input type="password" class="form-control" name="confirmar">
  </div>



  <button type="submit" class="btn btn-default btn-lg">Cadastrar</button>
  <a href="index.php" class="btn btn-default btn-lg">Voltar</a>

</form>
<br/>    
    </div>
   </div>
  </div>
</div>
</div>

</body>
</html>

cadastrar.php

<?php include_once "conexao.php";

        $nome = $_POST["nome"];
        $senha   = $_POST["senha"];
        $email  =   $_POST["email"];
        $confirmar = $_POST["confirmar"];

        if(inserir($conexao, $nome, $senha, $email, $confirmar)){
            echo "<center><h3> Cadastrado com sucesso!!! </h3></center>";
        }

        function inserir($conexao, $nome, $senha, $email, $confirmar){
            echo "Usuário:      $nome<br>";
            echo "Senha:        $senha<br>";
            echo "Email:         $email<br>";
            echo "Confirmar senha: $confirmar<br>";
            $sql = "INSERT INTO cadastro (nome, senha, email, confirmar)
                VALUES ('$nome', '$senha', '$email', '$confirmar')";
            $resultado = mysqli_query($conexao, $sql);
            return $resultado;
            

        if(inserir($conexao, $nome, $senha, $email, $confirmar)){
            echo "<h3> Adicionado com sucesso!!! </h3>";
        }

        }

        echo 
            "<!doctype html>" . 
            "<html>" .
                "<head>" .
                    "<meta charset = 'utf-8'/>" .
                    "<link rel = 'stylesheet' type = 'text/css' href = 'Cadastro.css '></link>" .
                    "<title> Cadastro </title>" .
                "</head>" . 
            "</html>";



?>


sistema.php

<link href="//maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" rel="stylesheet" id="bootstrap-css">
<script src="//maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>

<!DOCTYPE html><html lang='en' class=''>
<head><script src='//production-assets.codepen.io/assets/editor/live/console_runner-079c09a0e3b9ff743e39ee2d5637b9216b3545af0de366d4b9aad9dc87e26bfd.js'></script><script src='//production-assets.codepen.io/assets/editor/live/events_runner-73716630c22bbc8cff4bd0f07b135f00a0bdc5d14629260c3ec49e5606f98fdd.js'></script><script src='//production-assets.codepen.io/assets/editor/live/css_live_reload_init-2c0dc5167d60a5af3ee189d570b1835129687ea2a61bee3513dee3a50c115a77.js'></script><meta charset='UTF-8'><meta name="robots" content="noindex"><link rel="shortcut icon" type="image/x-icon" href="//production-assets.codepen.io/assets/favicon/favicon-8ea04875e70c4b0bb41da869e81236e54394d63638a1ef12fa558a4a835f1164.ico" /><link rel="mask-icon" type="" href="//production-assets.codepen.io/assets/favicon/logo-pin-f2d2b6d2c61838f7e76325261b7195c27224080bc099486ddd6dccb469b8e8e6.svg" color="#111" /><link rel="canonical" href="https://codepen.io/frytyler/pen/EGdtg" />

<link rel='stylesheet prefetch' href='https://cdnjs.cloudflare.com/ajax/libs/normalize/5.0.0/normalize.min.css'><script src='https://cdnjs.cloudflare.com/ajax/libs/prefixfree/1.0.7/prefixfree.min.js'></script>
<style class="cp-pen-styles">@import url(https://fonts.googleapis.com/css?family=Open+Sans);
.btn { display: inline-block; *display: inline; *zoom: 1; padding: 4px 10px 4px; margin-bottom: 0; font-size: 13px; line-height: 18px; color: #333333; text-align: center;text-shadow: 0 1px 1px rgba(255, 255, 255, 0.75); vertical-align: middle; background-color: #f5f5f5; background-image: -moz-linear-gradient(top, #ffffff, #e6e6e6); background-image: -ms-linear-gradient(top, #ffffff, #e6e6e6); background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#ffffff), to(#e6e6e6)); background-image: -webkit-linear-gradient(top, #ffffff, #e6e6e6); background-image: -o-linear-gradient(top, #ffffff, #e6e6e6); background-image: linear-gradient(top, #ffffff, #e6e6e6); background-repeat: repeat-x; filter: progid:dximagetransform.microsoft.gradient(startColorstr=#ffffff, endColorstr=#e6e6e6, GradientType=0); border-color: #e6e6e6 #e6e6e6 #e6e6e6; border-color: rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.1) rgba(0, 0, 0, 0.25); border: 1px solid #e6e6e6; -webkit-border-radius: 4px; -moz-border-radius: 4px; border-radius: 4px; -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.2), 0 1px 2px rgba(0, 0, 0, 0.05); -moz-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.2), 0 1px 2px rgba(0, 0, 0, 0.05); box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.2), 0 1px 2px rgba(0, 0, 0, 0.05); cursor: pointer; *margin-left: .3em; }
.btn:hover, .btn:active, .btn.active, .btn.disabled, .btn[disabled] { background-color: #e6e6e6; }
.btn-large { padding: 9px 14px; font-size: 15px; line-height: normal; -webkit-border-radius: 5px; -moz-border-radius: 5px; border-radius: 5px; }
.btn:hover { color: #333333; text-decoration: none; background-color: #e6e6e6; background-position: 0 -15px; -webkit-transition: background-position 0.1s linear; -moz-transition: background-position 0.1s linear; -ms-transition: background-position 0.1s linear; -o-transition: background-position 0.1s linear; transition: background-position 0.1s linear; }
.btn-primary, .btn-primary:hover { text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.25); color: #ffffff; }
.btn-primary.active { color: rgba(255, 255, 255, 0.75); }
.btn-primary { background-color: #4a77d4; background-image: -moz-linear-gradient(top, #6eb6de, #4a77d4); background-image: -ms-linear-gradient(top, #6eb6de, #4a77d4); background-image: -webkit-gradient(linear, 0 0, 0 100%, from(#6eb6de), to(#4a77d4)); background-image: -webkit-linear-gradient(top, #6eb6de, #4a77d4); background-image: -o-linear-gradient(top, #6eb6de, #4a77d4); background-image: linear-gradient(top, #6eb6de, #4a77d4); background-repeat: repeat-x; filter: progid:dximagetransform.microsoft.gradient(startColorstr=#6eb6de, endColorstr=#4a77d4, GradientType=0);  border: 1px solid #3762bc; text-shadow: 1px 1px 1px rgba(0,0,0,0.4); box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.2), 0 1px 2px rgba(0, 0, 0, 0.5); }
.btn-primary:hover, .btn-primary:active, .btn-primary.active, .btn-primary.disabled, .btn-primary[disabled] { filter: none; background-color: #4a77d4; }
.btn-block { width: 100%; display:block; }

* { -webkit-box-sizing:border-box; -moz-box-sizing:border-box; -ms-box-sizing:border-box; -o-box-sizing:border-box; box-sizing:border-box; }

html { width: 100%; height:100%; overflow:hidden; }

body { 
	width: 100%;
	height:100%;
	font-family: 'Open Sans', sans-serif;
	background: #092756;
	background: -moz-radial-gradient(0% 100%, ellipse cover, rgba(104,128,138,.4) 10%,rgba(138,114,76,0) 40%),-moz-linear-gradient(top,  rgba(57,173,219,.25) 0%, rgba(42,60,87,.4) 100%), -moz-linear-gradient(-45deg,  #670d10 0%, #092756 100%);
	background: -webkit-radial-gradient(0% 100%, ellipse cover, rgba(104,128,138,.4) 10%,rgba(138,114,76,0) 40%), -webkit-linear-gradient(top,  rgba(57,173,219,.25) 0%,rgba(42,60,87,.4) 100%), -webkit-linear-gradient(-45deg,  #670d10 0%,#092756 100%);
	background: -o-radial-gradient(0% 100%, ellipse cover, rgba(104,128,138,.4) 10%,rgba(138,114,76,0) 40%), -o-linear-gradient(top,  rgba(57,173,219,.25) 0%,rgba(42,60,87,.4) 100%), -o-linear-gradient(-45deg,  #670d10 0%,#092756 100%);
	background: -ms-radial-gradient(0% 100%, ellipse cover, rgba(104,128,138,.4) 10%,rgba(138,114,76,0) 40%), -ms-linear-gradient(top,  rgba(57,173,219,.25) 0%,rgba(42,60,87,.4) 100%), -ms-linear-gradient(-45deg,  #670d10 0%,#092756 100%);
	background: -webkit-radial-gradient(0% 100%, ellipse cover, rgba(104,128,138,.4) 10%,rgba(138,114,76,0) 40%), linear-gradient(to bottom,  rgba(57,173,219,.25) 0%,rgba(42,60,87,.4) 100%), linear-gradient(135deg,  #670d10 0%,#092756 100%);
	filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#3E1D6D', endColorstr='#092756',GradientType=1 );
}
.login { 
	position: absolute;
	top: 23%;
	left: 50%;
	margin: -150px 0 0 -150px;
	width:300px;
	height:300px;
}
.login h1 { color: #fff; text-shadow: 0 0 10px rgba(0,0,0,0.3); letter-spacing:1px; text-align:center; }

input { 
	width: 100%; 
	margin-bottom: 10px; 
	background: rgba(0,0,0,0.3);
	border: none;
	outline: none;
	padding: 10px;
	font-size: 13px;
	color: #fff;
	text-shadow: 1px 1px 1px rgba(0,0,0,0.3);
	border: 1px solid rgba(0,0,0,0.3);
	border-radius: 4px;
	box-shadow: inset 0 -5px 45px rgba(100,100,100,0.2), 0 1px 1px rgba(255,255,255,0.2);
	-webkit-transition: box-shadow .5s ease;
	-moz-transition: box-shadow .5s ease;
	-o-transition: box-shadow .5s ease;
	-ms-transition: box-shadow .5s ease;
	transition: box-shadow .5s ease;
}
input:focus { box-shadow: inset 0 -5px 45px rgba(100,100,100,0.4), 0 1px 1px rgba(255,255,255,0.2); }
</style></head><body>
<div class="login">
	<h1>Vendas</h1>
    <form method = POST    action = "vendas.php">
    	<input type="text" name="vendas" placeholder="Vendas Efetuadas" required="required" />
        <input type="date" name="date" placeholder="Data das Vendas" required="required" />
        <input type="text" name="numero" placeholder="Número de peças vendidas" required="required" />
        <input type="text" name="boleta" placeholder="Total de boletas" required="required" />
        <input type="text" name="despesas" placeholder="Despesas da loja" required="required" />
        <input type="text" name="dinheiro" placeholder="Pagamento em dinheiro" required="required" />
        <input type="text" name="debito" placeholder="Pagamento no débito" required="required" />
        <input type="text" name="credito" placeholder="Pagamento no crédito" required="required" />
        <button type="submit" class="btn btn-primary btn-block btn-large">Salvar</button>
        <a href="Total.php" class="btn btn-primary btn-block btn-large">Mostrar todas as vendas</a>
        <a href="Deletar.php" class="btn btn-primary btn-block btn-large">Deletar</a>
        <a href="mostrar.php" class="btn btn-primary btn-block btn-large">Mostrar venda específica</a>
    </form>
</div>
<script src='//production-assets.codepen.io/assets/common/stopExecutionOnTimeout-b2a7b3fe212eaa732349046d8416e00a9dec26eb7fd347590fbced3ab38af52e.js'></script>
<script >
</script>
</body>
</html>

vendas.php

<?php
    include_once "conexao.php";

    $vendas = $_POST["vendas"];
    $date =  $_POST["date"];
    $numero = $_POST["numero"];
    $boleta = $_POST["boleta"];
    $despesas = $_POST["despesas"];
    $dinheiro = $_POST["dinheiro"];
    $debito = $_POST["debito"];
    $credito = $_POST["credito"];
    $chaves = array(
        "vendas" => $vendas,
        "date"=> $date,
        "numero" => $numero,
        "boleta" => $boleta,
        "despesas" => $despesas,
        "dinheiro" => $dinheiro,
        "debito" => $debito,
        "credito" => $credito
    );

    foreach ($chaves as $chave => $valor)
        if (verificarChave($chave, $_POST))
            $valor = $_POST[$chave];

    $valido = true;
    $valoresInvalidos = array();

    foreach ($chaves as $chave => $valor)
        if (is_null($valor)) {
            $valoresInvalidos[$chave] = $chave;
            $valido = false;
        }

    if ($valido) {
        if(salvar ($conexao, $vendas, $date, $numero, $boleta, $despesas, $dinheiro, $debito, $credito)){
            echo "<center>
                    <h3> Salvo com sucesso !! </h3> </center>";
        }
        else{
            echo "Erro";
            echo mysqli_error($conexao);
        }
    }
    else {
        echo "É inválido!<br /><br />";
        echo "<strong>Valores inválidos encontrados:</strong>";
        echo "<ul>";
        
        foreach ($valoresInvalidos as $valor)
            echo "<li>Valor '<strong><u>" . $valor . "</u></strong>' é nulo.</li>";

        echo "</ul>";
    }

    return;

    function verificarChave($chave, $dicionario) {
        return array_key_exists($chave, $dicionario);
    }

    function salvar($conexao, $vendas, $date, $numero, $boleta, $despesas, $dinheiro, $debito, $credito){
        echo "<b>Vendas Efetuadas:</b> $vendas<br>";
        echo "<b>Data das Vendas:</b> $date<br>";
        echo "<b>Número de peças vendidas:</b> $numero<br>";
        echo "<b>Total de boletas:</b> $boleta<br>";
        echo "<b>Despesas da loja:</b> $despesas<br>";
        echo "<b>Pagamento em dinheiro:</b> $dinheiro<br>";
        echo "<b>Pagamento no cartão de débito:</b>  $debito<br>";
        echo "<b>Pagamento no cartão de crédito:</b> $credito<br>";
        $sql = "insert into vendas (vendas, date, numero, boleta, despesas, dinheiro, debito, credito)
        values ('$vendas',' $date', '$numero', '$boleta', '$despesas', '$dinheiro', '$debito', '$credito')";
        $resultado = mysqli_query($conexao, $sql);
        return $resultado;
    }

?>

mostrar.php

<html>
    <head>
    <title> mostrar </title>
    <meta charset = "utf-8">
    <style>
        body{
            background-image:url(PoloSeven1.jpg);
            background-attachment:fixed;
            background-size:270px;
            background-repeat:no-repeat;
            background-position:560px -10px;
            background-color:#000000;
        }
        label{
            color:whitesmoke;
        }
        h1{
            color: gray;
        }
        fieldset{
            border: 1px solid goldenrod;
            height: 10%;
        }
    </style>
    </head>
<body>
<center>
    <br><br><br><br><br><br><br><br><br><br><br><br>
    <h1> Mostrar vendas </h1>
    <fieldset>
        <form action = "mostrarVendas.php" method = POST>
            <label> Qual data deseja mostrar: </label>
            <input type = "Date" name = "date"><br><br>
            <input type = "submit" name = "OK" value = "OK"><br><br>
    </fieldset>
</center>
</body>
</html>

mostrarVendas.php

<?php
include_once ("conexao.php");

$date = $_POST['date'];

mostrarVendas($conexao, $date);

function mostrarVendas($conexao, $date){
    setlocale(LC_TIME, 'pt_BR', 'pt_BR.utf-8', 'pt_BR.utf-8', 'portuguese');
    date_default_timezone_set('America/Sao_Paulo');

    $sql = "SELECT `id_codigo`, `vendas`, `date`, `boleta` FROM `vendas` WHERE `date` = '$date' ORDER BY `id` ASC";
    $resultado = mysqli_query($conexao, $sql);
    $quantidade = mysqli_num_rows($resultado);

    if ($quantidade == 0) {
        echo "<center>
                <strong>Nenhum</strong> registro encontrado!
              </center>";
        echo 
            "<!doctype html>" . 
            "<html>" . 
                "<head>" . 
                    "<meta charset = 'utf-8' />" . 
                    "<title> Nenhum Registro </title>" . 
                    "<link rel = 'stylesheet' type = 'text/css' href = 'nenhum-registro.css'></link>" . 
                "</head>" . 
            "</html>" ;
        return;
    }
    
    echo
        "<!doctype html>" .
        "<html>" .
            "<head>" .
                "<meta charset='utf-8' />" .
                "<title>Mostrar Vendas</title>" .
                "<link rel='stylesheet' type='text/css' href='mostrar-vendas.css'></link>" .
            "</head>" .
            "<body>" .
                "<table>" .
                    "<thead>" .
                        "<th>Data</th>" .
                        "<th>Venda</th>" . 
                        "<th>Boleta</th>" . 
                    "</thead>" . 
                    "<tbody>" . 
                        "<tr>";

    while($venda = mysqli_fetch_assoc($resultado))
        echo 
                            "<td>" . strftime('%A, %d de %B de %Y', strtotime($venda['date'])) . "</td>" .
                            "<td>R$ " . number_format($venda['vendas'], 2) . "</td>" .
                            "<td>" . $venda['boleta'] . "</td>" .
                        "</tr>";

    echo
                    "</tbody>" .
                "</table>" .
            "</body>" .
        "</html>";
}

Total.php

<?php include_once ("conexao.php") ?>
<?php
    function listarVendas($conexao){
        
        setlocale(LC_TIME, 'pt_BR', 'pt_BR.utf-8', 'pt_BR.utf-8', 'portuguese');
        date_default_timezone_set('America/Sao_Paulo');

        $sql = "SELECT `id_codigo`, `vendas`, `date`, `numero`, `boleta`, `despesas`, `dinheiro`, `debito`, `credito`
         FROM `vendas` ORDER BY `id` ASC";
        $resultado = mysqli_query($conexao, $sql);
        $quantidade = mysqli_num_rows($resultado);

        echo 
            "<!doctype html>" .
            "<html>" .
                "<head>" .
                    "<meta charset = 'utf-8' />" .
                    "<title> Mostrar Tudo </title>" .
                    "<link rel = 'stylesheet' type = 'text/css' href = 'mostra-tudo.css'></link>" .
                "</head>" .
                "<body>" .
                    "<table>" .
                        "<thead>" .
                            "<th> Vendas </th>" .
                            "<th> Data </th>" .
                            "<th> Peças </th>" .
                            "<th> Boletas </th>" . 
                            "<th> Despesas </th>" .
                            "<th> Pagamento em Dinheiro </th>" . 
                            "<th> Pagamento no Debito </th>" .
                            "<th> Pagamento no Credito </th>" . 
                        "</thead>" . 
                        "<tbody>" . 
                            "<tr>";

        while($venda = mysqli_fetch_assoc($resultado))
            echo
                                "<td>" . strftime('%A, %d de %B de %Y', strtotime($venda['date'])) . "</td>" .
                                "<td> R$ " . number_format($venda['vendas'], 2) . "</td>" . 
                                "<td>" . $venda['numero'] . "</td>" . 
                                "<td>" . $venda['boleta'] . "</td>" .
                                "<td>" . $venda['despesas'] . "</td>" .
                                "<td>" . $venda['dinheiro'] . "</td>" . 
                                "<td>" . $venda['debito'] . "</td>" .
                                "<td>" . $venda['credito'] . "</td>" . 
                            "</tr>";
        echo 
                        "</tbody>" . 
                    "</table>" . 
                "</body>" . 
            "</html>";
        
    }
        listarVendas($conexao);

?>

Deletar.php
<html>
    <head>
    <title> deletar </title>
    <meta charset = "utf-8">
    <style>
        body{
            background-image:url(PoloSeven1.jpg);
            background-attachment:fixed;
            background-size:270px;
            background-repeat:no-repeat;
            background-position:560px -10px;
            background-color:#000000;
        }
        label{
            color:whitesmoke;
        }
        h1{
            color: gray;
        }
        fieldset{
            border: 1px solid goldenrod;
            height: 10%;
        }
}
    </style>
    </head>
<body>
<center>
    <br><br><br><br><br><br><br><br><br><br><br><br>
    <h1> Deletar vendas </h1>
    <fieldset>
        <form action = "DeletarValores.php" method = POST>
            <label> Qual id deseja deletar: </label>
            <input type = "text" name = "id"><br><br>
            <input type = "submit" name = "Deletar" value = "Deletar"><br><br>
    </fieldset>
</center>
</body>
</html>

DeletarValores.php

<?php include_once ("conexao.php") ?>
<?php
    $id = $_POST["id"];

    function removerVendas($conexao, $id){
        $sql = "delete from vendas where id = $id";
        $resultado = mysqli_query($conexao, $sql);
        return $resultado;
    }
    if(removerVendas($conexao, $id)){
        echo "
            <center>
                <h3>Deletado com sucesso!!</h3>
            </center>";
    }
    else{
        echo mysqli_error($conexao);
    }

    echo 
        "<!doctype html>" . 
            "<html>" . 
                "<head>" . 
                    "<meta charset = 'utf-8'>" .
                    "<title> Deletar Vendas </title>" . 
                    "<link rel = 'stylesheet' type = 'text/css' href = 'deletar.css'></link>" . 
                "</head>" .
            "</html>";
?>

