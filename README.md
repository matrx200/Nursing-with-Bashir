# Nursing-with-Bashir
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مدونة الباش ممرض بشير</title>
    <!-- تضمين Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        /* تنسيق عام */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        /* تنسيق الهيدر */
        header {
            background-color: #4CAF50; /* أخضر فاتح */
            color: white;
            padding: 60px 20px;
            position: relative;
            overflow: hidden;
        }

        /* شكل ECG في الخلفية */
        header::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 200 20"><path d="M0 10 Q 50 15, 100 10 T 200 10" stroke="white" stroke-width="2" fill="none" /></svg>') repeat-x;
            opacity: 0.3;
        }

        /* تنسيق العنوان */
        h1 {
            font-size: 3rem;
            margin: 0;
        }

        /* تنسيق القائمة */
        nav {
            margin: 20px 0;
        }

        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #4CAF50;
            font-weight: bold;
        }

        /* تنسيق الأيقونات */
        .icons {
            margin-top: 20px;
            font-size: 2.5rem;
        }

        .icons i {
            margin: 0 10px;
        }

        /* تنسيق الفوتر */
        footer {
            margin-top: 50px;
            padding: 20px 0;
            background-color: #333;
            color: white;
        }

        /* زر الواتساب العائم */
        .whatsapp-button {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #25D366; /* لون واتساب */
            color: white;
            border-radius: 50%;
            padding: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
            display: flex;
            align-items: center;
            justify-content: center;
            text-decoration: none;
            z-index: 1000;
        }

        .whatsapp-button img {
            width: 40px;
            height: 40px;
            border-radius: 50%;
        }

        .whatsapp-container {
            position: fixed;
            bottom: 20px;
            right: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .whatsapp-text {
            font-size: 14px;
            color: #25D366;
            margin-top: 10px; /* زيادة المسافة بين الأيقونة والنص */
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>مرحبًا بك في مدونة الباش ممرض بشير</h1>
        <div class="icons">
            <i class="fas fa-stethoscope"></i> <!-- أيقونة سماعة طبية -->
            <i class="fas fa-heartbeat"></i> <!-- أيقونة ECG -->
        </div>
    </header>
    <nav>
        <a href="#about">من أنا</a>
        <a href="#blog">المدونة</a>
        <a href="#contact">اتصل بي</a>
    </nav>
    <section id="about">
        <h2>من أنا</h2>
        <p>أنا بشير، ممرض محترف مع خبرة في [مجال تخصصك]. أسعى لمشاركة معرفتي وخبراتي مع الآخرين.</p>
    </section>
    <section id="blog">
        <h2>أحدث المقالات</h2>
        <div class="post">
            <h3>عنوان المقالة الأولى</h3>
            <p>مقتطف قصير من المقالة الأولى...</p>
            <a href="#">اقرأ المزيد</a>
        </div>
        <div class="post">
            <h3>عنوان المقالة الثانية</h3>
            <p>مقتطف قصير من المقالة الثانية...</p>
            <a href="#">اقرأ المزيد</a>
        </div>
    </section>
    <section id="contact">
        <h2>اتصل بي</h2>
        <p>يمكنك التواصل معي عبر البريد الإلكتروني: <a href="mailto:wwwbsher327@gmail.com">wwwbsher327@gmail.com</a></p>
    </section>
    <footer>
        <p>جميع الحقوق محفوظة &copy; 2023 مدونة الباش ممرض بشير</p>
    </footer>

    <!-- زر الواتساب العائم -->
    <div class="whatsapp-container">
        <a href="https://wa.me/+963991368775" class="whatsapp-button" target="_blank">
            <img src="https://i.postimg.cc/1tySjZ5d/Screenshot.jpg" alt="صورتك الشخصية">
        </a>
        <span class="whatsapp-text">اتصل بنا عبر واتساب</span>
    </div>
</body>
</html>
