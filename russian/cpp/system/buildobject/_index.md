---
title: "Метод System::BuildObject"
linktitle: "BuildObject"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::BuildObject. Создайте объект с разделяемым владением в C++."
type: docs
weight: 15700
url: /ru/cpp/system/buildobject/
---
## System::BuildObject method


Создайте объект с разделяемым владением.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
```


| Параметр | Описание |
| --- | --- |
| T | Тип объекта для создания |
| Аргументы | Типы аргументов для построения объекта |

| Параметр | Тип | Описание |
| --- | --- | --- |
| args | Args\&&... | Аргументы для передачи конструктору объекта |

### ReturnValue

ObjectBuilder, настроенный для создания shared pointer
## Примечания



Создаёт [SharedPtr<T>](../sharedptr/) и возвращает построитель для него
[Object](../object/) construction must be finished with [Get()](../get/) call 

## См. также

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
