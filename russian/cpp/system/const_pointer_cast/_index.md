---
title: "Метод System::const_pointer_cast"
linktitle: "const_pointer_cast"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::const_pointer_cast. Приводит умные указатели с помощью const_cast в C++."
type: docs
weight: 16500
url: /ru/cpp/system/const_pointer_cast/
---
## System::const_pointer_cast method


Приводит умные указатели с помощью const_cast.

```cpp
template<class Y,class X> SmartPtr<Y> System::const_pointer_cast(SmartPtr<X> const &x)
```


| Параметр | Описание |
| --- | --- |
| X | Тип объекта, на который указывает исходный указатель. |
| Y | Тип объекта, на который указывает целевой указатель. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | SmartPtr\\<X\\> const\\& | Указатель источника. |

### ReturnValue

Указатель после приведения.

## См. также

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
