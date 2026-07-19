---
title: "Метод System::SmartPtr::Is"
linktitle: "Is"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::SmartPtr::Is. Проверяет, является ли указанный объект объектом конкретного типа или его дочерним типом. Следует семантике ''is'' в C# в C++."
type: docs
weight: 1900
url: /ru/cpp/system/smartptr/is/
---
## SmartPtr::Is method


Проверяет, является ли объект, на который указывает указатель, конкретным типом или его дочерним типом. Соответствует семантике C# 'is'.

```cpp
bool System::SmartPtr<T>::Is(const System::TypeInfo &target) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| target | const System::TypeInfo\& | Указывает целевой тип для проверки. |

### ReturnValue

Истина, если проверка в стиле C# 'is' положительна, и ложь в противном случае.
## Примечания


Реализация.

## См. также

* Class [TypeInfo](../../typeinfo/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
