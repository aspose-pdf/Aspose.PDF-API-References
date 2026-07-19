---
title: "Метод System::Int64::TryParse"
linktitle: "TryParse"
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать метод TryParse класса System::Int64 в C++."
type: docs
weight: 200
url: /ru/cpp/system/int64/tryparse/
---
## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int64_t\&) method




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int64_t &result)
```

## См. также

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int64_t\&) method




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int64_t &result)
```

## См. также

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int64_t\&) method


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 64‑битное знаковое целое, используя предоставленную информацию о форматировании и стиль числа.

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int64_t &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const String\& | Строка для преобразования. |
| styles | Globalization::NumberStyles | Побитовое сочетание значений перечисления NumberStyles, которое определяет допустимый стиль строкового представления числа. |
| поставщик | const SharedPtr\<IFormatProvider\>\& | Указатель на объект, содержащий информацию о форматировании строки. |
| result | int64_t\& | Ссылка на переменную 64‑битного знакового целого, в которую помещается результат преобразования. |

### ReturnValue

True, если преобразование удалось, иначе — false.

## См. также

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int64_t\&) method




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int64_t &result)
```

## См. также

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int64::TryParse(const String\&, int64_t\&) method


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 64-битное знаковое целое.

```cpp
static bool System::Int64::TryParse(const String &value, int64_t &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const String\& | Строка для преобразования. |
| result | int64_t\& | Ссылка на переменную 64‑битного знакового целого, в которую помещается результат преобразования. |

### ReturnValue

True, если преобразование удалось, иначе — false.

## См. также

* Class [String](../../string/)
* Class [Int64](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
