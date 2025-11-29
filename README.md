<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>vCard - Personal Portfolio</title>
  <link rel="shortcut icon" href="./assets/images/logo.ico" type="image/x-icon">
  <link rel="stylesheet" href="./assets/css/style.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">
</head>
<body>
  <main>
    <aside class="sidebar" data-sidebar>
      <div class="sidebar-info">
        <figure class="avatar-box">
          <img src="/vcard-personal-portfolio-master/assets/images/5409031420187371611.jpg"Om Kharche" width="80">
        </figure>
        <div class="info-content">
          <h1 class="name" title="Om Kharche">Tynybekova Asema</h1>
          <p class="title">Информатик</p>
        </div>
        <button class="info_more-btn" data-sidebar-btn>
          <span>Контакты</span>
          <ion-icon name="chevron-down"></ion-icon>
        </button>
      </div>
      <div class="sidebar-info_more">
        <div class="separator"></div>
        <ul class="contacts-list">
          <li class="contact-item">
            <div class="icon-box">
              <ion-icon name="mail-outline"></ion-icon>
            </div>
            <div class="contact-info">
              <p class="contact-title">Email</p>
              <a href="asematynybekova8@gmail.com" class="contact-link">asematynybekova8@gmail.com </a>
            </div>
          </li>
          <li class="contact-item">
            <div class="icon-box">
              <ion-icon name="phone-portrait-outline"></ion-icon>
            </div>
            <div class="contact-info">
              <p class="contact-title">Телефон</p>
              <a href="tel:+12133522795" class="contact-link">+996501036328</a>
            </div>
          </li>
          <li class="contact-item">
            <div class="icon-box">
              <ion-icon name="calendar-outline"></ion-icon>
            </div>
            <div class="contact-info">
              <p class="contact-title">День Рождения</p>
              <time datetime="2007-06-22">29-Ноябрь 2007 года</time>
            </div>
          </li>
          <li class="contact-item">
            <div class="icon-box">
              <ion-icon name="location-outline"></ion-icon>
            </div>
            <div class="contact-info">
              <p class="contact-title">Локация</p>
              <address>Манас , Кыргызстан</address>
            </div>
          </li>
        </ul>
        <div class="separator"></div>
        <ul class="social-list">
          <li class="social-item">
            <a href="" class="social-link">
              <ion-icon name="logo-facebook"></ion-icon>
            </a>
          </li>
          <li class="social-item">
            <a href="#" class="social-link">
              <ion-icon name="logo-twitter"></ion-icon>
            </a>
          </li>
          <li class="social-item">
            <a href="#" class="social-link">
              <ion-icon name="logo-instagram"></ion-icon>
            </a>
          </li>
        </ul>
      </div>
    </aside>
    <div class="main-content">
      <nav class="navbar">
        <ul class="navbar-list">
          <li class="navbar-item">
            <button class="navbar-link  active" data-nav-link>About</button>
          </li>
          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Resume</button>
          </li>
          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Portfolio</button>
          </li>
          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Blog</button>
          </li>
          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Contact</button>
        </ul>
      </nav>
      <article class="about  active" data-page="about">
        <header>
          <h2 class="h2 article-title">Обо мне</h2>
        </header>
        <section class="about-text">
          <p>
            Я — Тыныбекова Асема, креативный директор, UI/UX-дизайнер и педагог по информатике из Оша, Кыргызстан.
Работаю в сфере дизайна и образования, помогая создавать понятные, стильные и эффективные визуальные решения,С принцапами UI/UX 
          </p>
          <p>
           Моя работа — создать сайт для педогогов, который будет одновременно функциональным, удобным для пользователя и привлекательным.
