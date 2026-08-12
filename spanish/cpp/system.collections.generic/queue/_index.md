---
title: "Clase System::Collections::Generic::Queue"
linktitle: "Queue"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::Generic::Queue. Declaración adelantada de la clase Queue en C++."
type: docs
weight: 3600
url: /es/cpp/system.collections.generic/queue/
---
## Queue class


[Queue](./) class forward declaration.

```cpp
template<typename T>class Queue : public System::Collections::Generic::IEnumerable<T>
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de elemento. |
## Nested classes

* Class [Enumerator](./enumerator/)
## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Clear](./clear/)() | Elimina todos los elementos de la cola. |
| virtual [Contains](./contains/)(const T\&) const | Comprueba si la cola contiene un elemento específico usando el operador == para comparar los elementos. |
| [data](./data/)() | Accesor de la estructura de datos subyacente. |
| [data](./data/)() const | Accesor de la estructura de datos subyacente. |
| [Dequeue](./dequeue/)() | Obtiene el elemento del principio de la cola. |
| [Enqueue](./enqueue/)(const T\&) | Coloca el elemento al final de la cola. |
| virtual [get_Count](./get_count/)() const | Obtiene el número de elementos en la cola. |
| [GetEnumerator](./getenumerator/)() override | Obtiene el enumerador para iterar a través de la cola. |
| [Peek](./peek/)() | Obtiene el elemento del principio de la cola, pero no lo elimina de la cola. |
| [Queue](./queue/)() | Construye una cola vacía. |
| [Queue](./queue/)(int) | Construye una cola vacía. |
| [Queue](./queue/)(const SharedPtr\<IEnumerable\<T\>\>\&) | Constructor de copia. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtiene la implementación del iterador const begin para el contenedor actual. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtiene la implementación del iterador begin para el contenedor actual. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtiene la implementación del end const iterator para el contenedor actual. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtiene la implementación del end iterator para el contenedor actual. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [IEnumerablePtr](./ienumerableptr/) | Contenedor de elementos del mismo tipo. |
| [IEnumeratorPtr](./ienumeratorptr/) | [Enumerator](./enumerator/) tipo. |
| [queue_t](./queue_t/) | Información RTTI. |
| [ValueType](./valuetype/) | Este tipo. |
## Observaciones


[Queue](./) container wrapping STL list. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.


```cpp
#include <system/collections/queue.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

void PrintItems(const SmartPtr<IEnumerable<int>> &queue)
{
  for (const int item: queue)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Crea la instancia de la clase Queue.
  auto queue = MakeObject<Queue<int>>();

  // Llena la cola.
  queue->Enqueue(1);
  queue->Enqueue(2);
  queue->Enqueue(3);

  // Imprime el primer elemento de la cola. El método Peek no elimina un elemento de la cola.
  std::cout << queue->Peek() << std::endl;
  // Imprime los elementos de la cola.
  PrintItems(queue);

  // Imprime el primer elemento de la cola. El método Dequeue elimina un elemento de la cola.
  std::cout << queue->Dequeue() << std::endl;
  // Imprime los elementos de la cola.
  PrintItems(queue);

  return 0;
}
/*
This code example produces the following output:
1
1 2 3
1
2 3
*/
```

## Ver también

* Class [IEnumerable](../ienumerable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
