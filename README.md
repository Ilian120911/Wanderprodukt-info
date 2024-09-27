<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mein Shop</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
        }

        main {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }

        section {
            margin-bottom: 40px;
            padding: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);

        }

        .product {
            border: 1px solid #ccc;
            margin: 20px 0;
            padding: 40px;
            border-radius: 8px;
           
        }

        .product h3 {
            margin-top: 0;
        }

        button {
            background: #28a745;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background: #218838;
        }

        footer {
            text-align: center;
            padding: 10px 0;
            background: #333;
            color: #fff;
            position: relative;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Willkommen im Wandershop</h1>
        <nav>
            <ul>
                <li><a href="#home">Startseite</a></li>
                <li><a href="#products">Produkte</a></li>
                <li><a href="#about">Über uns</a></li>
                <li><a href="#contact">Kontakt</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <h2>Wandershop</h2>
            <p>Hier findest du Produkte zum Wandern!</p>
        </section>

        <section id="products">
        
         <h2>Produkte: <br>
 <a href="test.html">Zelte</a> 
            <img src="https://img.icons8.com/?size=100&id=9899&format=png&color=000000" width="50" height="60" alt="Paris" align="center">
<br>
<a href="">Schlafsäcke</a> 

</h2>
            
            
                   </section>

        <section id="about">
            <h2>Über uns</h2>
            <p>Wir sind ein kleiner Online-Shop, der die besten Produkte für dich auswählt.</p>
        </section>

        <section id="contact">
            <h2>Kontakt</h2>
            <p>Bei Fragen kannst du uns jederzeit erreichen.</p>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">E-Mail:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Nachricht:</label>
                <textarea id="message" name="message" required></textarea>
                <button type="submit">Absenden</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Mein Shop. Alle Rechte vorbehalten.</p>
    </footer>
</body>
</html>


