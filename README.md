# Answers
ответы на вопросы на вакансию QA Intern Mindbox
## Вопрос 1

Чтобы протестировать форму, которая рассчитывает возможность оформления паспорта РФ в зависимости от возраста, можно использовать технику граничных значений и классов эквивалентности.

1. Техника граничных значений
Граничные значения — это точки, где происходит изменение результата. В данном случае границы можно определить следующим образом:

Минимальное возможное значение: 0 лет
Возраст, с которого можно оформить паспорт (14 лет, 20 лет и 45 лет)
Возраст 115 лет, так как это максимальное допустимое значение
Граничные значения:
Минимальная граница:

0 лет: "Нельзя оформить"
1 год: "Нельзя оформить"
Границы оформления паспорта:

13 лет: "Нельзя оформить"
14 лет: "Можно оформить"
15 лет: "Можно оформить"
19 лет: "Можно оформить"
20 лет: "Можно оформить"
21 год: "Можно оформить"
44 года: "Можно оформить"
45 лет: "Можно оформить"
46 лет: "Можно оформить"
Максимальная граница:

114 лет: "Можно оформить"
115 лет: "Можно оформить"
116 лет: "Ошибка" (не входит в допустимый диапазон)
2. Классы эквивалентности
Классы эквивалентности — это группы значений, которые программа должна обрабатывать одинаково. Разделим входные данные на следующие классы:

Негативные значения (недопустимые значения):

Пример: -1 год
Результат: "Ошибка"
Возраст до 14 лет:

Пример: 10 лет
Результат: "Нельзя оформить"
Возраст от 14 до 19 лет (первая возможность оформления паспорта):

Пример: 16 лет
Результат: "Можно оформить"
Возраст от 20 до 44 лет (вторая возможность оформления паспорта):

Пример: 30 лет
Результат: "Можно оформить"
Возраст от 45 лет и старше (третья возможность оформления паспорта):

Пример: 50 лет
Результат: "Можно оформить"
Возраст больше 115 лет (недопустимые значения):

Пример: 116 лет
Результат: "Ошибка"
Эти тесты охватывают различные сценарии и помогают убедиться, что система правильно обрабатывает разные диапазоны входных значений.


## Вопрос 2

Готова выйти на фултайм, в случаи успешного прохождения стажировки

## Вопрос 3

О вакансии узнала из портала hh.ru

