# CloakAI - Помощник по проведению собеседований/экзаменов | Interview/Exam Assistant

![CloakAI Logo](assets/logo.png)

## [RU] Описание проекта

**CloakAI** — это профессиональный инструмент для разработчиков, студентов и всех, кому необходима скрытная помощь во время технических интервью или ответственных онлайн-экзаменов. Приложение помогает автоматизировать решение сложных задач в реальном времени, сочетая передовые технологии компьютерного зрения и распознавания речи, оставаясь при этом полностью невидимым для систем прокторинга и мониторинга.

### Основные возможности

*   🤫 **Режим Stealth (Скрытность)**: Приложение маскируется под системный процесс "ServiceHost". Окно не отображается при демонстрации экрана (Zoom, Teams, Discord...итд) и защищено от захвата скриншотами.
*   🔑 **Модель BYOK (Bring Your Own Key)**: Вы используете собственные API-ключи. Это гарантирует максимальную конфиденциальность и отсутствие посредников. **Бонус**: мы предоставляем инструкции по получению API-ключей (до 5 млн токенов) для топовых ИИ-моделей!
*   ⚡ **Сверхбыстрая генерация**: Мгновенное получение ответов благодаря поддержке высокопроизводительных моделей.
*   🎙️ **Транскрипция в реальном времени**: приложение "слушает" собеседника и мгновенно выводит текст и ответы на экран.
*   🧠 **Smart Mode (Умный режим)**: ИИ автоматически распознает вопросы в потоке речи и начинает генерировать решение без необходимости нажимать кнопки.
*   📸 **Vision AI**: Анализ содержимого экрана. Отправьте скриншот, и ИИ предложит оптимальное решение.
*   📊 **Структурированные ответы**: Поддержка не только программирования, но и общих вопросов, задач по математике, физике и другим дисциплинам. Получайте:
    *   Сложные диаграммы и наглядные таблицы.
    *   Анализ временной и пространственной сложности (по Big O).
    *   Пошаговую стратегию решения.
    *   Чистый code-style и формулы.
*   📂 **Контекст интервью**: Добавьте свое резюме или описание вакансии. ИИ будет использовать эту информацию для адаптации ответов под конкретные требования.

---

## [EN] Project Description

**CloakAI** is a professional tool for developers, students, and anyone needing discreet assistance during technical interviews or high-stakes online exams. It helps automate real-time problem-solving by combining cutting-edge computer vision and speech recognition technologies, while remaining completely invisible to proctoring and monitoring systems.

### Key Features

*   🤫 **Stealth Mode**: The application disguises itself as a system process named "ServiceHost". The window is invisible during screen sharing (Zoom, Teams, Discord...etc) and is protected against screenshot capture.
*   🔑 **BYOK (Bring Your Own Key) Model**: Use your own API keys. This ensures maximum privacy and eliminates third-party dependencies. **Bonus**: We provide instructions on receiving API keys (up to 5M tokens) for top-tier AI models!
*   ⚡ **Ultra-fast Generation**: Instant answer delivery leveraging high-performance models.
*   🎙️ **Live Real-time Transcription**: The app "listens" to the speaker and instantly displays the transcript and answers on your screen.
*   🧠 **Smart Mode**: The AI automatically detects questions within the speech stream and triggers solution generation without manual input.
*   📸 **Vision AI**: Screen content analysis. Send a screenshot, and the AI will provide the optimal solution.
*    **Structured Answers**: Support for coding, general knowledge, math, physics, and more. Get:
    *   Professional diagrams and clear tables.
    *   Time and Space complexity analysis (Big O).
    *   Step-by-step solution strategies.
    *   Clean code-style and mathematical formulas.
*   📂 **Interview Context**: Provide your CV or job description. The AI will use this information to tailor its responses to specific requirements.

### Tech Stack

- **Frontend**: React, Tailwind CSS, Lucide Icons
- **Backend**: Electron, Node.js
- **AI Integration**: OpenAI SDK, Anthropic SDK, Deepgram SDK
- **Utilities**: screenshot-desktop, electron-store, react-query
