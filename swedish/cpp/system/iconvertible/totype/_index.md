---
title: "System::IConvertible::ToType metod"
linktitle: "ToType"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IConvertible::ToType metod. Konverterar värdet av detta objekt till ett System::Object av den angivna System::Type som har ett motsvarande värde, med hjälp av den angivna kulturspecifika formateringsinformationen i C++."
type: docs
weight: 1400
url: /sv/cpp/system/iconvertible/totype/
---
## IConvertible::ToType method


Konverterar värdet av detta objekt till ett [System::Object](../../object/) av den angivna System::Type som har ett motsvarande värde, med hjälp av den angivna kulturspecifika formateringsinformationen.

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| conversionType | const TypeInfo\& | System::Type som värdet av detta objekt konverteras till. |
| provider | System::SharedPtr\<System::IFormatProvider\> | En [System::IFormatProvider](../../iformatprovider/) gränssnittsimplementation som tillhandahåller kulturspecifik formateringsinformation. |

### ReturnValue

En [System::Object](../../object/) instans av typen conversionType vars värde är motsvarande värdet av detta objekt.

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [IConvertible](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
