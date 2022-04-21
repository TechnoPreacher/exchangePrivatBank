Созданный класс обеспечивает получение информации с сайта ПриватБанка

Реализована функция обмена валюты convert(), в которую передаётся желаемое число, вид обмена, обмениваемая валюта, и рассчитывается цена продажи или покупки в UAH.
Функция вернёт количество потраченных или полученных гривен в обмен на заданную валюту.

Внутри класса всё упаковано в колбэк, и, в зависимости от входящей строки, вызывается или функция sale(), которая позволяет продавать заданную валюту, или функция buy(), позволяющая её покупать.

В качестве единственного параметра передаётся строка фиксированного формата:
"sale xxx USD" или "buy ХХХ USD", где XXX - желаемое число для конвертации

Вместо USD можно указывать EUR или BTC !!!

референс по АПИ привата: https://api.privatbank.ua/#p24/exchange
