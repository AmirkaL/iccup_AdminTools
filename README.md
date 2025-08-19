# iCCup Admin Helper

![Python Version](https://img.shields.io/badge/python-3.9%2B-blue)

Инструмент для автоматизации обработки тикетов на игровой платформе iCCup. Приложение написано на Python с использованием PyQt6 и предназначено для администраторов, чтобы повысить скорость и консистентность рассмотрения жалоб на дисконнекты.

![asd]([data:image/png;base64,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])

## 🎯 Проблема и Решение

На игровой платформе iCCup администраторы ежедневно вручную обрабатывают десятки однотипных жалоб на разрывы соединения. Этот процесс (toil) требовал:
*   Переключения между 5-6 различными веб-страницами для сбора данных.
*   Ручного анализа информации по сложному набору правил.
*   Высоких временных затрат (10-15 минут на тикет).
*   Риска человеческой ошибки и inconsistентных решений.

**iCCup Admin Helper** решает эту проблему, полностью автоматизируя процесс. Он действует как персональный SRE-ассистент, превращая рутинную операционную задачу в один клик.

## ✨ Ключевые возможности

*   **Авторизация и управление сессией:** Безопасный вход на платформу и сохранение сессии для последующих запусков.
*   **Автоматический сбор тикетов:** Получение и отображение списка актуальных жалоб из раздела дисконнектов.
*   **Комплексный анализ в один клик:** Приложение последовательно выполняет все необходимые проверки:
    *   ✅ **Валидация реплея:** Сверяет игроков в реплее и в деталях матча.
    *   ✅ **Проверка срока давности:** Убеждается, что с момента игры прошло не более 7 дней.
    *   ✅ **Анализ активации ладдера:** Проверяет, был ли засчитан матч, с учетом исключения для случаев с **десинхронизацией**.
    *   ✅ **Глубокий анализ чат-лога:** Ищет ключевые слова о вылетах (`dropped`, `timed out`) и извлекает никнеймы ливеров.
    *   ✅ **Проверка на дубликаты:** Ищет в административных заметках игрока, не был ли уже произведен возврат по этой игре через другой тикет.
    *   ✅ **Анализ Clearstats:** Проверяет логи игрока на предмет обнуления статистики после рассматриваемой игры.
    *   ✅ **Анализ серии побед (Win Streak):** Просматривает историю матчей для корректного расчета восстановления прерванной серии побед.
*   **Расчет рекомендаций:** На основе всех данных приложение автоматически рассчитывает и предлагает готовые значения для команд `pts edit`, `wins edit`, `losses edit`, `leaves edit` и `streak edit`.
*   **Интегрированный веб-браузер:** Позволяет просматривать страницу тикета прямо в приложении для дополнительного контекста.
*   **Система авто-обновления:** Проверяет наличие новой версии на GitHub и предлагает пользователю обновиться.

## 🛠️ Технологический стек

*   **Бэкенд:** Python 3.9+
*   **Веб-скрейпинг:** `requests`, `BeautifulSoup4`
*   **GUI:** `PyQt6` (включая `QtWebEngine` для браузера)
*   **Сборка в .exe:** `PyInstaller`
*   **Создание установщика:** `Inno Setup`

## 🚀 Установка и Запуск

### Для пользователей

Готовый установщик для Windows можно скачать на странице **[Releases](https://github.com/AmirkaL/iccup_AdminTools/releases)**.
