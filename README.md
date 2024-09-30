<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Інформація про GNU/Linux</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        h1, h2 {
            color: #333;
        }
        h1 {
            font-size: 2.5em;
        }
        h2 {
            font-size: 1.8em;
            margin-top: 20px;
        }
        p {
            margin: 20px auto;
            max-width: 800px;
            text-align: justify;
        }
        ul {
            list-style-type: none;
            padding: 0;
            max-width: 800px;
            margin: 20px auto;
        }
        ul li {
            background: #eee;
            margin: 5px 0;
            padding: 10px;
            border-left: 5px solid #4CAF50;
        }
        pre {
            background: #333;
            color: #fff;
            padding: 15px;
            border-radius: 5px;
            overflow-x: auto;
            max-width: 800px;
            margin: 20px auto;
        }
        a {
            color: #4CAF50;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>GNU/Linux</h1>
</header>

<main>
    <p>GNU/Linux — це вільна і відкрита операційна система, що складається з ядра Linux і програмного забезпечення GNU.</p>

    <section>
        <h2>Популярні дистрибутиви</h2>
        <ul>
            <li>Ubuntu</li>
            <li>Debian</li>
            <li>Fedora</li>
            <li>CentOS</li>
            <li>Arch Linux</li>
            <li>Linux Mint</li>
            <li>openSUSE</li>
        </ul>
    </section>

    <section>
        <h2>Команди Linux CLI</h2>
        <ul>
            <li><strong>pwd</strong> — показує поточний робочий каталог</li>
            <li><strong>echo</strong> — виводить текст на екран</li>
            <li><strong>ls</strong> — показує список файлів і каталогів</li>
            <li><strong>cd</strong> — змінює поточний каталог</li>
            <li><strong>touch</strong> — створює новий файл</li>
            <li><strong>mkdir</strong> — створює каталог</li>
            <li><strong>cp</strong> — копіює файли</li>
            <li><strong>mv</strong> — переміщує або перейменовує файли</li>
            <li><strong>rm</strong> — видаляє файли</li>
            <li><strong>history</strong> — показує історію команд</li>
        </ul>
    </section>

    <section>
        <h2>BASH-скрипт авторизації</h2>
        <pre>
#!/bin/bash

USERNAME="admin"
PASSWORD="password123"

echo "Введіть ім'я користувача:"
read input_user

if [ "$input_user" == "$USERNAME" ]; then
    echo "Введіть пароль:"
    read -s input_pass
    
    if [ "$input_pass" == "$PASSWORD" ]; then
        echo "Авторизація пройшла успішно!"
    else
        echo "Невірний пароль."
    fi
else
    echo "Невірне ім'я користувача."
fi
        </pre>
    </section>

    <section>
        <h2>Джерела</h2>
        <ul>
            <li><a href="https://www.kernel.org/doc/">Офіційна документація GNU/Linux</a></li>
            <li><a href="https://www.gnu.org/software/bash/manual/">Посібник по BASH</a></li>
            <li><a href="https://linuxcommand.org/">Linux Command Line Tutorial</a></li>
        </ul>
    </section>
</main>

<footer>
    &copy; 2024 Інформація про GNU/Linux
</footer>

</body>
</html>
        <li><a href="https://www.kernel.org/doc/">Офіційна документація GNU/Linux</a></li>
        <li><a href="https://www.gnu.org/software/bash/manual/">Посібник по BASH</a></li>
        <li><a href="https://linuxcommand.org/">Linux Command Line Tutorial</a></li>
    </ul>
</body>
</html>
