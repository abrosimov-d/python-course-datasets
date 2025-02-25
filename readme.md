# python-course-datasets

## Использование

googleplaystore.csv
```
data = pd.read_csv('https://raw.githubusercontent.com/abrosimov-d/python-course-datasets/refs/heads/main/googleplaystore.csv')
```

titanic_train.csv
```
data = pd.read_csv('https://raw.githubusercontent.com/abrosimov-d/python-course-datasets/refs/heads/main/titanic_train.csv')
```

bike-sharing
```
data = pd.read_csv('https://raw.githubusercontent.com/abrosimov-d/python-course-datasets/refs/heads/main/bike-sharing/day.csv')

data = pd.read_csv('https://raw.githubusercontent.com/abrosimov-d/python-course-datasets/refs/heads/main/bike-sharing/hour.csv')
```


## Titanic Train Dataset (`titanic_train.csv`)

Этот датасет включает информацию о пассажирах Титаника, предназначенную для предсказания их выживаемости.

### Описание столбцов:
- **PassengerId**: Уникальный ID для каждого пассажира
- **Survived**: Индикатор выживаемости (0 = Нет, 1 = Да)
- **Pclass**: Класс билета (1 = 1-й, 2 = 2-й, 3 = 3-й)
- **Name**: Имя пассажира
- **Sex**: Пол
- **Age**: Возраст
- **SibSp**: Количество братьев/сестер и супругов на борту
- **Parch**: Количество родителей/детей на борту
- **Ticket**: Номер билета
- **Fare**: Стоимость билета
- **Cabin**: Номер каюты
- **Embarked**: Порт посадки (C = Шербур, Q = Куинстаун, S = Саутгемптон)

## Google Play Store Dataset (`googleplaystore.csv`)

Этот датасет содержит информацию о различных приложениях, доступных в Google Play Store.

### Описание столбцов:
- **App**: Название приложения
- **Category**: Категория приложения
- **Rating**: Средний рейтинг пользователей
- **Reviews**: Количество отзывов
- **Size**: Размер приложения
- **Installs**: Количество установок
- **Type**: Бесплатное или платное
- **Price**: Цена (для платных приложений)
- **Content Rating**: Возрастная группа, для которой подходит приложение
- **Genres**: Жанры приложения
- **Last Updated**: Дата последнего обновления
- **Current Ver**: Текущая версия
- **Android Ver**: Минимальная требуемая версия Android

## Bike Sharing Dataset (`bike-sharing`)

Этот датасет содержит информацию об аренде велосипедов в системе проката велосипедов.

### Описание столбцов:
- **instant**: Индекс записи
- **dteday**: Дата
- **season**: Сезон (1 = весна, 2 = лето, 3 = осень, 4 = зима)
- **yr**: Год (0 = 2011, 1 = 2012)
- **mnth**: Месяц (1 до 12)
- **hr**: Час (0 до 23)
- **holiday**: Праздничный день (1 = да, 0 = нет)
- **weekday**: День недели (0 = вс, 1 = пн, …, 6 = сб)
- **workingday**: Рабочий день (1 = да, 0 = нет)
- **weathersit**: Погодная ситуация (1: ясная, 2: облачная, 3: легкий дождь/снег, 4: сильный дождь/снег)
- **temp**: Температура в градусах Цельсия
- **atemp**: Ощущаемая температура в градусах Цельсия
- **hum**: Влажность
- **windspeed**: Скорость ветра
- **casual**: Количество нерегулярных пользователей
- **registered**: Количество зарегистрированных пользователей
- **cnt**: Общее количество аренд

---

Добавьте дополнительные сведения, специфичные для вашего проекта, если это необходимо. Удачного документирования! 🚀
