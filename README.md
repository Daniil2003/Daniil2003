<h1 align="center">Даниил Пикулев</h1>

<p align="center">
  <strong>Продуктовый аналитик · Юнит-экономика · A/B-тесты · Деревья метрик</strong>
</p>

<p align="center">
  Продуктовый аналитик полного цикла с математической базой. Связываю поведение пользователей
  и операционные цепочки с P&amp;L бизнеса: сократил затраты на привлечение на 5,8 млн ₽,
  поднял точность бизнес-планирования до 92%, автоматизировал 70% рутины отчётности.
</p>

### Опыт

**Брайт Софт — аналитик продуктового стрима** · сентябрь 2024 – настоящее время

Спроектировал дерево метрик с North Star Metric и перевёл приоритизацию бэклога на ICE-скоринг; довёл до раскатки 15+ A/B/n-экспериментов: +0,12 п.п. сквозной конверсии в покупку, −5,8 млн ₽ расходов на привлечение. Оптимизировал витрины данных на SQL и Python (−68% времени расчёта), внедрил self-service: 15+ дашбордов Apache Superset с разделением доступа (−70% рутины отчётности). Операционная аналитика FoodTech/логистики через process mining: +17% пропускной способности узла.

**Backstage Group — аналитик по развитию проектов** · сентябрь 2023 – август 2024

Собрал централизованный DWH по 560+ концертам из API билетных операторов — регулярная аналитика ускорилась на 65%. Построил прогноз темпов бронирования: MAPE < 8% за 7 дней до события, точность 92% (вдвое выше экспертной оценки), кассовые разрывы −30%. Провёл серию сплит-тестов промо-механик: конверсия промо-канала +20%, CPA −12–15%. Разработал алгоритм слоттинга артистов по стриминговым и медиа-данным: заполняемость залов на 10–15% выше интуитивного планирования.

### Фокус

- **Юнит-экономика.** LTV, CAC, ARPU, Payback, отток B2B-контрактов; оценка стоимости ошибки модели (замена 75% LLM-вызовов детерминированным поиском сохранила >65% маржинальности подписки).
- **Деревья метрик и приоритизация.** North Star Metric с Input/Output-метриками, удержание и воронки, факторный анализ, ICE/RICE, аудит пользовательских путей (CJM).
- **Эксперименты.** Дизайн A/B/n-тестов, размер выборки и MDE (power analysis), CUPED, стратификация, Z/t/Манн–Уитни/χ², бутстреп, защита от peeking и p-hacking.
- **Операционная аналитика.** Process mining, распределения Time-in-Status (P50/P95), пропускная способность и SLA.

### Ключевые проекты

**Gastro Guru (Брайт Софт) — юнит-экономика и A/B-тесты AI-платформы онбординга** — B2B-сервис онбординга сотрудников ресторанов терял маржинальность подписки из-за тяжёлых некэшируемых LLM-запросов. Оцифровал стоимость ошибки модели, выделил кластер из 75% типовых запросов и заменил их детерминированным поиском по базе меню; перевёл метрики онбординга на Completion Rate и Time-to-Productivity; спроектировал сплит-тест вводного сценария. Конверсия в успешное прохождение онбординга 1-го дня +18% (Z-тест, p < 0.01), маржинальность подписки >65% при росте нагрузки.

`Python` · `SQL` · `RAG` · `Superset` · `A/B Tests`

**Моделирование спроса на музыкальном рынке (R&D, Backstage Group)** — аналитический конвейер поверх стриминговых чартов, сообществ и регионального поискового индекса; датасет по 120+ артистам, кластеризация K-Means для выявления географических ядер аудитории, скоринг виральности треков. Методология легла в основу слоттинга Backstage: на 25% больше запланированных слотов дошло до анонса, заполняемость залов на 10–15% выше «слепых» запусков.

`Python` · `Scikit-learn` · `K-Means` · `Streaming Data` · `SQL`

