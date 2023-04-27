##№ Описание проекта
В проекте представлена моя работа по анализу результатов A/A/B-эксперимента, проведённого в дейтинговом приложении.
В ходе эксперимента для новых пользователей из нескольких стран была изменена стоимость премиум-подписки при покупке через две новые платежные системы.

В ходе исследования был проведён EDA, выбраны и расчитаны метрики: конверсия в покупку премиум подписки, retention 7-го дня, ARPU, ARPPU, а также средние чеки при покупки отдельных функций. Для каждой метрики был сначала проведён A/A-тест, чтобы убедиться в правильности системы сплитования, затем A/B-тест для статистической оценки изменений. Также, были проведены A/B-тесты для отдельных групп пользователей по полу, возрасту, стране и источнику трафика. 
Для статистической оценки конверсии и retention использовался критерий хи-квадрат. Для денежных метрик оценка проводилась при помощи bootstrap и т-теста.

Проект выполнен в Jupiter Notebook на языке Python
