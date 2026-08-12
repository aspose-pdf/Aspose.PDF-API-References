---
title: "System::Collections::Generic::SortedList::Enumerator clase"
linktitle: "Enumerador"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Collections::Generic::SortedList::Enumerator clase. Clase enumeradora para iterar a través de la lista. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2600
url: /es/cpp/system.collections.generic/sortedlist/enumerator/
---
## Enumerator class


[Enumerator](./) class to iterate through list. Objects of this class should only be allocated using [System::MakeObject()](../../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Enumerator : public System::Collections::Generic::SimpleEnumerator<map_t, KVPair>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Enumerator](./enumerator/)(const Ptr\&) | Crea un enumerador que itera a través de un diccionario específico. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [EnumeratorType](./enumeratortype/) | [Enumerator](./) alias de tipo. |
## Ver también

* Class [SimpleEnumerator](../../simpleenumerator/)
* Class [SortedList](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
