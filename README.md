![MasterHead](images/python-developer.gif)



<h1 align="center">Эдуард Татарников </h1>
<p align="center"> Я Backend-разработчик на Python.  
Мне нравится писать код на Python и я постоянно учусь делать это лучше! 😎</p>



<hr>
<h3 align="left">💡 Технлогии и Инструменты:</h3>
<a href="https://www.python.org/" title='Python' target="_blank"><img align="center" src="images/python.svg" width="36" height="36" alt="Python" hspace="2" /></a>
<a href="https://ru.wikipedia.org/wiki/SQL" title="Structured Query Language — язык управления базами данных для реляционных баз данных." target="_blank"><img align="center" src="images/sql.png" width="36" height="36" alt="SQL" hspace="2" /></a>
<a href="https://www.postgresql.org/" title="PostgreSQL" target="_blank"><img align="center" src="images/postgresql.svg" width="38" height="38" alt="PostgreSQL" hspace="2" /></a>
<a href="https://redis.io/" title="Redis" target="_blank"><img align="center" src="images/redis.png" width="43" height="43" alt="Redis" hspace="3"/></a>
<a href="https://www.djangoproject.com/" title="Django" target="_blank"><img align="center" src="images/django.svg" width="38" height="38" alt="Django" hspace="3" /></a>
<a href="https://flask.palletsprojects.com/" title="Flask" target="_blank"><img align="center" src="images/flask.png" width="45" height="45" alt="Flask" hspace="3" /></a>
<a href="https://docs.celeryq.dev/en/stable/" title="Celery" target="_blank"><img align="center" src="images/celery.png" width="36" height="36" alt="Celery" hspace="3" /></a>
<a href="https://docs.pytest.org/" title="Pytest" target="_blank"><img  align="center" src="images/pytest.svg" width="48" height="48" alt="Pytest" hspace="3" /></a>
<a href="https://www.docker.com/" title="Docker" target="_blank"><img align="center" src="images/docker.svg" width="41" height="41" alt="Docker" hspace="4" /></a>
<a href="https://docs.aiohttp.org/en/stable/" title="Aiohttp" target="_blank"><img align="center" src="images/aiohttp.svg" width="36" height="36" alt="Aiohttp" hspace="3" /></a>
<a href="https://git-scm.com/" title="Git" target="_blank"><img align="center" src="images/git.svg" width="35" height="35" alt="Git" hspace="3" /></a>
<a href="https://docs.github.com/en/actions" title="GitGub Actions" target="_blank"><img align="center" src="images/github-actions.svg" width="35" height="35" alt="GitGub Actions" hspace="3" /></a>
<a href="https://ru.wikipedia.org/wiki/CI/CD" title="CI/CD" target="_blank"><img align="center" src="images/cicd.png" width="36" alt="CI/CD" hspace="3" /></a>
<a href="https://ubuntu.com/" title="Ubuntu OS" target="_blank"><img align="center" src="images/ubuntu.svg" width="38" height="38" alt="Ubuntu OS" hspace="3" /></a>
<a href="https://www.jetbrains.com/pycharm/" title="PyCharm" target="_blank"><img align="center" src="images/pycharm.svg" width="34" height="34" alt="PyCharm" hspace="3" /></a>
<a href="https://git-scm.com/" title="Postman" target="_blank"><img align="center" src="images/postman.svg" width="35" height="35" alt="Postman" hspace="3" /></a>
<!--
Основной стек: Python • SOLID • GIT • GitHub • Django • Django Rest Framework • REST API • PostgreSQL • SQLite • SQLAlchemy • AsyncPG • SQL • Redis • Asyncio • Pytest • CI/CD • Linux • Docker • Celery • Nginx • Djoser • Typing • Loguru • ImageKit • Social_django • Aiocron • tqdm
-->



