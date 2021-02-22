# Streaming Platform
## Специфікація

## Зміст
1. [Контекст](#1-контекст)  
2. [Задачі](#2-задачі)  
3. [Функціональні вимоги](#3-функціональні-вимоги)
4. [Сценарії](#4-сценарії)

## 1. Контекст
Streaming Platform - це сервіс, що дозволяє зручно розміщувати відео матеріали та проводити трансляції. Цей проект розробляється для забезпечення простого та гнучкого функціоналу поширення відеоматеріалів, в тому числі проведення як класичних прямих трансляцій, так і спільного перегляду, завантажених на платформу, відео. Сервіс зосереджується на забезпеченні комфортного зв’язку між користувачами в реальному часі. Цей зв’язок забезпечує чат трансляції, що дає змогу коментувати події. Також існує можливість коментування відео, що дозволяє ділитися думками та враженнями. Сервіс забезпечує зручний пошук відео. Унікальність проекту заключається у поєднанні функцій відеохостингу та соціальної мережі.

Планується розгортання проекту з використанням екосистеми Spring та SpringBoot, зокрема Spring MVC, Spring Data JPA та Spring Testing Framework, менеджеру пакетів Maven. 

#### Команда:
- [Королюк Ярослав](https://github.com/Koroliuk)  
- [Пєнской Володимир](https://github.com/Pienskoi)  
- [Третяк Владислав](https://github.com/Proxima-C)  
- [Голік Владислав](https://github.com/vladlinu)  

## Технологічний стек
#### Back-end
 - Java 11  
 - Spring Ecosystem  
 - Maven - Dependency Management  
 - PostgreSQL - Database System  
#### Front-end: 
 - HTML5  
 - JavaScript  
 - CSS  

## 2. Задачі
#### Задачі, які вирішує проект:
 - зручне створення відео трансляцій  
 - комфортне завантаження відео  
 - зручний пошук відео  
 - зручний перегляд відео та трансляцій  
 - наявність публічних та приватних кімнат для перегляду  
 - забезпечення спілкування користувачів  
 - зручний моніторинг та аналіз перегляду та активності відео та трансляцій  
 - поширення відео  
 - пошук людей для спілкування зі спільними вподобаннями  
#### Задачі поза скоупом даного проекту:
 - демонстрація екрану при трансляції  
 - систему анонсів та запланованих подій  
 - відео та голосовий чат  
 - цензура висловлень  
 
## 3. Функціональні вимоги
 - Реєстрація
 - Авторизація
 - Перегляд відео
 - Завантаження відео
 - Коментування відео
 - Транслювання завантаженого відео для спільного перегляду
 - Спілкування між користувачами в чаті під час трансляції
 - Моніторинг активності відео чи трансляції
 - Пошук відео

## 4. Сценарії
#### 4.1 Реєстрація

1. Користувач заходить на сторінку реєстрації
2. Користувач задає необхідні дані
3. Перевірка коректності даних
4. Система реєструє користувача

#### 4.2 Авторизація користувача

1. Користувач заходить на сторінку авторизації
2. Користувач вводить необхідні дані
3. Перевірка коректності даних
4. Система авторизує користувача

#### 4.3 Перегляд відео

1. Користувач знаходить відео
2. Користувач натискає на прев’ю відео
3. Користувача перенаправляє на сторінку з програвачем та відповідним відео
4. Користувач переглядає відео

#### 4.4 Поширення відео

1. Користувач заходить на сторінку завантаження відео
2. Користувач обирає відео
3. Користувач вводить дані для опису відео та завантажує прев’ю
4. Відео завантажене

#### 4.5 Коментування відео

1. Користувач натискає опцію коментування
2. Користувач вводить та надсилає коментар
3. Система зберігає коментар

#### 4.6 Транслювання

1. Користувач створює трансляцію
2. Користувач вводить дані опису трансляції
3. Користувач використовує програму для запису та передачі відеопотоку

#### 4.7 Транслювання завантаженого відео для спільного перегляду

1. Користувач натискає на прев’ю відео
2. Користувача перенаправляє на сторінку з програвачем та відповідним відео
3. Користувач натискає опцію спільного перегляду
4. Користувач обирає тип кімнати
5. Система створює кімнату, відео якої синхронізується серед учасників 

#### 4.8 Спілкування в чаті під час трансляції

1. Користувач натискає на поле для вводу повідомлення в чаті трансляції
2. Користувач набирає потрібне йому повідомлення
3. Система обробляє повідомлення

#### 4.9 Моніторинг активності відео чи трансляції

1. Користувач обирає бажане відео чи трансляцію 
2. Користувач натискає опцію перегляду активності

#### 4.10 Пошук відео

1. Користувач вводить інформацію в поле пошуку
2. Система надає результат: знайдені відео


