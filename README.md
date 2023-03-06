# Project-3-Tariff-Recommendation  
Data Science project work during the Yandex Practicum  
Project #3  

Описание проекта:
Оператор мобильной связи «Мегалайн» выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра».
В вашем распоряжении данные о поведении клиентов, которые уже перешли на эти тарифы (из проекта курса «Статистический анализ данных»). Нужно построить модель для задачи классификации, которая выберет подходящий тариф. Предобработка данных не понадобится — вы её уже сделали.
Постройте модель с максимально большим значением accuracy. Чтобы сдать проект успешно, нужно довести долю правильных ответов по крайней мере до 0.75. Проверьте accuracy на тестовой выборке самостоятельно.

Инструкция по выполнению проекта:
- Откройте файл с данными и изучите его. Путь к файлу: /datasets/users_behavior.csv. Скачать датасет
- Разделите исходные данные на обучающую, валидационную и тестовую выборки.
- Исследуйте качество разных моделей, меняя гиперпараметры. Кратко напишите выводы исследования.
- Проверьте качество модели на тестовой выборке.
- Дополнительное задание: проверьте модели на вменяемость. Ничего страшного, если не получится: эти данные сложнее тех, с которыми вы работали раньше. В следующем курсе подробнее об этом расскажем.

Описание данных:
- Каждый объект в наборе данных — это информация о поведении одного пользователя за месяц. Известно:
  - сalls — количество звонков,
  - minutes — суммарная длительность звонков в минутах,
  - messages — количество sms-сообщений,
  - mb_used — израсходованный интернет-трафик в Мб,
  - is_ultra — каким тарифом пользовался в течение месяца («Ультра» — 1, «Смарт» — 0).
