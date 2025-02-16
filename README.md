## "Тестирование веб-приложений"
### qa.demoshopping.ru
Создаю тест-план для тестирования приложения <a href="https://qa.demoshopping.ru/">qa.demoshopping.ru</a>:
#### [Тест план (XLSX)](https://docs.google.com/spreadsheets/d/1nh5fPynGT30XWn77mzOJLZXpXhWm4Graaym8up7-iyI/)
Создаю веб страницу с тестовыми артефактами для приложения <a href="https://qa.demoshopping.ru/">qa.demoshopping.ru</a>:
#### [Тестовые артефакты (stantokarev.tiiny.site)](https://stantokarev.tiiny.site/)
Создание Чек-листа, который включает тестирование разделов: Регистрация, Логин, Каталог, Корзина и Оплата приложения <a href="https://qa.demoshopping.ru/">qa.demoshopping.ru</a>:
#### [Чек-лист для тестирования корзины и оплаты (XLSX)](https://docs.google.com/spreadsheets/d/1zwhsdN667Qrc3eg_2llk7Wu7GYBM7IAjVa9FMN-EVSE/)
Создание 10 тест-кейсов для раздела Корзина и 10 тест-кейсов для раздела Оплата приложения <a href="https://qa.demoshopping.ru/">qa.demoshopping.ru</a> в QASE:
#### [Тест-кейсы для тестирования корзины и оплаты из QASE (PDF)](https://github.com/StanTokarev/web/blob/main/Stan%20Tokarev%20-%20Test%20Cases%20for%20cart%20and%20payment.pdf)
Отчет о дефекте и тестовый прогон тест-кейсов приложения <a href="https://qa.demoshopping.ru/">qa.demoshopping.ru</a> в QASE, YouTrack:
#### [Тестовый прогон для корзины и оплаты из QASE (PDF)](https://github.com/StanTokarev/web/blob/main/Stan%20Tokarev%20-%20Test%20Runs%20for%20test%20cases%20cart%20and%20payment%20from%20QASE.pdf)
### [Отчеты о дефекте для корзины и оплаты из YouTrack (XLSX)](https://github.com/StanTokarev/web/blob/main/Stan%20Tokarev%20-%20Bug%20Reports%20for%20test%20cases%20cart%20and%20payment%20from%20YouTrack.xlsx)
Изменяю количество товаров в корзине: пользователь отправляет 2 товара в корзину, перехватываю запрос и изменяю на 500:
#### [Charles Proxy, Запрос отправляет 2 товара, изменяю на 500 (MP4)](https://github.com/StanTokarev/web/blob/main/1.%20%D0%9A%D0%BE%D0%BC%D0%BF%D1%8C%D1%8E%D1%82%D0%B5%D1%80.%20%D0%97%D0%B0%D0%BF%D1%80%D0%BE%D1%81%20%D0%BE%D1%82%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D1%8F%D0%B5%D1%82%D1%81%D1%8F%202%20%D1%82%D0%BE%D0%B2%D0%B0%D1%80%D0%B0%2C%20%D0%BC%D0%B5%D0%BD%D1%8F%D1%8E%20%D0%BD%D0%B0%20%D0%B4%D0%BE%D0%B1%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20500.mp4)
При обращении к приложению <a href="https://demoshopping.ru/">demoshopping.ru</a>: сервер вернет статус-код 403 (Forbidden):
#### [Charles Proxy, При обращении к demoshopping сервер вернет статус-код 403 (MP4)](https://github.com/StanTokarev/web/blob/main/2.%20%D0%9A%D0%BE%D0%BC%D0%BF%D1%8C%D1%8E%D1%82%D0%B5%D1%80.%20%D0%9F%D1%80%D0%B8%20%D0%BE%D0%B1%D1%80%D0%B0%D1%89%D0%B5%D0%BD%D0%B8%D0%B8%20%D0%BA%20demoshopping%20%D1%81%D0%B5%D1%80%D0%B2%D0%B5%D1%80%20%D0%B2%D0%B5%D1%80%D0%BD%D0%B5%D1%82%20%D1%81%D1%82%D0%B0%D1%82%D1%83%D1%81-%D0%BA%D0%BE%D0%B4%20403.mp4)
Перенаправляю запрос с с Prod version <a href="https://demoshopping.ru/">demoshopping.ru</a> на QA version <a href="https://qa.demoshopping.ru/">qa.demoshopping.ru</a>:
#### [Charles Proxy, Перенаправить запрос с Prod demoshopping на QA qa demoshopping (MP4)](https://github.com/StanTokarev/web/blob/main/3.%20%D0%9A%D0%BE%D0%BC%D0%BF%D1%8C%D1%8E%D1%82%D0%B5%D1%80.%20%D0%9F%D0%B5%D1%80%D0%B5%D0%BD%D0%B0%D0%BF%D1%80%D0%B0%D0%B2%D0%B8%D1%82%D1%8C%20%D0%B7%D0%B0%D0%BF%D1%80%D0%BE%D1%81%20%D1%81%20Prod%20%D0%BD%D0%B0%20QA%20.mp4)
