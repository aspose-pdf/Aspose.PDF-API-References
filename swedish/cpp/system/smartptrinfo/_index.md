---
title: "System::SmartPtrInfo klass"
linktitle: "SmartPtrInfo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::SmartPtrInfo klass. Serviceklass för att testa och ändra SmartPtr''s innehåll utan att känna till den slutgiltiga typen. Används för skräpsamling och upptäckt av loopreferenser, etc. Tänk på det som en ''pekare till pekare''. Vi kan inte använda SmartPtr''s bastyp eftersom den inte har någon; istället använder vi denna ''info''-klass i C++."
type: docs
weight: 5900
url: /sv/cpp/system/smartptrinfo/
---
## SmartPtrInfo class


Serviceklass för att testa och ändra [SmartPtr](../smartptr/)'s innehåll utan att känna till den slutgiltiga typen. Används för skräpsamling och upptäckt av loopreferenser, etc. Tänk på det som en 'pekare till pekare'. Vi kan inte använda [SmartPtr](../smartptr/)'s bastyp eftersom den inte har någon; istället använder vi denna 'info'-klass.

```cpp
class SmartPtrInfo
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getInternalPtr](./getinternalptr/)() const | Hämtar det råa objekt som den refererade pekaren pekar på. |
| [getObject](./getobject/)() const | Hämtar objektet som den refererade pekaren pekar på. |
| [getOwned](./getowned/)() const | Hämtar objektets ägda pekare. |
| [operator bool](./operatorbool/)() const | Kontrollerar om infoobjektet pekar på en icke-null pekare. |
| [operator!](./operator!/)() const | Kontrollerar om infoobjektet inte pekar på en icke-null pekare. |
| [operator->](./operator-_/)() const | Tillåter att anropa metoder på [Object](../object/) som pekas på av den refererade pekaren. |
| [operator<](./operator_/)(const SmartPtrInfo\&) const | Jämför mindre värden på pekare som refereras av två infoobjekt. |
| [SmartPtrInfo](./smartptrinfo/)() | Skapar ett tomt [SmartPtrInfo](./)-objekt. |
| explicit [SmartPtrInfo](./smartptrinfo/)(const SmartPtr\<T\>\&) | Skapar ett [SmartPtrInfo](./)-objekt med information om en specifik smartpekare. |
## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
