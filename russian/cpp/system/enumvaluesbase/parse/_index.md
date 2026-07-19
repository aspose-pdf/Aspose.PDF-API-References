---
title: "Метод System::EnumValuesBase::Parse"
linktitle: "Разобрать"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::EnumValuesBase::Parse. Возвращает объект, представляющий значение константы перечисления указанного типа перечисления с указанным именем в C++."
type: docs
weight: 400
url: /ru/cpp/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse method


Возвращает объект, представляющий значение константы перечисления указанного типа с указанным именем.

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| type | const TypeInfo\& | Объект [TypeInfo](../../typeinfo/), представляющий тип значения перечисления для возврата |
| str | const String\& | Имя константы перечисления |
| ignoreCase | bool | Указывает, следует ли игнорировать регистр при интерпретации имени константы перечисления |

### ReturnValue

Объект, представляющий значение константы перечисления, имя которой указано в **str**.

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [String](../../string/)
* Class [EnumValuesBase](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
