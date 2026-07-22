---
title: "System::Drawing::Imaging::PropertyItem-klass"
linktitle: "PropertyItem"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Imaging::PropertyItem-klass. Representerar en metadataegenskap som ska inkluderas i en bildfil. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1400
url: /sv/cpp/system.drawing.imaging/propertyitem/
---
## PropertyItem class


Representerar en metadataegenskap som ska inkluderas i en bildfil. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class PropertyItem : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Id](./get_id/)() const | Returnerar ID:t för egenskapen som representeras av det aktuella objektet. |
| [get_Len](./get_len/)() const | Returnerar längden på egenskapen som representeras av det aktuella objektet i byte. |
| [get_Type](./get_type/)() const | Returnerar typen av egenskapen som representeras av det aktuella objektet i byte. |
| [get_Value](./get_value/)() const | Returnerar värdet av egenskapen som representeras av det aktuella objektet i byte. |
| [PropertyItem](./propertyitem/)() | Skapar en ny instans av klassen [PropertyItem](./). |
| [set_Id](./set_id/)(int32_t) | Sätter ID:t för egenskapen som representeras av det aktuella objektet. |
| [set_Len](./set_len/)(int32_t) | Sätter längden på egenskapen som representeras av det aktuella objektet i byte. |
| [set_Type](./set_type/)(int16_t) | Ställer in typen av egenskapen som representeras av det aktuella objektet i byte. |
| [set_Value](./set_value/)(const System::ArrayPtr\<uint8_t\>\&) | Ställer in typen av egenskapen som representeras av det aktuella objektet i byte. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
