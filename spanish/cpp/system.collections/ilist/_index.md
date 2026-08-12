---
title: "System::Collections::IList class"
linktitle: "IList"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Collections::IList class. IList representa una colección no genérica de objetos que pueden accederse individualmente por índice en C++."
type: docs
weight: 1000
url: /es/cpp/system.collections/ilist/
---
## IList class


[IList](./) Represents a non-generic collection of objects that can be individually accessed by index.

```cpp
class IList : public virtual System::Collections::ICollection
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Add](./add/)(SharedPtr\<System::Object\>) | Agrega un elemento al final de la lista. |
| virtual [Clear](./clear/)() | Elimina todos los elementos de la lista. |
| virtual [Contains](./contains/)(SharedPtr\<System::Object\>) const | Comprueba si el elemento está en la lista. |
| virtual [get_IsFixedSize](./get_isfixedsize/)() const | Obtiene un valor que indica si la lista tiene un tamaño fijo. |
| virtual [idx_get](./idx_get/)(int, int) const | Información RTTI. |
| virtual [IndexOf](./indexof/)(SharedPtr\<System::Object\>) const | Obtiene el primer índice del elemento especificado. |
| virtual [Insert](./insert/)(int, SharedPtr\<System::Object\>) | Inserta el elemento en la lista en el índice especificado. |
| virtual [Remove](./remove/)(SharedPtr\<System::Object\>) | Elimina la primera instancia del elemento especificado de la lista. |
| virtual [RemoveAt](./removeat/)(int) | Elimina el elemento de la lista en el índice especificado. |
## Ver también

* Class [ICollection](../icollection/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
