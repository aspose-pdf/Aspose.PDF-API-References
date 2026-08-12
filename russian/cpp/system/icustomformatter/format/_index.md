---
title: "System::ICustomFormatter::Format метод"
linktitle: "Format"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::ICustomFormatter::Format метод. Возвращает строковое представление значения, представленного текущим объектом, используя указанный формат в C++."
type: docs
weight: 100
url: /ru/cpp/system/icustomformatter/format/
---
## ICustomFormatter::Format method


Возвращает строковое представление значения, представленного текущим объектом, используя указанный формат.

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| формат | System::String | Формат строки |
| arg | System::SharedPtr\<System::Object\> | Объект, подлежащий форматированию |
| formatProvider | System::SharedPtr\<System::IFormatProvider\> | Объект, предоставляющий информацию о форматировании |

### ReturnValue

Строковое представление **arg**, отформатированное согласно формату, указанному в **format** и **formatProvider**

## См. также

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [ICustomFormatter](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
