---
title: "Метод System::BoxedValueBase::Parse"
linktitle: "Разобрать"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::BoxedValueBase::Parse. Упаковывает значение константы перечисления указанного перечисления с заданным именем в C++."
type: docs
weight: 500
url: /ru/cpp/system/boxedvaluebase/parse/
---
## BoxedValueBase::Parse(const TypeInfo\&, const String\&) method


Упаковывает значение константы перечисления указанного перечисления с указанным именем.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | const TypeInfo\& | Указывает тип перечисления |
| str | const String\& | Имя константы перечисления, значение которой должно быть упаковано |

### ReturnValue

Умный указатель (shared pointer) на объект, представляющий упакованное значение указанной константы перечисления

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [String](../../string/)
* Class [BoxedValueBase](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## BoxedValueBase::Parse(const TypeInfo\&, const String\&, bool) method


Упаковывает значение константы перечисления указанного перечисления с указанным именем. Параметр указывает, следует ли игнорировать регистр при интерпретации строки, задающей имя константы перечисления.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | const TypeInfo\& | Указывает тип перечисления |
| str | const String\& | Имя константы перечисления, значение которой должно быть упаковано |
| ignoreCase | bool | Указывает, следует ли игнорировать регистр при интерпретации строки, представляющей имя константы перечисления |

### ReturnValue

Умный указатель (shared pointer) на объект, представляющий упакованное значение указанной константы перечисления

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [String](../../string/)
* Class [BoxedValueBase](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
