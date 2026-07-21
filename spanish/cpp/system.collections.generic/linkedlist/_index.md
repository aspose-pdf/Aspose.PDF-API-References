---
title: "System::Collections::Generic::LinkedList clase"
linktitle: "LinkedList"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Collections::Generic::LinkedList clase. Declaración adelantada de LinkedList en C++."
type: docs
weight: 3100
url: /es/cpp/system.collections.generic/linkedlist/
---
## LinkedList class


[LinkedList](./) forward declaration.

```cpp
template<typename T>class LinkedList : public virtual System::Object,
                                       public System::Collections::Generic::ICollection<T>,
                                       private System::Collections::Invalidatable
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de valor contenido. |
## Nested classes

* Class [Enumerator](./enumerator/)
## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const T\&) override | Agrega **element** al final de la lista. |
| [AddAfter](./addafter/)(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) | Agrega **element** después de **node** de la lista. |
| [AddAfter](./addafter/)(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) | Agrega **newNode** después de **node** de la lista. |
| [AddBefore](./addbefore/)(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) | Agrega **element** antes de **node** de la lista. |
| [AddBefore](./addbefore/)(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) | Agrega **newNode** antes de **node** de la lista. |
| [AddFirst](./addfirst/)(const T\&) | Agrega **element** al principio de la lista. |
| [AddFirst](./addfirst/)(const SharedPtr\<LinkedListNode\<T\>\>\&) | Agrega **newNode** al principio de la lista. |
| [AddLast](./addlast/)(const T\&) | Agrega **element** al final de la lista. |
| [AddLast](./addlast/)(const SharedPtr\<LinkedListNode\<T\>\>\&) | Agrega **newNode** al final de la lista. |
| [begin](./begin/)() | Obtiene el iterador al primer elemento de la colección. |
| [begin](./begin/)() const | Obtiene un iterador al primer elemento de la colección calificada como const. |
| [cbegin](./cbegin/)() const | Obtiene un iterador al primer elemento calificado como const de la colección. |
| [cend](./cend/)() const | Obtiene un iterador para un elemento calificado como const que no existe detrás del final de la colección. |
| [Clear](./clear/)() override | Elimina todos los elementos de la lista. |
| [Contains](./contains/)(const T\&) const override | Comprueba si **element** está presente en la lista. |
| [CopyTo](./copyto/)(ArrayPtr\<T\>, int) override | Copia los datos del contenedor en los elementos existentes del arreglo. |
| [crbegin](./crbegin/)() const | Obtiene un iterador inverso al último elemento calificado como const de la colección (el primero en reversa). |
| [crend](./crend/)() const | Obtiene un iterador inverso para un elemento calificado como const que no existe antes del inicio de la colección. |
| [end](./end/)() | Obtiene un iterador para un elemento que no existe detrás del final de la colección. |
| [end](./end/)() const | Obtiene un iterador para un elemento que no existe detrás del final de la colección calificada como const. |
| [Find](./find/)(const T\&) const | Realiza una búsqueda en dirección hacia adelante de un **element** en la lista. |
| [FindLast](./findlast/)(const T\&) const | Realiza una búsqueda en dirección inversa de un **element** en la lista. |
| [get_Count](./get_count/)() const override | Obtiene el número de elementos de la lista. |
| [get_First](./get_first/)() const | Obtiene un puntero al primer elemento de la lista. |
| [get_Last](./get_last/)() const | Obtiene un puntero al último elemento de la lista. |
| [GetEnumerator](./getenumerator/)() override | Obtiene un enumerador para iterar a través del [LinkedList](./) actual. |
| [LinkedList](./linkedlist/)() | Crea un [LinkedList](./) vacío. |
| [LinkedList](./linkedlist/)(const SharedPtr\<IEnumerable\<T\>\>\&) | Constructor de copia. |
| [rbegin](./rbegin/)() | Obtiene un iterador inverso al último elemento de la colección (el primero en reversa). |
| [rbegin](./rbegin/)() const | Obtiene un iterador inverso al último elemento de la colección calificada como const (el primero en reversa). |
| [Remove](./remove/)(const T\&) override | Elimina la primera aparición del **element** especificado de la lista. |
| [Remove](./remove/)(const SharedPtr\<LinkedListNode\<T\>\>\&) | Elimina el nodo de la lista. |
| [RemoveFirst](./removefirst/)() | Elimina el primer nodo de la lista. |
| [RemoveLast](./removelast/)() | Elimina el último nodo de la lista. |
| [rend](./rend/)() | Obtiene un iterador inverso para un elemento inexistente antes del inicio de la colección. |
| [rend](./rend/)() const | Obtiene un iterador inverso para un elemento inexistente antes del inicio de la colección calificada como const. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtiene la implementación del iterador const begin para el contenedor actual. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtiene la implementación del iterador begin para el contenedor actual. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtiene la implementación del end const iterator para el contenedor actual. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtiene la implementación del end iterator para el contenedor actual. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [const_iterator](./const_iterator/) | Tipo de iterador const. |
| [const_reverse_iterator](./const_reverse_iterator/) | Tipo de iterador inverso const. |
| [iterator](./iterator/) | Tipo de iterador. |
| [list_t](./list_t/) | Tipo de datos subyacente. |
| [reverse_iterator](./reverse_iterator/) | Tipo de iterador inverso. |
## Observaciones


Contenedor de lista enlazada. Implementa un contenedor sobre std::list. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.


```cpp
#include <system/collections/linkedlist.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Cree una instancia de la clase LinkedList.
  auto list = MakeObject<LinkedList<int>>();

  // Llena la lista enlazada.
  list->AddFirst(1);
  list->AddLast(30);
  list->AddAfter(list->get_First(), 15);
  list->AddBefore(list->get_Last(), 25);

  // Imprime los elementos de la lista enlazada.
  for (const auto item: list)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
This code example produces the following output:
1 15 25 30
*/
```

## Ver también

* Class [Object](../../system/object/)
* Class [ICollection](../icollection/)
* Class [Invalidatable](../../system.collections/invalidatable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
