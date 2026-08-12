---
title: "Метод System::Byte::TryParse"
linktitle: "TryParse"
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать метод TryParse класса System::Byte в C++."
type: docs
weight: 200
url: /ru/cpp/system/byte/tryparse/
---
## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) method




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint8_t &result)
```

## См. также

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [Byte](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) method




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint8_t &result)
```

## См. также

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Byte](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) method


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 8-битное целое, используя предоставленную информацию о форматировании и стиль числа.

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint8_t &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const String\& | Строка для преобразования. |
| styles | Globalization::NumberStyles | Побитовое сочетание значений перечисления NumberStyles, которое определяет допустимый стиль строкового представления числа. |
| поставщик | const SharedPtr\<IFormatProvider\>\& | Указатель на объект, содержащий информацию о форматировании строки. |
| result | uint8_t\& | Ссылка на переменную 8‑битного беззнакового целого, в которую помещается результат преобразования. |

### ReturnValue

True, если преобразование удалось, иначе — false.

## См. также

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Byte](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Byte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) method




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint8_t &result)
```

## См. также

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Class [Byte](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Byte::TryParse(const String\&, uint8_t\&) method


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 8-битное целое.

```cpp
static bool System::Byte::TryParse(const String &value, uint8_t &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const String\& | Строка для преобразования. |
| result | uint8_t\& | Ссылка на переменную 8‑битного беззнакового целого, в которую помещается результат преобразования. |

### ReturnValue

True, если преобразование удалось, иначе — false.

## См. также

* Class [String](../../string/)
* Class [Byte](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
