# Закономерности успешной игры.

Я аналитик в интернет-магазине «Стримчик», который продаёт по всему миру компьютерные игры. Нужно выявить определяющие успешность игры закономерности, для планирования рекламных компаний на потенциально популярный продукт. Даны исторические данные из открытых источников о продажах игр, оценках пользователей и экспертов, жанра и платформы (XBOX, PS, и подобные).

## Задача
Выявить закономерности, которые определяют успешность игры.

## Данные
- Name — название игры
- Platform — платформа
- Year_of_Release — год выпуска
- Genre — жанр игры
- NA_sales — продажи в Северной Америке (миллионы проданных копий)
- EU_sales — продажи в Европе (миллионы проданных копий)
- JP_sales — продажи в Японии (миллионы проданных копий)
- Other_sales — продажи в других странах (миллионы проданных копий)
- Critic_Score — оценка критиков (максимум 100)
- User_Score — оценка пользователей (максимум 10)
- Rating — рейтинг от организации ESRB (англ. Entertainment Software Rating Board). Эта ассоциация определяет рейтинг компьютерных игр и присваивает им подходящую возрастную категорию.

## Используемые библиотеки
- pandas - для работы с датафреймами
- numpy - для расчета дисперсии и стандартного отклонения
- matplotlib.pyplot - для работы с графиками
- seaborn - для построения множественных графиков.
- scipy - для статистики