Кроме того, я добавляю индивидуальность вашему продукту, делая его запоминающимся и простым в использовании.
Моя цель — максимально креативно донести вашу идею и 
я разрабатывала веб-сайт для педогогов .
          </p>
        </section>
        <section class="service">
          <h3 class="h3 service-title">Чем мы занимаемся</h3>
          <ul class="service-list">
            <li class="service-item">
              <div class="service-icon-box">
                <img src="./assets/images/icon-design.svg
                " alt="design icon" width="40">
              </div>
              <div class="service-content-box">
                <h4 class="h4 service-item-title">Веб-Дизайнер</h4>
                <p class="service-item-text">
                  Самый современный и качественный дизайн, выполненный на профессиональном уровне.
                </p>
              </div>
            </li>
            <li class="service-item">
              <div class="service-icon-box">
                <img src="./assets/images/icon-dev.svg" alt="Web development icon" width="40">
              </div>
              <div class="service-content-box">
                <h4 class="h4 service-item-title">Веб-Разработчик</h4>
                <p class="service-item-text">
                  Качественная разработка сайтов на профессиональном уровне.
                </p>
              </div>
            </li>
            <li class="service-item">
              <div class="service-icon-box">
                <img src="./assets/images/icon-app.svg" alt="mobile app icon" width="40">
              </div>
              <div class="service-content-box">
                <h4 class="h4 service-item-title">Разработки</h4>
                <p class="service-item-text">
                  Профессиональная разработка приложений для iOS и Android.
                </p>
              </div>
            </li>
            <li class="service-item">
              <div class="service-icon-box">
                <img src="./assets/images/icon-photo.svg" alt="camera icon" width="40">
              </div>
              <div class="service-content-box">
                <h4 class="h4 service-item-title">Фотография</h4>
                <p class="service-item-text">
                  Мы создаем качественные фотографии любой категории на профессиональном уровне..
                </p>
              </div>
            </li>
          </ul>
        </section>
        <section class="testimonials">
          <h3 class="h3 testimonials-title">Отзывы</h3>
          <ul class="testimonials-list has-scrollbar">
            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item>
                <figure class="testimonials-avatar-box">
                  <img src="./assets/images/avatar-1.png" alt="Daniel lewis" width="60" data-testimonials-avatar>
                </figure>
                <h4 class="h4 testimonials-item-title" data-testimonials-title>Пирмамбек</h4>
                <div class="testimonials-text" data-testimonials-text>
                  <p>
                    Асема была приглашёна для разработки корпоративного стиля, и мы остались очень довольны результатом.
                     Она обладает большим опытом и внимательно относится к потребностям клиента, предлагая решения высокого качества
                  </p>
                </div>
              </div>
            </li>
            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item>
                <figure class="testimonials-avatar-box">
                  <img src="./assets/images/avatar-2.png" alt="Jessica miller" width="60" data-testimonials-avatar>
                </figure>
                <h4 class="h4 testimonials-item-title" data-testimonials-title>Айтолкун</h4>
                <div class="testimonials-text" data-testimonials-text>
                  <p>
                    Асема — отличный графический дизайнер, с которым приятно и легко сотрудничать. Она обладает глубоким профессиональным опытом,
                     внимательна к деталям и всегда стремится понять потребности клиента. Асема предлагает креативные решения, быстро реагирует на правки и доводит работу до идеального результата. 
                    Мы остались очень довольны её подходом и качеством выполненной работы и с уверенностью рекомендуем её как высококлассного специалиста
                  </p>
                </div>
              </div>
            </li>
            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item>
                <figure class="testimonials-avatar-box">
                  <img src="./assets/images/avatar-3.png" alt="Emily evans" width="60" data-testimonials-avatar>
                </figure>
                <h4 class="h4 testimonials-item-title" data-testimonials-title>Эргешова</h4>
                <div class="testimonials-text" data-testimonials-text>
                  <p>
                    Работа с Асемой оставила только положительные впечатления. Она быстро понимает задачу, предлагает несколько вариантов дизайна и всегда находит оптимальное решение.
                     Её креативность и чувство стиля действительно выделяются.
                     Проект был выполнен раньше срока, а результат превзошёл наши ожидания. Отличный профессионал
                  </p>
                </div>
              </div>
            </li>
            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item>
                <figure class="testimonials-avatar-box">
                  <img src="./assets/images/avatar-4.png" alt="Henry william" width="60" data-testimonials-avatar>
                </figure>
                <h4 class="h4 testimonials-item-title" data-testimonials-title>акбаралиев</h4>
                <div class="testimonials-text" data-testimonials-text>
                  <p>
                    Асема — дизайнер, который умеет слушать и слышать клиента. Она тщательно продумывает каждую деталь и создаёт дизайн, 
                    который не только красиво выглядит, но и полностью отвечает поставленным задачам.
                     Работа выполнена качественно, аккуратно и с большим вкусом. Мы обязательно обратимся к ней снова.
                  </p>
                </div>
              </div>
            </li>
          </ul>
        </section>
        <div class="modal-container" data-modal-container>
          <div class="overlay" data-overlay></div>
          <section class="testimonials-modal">
            <button class="modal-close-btn" data-modal-close-btn>
              <ion-icon name="close-outline"></ion-icon>
            </button>
            <div class="modal-img-wrapper">
              <figure class="modal-avatar-box">
                <img src="./assets/images/avatar-1.png" alt="Daniel lewis" width="80" data-modal-img>
              </figure>
              <img src="./assets/images/icon-quote.svg" alt="quote icon">
            </div>
            <div class="modal-content">
              <h4 class="h3 modal-title" data-modal-title>Пользовпатель</h4>
              <time datetime="2021-06-14">14 June, 2021</time>
              <div data-modal-text>
                <p>
                  Сотрудничество с Асемой оказалось очень продуктивным. Она сразу погрузилась в проект,
                 предложила свежие и современные идеи и оперативно реализовала их в качественный дизайн. Асема ответственна, пунктуальна и по-настоящему увлечена своим делом. 
                  Результат работы получился стильным и профессиональным. Рекомендуем её как надёжного и талантливого специалиста
                </p>
              </div>
            </div>
          </section>
        </div>
        <section class="clients">
          <h3 class="h3 clients-title">Clients</h3>
          <ul class="clients-list has-scrollbar">
            <li class="clients-item">
              <a href="#">
                <img src="./assets/images/logo-1-color.png" alt="client logo">
              </a>
            </li>
            <li class="clients-item">
              <a href="#">
                <img src="./assets/images/logo-2-color.png" alt="client logo">
              </a>
            </li>
            <li class="clients-item">
              <a href="#">
                <img src="./assets/images/logo-3-color.png" alt="client logo">
              </a>
            </li>
            <li class="clients-item">
              <a href="#">
                <img src="./assets/images/logo-4-color.png" alt="client logo">
              </a>
            </li>
            <li class="clients-item">
              <a href="#">
                <img src="./assets/images/logo-5-color.png" alt="client logo">
              </a>
            </li>
            <li class="clients-item">
              <a href="#">
                <img src="./assets/images/logo-6-color.png" alt="client logo">
              </a>
            </li>
          </ul>
        </section>
      </article>
      <article class="resume" data-page="resume">
        <header>
          <h2 class="h2 article-title">Резьюме</h2>
        </header>
        <section class="timeline">
          <div class="title-wrapper">
            <div class="icon-box">
              <ion-icon name="book-outline"></ion-icon>
            </div>
            <h3 class="h3">Обучение</h3>
          </div>
          <ol class="timeline-list">
            <li class="timeline-item">
              <h4 class="h4 timeline-item-title">Ошский Государственный университет ОшГУ </h4>
              <span>2024 — 2028</span>
              <p class="timeline-text">
                МФТИТ институт Прикладная Информатика и Информационная Безопасность кафедра ПИиИБ
                Автоматизированные управление бизнес процессами и финансами 2 курс 
              </p>
            </li>
            <li class="timeline-item">
              <h4 class="h4 timeline-item-title">Иновационный лицей имени С.Давлетова №14 </h4>
              <span>2023 — 2024</span>
              <p class="timeline-text">
                10 класс
                11 класс
              </p>
            </li>
            <li class="timeline-item">
              <h4 class="h4 timeline-item-title">С.Жээнбеков №51 орто мектеби</h4>
              <span>2013 — 2022</span>
              <p class="timeline-text">
                1 класс
                -
                9 класс
              </p>
            </li>
          </ol>
        </section>
        <section class="timeline">
          <div class="title-wrapper">
            <div class="icon-box">
              <ion-icon name="book-outline"></ion-icon>
            </div>
            <h3 class="h3">Опыт</h3>
          </div>
          <ol class="timeline-list">
            <li class="timeline-item">
              <h4 class="h4 timeline-item-title">Веб-Дизайнер</h4>
              <span>2024 — Present</span>
              <p class="timeline-text">
                Фронтэнд и бекенд разработчик.
              </p>
            </li>
            <li class="timeline-item">
              <h4 class="h4 timeline-item-title">Fullstack developer</h4>
              <span>2024 — Present</span>
              <p class="timeline-text">
                Разрабатывать сайты и программы для улучшения и автоматизации приложении для удобства изпользования
              </p>
            </li>
            <li class="timeline-item">
              <h4 class="h4 timeline-item-title">Дизайнер</h4>
              <span>2022 — 2024</span>
              <p class="timeline-text">
                Опытный Дизайнер,стилист
              </p>
            </li>
          </ol>
        </section>
        <section class="skill">
          <h3 class="h3 skills-title">Mои навыки </h3>
          <ul class="skills-list content-card">
            <li class="skills-item">
              <div class="title-wrapper">
                <h5 class="h5">Веб-Дизайн</h5>
                <data value="80">80%</data>
              </div>
              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 80%;"></div>
              </div>
            </li>
            <li class="skills-item">
              <div class="title-wrapper">
                <h5 class="h5">Графический Дизайнер</h5>
                <data value="70">70%</data>
              </div>
              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 70%;"></div>
              </div>
            </li>
            <li class="skills-item">
              <div class="title-wrapper">
                <h5 class="h5">Кодирование</h5>
                <data value="90">90%</data>
              </div>
              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 90%;"></div>
              </div>
            </li>
            <li class="skills-item">
              <div class="title-wrapper">
                <h5 class="h5">WordPress</h5>
                <data value="50">50%</data>
              </div>
              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 50%;"></div>
              </div>
            </li>
          </ul>
        </section>
      </article>
      <article class="portfolio" data-page="portfolio">
        <header>
          <h2 class="h2 article-title">Портфолио</h2>
        </header>
        <section class="projects">
          <ul class="filter-list">
            <li class="filter-item">
              <button class="active" data-filter-btn>Все</button>
            </li>
          </ul>
          <div class="filter-select-box">
            <button class="filter-select" data-select>
              <div class="select-value" data-selecct-value>Выбрать категории</div>
              <div class="select-icon">
                <ion-icon name="chevron-down"></ion-icon>
              </div>
            </button>
            <ul class="select-list">
              <li class="select-item">
                <button data-select-item>All</button>
              </li>
              <li class="select-item">
                <button data-select-item>Web design</button>
              </li>
              <li class="select-item">
                <button data-select-item>Applications</button>
              </li>
              <li class="select-item">
                <button data-select-item>Web development</button>
              </li>
            </ul>
          </div>
          <ul class="project-list">
            <li class="project-item  active" data-filter-item data-category="web development">
              <a href="#">
                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>
                  <img src="./assets/images/project-1.jpg" alt="finance" loading="lazy">
                </figure>
                <h3 class="project-title">Реферат</h3>
                <p class="project-category"></p>
              </a>
            </li>
            <li class="project-item  active" data-filter-item data-category="web development">
              <a href="#">
                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>
                  <img src="./assets/images/project-2.jpg" alt="orizon" loading="lazy">
                </figure>
                <h3 class="project-title">Отчет</h3>
                <p class="project-category"></p>
              </a>
            </li>
            <li class="project-item  active" data-filter-item data-category="web design">
              <a href="#">
                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>
                  <img src="./assets/images/project-3.jpg" alt="fundo" loading="lazy">
                </figure>
                <h3 class="project-title">Реферат</h3>
                <p class="project-category"></p>
              </a>
            </li>
            <li class="project-item  active" data-filter-item data-category="applications">
              <a href="#">
                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>
                  <img src="./assets/images/project-4.jpg" alt="brawlhalla" loading="lazy">
                </figure>
                <h3 class="project-title">Дипломная Работа</h3>
                <p class="project-category"></p>
              </a>
            </li>
            <li class="project-item  active" data-filter-item data-category="web design">
              <a href="#">
                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>
                 <iframe src="/vcard-personal-portfolio-master/assets/files/1_Лекция.pdf" width="100%" height="400px"></iframe>
                </figure>
                <h3 class="project-title">1_Лекция</h3>
                <p class="project-category"></p>
              </a>
            </li>
            <li class="project-item  active" data-filter-item data-category="web design">
              <a href="/vcard-personal-portfolio-master/assets/files/жумушчу_программа.pdf">
                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>
                  <iframe src="/vcard-personal-portfolio-master/assets/files/жумушчу_программа.pdf" width="100%" height="400px"></iframe>
                </figure>
                <h3 class="project-title">жумушчу_программа</h3>
                <p class="project-category"></p>
              </a>
            </li>
            <li class="project-item  active" data-filter-item data-category="web development">
              <a href="/vcard-personal-portfolio-master/assets/files/Силлабус_Абдирайимова_1С-1.pdf">
                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>
                  <iframe src="/vcard-personal-portfolio-master/assets/files/Силлабус_Абдирайимова_1С-1.pdf" width="100%" height="400px"></iframe>
                </figure>
                <h3 class="project-title">Силлабус</h3>
                <p class="project-category"></p>
              </a>
            </li>
            <li class="project-item  active" data-filter-item data-category="applications">
              <a href="/vcard-personal-portfolio-master/assets/files/№1Лабораториялык_жумуш.pdf">
                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>
                  <iframe src="/vcard-personal-portfolio-master/assets/files/№1Лабораториялык_жумуш.pdf" width="100%" height="400px"></iframe>
                </figure>
                <h3 class="project-title">№1Лабораториялык_жумуш</h3>
                <p class="project-category"></p>
              </a>
            </li>
            <li class="project-item  active" data-filter-item data-category="web development">
              <a href="/vcard-personal-portfolio-master/assets/files/Силлабус_МАКЕТ_25-26.pdf">
                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>
                  <iframe src="/vcard-personal-portfolio-master/assets/files/Силлабус_МАКЕТ_25-26.pdf" width="100%" height="400px"></iframe>
                </figure>
                <h3 class="project-title">Силлабус_МАКЕТ_25-26</h3>
                <p class="project-category"></p>
              </a>
            </li>
          </ul>
        </section>
      </article>
      <article class="blog" data-page="blog">
        <header>
          <h2 class="h2 article-title">Blog</h2>
        </header>
        <section class="blog-posts">
          <ul class="blog-posts-list">
            <li class="blog-post-item">
              <a href="#">
                <figure class="blog-banner-box">
                  <img src="./assets/images/blog-1.jpg" alt="Design conferences in 2022" loading="lazy">
                </figure>
                <div class="blog-content">
                  <div class="blog-meta">
                    <p class="blog-category">Design</p>
                    <span class="dot"></span>
                    <time datetime="2022-02-23">Fab 23, 2022</time>
                  </div>
                  <h3 class="h3 blog-item-title"></h3>
                  <p class="blog-text">
                  </p>
                </div>
              </a>
            </li>
            <li class="blog-post-item">
              <a href="#">
                <figure class="blog-banner-box">
                  <img src="./assets/images/blog-2.jpg" alt="Best fonts every designer" loading="lazy">
                </figure>
                <div class="blog-content">
                  <div class="blog-meta">
                    <p class="blog-category">Design</p>
                    <span class="dot"></span>
                    <time datetime="2022-02-23">Ноя 27, 2023</time>
                  </div>
                  <h3 class="h3 blog-item-title"></h3>
                  <p class="blog-text">
                  </p>
                </div>
              </a>
            </li>
            <li class="blog-post-item">
              <a href="#">
                <figure class="blog-banner-box">
                  <img src="./assets/images/blog-3.jpg" alt="Design digest #80" loading="lazy">
                </figure>
                <div class="blog-content">
                  <div class="blog-meta">
                    <p class="blog-category">Design</p>
                    <span class="dot"></span>
                    <time datetime="2022-02-23">Fab 23, 2022</time>
                  </div>
                  <h3 class="h3 blog-item-title"></h3>
                  <p class="blog-text">
                  </p>
                </div>
              </a>
            </li>
            <li class="blog-post-item">
              <a href="#">
                <figure class="blog-banner-box">
                  <img src="./assets/images/blog-4.jpg" alt="UI interactions of the week" loading="lazy">
                </figure>
                <div class="blog-content">
                  <div class="blog-meta">
                    <p class="blog-category">Design</p>
                    <span class="dot"></span>
                    <time datetime="2022-02-23">Сен 5, 2023</time>
                  </div>
                  <h3 class="h3 blog-item-title"></h3>
                  <p class="blog-text">
                  </p>
                </div>
              </a>
            </li>
            <li class="blog-post-item">
              <a href="#">
                <figure class="blog-banner-box">
                  <img src="./assets/images/blog-5.jpg" alt="The forgotten art of spacing" loading="lazy">
                </figure>
                <div class="blog-content">
                  <div class="blog-meta">
                    <p class="blog-category">Design</p>
                    <span class="dot"></span>
                    <time datetime="2022-02-23">Аув 10, 2024</time>
                  </div>
                  <h3 class="h3 blog-item-title"></h3>
                  <p class="blog-text">
                  </p>
                </div>
              </a>
            </li>
            <li class="blog-post-item">
              <a href="#">
                <figure class="blog-banner-box">
                  <img src="./assets/images/blog-6.jpg" alt="Design digest #79" loading="lazy">
                </figure>
                <div class="blog-content">
                  <div class="blog-meta">
                    <p class="blog-category">Design</p>
                    <span class="dot"></span>
                    <time datetime="2022-02-23">Янв 23, 2025</time>
                  </div>
                  <h3 class="h3 blog-item-title"></h3>
                  <p class="blog-text">
                  </p>
                </div>
              </a>
            </li>
          </ul>
        </section>
      </article>
      <article class="contact" data-page="contact">
        <header>
          <h2 class="h2 article-title">Contact</h2>
        </header>
        <section class="mapbox" data-mapbox>
          <figure>
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3032.449069757429!2d72.79032400321319!3d40.53166681035268!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x38bdac05225c2cfd%3A0x16bd460bd75f22ab!2z0J7RiNGB0LrQuNC5INCT0L7RgdGD0LTQsNGA0YHRgtCy0LXQvdC90YvQuSDRg9C90LjQstC10YDRgdC40YLQtdGCICjQk9C70LDQstC90YvQuSDQutC-0YDQv9GD0YEp!5e0!3m2!1sru!2skg!4v1764347158154!5m2!1sru!2skg" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
          </figure>
        </section>
        <section class="contact-form">
          <h3 class="h3 form-title">Contact Form</h3>
          <form action="#" class="form" data-form>
            <div class="input-wrapper">
              <input type="text" name="fullname" class="form-input" placeholder="Full name" required data-form-input>
              <input type="email" name="email" class="form-input" placeholder="Email address" required data-form-input>
            </div>
            <textarea name="message" class="form-input" placeholder="Your Message" required data-form-input></textarea>
            <button class="form-btn" type="submit" disabled data-form-btn>
              <ion-icon name="paper-plane"></ion-icon>
              <span>Send Message</span>
            </button>
          </form>
        </section>
      </article>
    </div>
  </main>
  <script src="./assets/js/script.js"></script>
  <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
</body>
</html>
