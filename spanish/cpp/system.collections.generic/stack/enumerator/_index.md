---
title: "System::Collections::Generic::Stack::Enumerator clase"
linktitle: "Enumerador"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::Generic::Stack::Enumerator. Enumerador para iterar a través de la pila. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2000
url: /es/cpp/system.collections.generic/stack/enumerator/
---
## Enumerator class


[Enumerator](./) to iterate through stack. Objects of this class should only be allocated using [System::MakeObject()](../../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Enumerator : public System::Collections::Generic::ReverseEnumerator<stack_t>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Enumerator](./enumerator/)(const ThisPtr\&) | Construye un enumerador que itera a través de la pila dada. |
## Ver también

* Class [ReverseEnumerator](../../reverseenumerator/)
* Class [Stack](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
