<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <title>اتصل بنا | Azra Market</title>
    <style>
        body {
            direction: rtl;
            font-family: Arial;
            padding: 30px;
            background-color: #fefefe;
        }
        h2 {
            color: #8e44ad;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin-top: 8px;
            margin-bottom: 16px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }
        button {
            background-color: #8e44ad;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #732d91;
        }
    </style>
</head>
<body>

    <h2>اتصل بنا</h2>
    <p>لأي استفسار أو طلب، يرجى تعبئة النموذج التالي:</p>

    <form onsubmit="sendMessage(event)">
        <label>الاسم:</label>
        <input type="text" id="name" required>

        <label>البريد الإلكتروني:</label>
        <input type="email" id="email" required>

        <label>الرسالة:</label>
        <textarea id="message" rows="4" required></textarea>

        <button type="submit">إرسال</button>
    </form>

    <p>أو تواصل معنا مباشرة عبر:</p>
    <ul>
        <li>الهاتف: 0770 000 000</li>
        <li>واتساب: <a href="https://wa.me/213770000000" target="_blank">اضغط هنا</a></li>
        <li>البريد: azramarket@example.com</li>
    </ul>

    <p><a href="index.html">العودة إلى الرئيسية</a></p>

    <script>
        function sendMessage(e) {
            e.preventDefault();
            alert("تم إرسال رسالتك بنجاح! سنتواصل معك قريباً.");
            document.getElementById("name").value = "";
            document.getElementById("email").value = "";
            document.getElementById("message").value = "";
        }
    </script>

</body>
</html>
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <title>خدمة التوصيل | Azra Market</title>
    <style>
        body {
            direction: rtl;
            font-family: Arial;
            padding: 30px;
            background-color: #fff;
        }
        h2 {
            color: #8e44ad;
        }
    </style>
</head>
<body>

    <h2>خدمة التوصيل</h2>

    <p>نقدم خدمة توصيل سريعة وآمنة إلى جميع ولايات الجزائر.</p>

    <ul>
        <li>التوصيل داخل ولاية مستغانم: <strong>300 دج</strong></li>
        <li>التوصيل للولايات الكبرى (الجزائر، وهران، قسنطينة...): <strong>500 دج</strong></li>
        <li>مدة التوصيل: من 2 إلى 5 أيام عمل</li>
        <li>الدفع عند الاستلام متاح</li>
    </ul>

    <p>لمزيد من المعلومات، يرجى <a href="contact.html">الاتصال بنا</a>.</p>

    <p><a href="index.html">العودة إلى الرئيسية</a></p>

</body>
</html>
<nav>
    <a href="index.html">الرئيسية</a> |
    <a href="contact.html">اتصل بنا</a> |
    <a href="policy.html">سياسة الاستبدال</a> |
    <a href="delivery.html">خدمة التوصيل</a>
</nav>