<hr>
<h3 align="left">👨‍💻 Мои работы:</h3>

 <details open>
  <summary>Проекты</summary>
   <ul>
    <li><a href="https://github.com/Edmaroff/retail-order-api">API-сервис заказа товаров для розничных сетей</a></li>
     <details>
      <summary>Описание</summary>
       <b>&nbsp;&nbsp;&nbsp;&nbsp;Задача:</b>
        <ul><ul>
         <li>Разработать backend-часть для автоматизации процессов закупок и продаж в розничной торговой сети.</li>
        </ul></ul>
       <b>&nbsp;&nbsp;&nbsp;&nbsp;Результаты:</b>
        <ul><ul>
         <li>Реализовал регистрацию пользователей через Djoser с JWT аутентификацией, включая поддержку OAuth авторизации через Google и GitHub с помощью social_django;</li>
         <li>Добавил функционал управления корзиной, контактами покупателей и создания заказов с поддержкой товаров из нескольких магазинов;</li>
         <li>Реализовал управление магазинами и товарами для продавцов, включая асинхронный импорт/экспорт товаров с использованием Celery и Redis, а также обработку изображений с Imagekit;</li>
         <li>Настроил автоматическое тестирование и линтинг с flake8 через GitHub Actions, включая покрытие кода тестами Pytest и интеграцию с PostgreSQL;</li>
         <li>Подключил документацию API с помощью drf-spectacular и подготовил коллекцию Postman для тестирования;</li>
         <li>Улучшил административный интерфейс с помощью django-baton;</li>
         <li>Реализовал развертывание проекта через Docker Compose с использованием Nginx.</li>
        </ul></ul>
       <b>&nbsp;&nbsp;&nbsp;&nbsp;<u>Используемые технологии:</u></b>
        <ul><ul>
         <li>Python, Django, Django REST Framework, Celery, Redis, Djoser, Docker, social_django, Imagekit, Pytest, drf-spectacular, django-baton, Nginx.</li>
        </ul></ul>&nbsp;
     </details>
    <li><a href="https://github.com/Edmaroff/mailing-service">API-сервис рассылок</a></li> 
     <details>
      <summary>Описание</summary>
       <b>&nbsp;&nbsp;&nbsp;&nbsp;<u>Задача:</u></b>
        <ul><ul>
         <li>Разработать API для управления рассылками с функцией автоматического запуска сообщений клиентам по заданным фильтрам и времени.</li>
        </ul></ul>
       <b>&nbsp;&nbsp;&nbsp;&nbsp;<u>Результаты:</u></b>
        <ul><ul>
         <li>Реализовал REST API для создания, просмотра и управления рассылками на основе Django REST Framework;</li>
         <li>Добавил фильтрацию клиентов по коду оператора и тегам для отправки сообщений;</li>
         <li>Реализовал автоматический запуск рассылок по расписанию с учетом времени начала и окончания рассылки с Celery;</li>
         <li>Настроил асинхронную отправку сообщений через Celery и Redis;</li>
         <li>Сделал мониторинг задач рассылки через Flower;</li>
         <li>Подготовил фикстуры с тестовыми данными и коллекцию Postman для тестирования API.;</li>
         <li>Реализовал запуск проекта с использованием Docker Compose.</li>
        </ul></ul>
       <b>&nbsp;&nbsp;&nbsp;&nbsp;<u>Используемые технологии:</u></b>
        <ul><ul>
         <li>Python, Django REST framework, PostgreSQL, Celery, Redis, Docker, Flower, Postman.</li>
        </ul></ul>&nbsp;
     </details>
    <li><a href="https://github.com/Edmaroff/database-tatto-bot">Система управления данными для тату-мастеров и клиентов</a></li> 
     <details>
      <summary>Описание</summary>
       <b>&nbsp;&nbsp;&nbsp;&nbsp;<u>Задача:</u></b>
        <ul><ul>
         <li>Разработать асинхронную систему управления данными для взаимодействия тату-мастеров и клиентов.</li>
        </ul></ul>
       <b>&nbsp;&nbsp;&nbsp;&nbsp;<u>Результаты:</u></b>
        <ul><ul>
         <li>Спроектировал структуру БД PostgreSQL для хранения профилей мастеров, клиентов, стилей тату, лайков и жалоб;</li>
         <li>Реализовал набор асинхронных функций для работы с БД, включая поиск и ранжирование анкет мастеров с использованием SQLAlchemy, AsyncPG и Asyncio;</li>
         <li>Разработал функции для генерации фейковых профилей мастеров и сбора статистики для администраторов;</li>
         <li>Сделал типизацию и логирование с Typing и Loguru.</li>
         <li>Обеспечил обработку ошибок и логирование для облегчения отладки и мониторинга.</li>
        </ul></ul>
       <b>&nbsp;&nbsp;&nbsp;&nbsp;<u>Используемые технологии:</u></b>
        <ul><ul>
         <li>Python, PostgreSQL, SQLAlchemy, AsyncPG, Asyncio, Loguru, Typing.</li>
        </ul></ul>&nbsp;
     </details>
    <li><a href="https://github.com/Edmaroff/product-shop-api">API-сервис для интернет-магазина</a></li> 
     <details>
      <summary>Описание</summary>
       <b>&nbsp;&nbsp;&nbsp;&nbsp;<u>Задача:</u></b>
        <ul><ul>
         <li>Разработать API для интернет-магазина продуктов на Django Rest Framework.</li>
        </ul></ul>
       <b>&nbsp;&nbsp;&nbsp;&nbsp;<u>Результаты:</u></b>
        <ul><ul>
         <li>Реализовал управление категориями и подкатегориями товаров с полями: наименование, slug и изображение, включая эндпоинты для вывода данных с пагинацией;</li>
         <li>Создал функционал корзины, включая добавление, изменение и удаление товаров, а также подсчет общей стоимости;</li>
         <li>Настроил JWT-аутентификацию, обеспечив безопасный доступ к корзине пользователей;</li>
         <li>Оптимизировал обработку изображений продуктов, добавив автоматическое создание миниатюр с Imagekit;</li>
         <li>Настроил фикстуры для загрузки начальных данных в PostgreSQL и подключил Swagger UI для автоматической документации API;</li>
         <li>Покрыл тестами ключевые методы с использованием Pytest.</li>
        </ul></ul>
       <b>&nbsp;&nbsp;&nbsp;&nbsp;<u>Используемые технологии:</u></b>
        <ul><ul>
         <li>Python, Django REST framework,PostgreSQL, drf-spectacular, Imagekit, Pytest.</li>
        </ul></ul>&nbsp;
     </details>
    <li><a href="https://github.com/Edmaroff/fix-price-parser">Парсер Fix Price</a></li> 
     <details>
      <summary>Описание</summary>
       <b>&nbsp;&nbsp;&nbsp;&nbsp;<u>Задача:</u></b>
        <ul><ul>
         <li>Разработать программу для сбора данных о товарах интернет-магазина Fix Price с учетом региональных особенностей.</li>
        </ul></ul>
       <b>&nbsp;&nbsp;&nbsp;&nbsp;<u>Результаты:</u></b>
        <ul><ul>
         <li>Реализовал сбор данных о товарах, включая название, цену, скидки и наличие, с обработкой пагинации и региональных настроек;</li>
         <li>Добавил поддержку прокси-серверов для увеличения устойчивости работы парсера;</li>
         <li>Организовал сохранение данных в JSON-формате с заданной структурой для дальнейшей обработки;</li>
         <li>Обработал возможные ошибки и исключения для стабильной работы парсера;</li>
         <li>Реализовал запуск через docker-compose.</li>
        </ul></ul>
       <b>&nbsp;&nbsp;&nbsp;&nbsp;<u>Используемые технологии:</u></b>
        <ul><ul>
         <li>Python, Scrapy, Docker.</li>
        </ul></ul>&nbsp;
     </details>
    <li><a href="https://github.com/Edmaroff/database-marketing-bot/">Система управления данными для маркетинга</a></li> 
     <details>
      <summary>Описание</summary>
       <b>&nbsp;&nbsp;&nbsp;&nbsp;<u>Задача:</u></b>
        <ul><ul>
         <li>Разработать асинхронную систему управления реферальной программой с использованием реляционной базы данных.</li>
        </ul></ul>
       <b>&nbsp;&nbsp;&nbsp;&nbsp;<u>Результаты:</u></b>
        <ul><ul>
         <li>Спроектировал структуру БД для пользователей, реферальных связей и контент-плана;</li>
         <li>Интегрировал асинхронный драйвер AsyncPG и интерфейсы SQLAlchemy для взаимодействия с PostgreSQL;</li>
         <li>Разработал асинхронные функции для CRUD операций с помощью Asyncio;</li>
         <li>Реализовал асинхронный механизм персонализированной рассылки сообщений рефералам по контент-плану с Aiocron;</li>
         <li>Внедрил типизацию с Typing и логирование с Loguru;</li>
         <li>Обеспечил обработку ошибок и логирование для облегчения отладки и мониторинга.</li>
        </ul></ul>
       <b>&nbsp;&nbsp;&nbsp;&nbsp;<u>Используемые технологии:</u></b>
        <ul><ul>
         <li>Python, PostgreSQL, SQLAlchemy, AsyncPG, Asyncio, Loguru, Typing.</li>
        </ul></ul>&nbsp;
     </details>
    <li><a href="https://github.com/Edmaroff/library-manager">Менеджер библиотеки</a></li> 
     <details>
      <summary>Описание</summary>
       <b>&nbsp;&nbsp;&nbsp;&nbsp;<u>Задача:</u></b>
        <ul><ul>
         <li>Разработать консольное приложение для управления библиотекой книг без использования сторонних библиотек.</li>
        </ul></ul>
       <b>&nbsp;&nbsp;&nbsp;&nbsp;<u>Результаты:</u></b>
        <ul><ul>
         <li>Разработал модульную и масштабируемую архитектуру приложения с использованием принципов ООП, включая разделение на слои: модели данных, бизнес-логику, управление данными и пользовательский интерфейс;</li>
         <li>Реализовал основные функции: добавление, удаление, поиск, отображение и изменение статуса книг;</li>
         <li>Обеспечил хранение данных в формате JSON с поддержкой долговременного сохранения и восстановления информации;</li>
         <li>Реализовал обработку ошибок и исключений для предотвращения сбоев при некорректном вводе;</li>
         <li>Написал модульные тесты для проверки всех ключевых функций приложения c Pytest.</li>
        </ul></ul>
       <b>&nbsp;&nbsp;&nbsp;&nbsp;<u>Используемые технологии:</u></b>
        <ul><ul>
         <li>Python, Pytest.</li>
        </ul></ul>&nbsp;
     </details>
   </ul>
 </details>


