# Проект: *Виджет банковских операций клиента*

## Описание
Данный виджет имеет большой функционал, который со временем пополняется.
Из текущих функций можно отметить:
* шифрование номера карты *(реализовано в модуле **masks**)*;
* шифрование номера счета *(реализовано в модуле **masks**)*;
* автоматический выбор шифрования в зависимости от предоставлляемых данных (карта/счет)*(реализовано в модуле **widget**)*;
* конвертация времени с использованием модуля *datetime* *(реализовано в модуле **widget**)*;
* сортирует данные по ключу *(реализовано в модуле **processing**)*;
* сортирует данные по дате *(реализовано в модуле **processing**)*;
* в проекте дополнена директория *tests* для тестирования всех модулей;
* тесты покрыты на **100%**
* в модуле *generators* реализованы функции-генераторы по возвращению ID операции, данных по операции и генерированию номеров карт
* в модуле *decorators* реализован деккоратор для записи логов в консоль, либо в файл .txt