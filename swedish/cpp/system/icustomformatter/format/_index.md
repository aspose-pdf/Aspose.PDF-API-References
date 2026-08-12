---
title: "System::ICustomFormatter::Format metod"
linktitle: "Format"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ICustomFormatter::Format metod. Returnerar en strängrepresentation av ett värde som representeras av det aktuella objektet med angivet format i C++."
type: docs
weight: 100
url: /sv/cpp/system/icustomformatter/format/
---
## ICustomFormatter::Format method


Returnerar en strängrepresentation av ett värde som representeras av det aktuella objektet med det angivna formatet.

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | System::String | Strängformatet |
| arg | System::SharedPtr\<System::Object\> | Objektet som ska formateras |
| formatProvider | System::SharedPtr\\<System::IFormatProvider\\> | Objektet som tillhandahåller formateringsinformationen |

### ReturnValue

Strängrepresentationen av **arg** formaterad enligt formatet som specificerats av **format** och **formatProvider**

## Se även

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [ICustomFormatter](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
