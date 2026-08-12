---
title: "System::DynamicWeakPtr clase"
linktitle: "DynamicWeakPtr"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::DynamicWeakPtr class. Clase de puntero inteligente que rastrea los modos de puntero de los argumentos de plantilla del objeto almacenado y los actualiza después de cada asignación. Este tipo es un puntero para gestionar la eliminación de otro objeto. Debe ser asignado en la pila y pasado a funciones ya sea por valor o por referencia constante en C++."
type: docs
weight: 2300
url: /es/cpp/system/dynamicweakptr/
---
## DynamicWeakPtr class


Clase de puntero inteligente que rastrea los modos de puntero de los argumentos de plantilla del objeto almacenado y los actualiza después de cada asignación. Este tipo es un puntero para gestionar la eliminación de otro objeto. Debe asignarse en la pila y pasarse a funciones ya sea por valor o por referencia constante.

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```


| Parámetro | Descripción |
| --- | --- |
| Pointee | tipo. |
| trunkMode | Modo del puntero inteligente en sí, compartido o débil. |
| weakLeafs | Índices de los argumentos de plantilla del tipo almacenado que deben establecerse en modo puntero débil. |
## Nested classes

* Class [Reference](./reference/)
## Métodos

| Método | Descripción |
| --- | --- |
| [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | Crea un puntero inteligente nulo. |
| [DynamicWeakPtr](./dynamicweakptr/)(Pointee_ *) | Crea un puntero inteligente que apunta al objeto dado. |
| [DynamicWeakPtr](./dynamicweakptr/)(const SmartPtr_\&) | Construye por copia el puntero inteligente. |
| [DynamicWeakPtr](./dynamicweakptr/)(const SmartPtr\<Q\>\&) | Construye por copia el puntero inteligente. |
| [DynamicWeakPtr](./dynamicweakptr/)(const DynamicWeakPtr_\&) | Construye por copia el puntero inteligente. |
| [DynamicWeakPtr](./dynamicweakptr/)(SmartPtr_\&&) | Construye por movimiento el puntero inteligente. |
| [operator=](./operator=/)(SmartPtr_\&&) | Asigna por movimiento el puntero inteligente. |
| [operator=](./operator=/)(const SmartPtr_\&) | Asigna por copia el puntero inteligente. |
| [operator=](./operator=/)(const SmartPtr\<Q\>\&) | Asigna por copia el puntero inteligente. |
| [operator=](./operator=/)(typename SmartPtr_::Pointee_ *) | Asigna el puntero inteligente. |
| [operator=](./operator=/)(std::nullptr_t) | Establece el puntero inteligente a nulo. |
| [operator==](./operator==/)(std::nullptr_t) const | Comprueba si el puntero inteligente es null. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [DynamicWeakPtr_](./dynamicweakptr_/) | Alias del tipo propio. |
| [Pointee_](./pointee_/) | Tipo apuntado. |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) alias de clase base. |

## Ver también

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
