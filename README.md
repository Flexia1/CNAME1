# CNAME1
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fahrschule Butterfly - Anmeldung</title>
    <link rel="stylesheet" href="style.css"> 
</head>
<body>
    <header>
        <h1>Fahrschule Butterfly</h1>
        <nav>
            <ul>
                <li><a href="#">Startseite</a></li>
                <li><a href="#">Über uns</a></li>
                <li><a href="#">Führerscheinklassen</a></li>
                <li><a href="#">Preise</a></li>
                <li><a href="#">Kontakt</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section>
            <h2>Online-Anmeldung</h2>
            <form action="/anmeldung" method="post"> 
                <label for="vorname">Vorname:</label>
                <input type="text" id="vorname" name="vorname" required>

                <label for="nachname">Nachname:</label>
                <input type="text" id="nachname" name="nachname" required>

                <label for="email">E-Mail:</label>
                <input type="email" id="email" name="email" required>

                <label for="fuehrerschein">Gewünschte Führerscheinklasse:</label>
                <select id="fuehrerschein" name="fuehrerschein">
                    <option value="">-- Bitte auswählen --</option>
                    <option value="A">A</option>
                    <option value="A1">A1</option>
                    <option value="B">B</option>
                </select>

                <button type="submit">Anmelden</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 Fahrschule Butterfly</p>
    </footer>
</body>
</html>
