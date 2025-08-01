<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>مرحبًا بكم في موقعي</title>
  <style>
    /* إعادة ضبط هوامش المتصفح */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    /* الخلفية تغطي كامل الشاشة */
    body {
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      color: #ffffff;
      text-align: center;
      background: url('background.jpg') no-repeat center center fixed;
      background-size: cover;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
    /* تنسيق العنوان */
    h1 {
      font-size: 3rem;
      text-shadow: 0 2px 4px rgba(0,0,0,0.5);
      margin-bottom: 1rem;
    }
    /* تنسيق الفقرة الترحيبية */
    p {
      font-size: 1.2rem;
      max-width: 600px;
      line-height: 1.5;
      text-shadow: 0 1px 3px rgba(0,0,0,0.4);
    }
    /* زر دعوة للتفاعل (اختياري) */
    .btn {
      display: inline-block;
      margin-top: 2rem;
      padding: 0.8rem 1.5rem;
      font-size: 1rem;
      color: #ffffff;
      background-color: rgba(0, 123, 255, 0.7);
      text-decoration: none;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }
    .btn:hover {
      background-color: rgba(0, 123, 255, 1);
    }
  </style>
</head>
<body>
  <h1>أهلًا وسهلًا بك!</h1>
  <p>
    هذا هو موقعي الشخصي حيث أشارك فيه أحدث أعمالي وأفكاري.  
    تصفّح الأقسام وتعرّف أكثر على مشاريعي وخبراتي، ولا تتردد في 
    التواصل معي عبر صفحة “اتصل بنا”.
  </p>
  <a href="#contact" class="btn">تواصل معي</a>
</body>
</html>
