# tela-de-site
contem tela de cadastro e login<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>login</title>
</head>
<body>
    <a href="tela.html">Voltar</a>
    <form id="loginForm">
    <div>
         <h1>Tela de login</h1>
             <label for="userLogin">Nome:</label>
             <input style="color: white; background: transparent; border: solid white;" class="form-control ls-login-bg-user input-lg" id="userLogin" type="text" aria-label="Usuário" placeholder="Usuário">
         <br><br>
             <label for="userPassword">Senha:</label>
             <input style="color: white; background: transparent; border: solid white;" class="form-control ls-login-bg-password input-lg" id="userPassword" type="password" aria-label="Senha" placeholder="Senha">
         <br><br>
         <input class="inputsubmit" type="submit" name="submit" value="Entrar">
    </div>
</form>
<script src="login.js"></script>
</body>
</html>

essa é a tela de login  caso voc já esteja cadastrado usei href pra lincar uma tela  a outra  usei o form  pra poder chamar com o script  ai criei os inputs e o botão de enviar

body{
    font-family: Arial, Helvetica, sans-serif;
    background: linear-gradient(to right, rgb(20, 147, 220), rgb(17, 54, 71));
    background: url(https://i.pinimg.com/originals/b9/83/f2/b983f254d6b60f20f4ac3db6ddbd2467.jpg);
}

div{
    background-color: rgba(0, 0, 0, 0.6);
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    padding: 80px;
    border-radius: 15px;
    color: white;
}
input{
    padding: 15px;
    border: none;
    outline: none;
    font-size: 15px;
}
.inputsubmit{
    background-color: blue;
    border: none;
    padding: 15px;
    width: 100%;
    border-radius: 10px;
    color: white;
}
.inputsubmit:hover{
    background-color: deepskyblue;
    cursor: pointer;
}

esse é o style do login 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style2.css">
    <title>Tela inicial</title>
</head>
<body>
    <h1>Seja bem-vindo ao nosso site :)</h1>
    <h2>Entre na sua conta se não tiver cadastre-se</h2>
    <a href="index.html">Voltar</a>
    <div class="box">
        <a href="index.html">Login</a>
        <a href="cadastro.html">Cadastra-se</a>
    </div>
</body>
</html>

essa é a primeira tela  ela leva pras outras duas  

body{
    font-family: Arial, Helvetica, sans-serif;
    background: linear-gradient(to right, rgb(20, 147, 220), rgb(17, 54, 71));
    background: url(https://i.pinimg.com/originals/b9/83/f2/b983f254d6b60f20f4ac3db6ddbd2467.jpg);
}
.box{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    background-color: rgba(0, 0, 0, 0.6);
    padding: 30px;
    border-radius: 15px;
}
a{
    text-decoration: none;
    color: white;
    border: 3px solid dodgerblue;
    border-radius: 10px;
    padding: 10px;
}
a:hover{
    background-color: dodgerblue;
    cursor: pointer;
}

e esse é o seu styl

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
    <link rel="stylesheet" href="style3.css">
    <title>Tela de login</title>
</head>
<a href="tela.html">Voltar</a>
<body>
  
    <form id="cadastroForm">
    <div class="container">
        <h1 style="color: black;">Tela de Cadastro</h1>
           <label style="color: black;" for="exampleInputNome1">Nome</label>
           <input style="background: transparent; color:white;" type="nome" class="form-control" id="usuario" placeholder="Usuário">
           <br>
           <label style="color: black;" for="exampleInputEmail1">Endereço de email</label>
           <input style="background: transparent; color:white;" type="email" class="form-control" id="email" aria-describedby="emailHelp" placeholder="Email">
           <br>
           <small id="emailHelp" class="form-text tex-muted ">Nunca vamos compartilhar seu email, com ninguém</small>
           <br>
           <label style="color: black;" for="exampleInputPassword1">Senha</label>
           <input style="background: transparent; color: white;" type="password" class="form-control" id="senha" placeholder="Senha"
           <br>
           <fieldset>
            <label style="color: black;" for="exampleInputPassword1">Confirmar Senha</label>
            <input style="background: transparent; color: white;" type="password" class="form-control" id="confirmarSenha" placeholder="Confirme Senha"
           <br>
        </fieldset>
        <div class="form-grou form-check">
        </div> 
           <!-- Botão para acionar modal -->
           <br>
           <button type="submit" class="btn btn-primary">Enviar</button>
  </div>
  </form>
  <script src="cadastro.js"></script>
</body>
</html>

<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
< script  src = " https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js "  integridade = "sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy"  crossorigin = "anônimo" ></ script >

esse foi a tela de cadastro  com nome email e senha

body{
    font-family:Arial, Helvetica, sans-serif;
    overflow: hidden;
    background: url(https://wallpaperaccess.com/full/1236474.jpg);
    background-size: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
    width: 100vw; 
}
.small{
    color: white;
}
.container{
    position: relative;
}
.form-control{
    background: none;
    border: none;
    border-bottom: 1px solid white;
    outline: none;
    color: white;
    font-size: 15px;
}

esse é seu style 

const loginForm = document.getElementById('loginForm');
loginForm.addEventListener('submit', function(event) {
  event.preventDefault();

  const userLogin = document.getElementById('userLogin').value;
  const userPassword = document.getElementById('userPassword').value;

  const cadastroData = localStorage.getItem('cadastroData');
  if (cadastroData) {
    const cadastroObj = JSON.parse(cadastroData);
    if (userLogin === cadastroObj.usuario && userPassword === cadastroObj.senha) {
      alert('Login bem-sucedido!');
      loginForm.reset();
      return;
    }
  }

  alert('Usuário ou senha inválidos!');
});

esse foi o script do login 

// Cadastro
const cadastroForm = document.getElementById('cadastroForm');
cadastroForm.addEventListener('submit', function(event) {
  event.preventDefault();

 
  const usuario = document.getElementById('usuario').value;
  const email = document.getElementById('email').value;
  const senha = document.getElementById('senha').value;
  const confirmarSenha = document.getElementById('confirmarSenha').value;


  if (senha !== confirmarSenha) {
    alert('As senhas não coincidem!');
    return;
  }

 
  const cadastroData = {
    usuario: usuario,
    email: email,
    senha: senha
  };
  localStorage.setItem('cadastroData', JSON.stringify(cadastroData));

  alert('Cadastro realizado com sucesso!');
  cadastroForm.reset();
});

e esse do  o scripyt do cadastro
