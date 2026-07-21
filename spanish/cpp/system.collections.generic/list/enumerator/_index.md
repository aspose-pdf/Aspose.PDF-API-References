---
title: "Clase System::Collections::Generic::List::Enumerator"
linktitle: "Enumerador"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::Generic::List::Enumerator. Enumerador para iterar a través de los elementos de la lista. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 6100
url: /es/cpp/system.collections.generic/list/enumerator/
---
## Enumerator class


[Enumerator](./) to iterate through list elements. Objects of this class should only be allocated using [System::MakeObject()](../../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Enumerator : public System::Collections::Generic::SimpleEnumerator<vector_t>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Enumerator](./enumerator/)(const ThisPtr\&) | Crea un enumerador que itera a través de una lista específica. |
## Ver también

* Class [SimpleEnumerator](../../simpleenumerator/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
