---
title: "Класс System::Net::WebHeaderCollection"
linktitle: "WebHeaderCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Net::WebHeaderCollection. Представляет коллекцию заголовков протокола. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 3600
url: /ru/cpp/system.net/webheadercollection/
---
## WebHeaderCollection class


Представляет коллекцию заголовков протокола. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class WebHeaderCollection : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(String, String) | Добавляет указанную пару имени заголовка и значения заголовка в коллекцию. |
| [Add](./add/)(HttpResponseHeader, String) | Добавляет указанную пару заголовка и его значения в коллекцию. |
| [Add](./add/)(HttpRequestHeader, String) | Добавляет указанную пару заголовка и его значения в коллекцию. |
| [AllKeys](./allkeys/)() | Возвращает коллекцию имён заголовков, хранящихся в коллекции. |
| [get_Count](./get_count/)() const | Возвращает количество элементов в коллекции. |
| [get_Keys](./get_keys/)() | Возвращает коллекцию имён заголовков, хранящихся в коллекции. |
| [GetKey](./getkey/)(int) | Возвращает ключ по указанному индексу. |
| [GetValues](./getvalues/)(String) | Возвращает коллекцию значений заголовков. |
| [idx_get](./idx_get/)(HttpRequestHeader) | Получает значение заголовка, используя указанный заголовок запроса. |
| [idx_get](./idx_get/)(HttpResponseHeader) | Получает значение заголовка, используя указанный заголовок ответа. |
| [idx_get](./idx_get/)(String) | Получает значение заголовка, используя указанное имя заголовка. |
| [idx_set](./idx_set/)(HttpRequestHeader, String) | Устанавливает значение указанного заголовка. |
| [idx_set](./idx_set/)(HttpResponseHeader, String) | Устанавливает значение заголовка, используя указанный заголовок ответа. |
| [idx_set](./idx_set/)(String, String) | Устанавливает значение заголовка, используя указанное имя заголовка. |
| static [IsRestricted](./isrestricted/)(const String\&) | Проверяет, можно ли установить указанный HTTP‑заголовок для запроса. |
| [Remove](./remove/)(String) | Удаляет заголовок по указанному имени заголовка. |
| [Remove](./remove/)(HttpResponseHeader) | Удаляет указанный заголовок ответа. |
| [Remove](./remove/)(HttpRequestHeader) | Удаляет указанный заголовок запроса. |
| [Set](./set/)(String, String) | Устанавливает значение указанного заголовка. |
| [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| [WebHeaderCollection](./webheadercollection/)() | Создаёт новый экземпляр. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
