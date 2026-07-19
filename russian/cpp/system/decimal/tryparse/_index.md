---
title: "Метод System::Decimal::TryParse"
linktitle: "TryParse"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Decimal::TryParse. Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение Decimal в C++."
type: docs
weight: 5800
url: /ru/cpp/system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) method


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение [Decimal](../).

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const String\& | Строка для преобразования |
| result | Decimal\& | Ссылка на переменную [Decimal](../), в которую помещается результат преобразования |

### ReturnValue

True, если преобразование удалось, иначе — false

## См. также

* Class [String](../../string/)
* Class [Decimal](../)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) method


Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение [Decimal](../), используя предоставленную информацию о форматировании и стиль числа.

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const String\& | Строка для преобразования |
| styles | Globalization::NumberStyles | Битовая комбинация значений перечисления NumberStyles, определяющая разрешённый стиль строкового представления числа |
| поставщик | const SharedPtr\<IFormatProvider\>\& | Указатель на объект, содержащий информацию о формате строки |
| result | Decimal\& | Выходной аргумент; содержит результат преобразования |

### ReturnValue

True, если преобразование удалось, иначе — false

## См. также

* Class [String](../../string/)
* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Decimal](../)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
