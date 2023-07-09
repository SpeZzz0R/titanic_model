# Модель прогнозирования "Титаник"


## О проекте
Модель, предсказывающая вероятность спасения после кораблекрушения для разных групп пассажиров "Титаника". Модель разработана на основе библиотеки CatBoost.


## Используемые технологии
- Google Colab / Jupyter Notebook


## Результаты анализа данных	
В ходе проведенного анализа на основе человеческого обучения получены следующие результаты:
- шанс выжить для всех пассажиров составляет примерно 38 %;
- шанс выжить у женщин и мужчин составляет примерно 74 % и 19 % соответственно;
- наибольший шанс пережить катастрофу имеют дети до 10 лет среднего достатка и богаче, и состоятельные женщины (всех возрастов). Для данных категорий пассажиров шанс выжить составляет 100 % и более 95 % соответственно. Для женщин среднего достатка шанс выжить составляет от 83 %;
- наименьший шанс пережить катастрофу имеют мужчины малого достатка среднего возраста и старше. Для данной категории пассажиров шанс выжить близок к 0.
Такие результаты связаны с нехваткой спасательных шлюпок на корабле и вследствие этого капитаном было принято решение спасать в первую очередь женщин и всех детей до 10 лет среднего достатка и богаче.
	
Все результаты подтверждаются машинным обучением. 
Рассчитанные значения метрик:
- AUC = 0.85; 
- Accuracy = 0.82; 
- F1 = 0.71.

В исходных данных много отсутствующих значений, что влияет на точность прогнозирования.



==============================

> Автором проекта является начинающий data scientist
> Запесочный Владислав. 
> Страница на github: https://github.com/SpeZzz0R  
> 
