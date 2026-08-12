---
title: "System::Collections::Generic::Stack clase"
linktitle: "Pila"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::Generic::Stack. Declaración adelantada de la clase Stack en C++."
type: docs
weight: 4600
url: /es/cpp/system.collections.generic/stack/
---
## Stack class


[Stack](./) class forward declaration.

```cpp
template<typename T>class Stack : public System::Collections::Generic::IEnumerable<T>
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de elemento. |
## Nested classes

* Class [Enumerator](./enumerator/)
## Métodos

| Método | Descripción |
| --- | --- |
| [AddRange](./addrange/)(IEnumerablePtr) | Inserta elementos en la pila. |
| virtual [Clear](./clear/)() | Elimina todos los elementos de la pila. |
| virtual [Contains](./contains/)(const T\&) const | Comprueba si un elemento específico está presente en el contenedor; utiliza el operador == para la comparación. |
| [data](./data/)() | Accesor interno de la estructura de datos. |
| [data](./data/)() const | Accesor interno de la estructura de datos. |
| virtual [get_Count](./get_count/)() const | Obtiene el número de elementos en la pila. |
| [GetEnumerator](./getenumerator/)() override | Obtiene el enumerador para iterar a través de la pila actual. |
| [Peek](./peek/)() | Obtiene el elemento de la parte superior de la pila, pero lo mantiene en la pila. |
| [Pop](./pop/)() | Obtiene el elemento de la parte superior de la pila. |
| [Push](./push/)(const T\&) | Inserta el elemento en la parte superior de la pila. |
| [Stack](./stack/)() | Construye una pila vacía. |
| [Stack](./stack/)(int) | Construye una pila vacía. |
| [Stack](./stack/)(IEnumerablePtr) | Constructor de copia. |
| virtual [ToArray](./toarray/)() | Convierte la pila en una matriz. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtiene la implementación del iterador const begin para el contenedor actual. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtiene la implementación del iterador begin para el contenedor actual. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtiene la implementación del end const iterator para el contenedor actual. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtiene la implementación del end iterator para el contenedor actual. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [IEnumerablePtr](./ienumerableptr/) | Colección que contiene elementos del mismo tipo. |
| [IEnumeratorPtr](./ienumeratorptr/) | [Enumerator](./enumerator/) tipo. |
| [stack_t](./stack_t/) | Información RTTI. |
| [ValueType](./valuetype/) | Tipo de valor. |
## Observaciones


[Stack](./) class wrapping std::list. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.


```cpp
#include <system/collections/stack.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

void PrintItems(const SmartPtr<IEnumerable<int>> &stack)
{
  for (const auto item: stack)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Crea la instancia de la clase Stack.
  auto stack = MakeObject<Stack<int>>();

  // Llena la pila.
  stack->Push(1);
  stack->Push(2);
  stack->Push(3);

  // Imprime el último elemento de la pila. El método Peek no elimina un elemento de la pila.
  std::cout << stack->Peek() << std::endl;
  PrintItems(stack);

  // Imprime el último elemento de la pila. El método Pop elimina un elemento de la pila.
  std::cout << stack->Pop() << std::endl;
  PrintItems(stack);

  return 0;
}
/*
This code example produces the following output:
3
3 2 1
3
2 1
*/
```

## Ver también

* Class [IEnumerable](../ienumerable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
