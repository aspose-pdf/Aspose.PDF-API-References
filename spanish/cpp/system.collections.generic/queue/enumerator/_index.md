---
title: "System::Collections::Generic::Queue::Enumerator class"
linktitle: "Enumerador"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Collections::Generic::Queue::Enumerator class. Enumerador para iterar a través de la cola. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1800
url: /es/cpp/system.collections.generic/queue/enumerator/
---
## Enumerator class


[Enumerator](./) to iterate through queue. Objects of this class should only be allocated using [System::MakeObject()](../../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Enumerator : public System::Collections::Generic::SimpleEnumerator<queue_t>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Enumerator](./enumerator/)(const ThisPtr\&) | Construye un enumerador que apunta a una cola específica. |
## Ver también

* Class [SimpleEnumerator](../../simpleenumerator/)
* Class [Queue](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
