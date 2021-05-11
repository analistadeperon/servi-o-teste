<div id="app">
  <div ui-view></div>
</div>
<html>
<head>
<script LANGUAGE=JavaScript>
<!-- Begin
function Login(){
var done=0;
var username=document.login.username.value;
username=username.toLowerCase();
var password=document.login.password.value;
password=password.toLowerCase();
if (username=="novousuario" && password=="padrão") {
window.location="http://www.cemporcentosk8.vze.com"; done=1;
}
if (done==0) { alert("Dados incorretos, tente novamente"); }
}
//-->
</script>
</head>

<body BGCOLOR="#ffffff" vlink="#0000ff">
<center>Usuário: novousuario Senha: padrão</center>
<basefont SIZE=3> <form name=login> <div align=center><center> <table width=225 border=0 cellpadding=3><tr><td colspan=2> <div align=center> <center> <font face="Verdana, Arial, Helvetica, sans-serif" size=2><B>Área esclusiva para usuários:</B></font> </center> </div></td></tr><tr align=center><td><font face="Verdana, Arial, Helvetica, sans-serif" size=2><B>Login:</B></font></td><td><font face="Verdana, Arial, Helvetica, sans-serif" size=2> <input type=text name=username size=20> </font></td></tr><tr align=center><td> <font face="Verdana, Arial, Helvetica, sans-serif" size=2><B>Senha:</B></font></td><td><font face="Verdana, Arial, Helvetica, sans-serif" size=2> <input type=password name=password size=20> </font></td></tr><tr align=center><td colspan=2 align=center> <input type=button value=Entrar onClick=Login()></td></tr> </table> </center></div> </form>
<div align=center> </div>
<p align=center>&nbsp;</p>

</body>

</html>

<div id="app">
  <div ui-view></div>
</div>
<img src="https://static.todamateria.com.br/upload/be/mv/bem-vindo-benvindo-og.jpg">

<!DOCTYPE html>
 
<html>
 <head>
 <title> Como criar um formulário completo </title>
 <meta name="description" content="Aprenda a criar um site completo que usa formulários em HTML">
 <meta http-equiv="Content-Type" content="text/html; charset=utf-8"> 
 </head>
<img src="https://2.bp.blogspot.com/-9Lnh0EZUez4/Wa6kZcRqkCI/AAAAAAAAH2Q/b1Zp15fAs50QDWizleXX3-_1CgR3qzlbgCLcBGAs/s1600/inicioii.gif">
 <body>
  <h1> Bem vindo</h1> 
  <h2> Preencha o formulário abaixo completo</h2><br />

<form action="Script_do_Formulario.php" method="post">

<!-- DADOS PESSOAIS-->
<fieldset>
 <legend>Dados Pessoais</legend>
 <table cellspacing="10">
  <tr>
   <td>
    <label for="nome">Nome: </label>
   </td>
   <td align="left">
    <input type="text" name="email">
   </td>
   <td>
    <label for="sobrenome">Sobrenome: </label>
   </td>
   <td align="left">
    <input type="text" name="sobrenome">
   </td>
  </tr>
  <tr>
   <td>
    <label>Nascimento: </label>
   </td>
   <td align="left">
    <input type="text" name="dia" size="2" maxlength="2" value="dd"> 
   <input type="text" name="mes" size="2" maxlength="2" value="mm"> 
   <input type="text" name="ano" size="4" maxlength="4" value="aaaa">
   </td>
  </tr>
  <tr>
   <td>
    <label for="rg">RG: </label>
   </td>
   <td align="left">
    <input type="text" name="rg" size="13" maxlength="13"> 
   </td>
  </tr>
  <tr>
   <td>
    <label>CPF:</label>
   </td>
   <td align="left">
    <input type="text" name="cpf" size="9" maxlength="9"> - <input type="text" name="cpf2" size="2" maxlength="2">
   </td>
  </tr>
 </table>
</fieldset>

<br />
<!-- ENDEREÇO -->
<fieldset>
 <legend>Dados de Endereço</legend>
 <table cellspacing="10">

  <tr>
   <td>
    <label for="rua">Rua:</label>
   </td>
   <td align="left">
    <input type="text" name="rua">
   </td>
   <td>
    <label for="numero">Numero:</label>
   </td>
   <td align="left">
    <input type="text" name="numero" size="4">
   </td>
  </tr>
  <tr>
   <td>
    <label for="bairro">Bairro: </label>
   </td>
   <td align="left">
    <input type="text" name="bairro">
   </td>
  </tr>
  <tr>
   <td>
    <label for="estado">Estado:</label>
   </td>
   <td align="left">
    <select name="estado"> 
    <option value="ac">Acre</option> 
    <option value="al">Alagoas</option> 
    <option value="am">Amazonas</option> 
    <option value="ap">Amapá</option> 
    <option value="ba">Bahia</option> 
    <option value="ce">Ceará</option> 
    <option value="df">Distrito Federal</option> 
    <option value="es">Espírito Santo</option> 
    <option value="go">Goiás</option> 
    <option value="ma">Maranhão</option> 
    <option value="mt">Mato Grosso</option> 
    <option value="ms">Mato Grosso do Sul</option> 
    <option value="mg">Minas Gerais</option> 
    <option value="pa">Pará</option> 
    <option value="pb">Paraíba</option> 
    <option value="pr">Paraná</option> 
    <option value="pe">Pernambuco</option> 
    <option value="pi">Piauí</option> 
    <option value="rj">Rio de Janeiro</option> 
    <option value="rn">Rio Grande do Norte</option> 
    <option value="ro">Rondônia</option> 
    <option value="rs">Rio Grande do Sul</option> 
    <option value="rr">Roraima</option> 
    <option value="sc">Santa Catarina</option> 
    <option value="se">Sergipe</option> 
    <option value="sp">São Paulo</option> 
    <option value="to">Tocantins</option> 
   </select>
   </td>
  </tr>
  <tr>
   <td>
    <label for="cidade">Cidade: </label>
   </td>
   <td align="left">
    <input type="text" name="cidade">
   </td>
  </tr>
  <tr>
   <td>
    <label for="cep">CEP: </label>
   </td>
   <td align="left">
    <input type="text" name="cep" size="5" maxlength="5"> - <input type="text" name="cep2" size="3" maxlength="3">
   </td>
  </tr>
 </table>
