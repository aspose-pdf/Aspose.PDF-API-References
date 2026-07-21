---
title: "Clase System::Random"
linktitle: "Random"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Random. Representa un generador de números pseudoaleatorios. Los objetos de esta clase solo deben ser asignados usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 5400
url: /es/cpp/system/random/
---
## Random class


Representa un generador de números pseudoaleatorios. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class Random : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [IsNull](./isnull/)() const | Siempre devuelve false. |
| virtual [Next](./next/)() | Devuelve un número aleatorio no negativo menor que el valor máximo de int32. |
| virtual [Next](./next/)(int32_t) | Devuelve un número aleatorio no negativo menor que el máximo especificado. |
| virtual [Next](./next/)(int32_t, int32_t) | Devuelve un número aleatorio dentro del rango especificado. |
| virtual [NextBytes](./nextbytes/)(const ArrayPtr\<uint8_t\>\&) | Llena los elementos del arreglo de bytes especificado con números aleatorios. |
| virtual [NextDouble](./nextdouble/)() | Devuelve un número aleatorio entre 0.0 y 1.0. |
| [Random](./random/)() | Inicializa una nueva instancia, usando un valor de semilla predeterminado dependiente del tiempo. |
| [Random](./random/)(int32_t) | Inicializa una nueva instancia de la clase [System.Random](./), usando el valor de semilla especificado. |
## Observaciones



```cpp
#include "system/random.h"
#include "system/smart_ptr.h"
#include <iostream>

int main()
{
  const auto rnd = System::MakeObject<System::Random>();

  // Obtén un número de mes aleatorio y imprímelo.
  auto monthNumber = rnd->Next(1, 13);
  std::cout << "Month: " << monthNumber << std::endl;

  // Llena el arreglo con números aleatorios.
  auto arr = System::MakeObject<System::Array<uint8_t>>(12);
  rnd->NextBytes(arr);

  // Imprime el arreglo.
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

## Ver también

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
