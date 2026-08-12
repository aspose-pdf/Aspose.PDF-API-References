---
title: "System::IConvertible-klass"
linktitle: "IConvertible"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IConvertible-klass. Definierar metoder som konverterar värdet av den implementerande referens- eller värdetypen till en gemensam språk‑körnings‑typ som har ett motsvarande värde. Objekt av denna klass bör endast allokeras med hjälp av System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 3500
url: /sv/cpp/system/iconvertible/
---
## IConvertible class


Definierar metoder som konverterar värdet av den implementerande referens- eller värdetypen till en gemensam språk‑körnings‑typ som har ett motsvarande värde. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class IConvertible : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [GetTypeCode](./gettypecode/)() | Returnerar typkoden för detta objekt. |
| virtual [ToBoolean](./toboolean/)(System::SharedPtr\<System::IFormatProvider\>) | Konverterar värdet av detta objekt till ett motsvarande [Boolean](../boolean/)-värde med hjälp av den angivna kulturspecifika formateringsinformationen. |
| virtual [ToByte](./tobyte/)(System::SharedPtr\<System::IFormatProvider\>) | Konverterar värdet av detta objekt till ett motsvarande 8‑bitars uint32_teger med hjälp av den angivna kulturspecifika formateringsinformationen. |
| virtual [ToChar](./tochar/)(System::SharedPtr\<System::IFormatProvider\>) | Konverterar värdet av detta objekt till ett motsvarande Unicode‑tecken med hjälp av den angivna kulturspecifika formateringsinformationen. |
| virtual [ToDateTime](./todatetime/)(System::SharedPtr\<System::IFormatProvider\>) | Konverterar värdet av detta objekt till ett motsvarande [System::DateTime](../datetime/) med hjälp av den angivna kulturspecifika formateringsinformationen. |
| virtual [ToDecimal](./todecimal/)(System::SharedPtr\<System::IFormatProvider\>) | Konverterar värdet av detta objekt till ett motsvarande [System::Decimal](../decimal/)-tal med hjälp av den angivna kulturspecifika formateringsinformationen. |
| virtual [ToDouble](./todouble/)(System::SharedPtr\<System::IFormatProvider\>) | Konverterar värdet av detta objekt till ett motsvarande dubbelprecision flyttal med hjälp av den angivna kulturspecifika formateringsinformationen.. |
| virtual [ToInt16](./toint16/)(System::SharedPtr\<System::IFormatProvider\>) | Konverterar värdet av detta objekt till ett motsvarande 16‑bitars signerat heltal med hjälp av den angivna kulturspecifika formateringsinformationen. |
| virtual [ToInt32](./toint32/)(System::SharedPtr\<System::IFormatProvider\>) | Konverterar värdet av detta objekt till ett motsvarande 32‑bitars signerat heltal med hjälp av den angivna kulturspecifika formateringsinformationen. |
| virtual [ToInt64](./toint64/)(System::SharedPtr\<System::IFormatProvider\>) | Konverterar värdet av detta objekt till ett motsvarande 64‑bitars signerat heltal med hjälp av den angivna kulturspecifika formateringsinformationen. |
| virtual [ToSByte](./tosbyte/)(System::SharedPtr\<System::IFormatProvider\>) | Konverterar värdet av detta objekt till ett motsvarande 8‑bitars signerat heltal med hjälp av den angivna kulturspecifika formateringsinformationen. |
| virtual [ToSingle](./tosingle/)(System::SharedPtr\<System::IFormatProvider\>) | Konverterar värdet av detta objekt till ett motsvarande enkelprecision flyttal med hjälp av den angivna kulturspecifika formateringsinformationen. |
| virtual [ToString](./tostring/)(System::SharedPtr\<System::IFormatProvider\>) | Konverterar värdet för detta objekt till en motsvarande [System::String](../string/) med den angivna kultur‑specifika formateringsinformationen. |
| virtual [ToString](./tostring/)() const | Analog till C#‑metoden [Object.ToString()](../object/tostring/). Möjliggör konvertering av anpassade objekt till sträng. |
| virtual [ToType](./totype/)(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) | Konverterar värdet för detta objekt till ett [System::Object](../object/) av den angivna System::Type som har ett motsvarande värde, med den angivna kultur‑specifika formateringsinformationen. |
| virtual [ToUInt16](./touint16/)(System::SharedPtr\<System::IFormatProvider\>) | Konverterar värdet för detta objekt till en motsvarande 16‑bit uint32_teger med den angivna kultur‑specifika formateringsinformationen. |
| virtual [ToUInt32](./touint32/)(System::SharedPtr\<System::IFormatProvider\>) | Konverterar värdet för detta objekt till en motsvarande 32‑bit uint32_teger med den angivna kultur‑specifika formateringsinformationen. |
| virtual [ToUInt64](./touint64/)(System::SharedPtr\<System::IFormatProvider\>) | Konverterar värdet för detta objekt till en motsvarande 64‑bit uint32_teger med den angivna kultur‑specifika formateringsinformationen. |
## Se även

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
