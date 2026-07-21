---
title: "System::Collections::Generic::ListPtr clase"
linktitle: "ListPtr"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Collections::Generic::ListPtr clase. Puntero de lista con operadores de acceso. Este tipo es un puntero para gestionar la eliminación del objeto''s. Debe asignarse en la pila y pasarse a funciones ya sea por valor o por referencia constante en C++."
type: docs
weight: 3500
url: /es/cpp/system.collections.generic/listptr/
---
## ListPtr class


[List](../list/) pointer with access operators. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T>class ListPtr : public System::SmartPtr<T0>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ListPtr](./listptr/)(std::nullptr_t) | Inicializa un puntero nulo. |
| [ListPtr](./listptr/)(const SharedPtr\<List\<T\>\>\&) | Inicializa un puntero a la lista especificada. |
| [operator==](./operator==/)(std::nullptr_t) const | Comprueba si el puntero [List](../list/) es nulo. |
| [operator[]](./operator[]/)(int) | Accesor. |
| [operator[]](./operator[]/)(int) const | Accesor. |
## Ver también

* Class [SmartPtr](../../system/smartptr/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
