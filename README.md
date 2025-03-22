# AI Ассистент для компании по продаже услуг (экскурсий и мастер-классов)

Ссылки на скриншоты диалогов:

скриншот 1: https://github.com/izmailikaprompt/ai_assistent/blob/main/%20.png?raw=true

скриншот 2:(https://github.com/izmailikaprompt/ai_assistent/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-03-22%20%D0%B2%2015.15.45.png?raw=true)

скриншот 3:[(https://github.com/izmailikaprompt/ai_assistent/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-03-22%20%D0%B2%2015.16.06.png?raw=true)

скриншот 4:(https://github.com/izmailikaprompt/ai_assistent/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-03-22%20%D0%B2%2015.16.54.png?raw=true)

## Описание проекта

Проект представляет собой интеллектуального ассистента, созданного для автоматизации взаимодействия с клиентами компании, специализирующейся на продаже экскурсий и мастер-классов. Ассистент способен вести осмысленный диалог, отвечать на вопросы клиентов, предоставлять информацию из базы данных и записывать клиентов на встречи, добавляя их в Google Календарь.

Основная цель проекта — упростить процесс общения с клиентами, повысить эффективность работы сотрудников и улучшить качество обслуживания за счет автоматизации рутинных задач.

## Функционал

### 1. Осмысленное ведение диалога
Ассистент использует современные технологии обработки естественного языка (NLP) для понимания запросов клиентов и предоставления точных ответов. Благодаря этому диалог становится максимально естественным и удобным для пользователя.

### 2. Ответы на вопросы по базе данных
Ассистент имеет доступ к базе данных компании, содержащей информацию о доступных экскурсиях, мастер-классах, расписании, ценах и других важных деталях. Он может быстро находить нужную информацию и предоставлять её клиентам.

### 3. Запись клиента на встречу
При необходимости ассистент может записать клиента на выбранную экскурсию или мастер-класс. Для этого он собирает необходимые данные (ФИО, контактные данные, предпочтительное время) и подтверждает бронирование.

### 4. Интеграция с Google Календарь
Все записи автоматически добавляются в Google Календарь компании, что позволяет сотрудникам видеть актуальное расписание и избегать конфликтов при планировании.

---

## Используемые сервисы

### 1. Qwen
- **Ссылка:** [Qwen](https://chat.qwen.aliyun.com/)
- **Описание:** Платформа для создания системных промптов и базы знаний. Qwen был использован для настройки логики диалога и обучения ассистента на основе предоставленных данных.

### 2. Савви (Suvvy)
- **Ссылка:** [Савви](https://suvvy.ai/)
- **Описание:** Сервис для создания полноценного ИИ-ассистента. Савви обеспечивает интеграцию всех функций ассистента, включая обработку запросов, управление базой данных и взаимодействие с внешними сервисами.

---

## Архитектура проекта

1. **Frontend:**
   - Веб-интерфейс для взаимодействия с клиентами.
   - Может быть реализован как чат-виджет на сайте компании или как отдельное приложение.

2. **Backend:**
   - Обработка запросов от клиентов.
   - Логика взаимодействия с базой данных и внешними API.
   - Интеграция с Google Календарем.

3. **Database:**
   - Хранение информации об экскурсиях, мастер-классах, расписании и записях клиентов.

4. **AI Services:**
   - Использование моделей NLP для обработки естественного языка.
   - Настройка промптов и базы знаний через Qwen.
   - Создание ассистента через Савви.

5. **Настройка Google Календаря:**
   - Создайте проект в Google Cloud Console.
   - Включите API Google Календаря.

## Возможности для улучшения

1. **Мультиязычная поддержка:**
   Добавить возможность общения с клиентами на нескольких языках.

2. **Уведомления:**
   Реализовать отправку напоминаний клиентам о предстоящих встречах через SMS или email.

## Авторы
Если у вас есть вопросы или предложения, свяжитесь с нами через GitHub Issues или напишите на email: izmailikaprof@gmail.com
