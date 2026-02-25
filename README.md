<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>יאיר כהאן | המוח בשירות משמעותי: הרצאות מדעי המוח</title>
    <meta name="description" content="יאיר כהאן: מרצה בתחום מדעי המוח. הרצאות על פרפקציוניזם, חוסן נפשי ולקיחת אחריות למכינות, בתי ספר, צבא וחברות הייטק.">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Heebo:wght@300;400;500;600;700;900&family=Frank+Ruhl+Libre:wght@400;500;700;900&display=swap" rel="stylesheet">
    <style>
        :root{--gold:#C4923A;--gold-light:#E8C87A;--gold-dark:#A07428;--sand:#F5EDE0;--sand-light:#FAF6EF;--earth:#3D2E1F;--earth-mid:#6B5640;--cream:#FFFDF8;--warm-white:#FDF9F3;--charcoal:#2A2118;--accent:#B85C2F;--green:#25D366;--radius:6px;--shadow:0 4px 30px rgba(61,46,31,0.08);--shadow-lg:0 12px 40px rgba(61,46,31,0.12)}
        *{margin:0;padding:0;box-sizing:border-box}
        html{scroll-behavior:smooth;scroll-padding-top:80px; width: 100%; overflow-x: hidden;}
        body{font-family:'Heebo',sans-serif;background:var(--cream);color:var(--earth);line-height:1.8;overflow-x:hidden; width: 100%;}
        
        /* Loader */
        .loader{position:fixed;inset:0;background:var(--charcoal);z-index:9999;display:flex;align-items:center;justify-content:center;transition:opacity .6s,visibility .6s}.loader.hidden{opacity:0;visibility:hidden}
        .loader-brain{font-size:3rem;animation:pulse 1s ease infinite}
        @keyframes pulse{0%,100%{transform:scale(1);opacity:.7}50%{transform:scale(1.15);opacity:1}}

        /* Hero fix for full screen */
        .hero{position:relative;min-height:100vh;display:flex;align-items:flex-end;overflow:hidden; background-color: var(--charcoal);}
        .hero-bg{position:absolute;inset:0;z-index:0}
        .hero-bg img{width:100%;height:100%;object-fit:cover;object-position:center;}
        .hero-overlay{position:absolute;inset:0;background:linear-gradient(to top,rgba(42,33,24,0.95) 0%,rgba(42,33,24,0.4) 100%);z-index:1}
        .hero-content{position:relative;z-index:2;padding:2rem;max-width:900px;width: 100%;}
        .hero h1{font-family:'Frank Ruhl Libre',serif;font-size:clamp(2.5rem,8vw,4.5rem);font-weight:900;color:#fff;line-height:1.1;margin-bottom:1rem;}
        
        /* Stats Bar */
        .stats-bar{background:var(--charcoal);padding:2rem;border-bottom:1px solid rgba(196,146,58,0.2)}
        .stats-inner{max-width:900px;margin:0 auto;display:flex;justify-content:space-around;text-align:center;flex-wrap:wrap;gap:1.5rem}
        .stat-number{font-family:'Frank Ruhl Libre',serif;font-size:2.2rem;font-weight:900;color:var(--gold);}
        
        /* Sections General */
        section{padding:4rem 1.5rem}.container{max-width:900px;margin:0 auto}
        .section-title{font-family:'Frank Ruhl Libre',serif;font-size:2.2rem;font-weight:700;color:var(--charcoal);margin-bottom:1rem}
        
        /* About Image Fix */
        .about-grid{display:grid;grid-template-columns:1fr 280px;gap:2rem;align-items:center}
        .about-image img{width:220px;height:220px;border-radius:50%;object-fit:cover;border:4px solid var(--gold-light);}

        /* Buttons and Mobile Fixes */
        .btn-primary{display:inline-block;padding:1rem 2rem;background:var(--gold);color:#fff;text-decoration:none;border-radius:var(--radius);font-weight:600}
        .topics-grid, .audience-grid{display:grid;grid-template-columns:repeat(auto-fit, minmax(280px, 1fr));gap:1.5rem;margin-top:2rem}
        .topic-card{padding:1.5rem;background:rgba(255,255,255,0.05);border:1px solid rgba(196,146,58,0.2);border-radius:var(--radius);color:#fff}

        @media(max-width:768px){
            .about-grid{grid-template-columns:1fr;text-align:center}
            .about-image{order:-1;margin:0 auto}
            .stat-item{width: 45%;}
        }
    </style>
</head>
<body>

<div class="loader"><div class="loader-brain">🧠</div></div>

<section class="hero">
    <div class="hero-bg">
        <img src="profile.jpg" alt="יאיר כהאן">
    </div>
    <div class="hero-overlay"></div>
    <div class="hero-content">
        <div style="color:var(--gold-light); letter-spacing:2px; margin-bottom:10px">מדעי המוח · הרצאות · חוסן נפשי</div>
        <h1>יאיר כהאן
            <span style="display:block; font-size:1.2rem; font-family:'Heebo'; font-weight:300; margin-top:10px">המוח בשירות משמעותי: איך לקיחת אחריות קשורה להתפתחות החשיבה</span>
        </h1>
        <div style="display:flex; gap:10px; flex-wrap:wrap; margin-top:20px">
            <span style="padding:5px 15px; background:rgba(255,255,255,0.1); border-radius:50px; color:#fff; font-size:0.8rem">🎓 סטודנט לתואר שני בנוירופסיכולוגיה</span>
            <span style="padding:5px 15px; background:rgba(255,255,255,0.1); border-radius:50px; color:#fff; font-size:0.8rem">⭐ קצין סיירת נח״ל</span>
        </div>
        <div style="margin-top:30px">
            <a href="https://wa.me/972548360550" class="btn-primary">הזמינו הרצאה</a>
        </div>
    </div>
</section>

<div class="stats-bar">
    <div class="stats-inner">
        <div class="stat-item"><div class="stat-number">20+</div><div style="color:#aaa">הרצאות</div></div>
        <div class="stat-item"><div class="stat-number">500+</div><div style="color:#aaa">משתתפים</div></div>
        <div class="stat-item"><div class="stat-number">8</div><div style="color:#aaa">מסגרות</div></div>
    </div>
</div>

<section id="about">
    <div class="container">
        <div class="about-grid">
            <div class="about-text">
                <h2 class="section-title">הסיפור שלי</h2>
                <p>סטודנט לתואר שני בנוירופסיכולוגיה שיקומית, מעביר ידע אקדמי על תפקוד המוח ומנגיש כלים פרקטיים בנושאי חוסן וקבלת החלטות. במקביל אני קצין במילואים ומחלים ממחלת הסרטן.</p>
                <p style="margin-top:10px">ההרצאות נשענות על ידע מחקרי עדכני, לצד ניסיון חיים בהתמודדות עם אתגרים.</p>
            </div>
            <div class="about-image">
                <img src="profile.jpg" alt="יאיר כהאן">
            </div>
        </div>
    </div>
</section>

<section style="background:var(--charcoal); color:#fff" id="topics">
    <div class="container">
        <h2 class="section-title" style="color:#fff">נושאי ההרצאות</h2>
        <div class="topics-grid">
            <div class="topic-card">
                <div style="font-size:2rem; margin-bottom:10px">🧠</div>
                <h3>המוח בשירות משמעותי</h3>
                <p>איך לקיחת אחריות ואתגרי השירות תורמים להתפתחות קוגניטיבית וניהול עצמי.</p>
            </div>
            <div class="topic-card">
                <div style="font-size:2rem; margin-bottom:10px">🎯</div>
                <h3>פרפקציוניזם וביצועים</h3>
                <p>למה השאיפה למושלמות מעכבת? ואיך בונים חוסן אמיתי מבוסס מדע.</p>
            </div>
        </div>
    </div>
</section>

<script>
    window.addEventListener('load', () => {
        setTimeout(() => {
            document.querySelector('.loader').style.opacity = '0';
            setTimeout(() => {
                document.querySelector('.loader').style.display = 'none';
            }, 600);
        }, 1000);
    });
</script>

</body>
</html>
