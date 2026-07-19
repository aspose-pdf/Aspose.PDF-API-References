---
title: "System::Int16::TryParse метод"
linktitle: "TryParse"
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать метод TryParse класса System::Int16 в C++."
type: docs
weight: 200
url: /ru/cpp/system/int16/tryparse/
---
## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) method




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## См. также

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [Int16](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) method




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## См. также

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Int16](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) method


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 16-битное знаковое целое, используя предоставленную информацию о форматировании и стиль числа.

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const String\& | Строка для преобразования. |
| styles | Globalization::NumberStyles | Побитовое сочетание значений перечисления NumberStyles, которое определяет допустимый стиль строкового представления числа. |
| поставщик | const SharedPtr\<IFormatProvider\>\& | Указатель на объект, содержащий информацию о форматировании строки. |
| result | int16_t\& | Ссылка на 16-битную знаковую целочисленную переменную, в которую помещается результат преобразования. |

### ReturnValue

True, если преобразование удалось, иначе — false.

## См. также

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Int16](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) method




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
```

## См. также

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Class [Int16](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Int16::TryParse(const String\&, int16_t\&) method


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 16-битное знаковое целое.

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const String\& | Строка для преобразования. |
| result | int16_t\& | Ссылка на 16-битную знаковую целочисленную переменную, в которую помещается результат преобразования. |

### ReturnValue

True, если преобразование удалось, иначе — false.

## См. также

* Class [String](../../string/)
* Class [Int16](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
