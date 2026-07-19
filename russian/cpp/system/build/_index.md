---
title: "System::Build метод"
linktitle: "Build"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Build. Создайте объект с прямым владением в C++."
type: docs
weight: 15500
url: /ru/cpp/system/build/
---
## System::Build method


Создайте объект с прямым владением.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T> System::Build(Args &&... args)
```


| Параметр | Описание |
| --- | --- |
| T | Тип объекта для создания |
| Аргументы | Типы аргументов для построения объекта |

| Параметр | Тип | Описание |
| --- | --- | --- |
| args | Args\&&... | Аргументы для передачи конструктору объекта |

### ReturnValue

ObjectBuilder, настроенный для прямого построения объекта
## Примечания



[Object](../object/) construction must be finished with [Get()](../get/) call 

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
