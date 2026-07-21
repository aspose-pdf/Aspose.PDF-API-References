---
title: "System::Comparison clase"
linktitle: "Comparación"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Comparison clase. Representa un puntero al método que compara dos objetos del mismo tipo. Este tipo debe ser asignado en la pila y pasado a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo en C++."
type: docs
weight: 1400
url: /es/cpp/system/comparison/
---
## Comparison class


Representa un puntero al método que compara dos objetos del mismo tipo. Este tipo debe ser asignado en la pila y pasado a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../smartptr/) para gestionar objetos de este tipo.

```cpp
template<typename T>class Comparison : public System::MulticastDelegate<int(T, T)>
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los objetos que el método compara |
## Métodos

| Método | Descripción |
| --- | --- |
| [operator()](./operator()/)(T, T) | Invoca el objeto invocable al que apunta el objeto actual. |
## Observaciones



```cpp
#include "system/comparison.h"
#include "system/console.h"
#include "system/exceptions.h"
#include "system/string.h"
#include <algorithm>
#include <initializer_list>
#include <vector>

using namespace System;

// La clase plantilla que representa una matriz dinámica.
template <typename T>
class MyArray
{
  // Utilizada para almacenar los datos de la matriz.
  std::vector<T> m_data;

public:
  // Construye una nueva instancia de nuestra matriz dinámica.
  MyArray(const std::initializer_list<T>& source) : m_data(source) {};

  // Utilizada para ordenar los datos de la matriz. Este método acepta una instancia de la
  // 'System::Comparison' clase plantilla.
  void Sort(Comparison<T> comparison)
  {
    if (comparison.IsNull())
    {
      throw ArgumentNullException(u"comparison");
    }
    std::sort(m_data.begin(), m_data.end(), comparison);
  }

  // Devuelve un número de elementos que nuestra matriz dinámica almacena.
  size_t get_Size()
  {
    return m_data.size();
  }

  // Utilizada para obtener un elemento en el índice especificado.
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
  // Cree una instancia de la clase MyArray con los elementos especificados.
  MyArray<String> arr = {u"a", u"e", u"c", u"b", u"d"};

  // Ordene por elementos ascendentes de la matriz dinámica.
  arr.Sort([](const String &a, const String &b) -> int
  {
    return String::Compare(a, b);
  });

  // Imprima los elementos de la matriz dinámica.
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

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
