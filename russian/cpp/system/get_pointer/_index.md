---
title: "Метод System::get_pointer"
linktitle: "get_pointer"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::get_pointer. Получает объект, на который ссылается умный указатель в C++."
type: docs
weight: 21800
url: /ru/cpp/system/get_pointer/
---
## System::get_pointer method


Получает объект, на который ссылается умный указатель.

```cpp
template<class T> T * System::get_pointer(System::SmartPtr<T> const &x)
```


| Параметр | Описание |
| --- | --- |
| T | Тип указываемого. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | System::SmartPtr\<T\> const\& | Исходный умный указатель. |

### ReturnValue

Необработанный указатель на объект, на который ссылается переданный умный указатель.

## См. также

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
