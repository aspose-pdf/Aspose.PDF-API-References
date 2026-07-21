---
title: "Clase System::Collections::Concurrent::ConcurrentDictionary"
linktitle: "ConcurrentDictionary"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::Concurrent::ConcurrentDictionary. Implementación de diccionario seguro para subprocesos. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 100
url: /es/cpp/system.collections.concurrent/concurrentdictionary/
---
## ConcurrentDictionary class


Implementación de diccionario seguro para subprocesos. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
template<class TKey,class TValue>class ConcurrentDictionary : public System::Collections::Generic::Dictionary<TKey, TValue>
```


| Parámetro | Descripción |
| --- | --- |
| TKey | Tipo de clave. |
| TValue | Tipo de valor. |
## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const TKey\&, const TValue\&) override | Agrega un valor al diccionario. |
| [Clear](./clear/)() override | Elimina todos los elementos del contenedor. |
| [CopyTo](./copyto/)(ArrayPtr\<System::Collections::Generic::KeyValuePair\<TKey, TValue\>\>, int) override | Copia los elementos del contenedor a los elementos existentes de la matriz. |
| [get_KeysInternal](./get_keysinternal/)() const override | Obtiene la colección contenedora para acceder a las claves del diccionario. |
| [idx_set](./idx_set/)(const TKey\&, TValue) override | Información RTTI. |
| [Remove](./remove/)(const TKey\&) override | Elimina el elemento del contenedor. |
| [TryAdd](./tryadd/)(const TKey\&, const TValue\&) | Intenta agregar un par clave/valor al diccionario. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [BaseType](./basetype/) | Tipo de implementación. |
| [ThisType](./thistype/) | Este tipo. |
## Observaciones



```cpp
#include <system/collections/concurrent/concurrent_dictionary.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  const int itemsCount = 32;

  // Crea la instancia de la clase ConcurrentDictionary-class.
  auto concurrentDictionary = MakeObject<ConcurrentDictionary<int, int>>();

  // Llena el diccionario concurrente.
  for (auto i = 0; i < itemsCount; ++i)
  {
    concurrentDictionary->Add(i, i * i);
  }

  Console::WriteLine(concurrentDictionary->idx_get(3));

  return 0;
}
/*
This code example produces the following output:
9
*/
```

## Ver también

* Class [Dictionary](../../system.collections.generic/dictionary/)
* Namespace [System::Collections::Concurrent](../)
* Library [Aspose.PDF for C++](../../)
