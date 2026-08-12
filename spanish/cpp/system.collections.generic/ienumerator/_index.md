---
title: "Clase System::Collections::Generic::IEnumerator"
linktitle: "IEnumerator"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::Generic::IEnumerator. Interfaz del enumerador que puede usarse para iterar a través de algunos elementos. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2300
url: /es/cpp/system.collections.generic/ienumerator/
---
## IEnumerator class


Interfaz del enumerador que puede usarse para iterar a través de algunos elementos. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
template<typename T>class IEnumerator : public virtual System::IDisposable,
                                        public System::Details::EnumeratorBasedIterator<T>,
                                        protected System::Details::IteratorPointerUpdater<T, false>
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de elemento. |
## Métodos

| Método | Descripción |
| --- | --- |
| [AsVirtualizedIterator](./asvirtualizediterator/)() | Prepara el iterador para ser usado por la clase VirtualizedIterator. |
| [CloneIterator](./cloneiterator/)() const override | Clona el iterador actual. |
| virtual [Current](./current/)() const | Obtiene el elemento actual. |
| virtual [get_Current](./get_current/)() const | Obtiene el elemento actual. |
| [IEnumerator](./ienumerator/)() |  |
| [IncrementIterator](./incrementiterator/)() override | Mueve el iterador un paso adelante. |
| [InitializeIterator](./initializeiterator/)() override | Realiza la primera llamada a [MoveNext()](./movenext/) y prepara el objeto enumerador para ser usado por VirtualizedIterator. |
| [MarkOwnedByVirtualizedIterator](./markownedbyvirtualizediterator/)() | Marca el enumerador perteneciente al iterador virtualizado. |
| virtual [MoveNext](./movenext/)() | Mueve el enumerador al siguiente elemento. Si no se había referenciado ningún elemento antes, establece la referencia al primer elemento disponible. Si se alcanza el final del contenedor, no hace nada. |
| virtual [Reset](./reset/)() | Restablece el enumerador a la posición anterior al primer elemento. |
| virtual [~IEnumerator](./~ienumerator/)() |  |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [ValueType](./valuetype/) | Tipo de valor. |
## Observaciones



```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Crea la instancia de la clase List.
  auto collection = MakeObject<List<int>>();

  // Llena la lista.
  collection->Add(1);
  collection->Add(2);
  collection->Add(3);

  // Obtén el enumerador de la lista.
  auto enumerator = collection->GetEnumerator();

  while (enumerator->MoveNext())
  {
    // Obtén el elemento actual e imprímelo.
    std::cout << enumerator->get_Current() << ' ';
  }

  // Restablece el enumerador.
  enumerator->Reset();

  return 0;
}
/*
This code example produces the following output:
1 2 3
*/
```

## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
