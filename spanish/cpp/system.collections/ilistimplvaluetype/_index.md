---
title: "Clase System::Collections::IListImplValueType"
linktitle: "IListImplValueType"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::IListImplValueType. Stub que implementa la interfaz System::Collections::IList en el objeto System::Collections::Generic::List. Implementación para tipos de valor en C++."
type: docs
weight: 1200
url: /es/cpp/system.collections/ilistimplvaluetype/
---
## IListImplValueType class


Stub que implementa la interfaz [System::Collections::IList](../ilist/) en el objeto [System::Collections::Generic::List](../../system.collections.generic/list/). Implementación para tipos de valor.

```cpp
template<typename T>class IListImplValueType : public virtual System::Collections::IList
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(SharedPtr\<System::Object\>) override | Agrega un elemento al final de la lista. |
| [Clear](./clear/)() override | Elimina todos los elementos. |
| [Contains](./contains/)(SharedPtr\<System::Object\>) const override | Comprueba si el elemento está presente en la lista. |
| [get_Count](./get_count/)() const override | Implementación del método [ICollection.get_Count()](../icollection/get_count/) Obtiene el número de elementos en la colección. |
| [GetEnumerator](./getenumerator/)() override | Implementación de [IEnumerable.GetEnumerator()](../ienumerable/getenumerator/) Devuelve un enumerador que recorre una colección. |
| [idx_get](./idx_get/)(int, int) const override | Obtiene el elemento en el índice especificado. |
| [IListImplValueType](./ilistimplvaluetype/)(System::SharedPtr\<System::Collections::Generic::IList\<T\>\>) | Crea una nueva instancia de objeto. |
| [IndexOf](./indexof/)(System::SharedPtr\<System::Object\>) const override | Obtiene el índice de la primera aparición del elemento en el contenedor. |
| [Insert](./insert/)(int, System::SharedPtr\<System::Object\>) override | Inserta el elemento en la posición especificada, desplazando los demás elementos. |
| [Remove](./remove/)(SharedPtr\<System::Object\>) override | Elimina la primera instancia del elemento específico de la lista. |
| [RemoveAt](./removeat/)(int) override | Elimina el elemento en la posición especificada. |
## Ver también

* Class [IList](../ilist/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
