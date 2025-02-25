# architecture-landing-page
<!DOCTYPE html>
<html lang="he">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>אדריכלות ובנייה - שם העסק</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            direction: rtl;
            text-align: center;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            font-size: 24px;
        }
        .container {
            padding: 40px;
        }
        .btn {
            background-color: #007bff;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            font-size: 18px;
            border-radius: 5px;
            display: inline-block;
            margin-top: 20px;
        }
        .contact-form {
            background: white;
            padding: 20px;
            margin: 20px auto;
            width: 50%;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #28a745;
            color: white;
            border: none;
            padding: 10px;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
        }
    </style>
</head>
<body>

    <header>
        ברוכים הבאים ל-שם העסק - מומחים באדריכלות ובנייה
    </header>

    <div class="container">
        <h1>תכנון, עיצוב ובנייה - ברמה הגבוהה ביותר</h1>
        <p>אנו מתמחים ביצירת פתרונות אדריכלות מותאמים אישית, עיצוב פנים ותכנון מתקדם.</p>
        <a href="#contact" class="btn">צרו קשר</a>
    </div>

    <div id="contact" class="contact-form">
        <h2>השאירו פרטים ונחזור אליכם</h2>
        <form>
            <input type="text" placeholder="שם מלא" required>
            <input type="email" placeholder="אימייל" required>
            <input type="tel" placeholder="טלפון" required>
            <textarea placeholder="הודעה" rows="4" required></textarea>
            <button type="submit">שלח</button>
        </form>
    </div>

</body>
</html>
