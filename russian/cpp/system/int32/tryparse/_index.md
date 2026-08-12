---
title: "Метод System::Int32::TryParse"
linktitle: "TryParse"
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать метод TryParse класса System::Int32 в C++."
type: docs
weight: 200
url: /ru/cpp/system/int32/tryparse/
---
## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int32_t\&) method




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int32_t &result)
```

## См. также

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [Int32](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int32_t\&) method




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int32_t &result)
```

## См. также

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Int32](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int32_t\&) method


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 32‑битное знаковое целое, используя предоставленную информацию о форматировании и стиль числа.

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int32_t &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const String\& | Строка для преобразования. |
| styles | Globalization::NumberStyles | Побитовое сочетание значений перечисления NumberStyles, которое определяет допустимый стиль строкового представления числа. |
| поставщик | const SharedPtr\<IFormatProvider\>\& | Указатель на объект, содержащий информацию о форматировании строки. |
| result | int32_t\& | Ссылка на переменную 32-битного знакового целого, куда помещается результат преобразования. |

### ReturnValue

True, если преобразование удалось, иначе — false.

## См. также

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Int32](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int32_t\&) method




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int32_t &result)
```

## См. также

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Class [Int32](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int32::TryParse(const String\&, int32_t\&) method


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 32‑битное знаковое целое.

```cpp
static bool System::Int32::TryParse(const String &value, int32_t &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const String\& | Строка для преобразования. |
| result | int32_t\& | Ссылка на переменную 32-битного знакового целого, куда помещается результат преобразования. |

### ReturnValue

True, если преобразование удалось, иначе — false.

## См. также

* Class [String](../../string/)
* Class [Int32](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
