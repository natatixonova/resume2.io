<!DOCTYPE html>
<html>
<head>
    <title>Резюме - Тихонова Наталья Николаевна</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f3f3f3;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }

        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }

        .personal-info {
            border: 1px solid #ccc;
            padding: 20px;
            margin-bottom: 20px;
        }

        .experience {
            border: 1px solid #ccc;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: #333;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        ul li {
            margin-bottom: 10px;
        }

        button {
            background-color: #333;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            margin-top: 10px;
        }

        button:hover {
            background-color: #555;
        }
    </style>
</head>
<body>

<header>
    <h1>Резюме - Тихонова Наталья Николаевна</h1>
</header>

<div class="container">
    <div class="personal-info">
        <h2>Личная информация</h2>
        <ul>
            <li>Имя: Тихонова Наталья Николаевна</li>
            <li>курсант группы 2011</li>
            <li>Возраст: 18 лет</li>
            <li>Телефон: 8 905 450 90 83</li>
            <li>Email: nata.tixonova.12r@mail.ru</li>
        </ul>
    </div>

    <div class="experience">
        <h2>Опыт работы</h2>
        <ul>
            <li>Изучение следующих программ: MS Word, MS PowerPoint, MS Excel, MS Access, MS Publisher, Photoshop, Yandex. Browser, Google Chrome, Python.</li>
        </ul>
    </div>
    <div class="experience">
        <h2>Образование</h2>
        <ul>
            <li>МБОУ СОШ №8 г. Миллерово Ростовская область 01.09.2012 — 25.05.2023</li>
        </ul>
    </div>
    <div class="experience">
        <h2>Личные достиженния</h2>
        <ul>
            <li>По окончании школы получила золотую медаль  «За Особые успехи в учении», золотую медаль «За Особые успехи в учении выпускнику Дона»</li>
        </ul>
    </div>

    <button onclick="printResume()">Распечатать резюме</button>
</div>

<script>
    function printResume() {
        window.print();
    }
</script>

</body>
</html>
