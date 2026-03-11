<br clear="both">


<div align="center" style="margin-top: 40px;">
  <img src="assets/images/developergif.gif" width="700" height="300" style="display: block; margin: 0 auto;">
</div>


<h1 align="center">Привет, я Георгий!</h1>

<hr style="width: 100%; margin: 0; margin-top: 5px; margin-bottom: 40px; opacity: 0.5;">

##  &nbsp; Я веб-разработчик

-  👨‍🎓- Завершил обучение по веб-разработке на Python в ["Top Academy"](https://msk.top-academy.ru). В ходе обучения приобрел следующие навыки:

- Освоил Django и Flask для создания веб-приложений.
- Изучил клиентские технологии, такие как JavaScript, HTML и CSS, Bootstrap, GSAP.
  
- [Диплом](assets/pdf/диплом.pdf)

- Изучил Tailwind для быстрой и адаптивной верстки.

## 🚀 Pet проекты

### [🎵 RubySound.fm](https://github.com/MRGiorgiosDev8/musicPlatform_api_django)
**Fullstack-платформа для поиска музыки и социального взаимодействия**

* **Live Demo:** 🌍 [georgios8-rubysoundfm.onrender.com](https://georgios8-rubysoundfm.onrender.com)
* **Стек:** Python (Django, ASGI/Uvicorn), PostgreSQL, **Redis (Caching & Channels)**, Docker, GitHub Actions (CI/CD), GSAP (Animations).

---

#### 🚀 Технологические особенности и архитектура:

* **Умный асинхронный движок**: Реализован параллельный сбор данных (batch-запросы) из **iTunes**, **Deezer** и **Last.fm** с помощью `httpx`, что обеспечивает мгновенный отклик API даже при агрегации из нескольких источников.
* **Real-time Layer**: Интегрированы **WebSockets (Django Channels)** для реализации динамических функций:
    * **Presence**: Отображение статуса пользователя (Online/Offline) в реальном времени.
    * **Live-комментарии**: Мгновенная синхронизация обсуждений в публичных плейлистах без перезагрузки страницы.
    * **Уведомления**: Система оповещений о новых лайках и взаимодействиях.
* **Высокая производительность**: Настроено многоуровневое кэширование через **Redis**, что позволило оптимизировать нагрузку на внешние API и ускорить повторную выдачу результатов поиска в несколько раз.
* **Frontend Polish**: 
    * Интерактивное модальное окно биографий артистов на базе **Wikipedia API** с логикой автоматического перевода (RU/EN fallback).
    * Плавные интерфейсные анимации с использованием библиотеки **GSAP**.
    * Полная адаптивность по принципу **Mobile First**.

#### 🌟 Основные возможности:

- 🔍 **Умный асинхронный поиск**: Мгновенный сбор данных из трех внешних источников одновременно.
- 🧠 **Автокомплит**: Интерактивные подсказки артистов в выпадающем списке по мере ввода.
- 📈 **Интерактивные чарты**: Динамические списки популярных треков с фильтрацией по жанрам.
- ❤️ **Персональная медиатека**: Создание плейлистов, управление избранным и **умная фильтрация** внутри подборок (по дате релиза или артисту).
- 👍 **Социальные механики**: Публичные страницы, система лайков, глобальный рейтинг на Dashboard и Real-time комментарии.
- 🟢 **Presence System**: Отображение текущего онлайн-статуса пользователей через WebSocket.
- 📚 **Artist Bio**: Детальные биографии и фото артистов в модальных окнах (Wikipedia integration).
- 🔐 **Безопасность**: Защищенная аутентификация на базе JWT-токенов.
- 🔄 **Инфраструктура**: Контейнеризация проекта (**Docker**) и автоматизированный CI/CD пайплайн (**GitHub Actions**) для деплоя на Render.

---

### 🌍 Wikipedia API + Artist Bio Modal

При клике на имя артиста открывается модальное окно с:

- Биографией исполнителя (RU/EN fallback)  
- Фотографией из Wikipedia  
 

### ☸️ Kubernetes версия (ветка [k8s_version](https://github.com/MRGiorgiosDev8/musicPlatform_api_django/blob/k8s_version/readme.md))
* Дополнительно разработана инфраструктура оркестрации для обеспечения отказоустойчивости (**Self-healing**) и масштабируемости.
* Внедрены **Deep Health Checks** для мониторинга связей с БД и Redis, а также автоматизированная система **Disaster Recovery** (ежедневные бэкапы через CronJobs и сценарии быстрого восстановления).
* Настроены **InitContainers** для управления порядком запуска и **RollingUpdate** для обновлений без простоя (**Zero-Downtime**).


<hr style="width: 100%; margin: 0; margin-top: 5px; margin-bottom: 40px; opacity: 0.5;">


### 💬 Связь со мной:

[![Telegram Badge](https://img.shields.io/badge/Telegram-%40mrgiorgio8-blue)](https://t.me/mrgiorgio8)&nbsp;&nbsp;&nbsp;
[![Email Badge](https://img.shields.io/badge/Email-Gmail&#10144;-red)](mailto:gerorge.oblivantsev8@gmail.com)

<hr style="width: 100%; margin: 0; margin-top: 5px; margin-bottom: 20px; opacity: 0.5;">

<div align="center" style="margin-top: 40px;">
  <img src="assets/images/citygif.gif" width="600" height="260" style="display: block; margin: 0 auto;">
</div>

<hr style="width: 100%; margin: 0; margin-top: 5px; margin-bottom: 20px; opacity: 0.5;">

## 🛠 Технологии:
[![My Skills](https://skillicons.dev/icons?i=python,django,flask,postgres,docker,githubactions,linux,js,html,css,tailwind,bootstrap,pycharm,vscode)](https://skillicons.dev)
