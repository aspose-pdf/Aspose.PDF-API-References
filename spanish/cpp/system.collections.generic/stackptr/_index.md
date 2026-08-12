---
title: "System::Collections::Generic::StackPtr clase"
linktitle: "StackPtr"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Collections::Generic::StackPtr clase. Puntero de pila. Este tipo es un puntero para gestionar la eliminación del objeto''s. Debe asignarse en la pila y pasarse a funciones ya sea por valor o por referencia constante en C++."
type: docs
weight: 4700
url: /es/cpp/system.collections.generic/stackptr/
---
## StackPtr class


[Stack](../stack/) pointer. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T>class StackPtr : public System::SmartPtr<T0>
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de elemento. |
## Métodos

| Método | Descripción |
| --- | --- |
| [StackPtr](./stackptr/)() | Construye un puntero nulo. |
| [StackPtr](./stackptr/)(const SharedPtr\<Stack\<T\>\>\&) | Construye un puntero que referencia una pila específica. |

## Ver también

* Class [SmartPtr](../../system/smartptr/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
