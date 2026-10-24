
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="AMG WEB SERVICES - تصميم مواقع إلكترونية احترافية للمشاريع والمتاجر.">
  <title>AMG WEB SERVICES | تصميم المواقع</title>
  <style>
    * { box-sizing: border-box; }
    html { scroll-behavior: smooth; }
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0b1120;
      color: #f8fafc;
      line-height: 1.8;
    }
    a { text-decoration: none; }
    header {
      padding: 18px 7%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 12px;
      flex-wrap: wrap;
      background: #111a2d;
    }
    .logo { color: #22d3ee; font-size: 23px; font-weight: bold; }
    nav { display: flex; gap: 15px; flex-wrap: wrap; }
    nav a { color: #e2e8f0; font-size: 14px; }
    .hero {
      text-align: center;
      padding: 85px 20px;
      background: radial-gradient(ellipse at top, #164e63, #0b1120 70%);
    }
    .hero h1 { font-size: clamp(30px, 6vw, 52px); line-height: 1.4; }
    .hero p { color: #cbd5e1; max-width: 620px; margin: 20px auto; }
    .highlight { color: #22d3ee; }
    .btn {
      display: inline-block;
      background: #06b6d4;
      color: #06202a;
      padding: 12px 23px;
      border-radius: 9px;
      font-weight: bold;
      margin: 6px;
    }
    .btn.secondary {
      background: transparent;
      color: white;
      border: 1px solid #475569;
    }
    section { padding: 55px 7%; }
    .section-title { text-align: center; margin-bottom: 30px; }
    .section-title p { color: #94a3b8; }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 18px;
    }
    .card {
      padding: 24px;
      background: #111a2d;
      border: 1px solid #26364d;
      border-radius: 15px;
    }
    .card h3 { color: #22d3ee; }
    .card p, li { color: #cbd5e1; }
    .price { font-size: 27px; font-weight: bold; }
    .contact { text-align: center; background: #111a2d; }
    footer {
      text-align: center;
      color: #94a3b8;
      padding: 24px;
      font-size: 13px;
    }
    .whatsapp {
      position: fixed;
      bottom: 18px;
      left: 18px;
      z-index: 10;
      background: #25d366;
      color: #062a14;
      border-radius: 50px;
      padding: 12px 17px;
      font-weight: bold;
      box-shadow: 0 4px 18px #0005;
    }
  </style>
</head>
<body>

<header>
  <a class="logo" href="#">AMG WEB</a>
  <nav>
    <a href="#services">خدماتنا</a>
    <a href="#prices">الأسعار</a>
    <a href="#contact">تواصل معنا</a>
  </nav>
</header>

<main>
  <section class="hero">
    <h1>أنشئ موقعك الإلكتروني <span class="highlight">باحترافية</span></h1>
    <p>
      هل تريد موقعاً لمشروعك أو متجرك؟
      نصمم لك موقعاً عصرياً يناسب هاتفك ويعرض خدماتك
      بطريقة واضحة وجذابة.
    </p>
    <a class="btn" href="#contact">اطلب موقعك الآن</a>
    <a class="btn secondary" href="#services">اكتشف خدماتنا</a>
  </section>

  <section id="services">
    <div class="section-title">
      <h2>خدماتنا</h2>
      <p>حلول رقمية تناسب أفكارك ومشروعك</p>
    </div>
    <div class="grid">
      <article class="card">
        <h3>🌐 مواقع الشركات</h3>
        <p>موقع يعرض نشاطك التجاري ومعلوماتك وطرق التواصل معك.</p>
      </article>
      <article class="card">
        <h3>🛍️ المتاجر الإلكترونية</h3>
        <p>صفحات لعرض المنتجات والأسعار وطرق طلبها.</p>
      </article>
      <article class="card">
        <h3>🚀 صفحات الهبوط</h3>
        <p>صفحة جذابة لتقديم خدمة أو منتج وتشجيع العملاء على التواصل.</p>
      </article>
    </div>
  </section>

  <section id="prices">
    <div class="section-title">
      <h2>باقات الأسعار</h2>
      <p>أسعار تجريبية يمكنك تعديلها حسب خدمتك</p>
    </div>
    <div class="grid">
      <article class="card">
        <h3>الباقة الأساسية</h3>
        <div class="price">ابتداءً من 150 درهماً</div>
        <ul>
          <li>صفحة واحدة</li>
          <li>تصميم مناسب للهاتف</li>
          <li>زر واتساب</li>
        </ul>
        <a class="btn order" data-plan="الباقة الأساسية"
           href="#contact">اطلب الآن</a>
      </article>
      <article class="card">
        <h3>الباقة الاحترافية</h3>
        <div class="price">ابتداءً من 350 درهماً</div>
        <ul>
          <li>عدة أقسام وصفحات</li>
          <li>تصميم مخصص</li>
          <li>روابط التواصل</li>
        </ul>
        <a class="btn order" data-plan="الباقة الاحترافية"
           href="#contact">اطلب الآن</a>
      </article>
      <article class="card">
        <h3>المتجر الإلكتروني</h3>
        <div class="price">حسب المتطلبات</div>
        <ul>
          <li>عرض المنتجات</li>
          <li>سلة أو نموذج طلب حسب التنفيذ</li>
          <li>إعداد الدفع عند الاتفاق</li>
        </ul>
        <a class="btn order" data-plan="المتجر الإلكتروني"
           href="#contact">اطلب الآن</a>
      </article>
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>هل تريد إنشاء موقعك؟</h2>
    <p>تواصل معنا عبر واتساب وأرسل لنا تفاصيل مشروعك.</p>
    <a class="btn" id="contactBtn" href="#">تواصل عبر واتساب</a>
    <p>يمكنك أيضاً مراسلتنا على حسابات التواصل التي تضيفها هنا.</p>
  </section>
</main>

<footer>
  © <span id="year"></span> AMG WEB SERVICES - جميع الحقوق محفوظة
</footer>

<a class="whatsapp" id="floatingBtn" href="#" aria-label="تواصل عبر واتساب">
  واتساب
</a>

<script>
  // استبدل الرقم برقمك مع رمز الدولة، دون + أو مسافات.
  // مثال مغربي: 2126XXXXXXXX
  const WHATSAPP_NUMBER = "2126XXXXXXXX";

  document.getElementById("year").textContent =
    new Date().getFullYear();

  function whatsappLink(message) {
    return "https://wa.me/" + WHATSAPP_NUMBER +
      "?text=" + encodeURIComponent(message);
  }

  document.getElementById("contactBtn").href =
    whatsappLink("السلام عليكم، أريد الاستفسار عن إنشاء موقع إلكتروني.");

  document.getElementById("floatingBtn").href =
    whatsappLink("السلام عليكم، أريد إنشاء موقع إلكتروني.");

  document.querySelectorAll(".order").forEach(function(button) {
    button.addEventListener("click", function(event) {
      event.preventDefault();
      const plan = button.dataset.plan;
      window.open(
        whatsappLink("السلام عليكم، أريد طلب: " + plan),
        "_blank",
        "noopener,noreferrer"
      );
    });
  });
</script>

</body>
</html>
