# servi-o-teste
<div id="app">
  <div ui-view></div>
</div>
<!DOCTYPE html>
 
<html>
 <head>
 <title> Como criar um formulário completo </title>
 <meta name="description" content="Aprenda a criar um site completo que usa formulários em HTML">
 <meta http-equiv="Content-Type" content="text/html; charset=utf-8"> 
 </head>
<img src="https://www.universidadedolivro.com.br/wp-content/uploads/2020/08/Mecanica-produto-teste-nao-comprar-p-1533242083167.jpg">
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
