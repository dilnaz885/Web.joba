<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Кіру</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Кіру</h1>
    </header>
    <main>
        <form action="login_process.php" method="POST">
            <label for="username">Пайдаланушы аты:</label>
            <input type="text" id="username" name="username" required>
            
            <label for="password">Құпия сөз:</label>
            <input type="password" id="password" name="password" required>

            <button type="submit">Кіру</button>
        </form>
    </main>
    <footer>
        <p>© 2024, Біздің компания.</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Тіркелу</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Тіркелу</h1>
    </header>
    <main>
        <form action="register_process.php" method="POST">
            <label for="username">Пайдаланушы аты:</label>
            <input type="text" id="username" name="username" required>
            
            <label for="password">Құпия сөз:</label>
            <input type="password" id="password" name="password" required>

            <button type="submit">Тіркелу</button>
        </form>
    </main>
    <footer>
        <p>© 2024, Біздің компания.</p>
    </footer>
</body>
</html>
