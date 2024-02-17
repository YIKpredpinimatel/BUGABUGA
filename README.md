# BUGABUGA
<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>главная страница</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }

        nav {
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 10px;
        }

        main {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 5px;
        }

        form {
            margin-top: 20px;
            display: flex;
            flex-direction: column;
        }

        label {
            margin-bottom: 5px;
        }

        input,
        textarea,
        select {
            width: 100%;
            padding: 5px;
            margin-bottom: 10px;
            border-radius: 3px;
            border: 1px solid #ccc;
        }

        button {
            padding: 10px;
            background-color: #333;
            color: #fff;
            border: none;
            border-radius: 3px;
            cursor: pointer;
        }

        button:hover {
            background-color: #555;
        }
    </style>
</head>

<body>
    <header>
        <h1>мой сайт</h1>
        <nav>
            <ul>
                <li><a href="#">главная</a></li>
                <li><a href="#">о нас</a></li>
                <li><a href="#">контакты</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <h2>загрузка публикации</h2>
        <form>
            <label for="title">название публикации:</label>
            <input type="text" id="title" name="title">
            <label for="content">содержание публикации:</label>
            <textarea id="content" name="content"></textarea>
            <label for="category">категория:</label>
            <select id="category" name="category">
                <option value="olympiad">олимпиадная</option>
                <option value="educational">учебная</option>
            </select>
            <label for="grade">класс:</label>
            <select id="grade" name="grade">
                <option value="1">1</option>
                <option value="2">2</option>
                <option value="3">3</option>
                <option value="4">4</option>
                <option value="5">5</option>
                <option value="6">6</option>
                <option value="7">7</option>
                <option value="8">8</option>
                <option value="9">9</option>
                <option value="10">10</option>
                <option value="11">11</option>
            </select>
            <label for="class">буква класса:</label>
            <select id="class" name="class">
                <option value="a">а</option>
                <option value="b">б</option>
                <option value="c">в</option>
                <option value="d">д</option>
            </select>
            <button type="submit">опубликовать</button>
        </form>
    </main>
</body>

</html>
