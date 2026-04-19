# Roman Shemetov

### AI Implementation / Delivery Manager | Technical Customer Success / Solutions Engineer | AI Automation / Integration Engineer

> 🎯 **Помогаю бизнесу доводить AI и автоматизацию до внедрения, интеграции и измеримого результата.**  

---

## 🛠 Технологический стек

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11+-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/AsyncIO-✅-000000?style=flat" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLAlchemy-2.0-D71F00?style=flat&logo=sqlalchemy&logoColor=white" />
  <img src="https://img.shields.io/badge/aiogram-3.x-2CA5E0?style=flat&logo=telegram&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-🦜🔗-000000?style=flat" />
  <img src="https://img.shields.io/badge/OpenAI_API-✅-412991?style=flat&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/RAG-🔍-FF6B6B?style=flat" />
  <img src="https://img.shields.io/badge/Prompt_Engineering-💡-FFD93D?style=flat" />
  <img src="https://img.shields.io/badge/React-18-61DAFB?style=flat&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-✅-3178C6?style=flat&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-16-4169E1?style=flat&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-✅-003B57?style=flat&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-✅-2496ED?style=flat&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker_Compose-✅-2496ED?style=flat" />
  <img src="https://img.shields.io/badge/Nginx-🔄-009639?style=flat&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/REST_API-✅-000000?style=flat" />
  <img src="https://img.shields.io/badge/JWT-🔐-000000?style=flat" />
  <img src="https://img.shields.io/badge/1C_Integration-✅-FFCC00?style=flat" />
  <img src="https://img.shields.io/badge/Mindbox-✅-0077CC?style=flat" />
  <img src="https://img.shields.io/badge/iiko-✅-FF6B35?style=flat" />
  <img src="https://img.shields.io/badge/R_Keeper-✅-00A651?style=flat" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/Loki-🪵-3178C6?style=flat" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Vibe_Coding-🎯-9333EA?style=flat" />
</p>

---

## ⭐ Избранные проекты

### 🔹 [ClientOrder](https://github.com/RomanShe19/ClientOrder) `Full-Stack` `Production-Ready`
**Проблема:** Большинство учебных проектов не учитывают ограничения реального сервера и требования к безопасности.  
**Решение:** Самохостируемая платформа для приёма заказов с React + FastAPI, оптимизированная под **VPS с 1 ГБ RAM**. Реализованы: JWT-аутентификация, поведенческая аналитика (тепловые карты, клики), reverse proxy (Nginx), лимиты ресурсов на контейнеры, авто-деплой через Watchtower.  
*Stack: FastAPI, React 18 + TS, PostgreSQL, Docker Compose, Nginx, SQLAlchemy 2 (async)*

### 🔹 [AI Bot Generator](https://github.com/RomanShe19/telegram_bot_generator) `LangChain` `Code Generation`
**Проблема:** Рутинная разработка типовых ботов отнимает время.  
**Решение:** 5-этапный LLM-пайплайн на LangChain, который превращает текстовое ТЗ в готовый код на aiogram 3.x с валидацией синтаксиса и структуры.  
*Stack: LangChain, ProxyAPI, aiogram 3.x, Pydantic*

### 🔹 [AI Agent with Tools](https://github.com/RomanShe19/AI_Agent_with_tools) `Agents` `Function Calling`
**Проблема:** Локальные AI-ассистенты часто ограничены «болтовней» без доступа к внешним данным.  
**Решение:** Агент с системой инструментов (Web Search, Weather, Crypto, Files, Terminal) и двойным интерфейсом (CLI + Telegram). Реализована контекстная память и логирование действий.  
*Stack: LangChain, OpenAI API, aiogram, duckduckgo-search*

### 🔹 [Parser + Telegram Bot](https://github.com/RomanShe19/Parser) `Scraping` `Anti-Detect`
**Проблема:** Сбор данных с сайтов, защищённых от ботов, требует обхода антидетект-механизмов.  
**Решение:** Асинхронный парсер с `curl-cffi` и `Playwright` для эмуляции реального браузера. Управление и просмотр результатов — через Telegram-бота. Полная изоляция в Docker.  
*Stack: asyncio, Playwright, curl-cffi, aiogram 3.x, SQLite, Docker*

### 🔹 [Monitoring Stack](https://github.com/RomanShe19/monitoring) `DevOps` `Observability`
**Проблема:** Понимание observability критично для production-разработки, но редко встречается в учебных проектах.  
**Решение:** Развёрнутый стек Grafana + Loki + Promtail для сбора, визуализации и анализа логов. Демонстрирует подход к отладке и мониторингу как к инженерной задаче.  
*Stack: Docker, Grafana, Loki, Promtail, Python logging*

### 🔹 [AI Assistant Telegram Bot](https://github.com/RomanShe19/AI_Assistant_TGbot)
**Проблема:** Пользователям нужен не просто чат с ИИ, а ассистент с памятью, ролями и мультимодальностью.  
**Решение:** Бот с контекстной памятью, переключением ролей (developer/analyst/writer), генерацией изображений (DALL·E) и учётом токенов.  
*Stack: aiogram 3.x, OpenAI API, SQLAlchemy, asyncpg*

> 💡 *Полный список проектов: [Repositories](https://github.com/RomanShe19?tab=repositories)*

---

# 🌟 Чем я полезен вашему продукту

| Роль | Как я создаю ценность |
|------|----------------------|
| **AI Implementation / Delivery Manager** | Беру на себя внедрение AI/tech-решения от discovery до go-live: координирую интеграции, управляю рисками запуска, держу в фокусе adoption, time-to-value и бизнес-результат. |
| **Technical Customer Success / Solutions Engineer** | Помогаю клиенту быстро дойти до ценности через интеграции, onboarding, rollout и technical consulting. Могу сам разобрать API, найти ограничение и предложить рабочий путь внедрения. |
| **AI Automation / Integration Engineer** | Собираю automation и integration MVP на Python, API и LLM-инструментах: быстро проверяю гипотезу, увязываю сервисы между собой и довожу до работающего сценария. |


<p align="center">
  <strong>🎯 Vibecode-подход</strong> • AI как рычаг, а не автопилот
</p>
<p align="center">
  🧠 <b>Implementation:</b> go-live, adoption и delivery под контролем • 
  ⚡ <b>Tech CSM / Solutions:</b> быстрый TTV и value realization для клиента • 
  🧱 <b>Automation / Integrations:</b> код, API и workflow собираются в рабочий сценарий • 
  🔄 <b>Все роли:</b> рутина автоматизируется по умолчанию
</p>
<p align="center">
  <sub>Прототип → валидация → production: быстро, измеримо, масштабируемо</sub>
</p>

---

## 📈 Текущий фокус развития

- 🤖 Углубление в агентные архитектуры и multi-agent системы
- ⚙️ Оптимизация async-приложений под высокие нагрузки
- 🧪 Внедрение тестирования (unit/integration) в пет-проекты
- 📦 Изучение Kubernetes и cloud-деплой (AWS/GCP)

---

## 📫 Давайте свяжемся

Готов обсудить, как мой опыт в запуске 600+ внедрений и технические навыки в Python/AI могут помочь вашему продукту расти.

| 📧 Email | [rabota.adsgroup@gmail.com] |
|----------|--------------|
| 🐙 GitHub | [RomanShe19](https://github.com/RomanShe19) |

> 💡 *"Моя цель — не просто написать код, а создать решение, которое измеряется в бизнес-метриках: выручка, удержание, эффективность."*

---

<p align="center">
  <i>⚡ Vibecode: чистый код, умные инструменты, быстрый результат.</i>
</p>
