---
title: "System::Array::Enumerator‑klass"
linktitle: "Enumerator"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Array::Enumerator-klass. Implementerar IEnumerator-gränssnittet som möjliggör uppräkning av element i ett Array-objekt. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 7000
url: /sv/cpp/system/array/enumerator/
---
## Enumerator class


Implementerar IEnumerator-gränssnittet som möjliggör uppräkning av element i ett [Array](../)-objekt. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class Enumerator : public virtual System::Object,
                   public System::Collections::Generic::IEnumerator<T>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Enumerator](./enumerator/)(const SharedPtr\<Array\<T\>\>\&) | Skapar ett nytt [Enumerator](./)-objekt som representerar den angivna arrayen. |
| [get_Current](./get_current/)() const override | Returnerar en kopia av det aktuella elementet. |
| [MoveNext](./movenext/)() override | Kontrollerar om det aktuella elementets index inte pekar på det sista elementet i arrayen och avancerar det om det inte gör det. |
| [Reset](./reset/)() override | Återställer det aktuella elementets index. |
| virtual [~Enumerator](./~enumerator/)() | Destruktor. |
## Se även

* Class [Object](../../object/)
* Class [IEnumerator](../../../system.collections.generic/ienumerator/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
