---
title: "Класс System::WeakReference< T >"
linktitle: "WeakReference< T >"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::WeakReference< T >. Представляет слабую ссылку, которая ссылается на объект, позволяя при этом удалять этот объект в C++."
type: docs
weight: 8000
url: /ru/cpp/system/weakreference_t_/
---
## WeakReference< T > class


Представляет слабую ссылку, которая ссылается на объект, но при этом позволяет удалить этот объект.

```cpp
template<typename T>class WeakReference< T > : public System::Object
```


| Параметр | Описание |
| --- | --- |
| T | Тип ссылочного объекта. |
## Методы

| Метод | Описание |
| --- | --- |
| [operator!=](./operator!=/)(std::nullptr_t) const | Проверяет, что ссылочный объект не равен null. |
| [operator!=](./operator!=/)(const WeakReference\<T\>\&) const | Сравнивает ссылочный объект с другим экземпляром класса [WeakReference](../weakreference/). |
| [operator==](./operator==/)(std::nullptr_t) const | Проверяет, является ли ссылка на объект нулевой. |
| [operator==](./operator==/)(const WeakReference\<T\>\&) const | Сравнивает ссылочный объект с другим экземпляром класса [WeakReference](../weakreference/). |
| [reset](./reset/)() |  |
| [SetTarget](./settarget/)(const SmartPtr\<T\>\&) | Устанавливает объект (цель), на который ссылается текущий объект [WeakReference](../weakreference/). |
| [TryGetTarget](./trygettarget/)(const SmartPtr\<T\>\&) const | Возвращает объект (цель), на который ссылается текущий объект [WeakReference](../weakreference/). |
| [WeakReference](./weakreference/)() | Конструктор по умолчанию. |
| [WeakReference](./weakreference/)(std::nullptr_t) | Конструктор из nullptr. |
| [WeakReference](./weakreference/)(const SmartPtr\<T\>\&) | Инициализирует новый экземпляр класса [WeakReference](../weakreference/), ссылающийся на указанный объект. |
| [WeakReference](./weakreference/)(const SmartPtr\<T\>\&, bool) | Инициализирует новый экземпляр класса [WeakReference](../weakreference/), ссылающийся на указанный объект. |

## См. также

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