**Оптимизация операционного цикла логистики (Брайт Софт)** — каскадный рост времени сборки заказов в пиковые часы приводил к срывам SLA и зависшим очередям. Восстановил цифровой след статусов заказа по логам ClickHouse, рассчитал распределения Time-in-Status (P50/P95), локализовал узкое место в фазе ожидания автоназначения и инициировал переход от пакетной сборки к динамической поточной очереди. Пропускная способность +17%, P95 Lead Time −22%, систематические срывы SLA исключены.

`Python` · `ClickHouse` · `SQL` · `Process Mining`

### Технологии

#### Продуктовая аналитика

<p>
  <img src="https://img.shields.io/badge/Unit%20Economics-1F2328?style=for-the-badge" alt="Unit Economics" />
  <img src="https://img.shields.io/badge/North%20Star%20Metric-1F2328?style=for-the-badge" alt="North Star Metric" />
  <img src="https://img.shields.io/badge/Metric%20Trees-1F2328?style=for-the-badge" alt="Metric Trees" />
  <img src="https://img.shields.io/badge/A%2FB%20Testing-1F2328?style=for-the-badge" alt="A/B Testing" />
  <img src="https://img.shields.io/badge/ICE%20%2F%20RICE-1F2328?style=for-the-badge" alt="ICE / RICE" />
  <img src="https://img.shields.io/badge/CJM-1F2328?style=for-the-badge" alt="CJM" />
  <img src="https://img.shields.io/badge/Process%20Mining-1F2328?style=for-the-badge" alt="Process Mining" />
</p>

#### Эксперименты и статистика

<p>
  <img src="https://img.shields.io/badge/Power%20Analysis%20%2F%20MDE-1F2328?style=for-the-badge" alt="Power Analysis / MDE" />
  <img src="https://img.shields.io/badge/CUPED-1F2328?style=for-the-badge" alt="CUPED" />
  <img src="https://img.shields.io/badge/Stratification-1F2328?style=for-the-badge" alt="Stratification" />
  <img src="https://img.shields.io/badge/Bootstrap-1F2328?style=for-the-badge" alt="Bootstrap" />
  <img src="https://img.shields.io/badge/Z%20%2F%20t%20%2F%20Mann--Whitney%20%2F%20χ%C2%B2-1F2328?style=for-the-badge" alt="Z / t / Mann–Whitney / χ²" />
</p>

#### Данные и программирование

<p>
  <img src="https://img.shields.io/badge/Python-1F2328?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/pandas-1F2328?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas" />
  <img src="https://img.shields.io/badge/NumPy-1F2328?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/SciPy-1F2328?style=for-the-badge" alt="SciPy" />
  <img src="https://img.shields.io/badge/scikit--learn-1F2328?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
  <img src="https://img.shields.io/badge/SQL-1F2328?style=for-the-badge" alt="SQL" />
  <img src="https://img.shields.io/badge/PostgreSQL-1F2328?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/ClickHouse-1F2328?style=for-the-badge&logo=clickhouse&logoColor=white" alt="ClickHouse" />
  <img src="https://img.shields.io/badge/MySQL-1F2328?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
</p>

#### BI и инженерия

<p>
  <img src="https://img.shields.io/badge/Apache%20Superset-1F2328?style=for-the-badge" alt="Apache Superset" />
  <img src="https://img.shields.io/badge/Tableau-1F2328?style=for-the-badge&logo=tableau&logoColor=white" alt="Tableau" />
  <img src="https://img.shields.io/badge/Power%20BI-1F2328?style=for-the-badge" alt="Power BI" />
  <img src="https://img.shields.io/badge/Git-1F2328?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Linux-1F2328?style=for-the-badge&logo=linux&logoColor=white" alt="Linux" />
  <img src="https://img.shields.io/badge/Bash-1F2328?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash" />
  <img src="https://img.shields.io/badge/Advanced%20Excel-1F2328?style=for-the-badge" alt="Advanced Excel" />
</p>

**Языки:** Русский — родной · Английский — B1

### Контакты

<p>
  <a target="_blank" rel="noopener noreferrer" href="https://t.me/d_pik">Telegram</a> ·
  <a target="_blank" rel="noopener noreferrer" href="mailto:pikulev_d_v@mail.ru">Email</a> ·
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/Daniil2003">GitHub</a>
</p>
