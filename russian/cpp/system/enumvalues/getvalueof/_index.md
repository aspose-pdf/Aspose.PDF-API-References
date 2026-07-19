---
title: "Метод System::EnumValues::GetValueOf"
linktitle: "GetValueOf"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::EnumValues::GetValueOf. Возвращает упакованное значение константы перечисления с указанным именем в C++."
type: docs
weight: 500
url: /ru/cpp/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String\&, bool) const method


Возвращает упакованное значение константы перечисления с указанным именем.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const String\& | Имя константы перечисления |
| ignoreCase | bool | Указывает, следует ли игнорировать регистр при интерпретации имени константы перечисления |

### ReturnValue

Упакованное значение константы перечисления, имя которой указано в **str**.

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [String](../../string/)
* Class [EnumValues](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## EnumValues::GetValueOf(long) const method


Возвращает упакованное значение константы перечисления с указанным значением.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| val | long | Значение константы перечисления |

### ReturnValue

Упакованное значение константы перечисления, значение которой указано в **str**.

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [EnumValues](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
