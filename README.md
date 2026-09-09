👋 Привет, я Кулясов Иван Алексеевич

🚀 Full-Stack Developer (Telegram Mini Apps & Web3 / GameFi)

Занимаюсь проектированием и разработкой асинхронных бэкенд-систем, Web3-сервисов и полноэкранных Telegram Mini Apps (TMA) со сложной игровой и финансовой логикой.

---

🎓 Образование
* **СПO:** Информационные системы и программирование *(Окончено)*
* **ВПО (Бакалавриат):** Разработка информационных систем и систем искусственного интеллекта *(В процессе)*

---

🛠 Технологический стек

* **Backend:** Python (Flask), Node.js (Express), Asyncio, REST API.
* **Databases:** PostgreSQL (psycopg), Google Firestore (NoSQL, Transactions, Atomic updates).
* **Telegram & Web3:** Telegram Web App API, python-telegram-bot, TON Blockchain (ton://, Tonkeeper API), Coinbase Commerce API.
* **Frontend & Mobile UX:** HTML5/CSS3 (Glassmorphism UI), Javascript, Bootstrap 5, iOS Safe Area / Dynamic Island Adaptation.
* **Security & Architecture:** Server-Authoritative Logic, HMAC-SHA256 Auth, Transational Game Engine.
* **DevOps & Hosting:** Render, Vercel, Git, GitHub Actions.

---

🌟 Флагманский проект: TonStore & StoreTycoon

Гибридная Web3-экосистема внутри Telegram, объединяющая e-commerce магазин и GameFi-тайкун.

**Ключевая архитектура и особенности:**
* **E-Commerce модуль (TonStore):** Написан на Python/Flask. Обрабатывает корзину, каталоги вариативных товаров и заказы с хранением в PostgreSQL.
* **GameFi Engine (StoreTycoon):** Выделенный Node.js/Express бэкенд. Построен по принципу **Server-Authoritative** (сервер — единственный источник правды), исключающему накрутку баланса и откаты через атомарные транзакции Firestore и проверку клик-дельт.
* **Web3 & Крипто-экономика:** Бесшовная интеграция токена TST, прямые платежи в TON Blockchain через Base64 QR-коды и инвойсы Coinbase Commerce.
* **Безопасность:** Криптографическая валидация каждой сессии `initData` через HMAC-SHA256.
* **UI/UX & Mobile Adaptation:** Адаптивный Glassmorphism-дизайн, обход ограничений свайпов Telegram API, поддержка Dynamic Island и бесшовный полноэкранный `iframe`-оверлей для игры.
* **Деплой:** Микросервисная распределенная инфраструктура на Render (Flask) и Vercel (Game Node).

---

📬 Связь со мной

* **Telegram:** [@fr0gsel]
* **Email:** [ivanculyasov@yandex.ru]
