[English version](#kinopoisk-ratings-parser-) | [Русская версия](#парсер-оценок-кинопоиска-)


# Kinopoisk Ratings Parser 📚

This program allows you to parse and analyze movie ratings from the Kinopoisk website. It uses the `requests` and `BeautifulSoup` libraries to extract rating data from the Kinopoisk website, and then writes this data into a CSV file.

## How to Run 🚀

1. Clone the repository using the command `git clone [repository URL]`.
2. Create a virtual environment in the repository folder (optional, but recommended for isolation) `python3 -m venv venv` and `source venv/bin/activate`.
3. Install the necessary libraries by running the command `pip install -r requirements.txt`.
4. Add cookies from the KinoPoisk website (important!)without logging into your account in the variable `string_cookies` in the file `cookies_file`.
[Imgur](https://i.imgur.com/ZCSvcFW.png)
5. Add to the variable `numer_user` from the address bar on the KinoPoisk profile website in the file `cookies_file`.
[Imgur](https://i.imgur.com/sVP2aRq.png)
6. Run the program using the command `python main.py`.
7. The program will create a `.csv` file with the parsed Kinopoisk ratings, which you can then analyze or use it for import on the Letterboxd website.

# Парсер Оценок КиноПоиска 📚

Эта программа позволяет парсить и анализировать рейтинги фильмов с сайта КиноПоиск. Она использует библиотеки `requests` и `BeautifulSoup` для извлечения данных о рейтингах с сайта КиноПоиск, а затем записывает эти данные в файл CSV.

## Как запустить 🚀

1. Склонируйте репозиторий с помощью команды `git clone [URL репозитория]`.
2. Создайте виртуальное окружение в папке репозитория (по желанию, но рекомендуется для изоляции) `python3 -m venv venv` и `source venv/bin/activate`.
3. Установите необходимые библиотеки, выполнив команду `pip install -r requirements.txt`.
4. Добавьте cookies с сайта КиноПоиск (важно!)без входа в свой аккаунт в переменную `sting_cookies` в файле `cookies_file`.
[Imgur](https://i.imgur.com/ZCSvcFW.png)
5. Добавьте в переменную `numer_user` из адресной строки на сайте профиля КиноПоиск  в файле `cookies_file`.
[Imgur](https://i.imgur.com/sVP2aRq.png)
6. Запустите программу с помощью команды `python main.py`.
7. Программа создаст файл `.csv` с распарсенными рейтингами КиноПоиск, которые вы затем можете проанализировать или использовать его для импорта на сайте Letterboxd.
