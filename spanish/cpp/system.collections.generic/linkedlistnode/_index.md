---
title: "Clase System::Collections::Generic::LinkedListNode"
linktitle: "LinkedListNode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::Generic::LinkedListNode. Nodo de lista enlazada. Implementa un contenedor sobre un iterador de std::list que está envuelto en una lista enlazada. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 3200
url: /es/cpp/system.collections.generic/linkedlistnode/
---
## LinkedListNode class


Nodo de lista enlazada. Implementa un envoltorio sobre un iterador de std::list que está envuelto en una lista enlazada. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
template<typename T>class LinkedListNode : public System::Object
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de valor almacenado. |
## Métodos

| Método | Descripción |
| --- | --- |
| [get_List](./get_list/)() const | Obtiene la lista contenedora. |
| [get_Next](./get_next/)() const | Obtiene el nodo siguiente. |
| [get_Previous](./get_previous/)() const | Obtiene el nodo anterior. |
| [get_Value](./get_value/)() const | Obtiene el valor almacenado. |
| [LinkedListNode](./linkedlistnode/)(const T\&) | Constructor. |
| [set_Value](./set_value/)(const T\&) | Establece el valor almacenado. |

## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
