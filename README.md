<p><!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PIRD - ProinnovaRD</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }

        .header {
            background-color: #232f3e;
            color: white;
            padding: 10px 20px;
        }

        .top-bar {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo-location {
            display: flex;
            align-items: center;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            margin-right: 15px;
        }

        .location {
            font-size: 14px;
        }

        .search-container {
            display: flex;
            flex-grow: 1;
            justify-content: center;
            max-width: 600px;
        }

        .search-bar {
            width: 100%;
            padding: 10px;
            border: none;
            border-radius: 4px 0 0 4px;
            font-size: 16px;
        }

        .search-btn {
            padding: 10px;
            background-color: #febd69;
            border: none;
            border-radius: 0 4px 4px 0;
            cursor: pointer;
        }

        .contact-btn a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            background-color: #ff9900;
            border-radius: 4px;
        }

        .contact-btn a:hover {
            background-color: #e68a00;
        }

        .cart-container {
            margin-left: 20px;
        }

        .nav-bar {
            margin-top: 10px;
        }

        .nav-bar ul {
            list-style: none;
            padding: 0;
            display: flex;
        }

        .nav-bar ul li {
            margin-right: 15px;
        }

        .nav-bar ul li a {
            color: white;
            text-decoration: none;
            font-size: 16px;
            padding: 10px;
            display: block;
        }

        .nav-bar ul li a:hover {
            background-color: #37475a;
            border-radius: 4px;
        }

        .contact-form {
            max-width: 500px;
            margin: 50px auto;
            padding: 20px;
            background-color: #f3f3f3;
            border-radius: 8px;
        }

        .contact-form h2 {
            text-align: center;
            margin-bottom: 20px;
        }

        .contact-form label {
            display: block;
            margin-bottom: 5px;
        }

        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        .contact-form button {
            width: 100%;
            padding: 10px;
            background-color: #232f3e;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        .contact-form button:hover {
            background-color: #37475a;
        }
    </style>
</head>
<body>
    <header class="header">
        <div class="top-bar">
            <div class="logo-location">
                <span class="logo">PIRD</span>
                <span class="location">Dominican Republic</span>
            </div>
            <div class="search-container">
                <input type="text" class="search-bar" placeholder="Buscar en ProinnovaRD">
                <button class="search-btn">🔍</button>
            </div>
            <div class="contact-btn">
                <a href="#contacto">Contacto</a>
            </div>
            <div class="cart-container">
                <a href="cart.html">Cart</a>
            </div>
        </div>
        <nav class="nav-bar">
            <ul>
                <li><a href="#todo">Todo</a></li>
                <li><a href="#metas">Metas</a></li>
                <li><a href="#nosotros">Nosotros</a></li>
                <li><a href="#informacion">Información</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <div id="contacto" class="contact-form">
            <h2>Contacto</h2>
            <form action="https://formsubmit.co/jg2777613@gmail.com" method="POST">
                <label for="name">Nombre:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Correo Electrónico:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Mensaje:</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit">Enviar</button>
            </form>
        </div>
    </main>
</body>
</html>

</p>
