<!DOCTYPE html>
<html lang="hy">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#f8f5ef">
  <meta name="description" content="Անգլերենի առցանց անհատական դասեր երեխաների և մեծահասակների համար։ Խոսակցական անգլերեն, քերականություն և ուսումնական նպատակներին համապատասխան ծրագիր։ Գրանցվեք English with Viktorya-ում։">
  <meta name="robots" content="index,follow">
  <title>English with Viktorya | Անգլերենի առցանց դասեր</title>
  <style>
    :root { --paper:#f8f5ef; --ink:#222c27; --muted:#68736c; --green:#294c3b; --mint:#dce8dc; --line:#e2e4dc; --white:#fffefa; --gold:#d7ad68; }
    * { box-sizing:border-box; }
    html { scroll-behavior:smooth; }
    body { margin:0; background:var(--paper); color:var(--ink); font-family:Inter,ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,"Segoe UI",sans-serif; line-height:1.6; }
    a { color:inherit; }
    .wrap { width:min(1120px, calc(100% - 40px)); margin:0 auto; }
    header { padding:22px 0; border-bottom:1px solid var(--line); }
    .nav { display:flex; align-items:center; justify-content:space-between; gap:18px; }
    .brand { font-weight:800; letter-spacing:-.04em; font-size:1.13rem; text-decoration:none; }
    .brand span { color:var(--green); }
    .navright { display:flex; align-items:center; gap:20px; }
    .navlink { text-decoration:none; font-size:.93rem; color:var(--muted); }
    .lang { border:1px solid #cbd5cb; background:transparent; padding:8px 11px; border-radius:99px; color:var(--green); font-weight:700; cursor:pointer; }
    .hero { display:grid; grid-template-columns:1.15fr .85fr; gap:56px; align-items:center; padding:76px 0 68px; }
    .eyebrow { color:var(--green); text-transform:uppercase; letter-spacing:.15em; font-size:.76rem; font-weight:800; }
    h1 { font-size:clamp(2.7rem,6vw,5.25rem); line-height:1.02; letter-spacing:-.065em; margin:18px 0 22px; max-width:720px; }
    h1 em { color:var(--green); font-family:Georgia,serif; font-weight:500; }
    .lead { font-size:1.13rem; max-width:580px; color:#59645d; }
    .actions { display:flex; gap:12px; flex-wrap:wrap; margin-top:30px; }
    .btn { display:inline-flex; align-items:center; justify-content:center; text-decoration:none; padding:14px 21px; border-radius:999px; font-weight:750; border:1px solid var(--green); transition:transform .18s, background .18s; }
    .btn:hover { transform:translateY(-2px); }
    .primary { background:var(--green); color:white; }
    .secondary { color:var(--green); }
    .visual { min-height:410px; position:relative; display:flex; align-items:center; justify-content:center; }
    .orb { width:min(100%,390px); aspect-ratio: .88; background:var(--mint); border-radius:48% 48% 26px 26px; position:relative; overflow:hidden; display:flex; align-items:center; justify-content:center; }
    .orb:before { content:""; position:absolute; width:250px; height:250px; border-radius:50%; border:1px solid rgba(41,76,59,.24); top:32px; right:-58px; }
    .orb:after { content:"A B C"; position:absolute; bottom:26px; left:26px; font-size:1rem; letter-spacing:.22em; color:var(--green); font-weight:800; }
    .book { width:64%; height:67%; border-radius:12px; background:var(--white); box-shadow:0 25px 55px #294c3b20; transform:rotate(-5deg); padding:27px; position:relative; z-index:1; display:flex; flex-direction:column; justify-content:space-between; border:1px solid #ffffffa8; }
    .book small { color:var(--muted); letter-spacing:.15em; text-transform:uppercase; font-weight:800; }
    .book strong { font:500 clamp(2.2rem,4vw,3.3rem)/1 Georgia,serif; letter-spacing:-.06em; color:var(--green); }
    .book .scribble { font:italic 1rem Georgia,serif; color:#8b9b8c; }
    .note { position:absolute; right:-2px; top:38px; background:var(--white); border:1px solid var(--line); border-radius:16px; padding:13px 17px; box-shadow:0 10px 30px #222c270c; z-index:2; font-size:.9rem; }
    .note b { color:var(--green); display:block; }
    section { padding:66px 0; }
    .sectionhead { max-width:680px; margin-bottom:32px; }
    h2 { font-size:clamp(2rem,4vw,3rem); line-height:1.12; letter-spacing:-.05em; margin:10px 0 14px; }
    .sub { color:var(--muted); margin:0; }
    .cards { display:grid; grid-template-columns:repeat(3,1fr); gap:16px; }
    .card { background:var(--white); border:1px solid var(--line); border-radius:20px; padding:25px; min-height:218px; }
    .number { color:#8a9c8b; font:italic 1.6rem Georgia,serif; }
    .card h3 { margin:18px 0 8px; font-size:1.15rem; }
    .card p { color:var(--muted); margin:0; font-size:.96rem; }
    .about { display:grid; grid-template-columns:.7fr 1.3fr; gap:54px; align-items:start; background:#edf0e8; border-radius:28px; padding:42px; }
    .monogram { min-height:235px; display:flex; align-items:center; justify-content:center; background:var(--green); color:#f8f5ef; border-radius:22px; font:italic 5rem Georgia,serif; }
    .about p { color:#58645c; }
    .chips { display:flex; flex-wrap:wrap; gap:8px; margin-top:20px; }
    .chip { border:1px solid #cdd7ca; border-radius:999px; padding:7px 12px; font-size:.86rem; color:var(--green); }
    .offer { background:var(--green); color:#fffefa; border-radius:28px; padding:clamp(30px,6vw,60px); display:grid; grid-template-columns:1fr auto; gap:28px; align-items:center; }
    .offer .eyebrow { color:#d8e5d7; }
    .offer h2 { max-width:620px; }
    .offer p { color:#d8e1d9; max-width:580px; }
    .offer .btn { background:#fffefa; color:var(--green); border-color:#fffefa; white-space:nowrap; }
    .contact { text-align:center; padding:80px 0; }
    .contact h2 { max-width:650px; margin:12px auto; }
    .contact p { color:var(--muted); max-width:560px; margin:0 auto; }
    .contact .actions { justify-content:center; }
    footer { border-top:1px solid var(--line); padding:22px 0 30px; color:var(--muted); font-size:.86rem; }
    .foot { display:flex; justify-content:space-between; gap:15px; flex-wrap:wrap; }
    @media (max-width:760px) { .wrap{width:min(100% - 30px, 560px)} .navlink{display:none} .hero{grid-template-columns:1fr;gap:18px;padding:52px 0 40px} .visual{min-height:330px} .orb{max-width:310px} .note{right:0;top:20px} .cards{grid-template-columns:1fr} .card{min-height:unset} section{padding:48px 0} .about{grid-template-columns:1fr;gap:22px;padding:22px} .monogram{min-height:150px} .offer{grid-template-columns:1fr} .offer .btn{justify-self:start} }
    @media (prefers-reduced-motion:reduce) { html{scroll-behavior:auto} *{transition:none!important} }
  </style>
  <script type="application/ld+json">
  {"@context":"https://schema.org","@type":"Course","name":"English with Viktorya — Online English Lessons","description":"Individual online English lessons for children and adults, tailored to each learner's level and goals.","inLanguage":["hy","en","ru"],"provider":{"@type":"Person","name":"Viktorya","jobTitle":"English tutor"},"educationalLevel":["Beginner","Elementary","Intermediate","Advanced"]}
  </script>
</head>
<body>
  <header><div class="wrap nav"><a class="brand" href="#home">English <span>with Viktorya</span></a><div class="navright"><a class="navlink" href="#lessons" data-i18n="navLessons">Դասեր</a><a class="navlink" href="#about" data-i18n="navAbout">Իմ մասին</a><a class="navlink" href="#contact" data-i18n="navContact">Կապ</a><button class="lang" id="langToggle" aria-label="Change language">HY / EN / RU</button></div></div></header>
  <main id="home">
    <div class="wrap hero">
      <div><div class="eyebrow" data-i18n="eyebrow">Անգլերեն՝ քո նպատակներին համապատասխան</div><h1 data-i18n="heroTitle">Ավելի վստահ խոսիր <em>անգլերեն։</em></h1><p class="lead" data-i18n="heroLead">Անհատական առցանց դասեր երեխաների և մեծահասակների համար՝ քո մակարդակին, հետաքրքրություններին և նպատակներին համապատասխան։</p><div class="actions"><a class="btn primary" href="#contact" data-i18n="book">Գրանցվել դասին ↗</a><a class="btn secondary" href="#lessons" data-i18n="explore">Ծանոթանալ դասերին</a></div></div>
      <div class="visual" aria-label="Decorative English learning illustration"><div class="orb"><div class="book"><small>YOUR NEXT CHAPTER</small><strong>Speak<br>with<br>confidence.</strong><span class="scribble">One lesson at a time ✦</span></div></div><div class="note"><b data-i18n="noteTitle">Քո տեմպով</b><span data-i18n="noteText">Քո նպատակների համար</span></div></div>
    </div>
    <section id="lessons"><div class="wrap"><div class="sectionhead"><div class="eyebrow" data-i18n="lessonsEyebrow">Դասեր</div><h2 data-i18n="lessonsTitle">Անգլերեն՝ իրական կյանքում օգտագործելու համար</h2><p class="sub" data-i18n="lessonsSub">Սովորում ենք հստակ նպատակով, գործնական վարժություններով և անհատական մոտեցմամբ։</p></div><div class="cards">
      <article class="card"><div class="number">01</div><h3 data-i18n="card1Title">Երեխաների համար</h3><p data-i18n="card1Text">Պարզ բացատրություններ, հետաքրքիր առաջադրանքներ և աջակցություն դպրոցական անգլերենում։</p></article>
      <article class="card"><div class="number">02</div><h3 data-i18n="card2Title">Մեծահասակների համար</h3><p data-i18n="card2Text">Խոսակցական անգլերեն, քերականություն և վստահություն՝ առօրյա ու աշխատանքային իրավիճակներում։</p></article>
      <article class="card"><div class="number">03</div><h3 data-i18n="card3Title">Քո նպատակին համապատասխան</h3><p data-i18n="card3Text">Դասերի ծրագիրը հարմարեցվում է քո մակարդակին, հետաքրքրություններին և սովորելու նպատակին։</p></article>
    </div></div></section>
    <section id="about"><div class="wrap about"><div class="monogram" aria-hidden="true">W.</div><div><div class="eyebrow" data-i18n="aboutEyebrow">Ծանոթանանք</div><h2 data-i18n="aboutTitle">Բարև՛, ես Վիկտորյան եմ։</h2><p data-i18n="aboutText">Անգլերենի դասավանդման ավելի քան երեք տարվա փորձ ունեմ և աշխատում եմ երեխաների ու մեծահասակների հետ։ Իմ նպատակն է ստեղծել ընկերական միջավայր, որտեղ կարող ես հարցեր տալ, սխալվել, փորձել նորից և աստիճանաբար ավելի վստահ օգտագործել անգլերենը։</p><div class="chips"><span class="chip" data-i18n="chip1">Անհատական դասեր</span><span class="chip" data-i18n="chip2">Խոսակցական պրակտիկա</span><span class="chip" data-i18n="chip3">Երեխաներ և մեծահասակներ</span><span class="chip" data-i18n="chip4">Առցանց ուսուցում</span></div></div></div></section>
    <section><div class="wrap offer"><div><div class="eyebrow" data-i18n="offerEyebrow">Սկսենք միասին</div><h2 data-i18n="offerTitle">Քո անգլերենի հաջորդ քայլը սկսվում է այստեղից։</h2><p data-i18n="offerText">Գրիր ինձ Telegram-ում։ Կքննարկենք քո մակարդակը, նպատակները և դասերի հարմար տարբերակը։</p></div><a class="btn" href="#contact" data-i18n="offerButton">Հարցնել դասերի մասին ↗</a></div></section>
    <section id="contact" class="contact"><div class="wrap"><div class="eyebrow" data-i18n="contactEyebrow">Կապ</div><h2 data-i18n="contactTitle">Պատրա՞ստ ես սկսել։</h2><p data-i18n="contactText">Ուղարկիր հաղորդագրություն Telegram-ով և նշիր՝ ում համար են դասերը, ինչ մակարդակ ունես և ինչի ես ուզում հասնել։</p><div class="actions"><a class="btn primary" id="telegramLink" href="https://t.me/Arakellyanv" target="_blank" rel="noopener noreferrer" data-i18n="telegramButton">Գրել Telegram-ում ↗</a></div></div></section>
  </main>
  <footer><div class="wrap foot"><span>© <span id="year">2026</span> English with Viktorya</span><span data-i18n="footer">Առցանց անգլերենի դասեր • Հայաստան և աշխարհի ցանկացած կետից</span></div></footer>
  <script>
    const translations = {
      hy:{navLessons:'Դասեր',navAbout:'Իմ մասին',navContact:'Կապ',eyebrow:'Անգլերեն՝ քո նպատակներին համապատասխան',heroTitle:'Ավելի վստահ խոսիր <em>անգլերեն։</em>',heroLead:'Անհատական առցանց դասեր երեխաների և մեծահասակների համար՝ քո մակարդակին, հետաքրքրություններին և նպատակներին համապատասխան։',book:'Գրանցվել դասին ↗',explore:'Ծանոթանալ դասերին',noteTitle:'Քո տեմպով',noteText:'Քո նպատակների համար',lessonsEyebrow:'Դասեր',lessonsTitle:'Անգլերեն՝ իրական կյանքում օգտագործելու համար',lessonsSub:'Սովորում ենք հստակ նպատակով, գործնական վարժություններով և անհատական մոտեցմամբ։',card1Title:'Երեխաների համար',card1Text:'Պարզ բացատրություններ, հետաքրքիր առաջադրանքներ և աջակցություն դպրոցական անգլերենում։',card2Title:'Մեծահասակների համար',card2Text:'Խոսակցական անգլերեն, քերականություն և վստահություն՝ առօրյա ու աշխատանքային իրավիճակներում։',card3Title:'Քո նպատակին համապատասխան',card3Text:'Դասերի ծրագիրը հարմարեցվում է քո մակարդակին, հետաքրքրություններին և սովորելու նպատակին։',aboutEyebrow:'Ծանոթանանք',aboutTitle:'Բարև՛, ես Վիկտորյան եմ։',aboutText:'Անգլերենի դասավանդման ավելի քան երեք տարվա փորձ ունեմ և աշխատում եմ երեխաների ու մեծահասակների հետ։ Իմ նպատակն է ստեղծել ընկերական միջավայր, որտեղ կարող ես հարցեր տալ, սխալվել, փորձել նորից և աստիճանաբար ավելի վստահ օգտագործել անգլերենը։',chip1:'Անհատական դասեր',chip2:'Խոսակցական պրակտիկա',chip3:'Երեխաներ և մեծահասակներ',chip4:'Առցանց ուսուցում',offerEyebrow:'Սկսենք միասին',offerTitle:'Քո անգլերենի հաջորդ քայլը սկսվում է այստեղից։',offerText:'Գրիր ինձ Telegram-ում։ Կքննարկենք քո մակարդակը, նպատակները և դասերի հարմար տարբերակը։',offerButton:'Հարցնել դասերի մասին ↗',contactEyebrow:'Կապ',contactTitle:'Պատրա՞ստ ես սկսել։',contactText:'Ուղարկիր հաղորդագրություն Telegram-ով և նշիր՝ ում համար են դասերը, ինչ մակարդակ ունես և ինչի ես ուզում հասնել։',telegramButton:'Գրել Telegram-ում ↗',telegramNote:'Գրիր ինձ Telegram-ում՝ @Arakellyanv։',footer:'Առցանց անգլերենի դասեր • Հայաստան և աշխարհի ցանկացած կետից'},
      en:{navLessons:'Lessons',navAbout:'About me',navContact:'Contact',eyebrow:'English lessons built around your goals',heroTitle:'Speak English with <em>confidence.</em>',heroLead:'Personalised online English lessons for children and adults, tailored to your level, interests and goals.',book:'Book a lesson ↗',explore:'Explore lessons',noteTitle:'At your pace',noteText:'For your goals',lessonsEyebrow:'Lessons',lessonsTitle:'English for real life',lessonsSub:'Learn with a clear purpose, practical activities and an individual approach.',card1Title:'For children',card1Text:'Clear explanations, engaging activities and support with school English.',card2Title:'For adults',card2Text:'Speaking practice, grammar and confidence for everyday and professional situations.',card3Title:'Made for your goals',card3Text:'Lessons are adapted to your level, interests and learning goals.',aboutEyebrow:'Meet your tutor',aboutTitle:'Hi, I’m Viktorya.',aboutText:'I have over three years of English teaching experience and work with both children and adults. My goal is to create a friendly space where you can ask questions, make mistakes, try again and gradually feel more confident using English.',chip1:'Individual lessons',chip2:'Speaking practice',chip3:'Children and adults',chip4:'Online learning',offerEyebrow:'Let’s get started',offerTitle:'Your next step in English starts here.',offerText:'Message me on Telegram. We’ll discuss your level, goals and the right lesson plan for you.',offerButton:'Ask about lessons ↗',contactEyebrow:'Contact',contactTitle:'Ready to get started?',contactText:'Send me a Telegram message and tell me who the lessons are for, your current level and what you want to achieve.',telegramButton:'Message on Telegram ↗',telegramNote:'Message me on Telegram: @Arakellyanv.',footer:'Online English lessons • From Armenia to anywhere in the world'},
      ru:{navLessons:'Занятия',navAbout:'Обо мне',navContact:'Контакты',eyebrow:'Английский в соответствии с вашими целями',heroTitle:'Говорите по-английски <em>увереннее.</em>',heroLead:'Индивидуальные онлайн-занятия для детей и взрослых с учётом вашего уровня, интересов и целей.',book:'Записаться на занятие ↗',explore:'О занятиях',noteTitle:'В своём темпе',noteText:'Для ваших целей',lessonsEyebrow:'Занятия',lessonsTitle:'Английский для реальной жизни',lessonsSub:'Учимся с понятной целью, практическими заданиями и индивидуальным подходом.',card1Title:'Для детей',card1Text:'Понятные объяснения, интересные задания и помощь со школьным английским.',card2Title:'Для взрослых',card2Text:'Разговорная практика, грамматика и уверенность в повседневных и рабочих ситуациях.',card3Title:'Под ваши цели',card3Text:'Программа адаптируется к вашему уровню, интересам и целям обучения.',aboutEyebrow:'Давайте знакомиться',aboutTitle:'Здравствуйте, я Виктория.',aboutText:'У меня более трёх лет опыта преподавания английского языка. Я работаю и с детьми, и со взрослыми. Моя цель — создать дружелюбную атмосферу, где можно задавать вопросы, ошибаться, пробовать снова и постепенно увереннее использовать английский.',chip1:'Индивидуальные занятия',chip2:'Разговорная практика',chip3:'Дети и взрослые',chip4:'Онлайн-обучение',offerEyebrow:'Начнём вместе',offerTitle:'Следующий шаг в английском начинается здесь.',offerText:'Напишите мне в Telegram. Обсудим ваш уровень, цели и подходящий формат занятий.',offerButton:'Узнать о занятиях ↗',contactEyebrow:'Контакты',contactTitle:'Готовы начать?',contactText:'Напишите мне в Telegram и расскажите, для кого нужны занятия, какой у вас уровень и чего вы хотите достичь.',telegramButton:'Написать в Telegram ↗',telegramNote:'Напишите мне в Telegram: @Arakellyanv.',footer:'Онлайн-уроки английского • Из Армении и из любой точки мира'}
    };
    let current = 'hy';
    document.getElementById('langToggle').addEventListener('click',()=>{ current = current==='hy'?'en':current==='en'?'ru':'hy'; document.documentElement.lang=current; document.querySelectorAll('[data-i18n]').forEach(el=>{const key=el.dataset.i18n;if(translations[current][key]) el.innerHTML=translations[current][key];}); });
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html><!DOCTYPE html>
<html lang="hy">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#f8f5ef">
  <meta name="description" content="Անգլերենի առցանց անհատական դասեր երեխաների և մեծահասակների համար։ Խոսակցական անգլերեն, քերականություն և ուսումնական նպատակներին համապատասխան ծրագիր։ Գրանցվեք English with Viktorya-ում։">
  <meta name="robots" content="index,follow">
  <title>English with Viktorya | Անգլերենի առցանց դասեր</title>
  <style>
    :root { --paper:#f8f5ef; --ink:#222c27; --muted:#68736c; --green:#294c3b; --mint:#dce8dc; --line:#e2e4dc; --white:#fffefa; --gold:#d7ad68; }
    * { box-sizing:border-box; }
    html { scroll-behavior:smooth; }
    body { margin:0; background:var(--paper); color:var(--ink); font-family:Inter,ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,"Segoe UI",sans-serif; line-height:1.6; }
    a { color:inherit; }
    .wrap { width:min(1120px, calc(100% - 40px)); margin:0 auto; }
    header { padding:22px 0; border-bottom:1px solid var(--line); }
    .nav { display:flex; align-items:center; justify-content:space-between; gap:18px; }
    .brand { font-weight:800; letter-spacing:-.04em; font-size:1.13rem; text-decoration:none; }
    .brand span { color:var(--green); }
    .navright { display:flex; align-items:center; gap:20px; }
    .navlink { text-decoration:none; font-size:.93rem; color:var(--muted); }
    .lang { border:1px solid #cbd5cb; background:transparent; padding:8px 11px; border-radius:99px; color:var(--green); font-weight:700; cursor:pointer; }
    .hero { display:grid; grid-template-columns:1.15fr .85fr; gap:56px; align-items:center; padding:76px 0 68px; }
    .eyebrow { color:var(--green); text-transform:uppercase; letter-spacing:.15em; font-size:.76rem; font-weight:800; }
    h1 { font-size:clamp(2.7rem,6vw,5.25rem); line-height:1.02; letter-spacing:-.065em; margin:18px 0 22px; max-width:720px; }
    h1 em { color:var(--green); font-family:Georgia,serif; font-weight:500; }
    .lead { font-size:1.13rem; max-width:580px; color:#59645d; }
    .actions { display:flex; gap:12px; flex-wrap:wrap; margin-top:30px; }
    .btn { display:inline-flex; align-items:center; justify-content:center; text-decoration:none; padding:14px 21px; border-radius:999px; font-weight:750; border:1px solid var(--green); transition:transform .18s, background .18s; }
    .btn:hover { transform:translateY(-2px); }
    .primary { background:var(--green); color:white; }
    .secondary { color:var(--green); }
    .visual { min-height:410px; position:relative; display:flex; align-items:center; justify-content:center; }
    .orb { width:min(100%,390px); aspect-ratio: .88; background:var(--mint); border-radius:48% 48% 26px 26px; position:relative; overflow:hidden; display:flex; align-items:center; justify-content:center; }
    .orb:before { content:""; position:absolute; width:250px; height:250px; border-radius:50%; border:1px solid rgba(41,76,59,.24); top:32px; right:-58px; }
    .orb:after { content:"A B C"; position:absolute; bottom:26px; left:26px; font-size:1rem; letter-spacing:.22em; color:var(--green); font-weight:800; }
    .book { width:64%; height:67%; border-radius:12px; background:var(--white); box-shadow:0 25px 55px #294c3b20; transform:rotate(-5deg); padding:27px; position:relative; z-index:1; display:flex; flex-direction:column; justify-content:space-between; border:1px solid #ffffffa8; }
    .book small { color:var(--muted); letter-spacing:.15em; text-transform:uppercase; font-weight:800; }
    .book strong { font:500 clamp(2.2rem,4vw,3.3rem)/1 Georgia,serif; letter-spacing:-.06em; color:var(--green); }
    .book .scribble { font:italic 1rem Georgia,serif; color:#8b9b8c; }
    .note { position:absolute; right:-2px; top:38px; background:var(--white); border:1px solid var(--line); border-radius:16px; padding:13px 17px; box-shadow:0 10px 30px #222c270c; z-index:2; font-size:.9rem; }
    .note b { color:var(--green); display:block; }
    section { padding:66px 0; }
    .sectionhead { max-width:680px; margin-bottom:32px; }
    h2 { font-size:clamp(2rem,4vw,3rem); line-height:1.12; letter-spacing:-.05em; margin:10px 0 14px; }
    .sub { color:var(--muted); margin:0; }
    .cards { display:grid; grid-template-columns:repeat(3,1fr); gap:16px; }
    .card { background:var(--white); border:1px solid var(--line); border-radius:20px; padding:25px; min-height:218px; }
    .number { color:#8a9c8b; font:italic 1.6rem Georgia,serif; }
    .card h3 { margin:18px 0 8px; font-size:1.15rem; }
    .card p { color:var(--muted); margin:0; font-size:.96rem; }
    .about { display:grid; grid-template-columns:.7fr 1.3fr; gap:54px; align-items:start; background:#edf0e8; border-radius:28px; padding:42px; }
    .monogram { min-height:235px; display:flex; align-items:center; justify-content:center; background:var(--green); color:#f8f5ef; border-radius:22px; font:italic 5rem Georgia,serif; }
    .about p { color:#58645c; }
    .chips { display:flex; flex-wrap:wrap; gap:8px; margin-top:20px; }
    .chip { border:1px solid #cdd7ca; border-radius:999px; padding:7px 12px; font-size:.86rem; color:var(--green); }
    .offer { background:var(--green); color:#fffefa; border-radius:28px; padding:clamp(30px,6vw,60px); display:grid; grid-template-columns:1fr auto; gap:28px; align-items:center; }
    .offer .eyebrow { color:#d8e5d7; }
    .offer h2 { max-width:620px; }
    .offer p { color:#d8e1d9; max-width:580px; }
    .offer .btn { background:#fffefa; color:var(--green); border-color:#fffefa; white-space:nowrap; }
    .contact { text-align:center; padding:80px 0; }
    .contact h2 { max-width:650px; margin:12px auto; }
    .contact p { color:var(--muted); max-width:560px; margin:0 auto; }
    .contact .actions { justify-content:center; }
    footer { border-top:1px solid var(--line); padding:22px 0 30px; color:var(--muted); font-size:.86rem; }
    .foot { display:flex; justify-content:space-between; gap:15px; flex-wrap:wrap; }
    @media (max-width:760px) { .wrap{width:min(100% - 30px, 560px)} .navlink{display:none} .hero{grid-template-columns:1fr;gap:18px;padding:52px 0 40px} .visual{min-height:330px} .orb{max-width:310px} .note{right:0;top:20px} .cards{grid-template-columns:1fr} .card{min-height:unset} section{padding:48px 0} .about{grid-template-columns:1fr;gap:22px;padding:22px} .monogram{min-height:150px} .offer{grid-template-columns:1fr} .offer .btn{justify-self:start} }
    @media (prefers-reduced-motion:reduce) { html{scroll-behavior:auto} *{transition:none!important} }
  </style>
  <script type="application/ld+json">
  {"@context":"https://schema.org","@type":"Course","name":"English with Viktorya — Online English Lessons","description":"Individual online English lessons for children and adults, tailored to each learner's level and goals.","inLanguage":["hy","en","ru"],"provider":{"@type":"Person","name":"Viktorya","jobTitle":"English tutor"},"educationalLevel":["Beginner","Elementary","Intermediate","Advanced"]}
  </script>
</head>
<body>
  <header><div class="wrap nav"><a class="brand" href="#home">English <span>with Viktorya</span></a><div class="navright"><a class="navlink" href="#lessons" data-i18n="navLessons">Դասեր</a><a class="navlink" href="#about" data-i18n="navAbout">Իմ մասին</a><a class="navlink" href="#contact" data-i18n="navContact">Կապ</a><button class="lang" id="langToggle" aria-label="Change language">HY / EN / RU</button></div></div></header>
  <main id="home">
    <div class="wrap hero">
      <div><div class="eyebrow" data-i18n="eyebrow">Անգլերեն՝ քո նպատակներին համապատասխան</div><h1 data-i18n="heroTitle">Ավելի վստահ խոսիր <em>անգլերեն։</em></h1><p class="lead" data-i18n="heroLead">Անհատական առցանց դասեր երեխաների և մեծահասակների համար՝ քո մակարդակին, հետաքրքրություններին և նպատակներին համապատասխան։</p><div class="actions"><a class="btn primary" href="#contact" data-i18n="book">Գրանցվել դասին ↗</a><a class="btn secondary" href="#lessons" data-i18n="explore">Ծանոթանալ դասերին</a></div></div>
      <div class="visual" aria-label="Decorative English learning illustration"><div class="orb"><div class="book"><small>YOUR NEXT CHAPTER</small><strong>Speak<br>with<br>confidence.</strong><span class="scribble">One lesson at a time ✦</span></div></div><div class="note"><b data-i18n="noteTitle">Քո տեմպով</b><span data-i18n="noteText">Քո նպատակների համար</span></div></div>
    </div>
    <section id="lessons"><div class="wrap"><div class="sectionhead"><div class="eyebrow" data-i18n="lessonsEyebrow">Դասեր</div><h2 data-i18n="lessonsTitle">Անգլերեն՝ իրական կյանքում օգտագործելու համար</h2><p class="sub" data-i18n="lessonsSub">Սովորում ենք հստակ նպատակով, գործնական վարժություններով և անհատական մոտեցմամբ։</p></div><div class="cards">
      <article class="card"><div class="number">01</div><h3 data-i18n="card1Title">Երեխաների համար</h3><p data-i18n="card1Text">Պարզ բացատրություններ, հետաքրքիր առաջադրանքներ և աջակցություն դպրոցական անգլերենում։</p></article>
      <article class="card"><div class="number">02</div><h3 data-i18n="card2Title">Մեծահասակների համար</h3><p data-i18n="card2Text">Խոսակցական անգլերեն, քերականություն և վստահություն՝ առօրյա ու աշխատանքային իրավիճակներում։</p></article>
      <article class="card"><div class="number">03</div><h3 data-i18n="card3Title">Քո նպատակին համապատասխան</h3><p data-i18n="card3Text">Դասերի ծրագիրը հարմարեցվում է քո մակարդակին, հետաքրքրություններին և սովորելու նպատակին։</p></article>
    </div></div></section>
    <section id="about"><div class="wrap about"><div class="monogram" aria-hidden="true">W.</div><div><div class="eyebrow" data-i18n="aboutEyebrow">Ծանոթանանք</div><h2 data-i18n="aboutTitle">Բարև՛, ես Վիկտորյան եմ։</h2><p data-i18n="aboutText">Անգլերենի դասավանդման ավելի քան երեք տարվա փորձ ունեմ և աշխատում եմ երեխաների ու մեծահասակների հետ։ Իմ նպատակն է ստեղծել ընկերական միջավայր, որտեղ կարող ես հարցեր տալ, սխալվել, փորձել նորից և աստիճանաբար ավելի վստահ օգտագործել անգլերենը։</p><div class="chips"><span class="chip" data-i18n="chip1">Անհատական դասեր</span><span class="chip" data-i18n="chip2">Խոսակցական պրակտիկա</span><span class="chip" data-i18n="chip3">Երեխաներ և մեծահասակներ</span><span class="chip" data-i18n="chip4">Առցանց ուսուցում</span></div></div></div></section>
    <section><div class="wrap offer"><div><div class="eyebrow" data-i18n="offerEyebrow">Սկսենք միասին</div><h2 data-i18n="offerTitle">Քո անգլերենի հաջորդ քայլը սկսվում է այստեղից։</h2><p data-i18n="offerText">Գրիր ինձ Telegram-ում։ Կքննարկենք քո մակարդակը, նպատակները և դասերի հարմար տարբերակը։</p></div><a class="btn" href="#contact" data-i18n="offerButton">Հարցնել դասերի մասին ↗</a></div></section>
    <section id="contact" class="contact"><div class="wrap"><div class="eyebrow" data-i18n="contactEyebrow">Կապ</div><h2 data-i18n="contactTitle">Պատրա՞ստ ես սկսել։</h2><p data-i18n="contactText">Ուղարկիր հաղորդագրություն Telegram-ով և նշիր՝ ում համար են դասերը, ինչ մակարդակ ունես և ինչի ես ուզում հասնել։</p><div class="actions"><a class="btn primary" id="telegramLink" href="https://t.me/Arakellyanv" target="_blank" rel="noopener noreferrer" data-i18n="telegramButton">Գրել Telegram-ում ↗</a></div></div></section>
  </main>
  <footer><div class="wrap foot"><span>© <span id="year">2026</span> English with Viktorya</span><span data-i18n="footer">Առցանց անգլերենի դասեր • Հայաստան և աշխարհի ցանկացած կետից</span></div></footer>
  <script>
    const translations = {
      hy:{navLessons:'Դասեր',navAbout:'Իմ մասին',navContact:'Կապ',eyebrow:'Անգլերեն՝ քո նպատակներին համապատասխան',heroTitle:'Ավելի վստահ խոսիր <em>անգլերեն։</em>',heroLead:'Անհատական առցանց դասեր երեխաների և մեծահասակների համար՝ քո մակարդակին, հետաքրքրություններին և նպատակներին համապատասխան։',book:'Գրանցվել դասին ↗',explore:'Ծանոթանալ դասերին',noteTitle:'Քո տեմպով',noteText:'Քո նպատակների համար',lessonsEyebrow:'Դասեր',lessonsTitle:'Անգլերեն՝ իրական կյանքում օգտագործելու համար',lessonsSub:'Սովորում ենք հստակ նպատակով, գործնական վարժություններով և անհատական մոտեցմամբ։',card1Title:'Երեխաների համար',card1Text:'Պարզ բացատրություններ, հետաքրքիր առաջադրանքներ և աջակցություն դպրոցական անգլերենում։',card2Title:'Մեծահասակների համար',card2Text:'Խոսակցական անգլերեն, քերականություն և վստահություն՝ առօրյա ու աշխատանքային իրավիճակներում։',card3Title:'Քո նպատակին համապատասխան',card3Text:'Դասերի ծրագիրը հարմարեցվում է քո մակարդակին, հետաքրքրություններին և սովորելու նպատակին։',aboutEyebrow:'Ծանոթանանք',aboutTitle:'Բարև՛, ես Վիկտորյան եմ։',aboutText:'Անգլերենի դասավանդման ավելի քան երեք տարվա փորձ ունեմ և աշխատում եմ երեխաների ու մեծահասակների հետ։ Իմ նպատակն է ստեղծել ընկերական միջավայր, որտեղ կարող ես հարցեր տալ, սխալվել, փորձել նորից և աստիճանաբար ավելի վստահ օգտագործել անգլերենը։',chip1:'Անհատական դասեր',chip2:'Խոսակցական պրակտիկա',chip3:'Երեխաներ և մեծահասակներ',chip4:'Առցանց ուսուցում',offerEyebrow:'Սկսենք միասին',offerTitle:'Քո անգլերենի հաջորդ քայլը սկսվում է այստեղից։',offerText:'Գրիր ինձ Telegram-ում։ Կքննարկենք քո մակարդակը, նպատակները և դասերի հարմար տարբերակը։',offerButton:'Հարցնել դասերի մասին ↗',contactEyebrow:'Կապ',contactTitle:'Պատրա՞ստ ես սկսել։',contactText:'Ուղարկիր հաղորդագրություն Telegram-ով և նշիր՝ ում համար են դասերը, ինչ մակարդակ ունես և ինչի ես ուզում հասնել։',telegramButton:'Գրել Telegram-ում ↗',telegramNote:'Գրիր ինձ Telegram-ում՝ @Arakellyanv։',footer:'Առցանց անգլերենի դասեր • Հայաստան և աշխարհի ցանկացած կետից'},
      en:{navLessons:'Lessons',navAbout:'About me',navContact:'Contact',eyebrow:'English lessons built around your goals',heroTitle:'Speak English with <em>confidence.</em>',heroLead:'Personalised online English lessons for children and adults, tailored to your level, interests and goals.',book:'Book a lesson ↗',explore:'Explore lessons',noteTitle:'At your pace',noteText:'For your goals',lessonsEyebrow:'Lessons',lessonsTitle:'English for real life',lessonsSub:'Learn with a clear purpose, practical activities and an individual approach.',card1Title:'For children',card1Text:'Clear explanations, engaging activities and support with school English.',card2Title:'For adults',card2Text:'Speaking practice, grammar and confidence for everyday and professional situations.',card3Title:'Made for your goals',card3Text:'Lessons are adapted to your level, interests and learning goals.',aboutEyebrow:'Meet your tutor',aboutTitle:'Hi, I’m Viktorya.',aboutText:'I have over three years of English teaching experience and work with both children and adults. My goal is to create a friendly space where you can ask questions, make mistakes, try again and gradually feel more confident using English.',chip1:'Individual lessons',chip2:'Speaking practice',chip3:'Children and adults',chip4:'Online learning',offerEyebrow:'Let’s get started',offerTitle:'Your next step in English starts here.',offerText:'Message me on Telegram. We’ll discuss your level, goals and the right lesson plan for you.',offerButton:'Ask about lessons ↗',contactEyebrow:'Contact',contactTitle:'Ready to get started?',contactText:'Send me a Telegram message and tell me who the lessons are for, your current level and what you want to achieve.',telegramButton:'Message on Telegram ↗',telegramNote:'Message me on Telegram: @Arakellyanv.',footer:'Online English lessons • From Armenia to anywhere in the world'},
      ru:{navLessons:'Занятия',navAbout:'Обо мне',navContact:'Контакты',eyebrow:'Английский в соответствии с вашими целями',heroTitle:'Говорите по-английски <em>увереннее.</em>',heroLead:'Индивидуальные онлайн-занятия для детей и взрослых с учётом вашего уровня, интересов и целей.',book:'Записаться на занятие ↗',explore:'О занятиях',noteTitle:'В своём темпе',noteText:'Для ваших целей',lessonsEyebrow:'Занятия',lessonsTitle:'Английский для реальной жизни',lessonsSub:'Учимся с понятной целью, практическими заданиями и индивидуальным подходом.',card1Title:'Для детей',card1Text:'Понятные объяснения, интересные задания и помощь со школьным английским.',card2Title:'Для взрослых',card2Text:'Разговорная практика, грамматика и уверенность в повседневных и рабочих ситуациях.',card3Title:'Под ваши цели',card3Text:'Программа адаптируется к вашему уровню, интересам и целям обучения.',aboutEyebrow:'Давайте знакомиться',aboutTitle:'Здравствуйте, я Виктория.',aboutText:'У меня более трёх лет опыта преподавания английского языка. Я работаю и с детьми, и со взрослыми. Моя цель — создать дружелюбную атмосферу, где можно задавать вопросы, ошибаться, пробовать снова и постепенно увереннее использовать английский.',chip1:'Индивидуальные занятия',chip2:'Разговорная практика',chip3:'Дети и взрослые',chip4:'Онлайн-обучение',offerEyebrow:'Начнём вместе',offerTitle:'Следующий шаг в английском начинается здесь.',offerText:'Напишите мне в Telegram. Обсудим ваш уровень, цели и подходящий формат занятий.',offerButton:'Узнать о занятиях ↗',contactEyebrow:'Контакты',contactTitle:'Готовы начать?',contactText:'Напишите мне в Telegram и расскажите, для кого нужны занятия, какой у вас уровень и чего вы хотите достичь.',telegramButton:'Написать в Telegram ↗',telegramNote:'Напишите мне в Telegram: @Arakellyanv.',footer:'Онлайн-уроки английского • Из Армении и из любой точки мира'}
    };
    let current = 'hy';
    document.getElementById('langToggle').addEventListener('click',()=>{ current = current==='hy'?'en':current==='en'?'ru':'hy'; document.documentElement.lang=current; document.querySelectorAll('[data-i18n]').forEach(el=>{const key=el.dataset.i18n;if(translations[current][key]) el.innerHTML=translations[current][key];}); });
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
