---
title: "Clase System::Collections::CollectionBase"
linktitle: "CollectionBase"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::CollectionBase. Proporciona una clase base abstracta para una colección fuertemente tipada en C++."
type: docs
weight: 300
url: /es/cpp/system.collections/collectionbase/
---
## CollectionBase class


Proporciona una clase base abstracta para una colección fuertemente tipada.

```cpp
template<typename T>class CollectionBase : public virtual System::Collections::Generic::IEnumerable<T>
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de elementos de la colección |
## Nested classes

* Class [ListImpl](./listimpl/)
## Métodos

| Método | Descripción |
| --- | --- |
| [Clear](./clear/)() | Elimina todos los objetos de la instancia de la colección. Este método no puede ser sobrescrito. |
| [get_Capacity](./get_capacity/)() | Devuelve el número de elementos que la colección puede contener. |
| [get_Count](./get_count/)() | Devuelve el número de elementos contenidos en la instancia de la colección. Este método no puede ser sobrescrito. |
| [GetEnumerator](./getenumerator/)() override | Devuelve un enumerador que recorre la instancia de la colección. |
| [RemoveAt](./removeat/)(int32_t) | Elimina el elemento en el índice especificado de la instancia de la colección. Este método no es sobrescribible. |
| [set_Capacity](./set_capacity/)(int32_t) | Establece el número de elementos que la colección puede contener. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Establece el n‑ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |

## Ver también

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
