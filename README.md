# Машинно самообучение

## Линейна регресия

## Линейна регресия на много променливи

### Домашно 1
Данните за домашното може да намерите в папка week1. Файлът се нарича houseprices2.txt
Съдържа три колони - размер на жилище, брой стаи и цена. 
Променливата, която искаме да предвидим е цената на жилището на база брой стаи и размер.
Модифицирайте кода в LinearRegression, така че да работи за повече от един атрибут.

Какво трябва да напарвите?

1. Заредете с pandas или по друг начин houseprices2.txt
2. Извършете нормализация на данните - пример има в края на LinearRegression
3. Модифицирате gradient_descent, така че да работи за много атрибути
4. Обучете линейният модел и начертайте графика на грешката, като функция на броя итерации
5. Визуализирайте линията на обученият модел и обучаващите данни
