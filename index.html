<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Энциклопедия Мата</title>
    <script src="https://telegram.org/js/telegram-web-app.js"></script>
    <style>
        * {
            box-sizing: border-box;
            user-select: none;
            -webkit-user-select: none;
        }
        body {
            margin: 0;
            padding: 16px;
            background: linear-gradient(135deg, #12041a, #1f0c2e, #0a0512);
            color: #fff;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .header {
            text-align: center;
            margin-bottom: 20px;
        }
        h1 {
            font-size: 26px;
            margin: 0 0 5px 0;
            color: #ff2a85;
            text-shadow: 0 0 10px rgba(255, 42, 133, 0.5);
        }
        .subtitle {
            font-size: 13px;
            color: #a090c0;
        }
        .card {
            background: rgba(25, 15, 40, 0.8);
            border: 1px solid #4a1f6b;
            border-radius: 16px;
            padding: 20px;
            width: 100%;
            max-width: 400px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.5);
            margin-bottom: 20px;
        }
        .word-title {
            font-size: 28px;
            font-weight: bold;
            color: #00ffff;
            margin-bottom: 10px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .badge {
            font-size: 11px;
            background: #ff2a85;
            color: #fff;
            padding: 4px 8px;
            border-radius: 8px;
            text-transform: uppercase;
        }
        .section-title {
            font-size: 12px;
            color: #ff79c6;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-top: 12px;
            margin-bottom: 4px;
        }
        .section-text {
            font-size: 14px;
            color: #e0d0f0;
            line-height: 1.4;
        }
        .btn {
            background: linear-gradient(135deg, #ff2a85, #b80058);
            color: white;
            border: none;
            border-radius: 12px;
            padding: 14px;
            font-size: 16px;
            font-weight: bold;
            width: 100%;
            max-width: 400px;
            cursor: pointer;
            box-shadow: 0 4px 15px rgba(255, 42, 133, 0.4);
            transition: transform 0.1s ease;
        }
        .btn:active {
            transform: scale(0.96);
        }
    </style>
</head>
<body>

    <div class="header">
        <h1>🗣 Лингво-Кутеж</h1>
        <div class="subtitle">Энциклопедия экспрессивной лексики</div>
    </div>

    <div class="card" id="cardContainer">
        <div class="word-title">
            <span id="wordName">Блядь</span>
            <span class="badge" id="wordLang">Русский</span>
        </div>
        
        <div class="section-title">📜 Происхождение</div>
        <div class="section-text" id="wordOrigin">Происходит от праславянского *blędь («заблуждение», «ошибка», «обман»). Изначально означало вовсе не то, что сейчас, а болтовню или заблуждение.</div>

        <div class="section-title">🎯 Когда использовать</div>
        <div class="section-text" id="wordContext">Идеально подходит для выражения спектра эмоций от легкого удивления до экзистенциального ужаса при падении бутерброда маслом вниз.</div>

        <div class="section-title">🔥 Уровень боли</div>
        <div class="section-text" id="wordLevel">8 из 10 (Классика жанра)</div>
    </div>

    <button class="btn" id="nextBtn">Случайное слово 🎲</button>

    <script>
        const database = [
            {
                name: "Блядь",
                lang: "Русский",
                origin: "От праславянского *blędь («заблуждение», «обман»). Раньше так называли лжецов и пустословов.",
                context: "Универсальный маркер боли, неожиданности, радости или связующее звено в предложении.",
                level: "8 / 10 (Классика)"
            },
            {
                name: "Fuck",
                lang: "Английский",
                origin: "Предположительно германские корни (значение «ударять», «толкать» или связано с размножением). Впервые в судах зафиксировано в 15 веке.",
                context: "Самое гибкое слово в английском языке. Может быть глаголом, существительным, наречием и даже междометием.",
                level: "9 / 10 (Международный)"
            },
            {
                name: "Ёлки-палки",
                lang: "Эвфемизм",
                origin: "Чисто народное изобретение для ситуаций, когда материться нельзя (при бабушке или детях), но пар выпустить надо.",
                context: "Применяется при легком разочаровании, когда споткнулся о порог.",
                level: "2 / 10 (Безопасный)"
            },
            {
                name: "Motherfucker",
                lang: "Английский",
                origin: "Американский сленг начала XX века. Изначально — оскорбление высшей степени тяжести.",
                context: "В фильмах Тарантино используется как знак уважения или глубокого презрения. Зависит от интонации.",
                level: "10 / 10 (Тяжелая артиллерия)"
            },
            {
                name: "Пипец",
                lang: "Сленг",
                origin: "Мягкая цензурная замена матерного аналога на букву «П». Стало культовым в 90-х и нулевых.",
                context: "Когда ситуация вышла из-под контроля, но ругаться матом культурный уровень еще позволяет.",
                level: "4 / 10 (Бытовой)"
            }
        ];

        const wordName = document.getElementById('wordName');
        const wordLang = document.getElementById('wordLang');
        const wordOrigin = document.getElementById('wordOrigin');
        const wordContext = document.getElementById('wordContext');
        const wordLevel = document.getElementById('wordLevel');
        const nextBtn = document.getElementById('nextBtn');

        if (window.Telegram && window.Telegram.WebApp) {
            window.Telegram.WebApp.ready();
            window.Telegram.WebApp.expand();
        }

        nextBtn.addEventListener('click', () => {
            if (window.Telegram && window.Telegram.WebApp && window.Telegram.WebApp.HapticFeedback) {
                window.Telegram.WebApp.HapticFeedback.impactOccurred('medium');
            }
            
            const randomIndex = Math.floor(Math.random() * database.length);
            const item = database[randomIndex];

            wordName.textContent = item.name;
            wordLang.textContent = item.lang;
            wordOrigin.textContent = item.origin;
            wordContext.textContent = item.context;
            wordLevel.textContent = item.level;
        });
    </script>
</body>
</html>