<hr>
<h3 align="left">📞 Связаться со мной:</h3>
<p align="left">
 <a href="https://t.me/ed_tatarnikov" title='Telegram' target="_blank"><img align="center" src="images/telegram.svg" alt="Telegram" width="40" hspace="3" /></a>
 <a href="mailto:edmaroff@gmail.com" title="Gmail" target="_blank"><img align="center" src="images/gmail.svg" alt="Gmail" width="35" hspace="3"/></a>
 <a href="mailto:edmarof@yandex.ru" title="Yandex Mail" target="_blank"><img align="center" src="images/yandex_mail.svg" alt="Yandex Mail" width="45"/></a>
</p>



<hr> 
<h3 align="left">📈 GitHub:</h3>
<table>
  <tr>
    <td>
      <img align="left" src="http://github-readme-streak-stats.herokuapp.com?user=Edmaroff&theme=dark&background=000000" alt="webDev's Github stats" />
    </td>
    <td>
      <img height="195px" align="right" alt="webDev's Github Languages" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=Edmaroff&layout=compact&theme=vision-friendly-dark" />
    </td>
  </tr>
</table>



<!-- ---
<hr>
<h3 align="left"><a href="https://www.codewars.com/users/Edmaroff" title='Codewars' target="_blank"><img src="images/codewars.svg" alt="Codewars" width="20" /></a>  Codewars:</h3>
<a href="https://www.codewars.com/users/Edmaroff" title='Codewars' target="_blank"><img align="center" src="https://www.codewars.com/users/Edmaroff/badges/large" alt="Codewars rank" /></a> -->



<hr>
<p align="center"><img src="https://komarev.com/ghpvc/?username=Edmaroff&style=flate&color=blue" alt=""></p>
