---
title: "System::Comparison klass"
linktitle: "Jämförelse"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Comparison klass. Representerar en pekare till metoden som jämför två objekt av samma typ. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig System::SmartPtr-klassen för att hantera objekt av denna typ i C++."
type: docs
weight: 1400
url: /sv/cpp/system/comparison/
---
## Comparison class


Representerar en pekare till metoden som jämför två objekt av samma typ. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig [System::SmartPtr](../smartptr/)-klassen för att hantera objekt av denna typ.

```cpp
template<typename T>class Comparison : public System::MulticastDelegate<int(T, T)>
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen av objekten som metoden jämför |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [operator()](./operator()/)(T, T) | Anropar det anropbara objektet som det aktuella objektet pekar på. |
## Anmärkningar



```cpp
#include "system/comparison.h"
#include "system/console.h"
#include "system/exceptions.h"
#include "system/string.h"
#include <algorithm>
#include <initializer_list>
#include <vector>

using namespace System;

// Mallklassen som representerar en dynamisk array.
template <typename T>
class MyArray
{
  // Används för att lagra arraydata.
  std::vector<T> m_data;

public:
  // Skapar en ny instans av vår dynamiska array.
  MyArray(const std::initializer_list<T>& source) : m_data(source) {};

  // Används för att sortera arraydata. Denna metod accepterar en instans av
  // 'System::Comparison'-mallklassen.
  void Sort(Comparison<T> comparison)
  {
    if (comparison.IsNull())
    {
      throw ArgumentNullException(u"comparison");
    }
    std::sort(m_data.begin(), m_data.end(), comparison);
  }

  // Returnerar antalet element som vår dynamiska array lagrar.
  size_t get_Size()
  {
    return m_data.size();
  }

  // Används för att hämta ett element på det angivna indexet.
  T& operator[](int index)
  {
    if (index < 0 || index >= m_data.size())
    {
      throw IndexOutOfRangeException(u"index");
    }
    return m_data[index];
  }
};

int main() {
  // Skapa en instans av MyArray-klassen med de angivna elementen.
  MyArray<String> arr = {u"a", u"e", u"c", u"b", u"d"};

  // Sortera efter stigande element i den dynamiska arrayen.
  arr.Sort([](const String &a, const String &b) -> int
  {
    return String::Compare(a, b);
  });

  // Skriv ut element i den dynamiska arrayen.
  for (auto i = 0; i < arr.get_Size(); ++i)
  {
    Console::WriteLine(arr[i]);
  }

  return 0;
}
/*
This code example produces the following output:
a
b
c
d
e
*/
```

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
