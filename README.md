<!DOCTYPE html>
<html lang="lv">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SQL Spēles apgūšanas starpnieks</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            margin: 0;
            color: black;
            line-height: 1.6;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 24px 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 1.6em;
            font-weight: normal;
        }
        main {
            max-width: 720px;
            margin: 32px auto;
            background-color: white;
            padding: 32px;
        }
        section + section {
            margin-top: 36px;
        }
        h2 {
            text-align: center;
            font-size: 1.2em;
            font-weight: normal;
            margin: 0 0 16px;
        }
        p {
            margin: 8px 0;
        }
        ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }
        li {
            background-color: #e7f3e7;
            margin: 4px 0;
            padding: 8px 12px;
        }
        a {
            display: inline-block;
            margin-top: 16px;
            color: #4CAF50;
        }
        footer {
            text-align: center;
            margin: 32px 20px;
            color: #555;
            font-size: 0.85em;
        }
        footer p {
            margin: 4px 0;
        }
        .credit {
            font-size: 0.9em;
            opacity: 0.8;
        }
    </style>
</head>
<body>
    <header>
        <h1>SQL Spēles apgūšanas starpnieks</h1>
    </header>

    <main>
        <section>
            <h2>Par spēli</h2>
            <p>Šī spēle palīdz apgūt SQL, izmantojot RPG Maker MV. Kustība notiek ar <strong>bultiņām</strong> vai <strong>kreisās peles pogas nospiešanu</strong>. Saskarsme ar personāžiem notiek ar <strong>Enter</strong> vai <strong>kreisās pogas uzspiešanu</strong>.</p>
        </section>

        <section>
            <h2>9 līmeņi SQL apguvei</h2>
            <ul>
                <li><strong>1. līmenis:</strong> CREATE TABLE</li>
                <li><strong>2. līmenis:</strong> INSERT INTO</li>
                <li><strong>3. līmenis:</strong> SELECT</li>
                <li><strong>4. līmenis:</strong> UPDATE</li>
                <li><strong>5. līmenis:</strong> DELETE</li>
                <li><strong>6. līmenis:</strong> ORDER BY, LIMIT</li>
                <li><strong>7. līmenis:</strong> JOIN (INNER, LEFT)</li>
                <li><strong>8. līmenis:</strong> GROUP BY, COUNT, SUM, AVG</li>
                <li><strong>9. līmenis:</strong> Fināla tests</li>
            </ul>
            <a href="https://notepadexe.itch.io/sql-quest">SQL quest by Notepad.exe</a>
        </section>

        <section>
            <h2>Vadība</h2>
            <p><strong>Kustība:</strong> bultiņas vai kreisā peles poga uz mērķa vietu</p>
            <p><strong>Saskarsme ar personāžiem:</strong> Enter vai kreisā peles poga</p>
            <p><strong>Piekļuve meņu:</strong> poga ESC</p>
        </section>
    </main>

    <footer>
        <p class="credit">SMU ir tapis Junior Achivement Latvia programmas «Skolēnu mācību uzņēmums» ietvaros sadarbībā ar RTU Austrumlatvijas Tehnoloģiju vidusskolu.</p>
        <p>&copy; 2025 SQL Spēles Apgūšanas Starpnieks</p>
    </footer>
</body>
</html>
