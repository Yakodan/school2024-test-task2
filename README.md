# Тестовое задание для отбора в Летнюю Школу по разработке ПО

## Условие задания
Один развивающийся и перспективный маркетплейс активно растет в настоящее время. Текущая команда разработки вовсю занята тем, что развивает ядро системы. Помимо этого, перед CTO маркетплейса стоит задача — разработать подсистему аналитики, которая на основе накопленных данных формировала бы разнообразные отчеты и статистику.

Вы — компания подрядчик, с которой маркетплейс заключил рамочный договор на выполнение работ по разработке этой подсистемы. В рамках первого этапа вы условились провести работы по прототипированию и определению целевого технологического стека и общих подходов к разработке.

На одном из совещаний с Заказчиком вы определили задачу, на которой будете выполнять работы по прототипированию. В качестве такой задачи была выбрана разработка отчета о наиболее популярных категориях товаров, продаваемых во время подготовки новогодних подарков покупателями.

Аналитики со стороны маркетплейса предоставили небольшой срез массива данных (файл format.json) о совершенных покупках пользователей за 4-й квартал 2023 года, на примере которого вы смогли бы ознакомиться с форматом входных данных. Каждая запись данного среза содержит следующую информацию:
- Дата и время оформления заказа;
- Корзина.

В пояснительной записке к массиву данных была уточняющая информация относительно формате данных, представленных в корзине. Так, например, корзина - это массив однотипных сведений о купленных товаров, определяемых следующим набором данных:
- Идентификатор товара;
- Наименование товара;
- Категория.

В свою очередь сведения о категории представлены в следующем виде:
- Идентификатор категории;
- Наименование категории.

Необходимо разработать отчет, определяющий категории товаров, наиболее популярные перед Новым годом. Если популярных категорий товаров больше, чем одна, отчет должен показывать их все. Предновогодним периодом будем считать срок с 1 по 31 декабря.

Требования к реализации:
1. Реализация должна содержать, как минимум, одну процедуру (функцию/метод), отвечающую за формирование отчета, и должна быть описана в readme.md в соответствии с чек-листом;
2. В качестве входных данных программа использует json-файл (input.json), соответствующий структуре, описанной в условиях задания;
3. Процедура (функция/метод) формирования отчета должна возвращать строку в формате json следующего формата:
   - {«categories»: [«Бытовая техника»]}
   - {«categories»: [«Бытовая техника», «Косметика»]}
4. Найденная в соответствии с условием задачи категория должна выводиться в изначальном наименовании, приведенном в файле с входными данными. Если таких категорий несколько, то на вывод они все подаются в алфавитном порядке.

## Автор решения

## Описание реализации

## Инструкция по сборке и запуску решения
