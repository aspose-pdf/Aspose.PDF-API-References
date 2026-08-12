---
title: "System::Random klass"
linktitle: "Slumpmässig"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Random-klass. Representerar en pseudoslumpmässig talgenerator. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 5400
url: /sv/cpp/system/random/
---
## Random class


Representerar en pseudoslumpmässig talgenerator. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class Random : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [IsNull](./isnull/)() const | Returnerar alltid falskt. |
| virtual [Next](./next/)() | Returnerar ett icke‑negativt slumpmässigt tal som är mindre än int32:s maximala värde. |
| virtual [Next](./next/)(int32_t) | Returnerar ett icke‑negativt slumpmässigt tal som är mindre än det angivna maximumet. |
| virtual [Next](./next/)(int32_t, int32_t) | Returnerar ett slumpmässigt tal inom det angivna intervallet. |
| virtual [NextBytes](./nextbytes/)(const ArrayPtr\<uint8_t\>\&) | Fyller elementen i den angivna byte‑arrayen med slumpmässiga tal. |
| virtual [NextDouble](./nextdouble/)() | Returnerar ett slumpmässigt tal mellan 0,0 och 1,0. |
| [Random](./random/)() | Initierar en ny instans med ett tidsberoende standardfrö. |
| [Random](./random/)(int32_t) | Initierar en ny instans av [System.Random](./)-klassen med det angivna frövärdet. |
## Anmärkningar



```cpp
#include "system/random.h"
#include "system/smart_ptr.h"
#include <iostream>

int main()
{
  const auto rnd = System::MakeObject<System::Random>();

  // Hämta ett slumpmässigt månadsnummer och skriv ut det.
  auto monthNumber = rnd->Next(1, 13);
  std::cout << "Month: " << monthNumber << std::endl;

  // Fyll arrayen med slumpmässiga tal.
  auto arr = System::MakeObject<System::Array<uint8_t>>(12);
  rnd->NextBytes(arr);

  // Skriv ut arrayen.
  for (auto i = 0; i < arr->get_Length(); ++i)
  {
    std::cout << static_cast<int>(arr[i]) << ' ';
  }
  std::cout << std::endl;

  return 0;
}
/*
This code example produces the following output:
Month: 4
177 213 89 240 68 182 18 96 109 131 1 78
*/
```

## Se även

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
