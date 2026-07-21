---
title: "System::ArraySegment clase"
linktitle: "ArraySegment"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::ArraySegment clase. Representa un segmento del arreglo unidimensional. Este tipo debe ser asignado en la pila y pasado a funciones por valor o por referencia. Nunca use System::SmartPtr clase para gestionar objetos de este tipo en C++."
type: docs
weight: 400
url: /es/cpp/system/arraysegment/
---
## ArraySegment class


Representa un segmento del arreglo unidimensional. Este tipo debe ser asignado en la pila y pasado a funciones por valor o por referencia. Nunca use [System::SmartPtr](../smartptr/) clase para gestionar objetos de este tipo.

```cpp
template<typename T>class ArraySegment : public System::Object
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los elementos del segmento del arreglo. |
## Métodos

| Método | Descripción |
| --- | --- |
| [ArraySegment](./arraysegment/)(System::ArrayPtr\<T\>) |  |
| [ArraySegment](./arraysegment/)(System::ArrayPtr\<T\>, int32_t, int32_t) |  |
| [ArraySegment](./arraysegment/)() |  |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override |  |
| [Equals](./equals/)(ArraySegment\<T\>) |  |
| [get_Array](./get_array/)() const |  |
| [get_Count](./get_count/)() const |  |
| [get_Offset](./get_offset/)() const |  |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../object/gethashcode/). Permite el hash de objetos personalizados. |
| [operator[]](./operator[]/)(int32_t) const |  |
| [Slice](./slice/)(int32_t, int32_t) |  |
| [ToArray](./toarray/)() const |  |
## Observaciones



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
  // Crea y llena la matriz.
  auto array = System::MakeObject<Array<String>>(3);
  array[0] = u"First";
  array[1] = u"Second";
  array[2] = u"Third";

  // Cree el segmento del arreglo que contiene todo el arreglo.
  auto fullArray = MakeObject<ArraySegment<String>>(array);

  // Imprima los elementos del segmento del arreglo.
  Print(fullArray);

  // Cree el segmento del arreglo.
  auto segment = MakeObject<ArraySegment<String>>(array, 1, 2);

  // Imprima los elementos del segmento del arreglo.
  Print(segment);

  return 0;
}
/*
This code example produces the following output:
First Second Third
Second Third
*/
```

## Ver también

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
