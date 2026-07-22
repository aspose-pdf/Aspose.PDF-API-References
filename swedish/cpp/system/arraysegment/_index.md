---
title: "System::ArraySegment-klass"
linktitle: "ArraySegment"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ArraySegment-klass. Representerar ett segment av den endimensionella arrayen. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig System::SmartPtr‑klassen för att hantera objekt av denna typ i C++."
type: docs
weight: 400
url: /sv/cpp/system/arraysegment/
---
## ArraySegment class


Representerar ett segment av den endimensionella arrayen. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig [System::SmartPtr](../smartptr/)-klassen för att hantera objekt av denna typ.

```cpp
template<typename T>class ArraySegment : public System::Object
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen av arraysegmentets element. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ArraySegment](./arraysegment/)(System::ArrayPtr\<T\>) |  |
| [ArraySegment](./arraysegment/)(System::ArrayPtr\<T\>, int32_t, int32_t) |  |
| [ArraySegment](./arraysegment/)() |  |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override |  |
| [Equals](./equals/)(ArraySegment\<T\>) |  |
| [get_Array](./get_array/)() const |  |
| [get_Count](./get_count/)() const |  |
| [get_Offset](./get_offset/)() const |  |
| [GetHashCode](./gethashcode/)() const override | Analog till C#‑metoden [Object.GetHashCode()](../object/gethashcode/). Möjliggör hashning av anpassade objekt. |
| [operator[]](./operator[]/)(int32_t) const |  |
| [Slice](./slice/)(int32_t, int32_t) |  |
| [ToArray](./toarray/)() const |  |
## Anmärkningar



```cpp
#include <system/array_segment.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<ArraySegment<String>> &segment)
{
  for (auto i = segment->get_Offset(); i < segment->get_Offset() + segment->get_Count(); i++)
  {
    std::cout << segment->get_Array()[i] << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Skapa och fyll arrayen.
  auto array = System::MakeObject<Array<String>>(3);
  array[0] = u"First";
  array[1] = u"Second";
  array[2] = u"Third";

  // Skapa arraysegmentet som innehåller hela arrayen.
  auto fullArray = MakeObject<ArraySegment<String>>(array);

  // Skriv ut arraysegmentets element.
  Print(fullArray);

  // Skapa arraysegmentet.
  auto segment = MakeObject<ArraySegment<String>>(array, 1, 2);

  // Skriv ut arraysegmentets element.
  Print(segment);

  return 0;
}
/*
This code example produces the following output:
First Second Third
Second Third
*/
```

## Se även

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