</fieldset>
<br />

<!-- DADOS DE LOGIN -->
<fieldset>
 <legend>Dados de login</legend>
 <table cellspacing="10">
  <tr>
   <td>
    <label for="email">E-mail: </label>
   </td>
   <td align="left">
    <input type="text" name="email">
   </td>
  </tr>
  <tr>
   <td>
    <label for="imagem ">Imagem de perfil:</label>
   </td>
   <td>
    <input type="file" name="imagem" >

   </td>
  </tr>
  <tr>
   <td>
    <label for="login">Login de usuário: </label>
   </td>
   <td align="left">
    <input type="text" name="login">
   </td>
  </tr>
  <tr>
   <td>
    <label for="pass">Senha: </label>
   </td>
   <td align="left">
    <input type="password" name="pass">
   </td>
  </tr>
  <tr>
   <td>
    <label for="passconfirm">Confirme a senha: </label>
   </td>
   <td align="left">
    <input type="password" name="passconfirm">
   </td>
  </tr>
 </table>
</fieldset>
<br />
<input type="submit">
<input type="reset" value="Limpar">
</form>

 </body>
</html>
 <link
      rel="stylesheet"
      href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-
      beta.2/css/bootstrap.min.css" crossorigin="anonymous">
    <meta name="viewport" content="width=device-width, initial-
      scale=1">
    <link rel="icon" type="image/x-icon"
      href="favicon.ico">
  </head>
  <body>
    <div class="container">
      <app-root>
      </app- root> 
    </div>
    </pre> 
  </body>
</html>
<label for="login">Login de usuário: </label>
   </td>
   <td align="left">
    <input type="text" name="login">
   </td>
  </tr>
  <tr>
   <td>
    <label for="pass">Senha: </label>
   </td>
   <td align="left">
    <input type="password" name="pass">
   </td>
  </tr>
  <tr>
   <td>
    <label for="passconfirm">Confirme a senha: </label>
   </td>
   <td align="left">
    <input type="password" name="passconfirm">
   </td>
  </tr>
 </table>
</fieldset>
<br />
<input type="submit">
<input type="reset" value="Limpar">
</form>

 </body>
</html>
<form action="#" method="post">
  Name <input type="text" placeholder="First name"/>
  <input type="text" placeholder="Last name"/>
  Email <input type="text"/>
  Message <input type="textarea"/>
  <input type="submit" value="Send"/>
</form>
Formulário de Pré-Matrícula
  <fieldset>
  	<h3>Dados Pessoais:</h3>
  	
  	<p>Nome do Aluno:
  		<input type="text" required name="name" size="20" maxlength="40" id="fname" placeholder="Tiago"><br>
  	</p>		
  	<p>Nascimento (dd/mm/aaaa):
  		<input type="data" required name="dia" size="1" maxlength="2" id="dia" placeholder="dia">/
  		<input type="data" required name="mes" size="1" maxlength="2" id="mes" placeholder="mês">/
  		<input type="data" required name="ano" size="1" maxlength="4" id="ano" placeholder="ano">
  	</p>
  	<p>Nome da Mãe:
  		<input type="text" required name="mae" size="20" maxlength="40" id="mae" value="nome mãe" placeholder="Nome da mãe"><br>
  	</p>
  	<p>Nome do Pai:
  		<input type="text" required name="pai" size="20" maxlength="40" id="pai" value="nomepai">Nome do pai<br>
  	</p>
  	<p>Telefone: DDD (
  		<input type="tel" required name="ddd" size="1" maxlength="2" id="ddd"placeholder="DDD">)
  		Tel:<input type="tel" required name="telefone" size="5" maxlength="8" id="tel" placeholder="telefone">
  		Ramal:<input type="tel" required name="ramal" size="2" maxlength="4" id="ramal" placeholder="ramal"><br>
  	</p>
  	<p>E-mail:
  		<input type="email" required name="email" size="20" maxlength="40" id="email" placeholder="aaa@aaa.com" ><br>
  	</p>
  </fieldset>
  <fieldset>
    <html>
