<!DOCTYPE html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .login{
            top:50%;
            left: 50%;
            transform: translate(-50%,-50%);
            position: absolute;
            border: 1px solid rgba(0, 0, 0, 0.409);
            padding: 2rem;
            border-radius: 6px;
        }
        *{
            font-family: sans-serif;
        }
        input{
            margin-top: 0.9rem;
            margin-bottom: 0.5rem;
        }
        button{
            background-color: #0071bd;
            color:white;
            padding: 0.5rem 0.9rem;
            font-size: medium;
            border: none;
            outline: none;
            border-radius: 6px;
            text-align: center;
            margin-left: 30%;
        }
        
    </style>
</head>
<body>
    <div  class="login">
        <h1>Login to LMS</h1>
        <label>Email id</label><br/>
        <input type="text" placeholder="enter email id" /><br/>
        <label>Password</label><br/>
        <input type="password" placeholder="enter password" /><br/>
        <img class="rotate" width="80px" height="80px" src="Sample.jpeg" />
        <button>Login</button>
    </div>
</body>
</html> # sample-htmlcss
