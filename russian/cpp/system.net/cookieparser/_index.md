---
title: "System::Net::CookieParser класс"
linktitle: "CookieParser"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Net::CookieParser. Используется для разбора заголовка cookie и создания экземпляра класса Cookie. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 500
url: /ru/cpp/system.net/cookieparser/
---
## CookieParser class


Используется для разбора заголовка cookie и создания экземпляра класса [Cookie](../cookie/). Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class CookieParser : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| static [CheckQuoted](./checkquoted/)(String) | Проверяет, заключена ли указанная строка в кавычки. |
| [CookieParser](./cookieparser/)(String) | Информация RTTI. |
| [Get](./get/)() | Возвращает экземпляр на основе указанной строки. |
| [GetServer](./getserver/)() | Получает cookie сервера. |
| [GetString](./getstring/)() | Возвращает строковое представление заголовка cookie. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