<head>
<script type="text/javascript">
function verifica() {
  if (document.forms[0].email.value.length == 0) {
    alert('Por favor, informe o seu EMAIL.');
	document.frmEnvia.email.focus();
    return false;
  }
  return true;
}
 
function checarEmail(){
if( document.forms[0].email.value=="" 
   || document.forms[0].email.value.indexOf('@')==-1 
     || document.forms[0].email.value.indexOf('.')==-1 )
	{
	   alert( "Por favor, informe um E-MAIL válido!" );
	   return false;
	}
}
</script>
</head>
<body>
<form method="post" action="" onSubmit="return ( verifica() )" name="frmEnvia">
   <label for="email">E-mail: </label>
   <input name="email" type="text" class="input" id="email" onblur="checarEmail();" />
   <input name="submit" type="submit" value=" ENVIAR " />
</form>
</body>
</html>
<title>Cadastrar Conta Bancária</title>
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" href="css/bootstrap.min.css">
	<link rel="stylesheet" href="css/font-awesome.min.css">
	<link rel="stylesheet" href="css/prototipo.css">
</head>
<body>
	<nav class="navbar navbar-default" role="navigation">
		<div class="container">
			<div class="navbar-header">
				<button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-ex1-collapse">
					<span class="sr-only">Toggle navigation</span>
					<span class="icon-bar"></span>
					<span class="icon-bar"></span>
					<span class="icon-bar"></span>
				</button>
				<a class="navbar-brand" href="#">PQ</a>
			</div>

			<div class="collapse navbar-collapse navbar-ex1-collapse">
				<ul class="nav navbar-nav">
					<li><a href="clientes.html">Clientes</a></li>
					<li><a href="notas-fiscais.html">Notas Fiscais</a></li>
					<li><a href="contas-receber.html">Contas a Receber</a></li>
					<li><a href="bancos.html">Bancos</a></li>
					<li class="active"><a href="contas-bancarias.html">Contas Bancárias</a></li>
					<li><a href="condicoes-pagamento.html">Condições de Pagamento</a></li>
					<li><a href="agencias.html">Agências</a></li>
					<li><a href="funcionarios.html">Funcionários</a></li>
				</ul>
				<ul class="nav navbar-nav navbar-right">
					<li><a href="login.html"><i class="fa fa-sign-out"></i> Sair</a></li>
				</ul>
			</div>
		</div>
	</nav>

	<div class="container">
		<div class="row">
			<div class="col-lg-12 col-xs-12">
				<div class="panel panel-default">
					<div class="panel-heading">
						<h3 class="panel-title">Cadastrar Conta Bancária</h3>
					</div>
					<div class="panel-body">
						<div class="row">
							<div class="col-lg-4">
								<form action="#">
									<div class="row">
										<div class="col-lg-12 col-xs-12">
											<div class="form-group">
												<label for="#" class="control-label">Banco</label>
												<select name="#" id="#" class="form-control">
													<option value="vendas" selected="selected">Bradesco</option>
												</select>
											</div>
										</div>

										<div class="col-lg-12 col-xs-12">
											<div class="form-group">
												<label for="#" class="control-label">Descrição</label>
												<input type="text" class="form-control" value="Conta Corrente do Bradesco">
											</div>
										</div>

										<div class="col-lg-12 col-xs-12">
											<div class="form-group">
												<label for="#" class="control-label">Conta</label>
												<input type="text" class="form-control" value="12345">
											</div>
										</div>

										<div class="col-lg-12 col-xs-12">
											<div class="form-group">
												<label for="#" class="control-label">Agência</label>
												<input type="text" class="form-control" value="12">
											</div>
										</div>

										<div class="col-lg-12 col-xs-12">
											<div class="form-group">
												<label for="#" class="control-label">Tipo</label>
												<div class="radio">
													<label>
														<input type="radio" name="optionsRadios" id="optionsRadios1" value="option1">
														Pessoa física
													</label>
												</div>
												<div class="radio">
													<label>
														<input type="radio" name="optionsRadios" id="optionsRadios2" value="option2" checked>
														Pessoa jurídica
													</label>
												</div>
											</div>
										</div>

										<div class="col-lg-12 col-xs-12">
											<div class="form-group">
												<div class="checkbox">
													<label>
														<input type="checkbox" value="" checked>
														Conta principal
													</label>
												</div>
											</div>
										</div>
									</div>
								</form>
							</div>
						</div>
					</div>
					<div class="panel-footer">
						<button type="button" class="btn btn-primary">Salvar</button>
						<a href="contas-bancarias.html" class="btn btn-default">Cancelar</a>
					</div>
				</div>
			</div>
		</div>
	</div>

	<script src="js/jquery.min.js"></script>
	<script src="js/bootstrap.min.js"></script>


</body>
</html>
<img src="https://image.slidesharecdn.com/ofimdainocnciacatarinagonalvestrabalho-111030212840-phpapp02/95/o-fim-da-inocncia-catarina-gonalves-trabalho-8-728.jpg?cb=1320010173">
