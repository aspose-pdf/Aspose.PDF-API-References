---
title: "Aspose::Pdf::BoundsCheckableList clase"
linktitle: "BoundsCheckableList"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::BoundsCheckableList clase. Representa BoundsCheckableList - envoltorio alrededor de System.Collections.Generic.List en C++."
type: docs
weight: 1400
url: /es/cpp/aspose.pdf/boundscheckablelist/
---
## BoundsCheckableList class


Representa [BoundsCheckableList](./) - envoltorio alrededor de [System.Collections.Generic.List](../../system.collections.generic/list/).

```cpp
template<typename T>class BoundsCheckableList : public System::Collections::Generic::IList<T>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const T\&) override | Agrega un objeto al final de [System.Collections.Generic.List](../../system.collections.generic/list/) dependiendo del parámetro "boundsCheckMode". |
| [begin](./begin/)() | Obtiene un iterador que apunta al primer elemento (si lo hay) de la colección. |
| [begin](./begin/)() const | Obtiene un iterador que apunta al primer elemento (si lo hay) de la instancia calificada como const de la colección. |
| [BoundsCheckableList](./boundscheckablelist/)() | Inicializa una nueva instancia de la clase [BoundsCheckableList](./). |
| [BoundsCheckableList](./boundscheckablelist/)(BoundsCheckMode, double, double) | Inicializa una nueva instancia de la clase [BoundsCheckableList](./). |
| [cbegin](./cbegin/)() const | Obtiene un iterador que apunta al primer elemento calificado como const (si lo hay) de la colección. |
| [cend](./cend/)() const | Obtiene un iterador que apunta justo después del último elemento calificado como const (si lo hay) de la colección. |
| [Clear](./clear/)() override | Elimina todos los elementos de [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [Contains](./contains/)(const T\&) const override | Determina si un elemento está en la [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [CopyTo](./copyto/)(System::ArrayPtr\<T\>, int32_t) override | Copia la [System.Collections.Generic.List](../../system.collections.generic/list/) completa a una matriz unidimensional compatible, comenzando en el índice especificado del arreglo de destino. |
| [end](./end/)() | Obtiene un iterador que apunta justo después del último elemento (si lo hay) de la colección. |
| [end](./end/)() const | Obtiene un iterador que apunta justo después del último elemento (si lo hay) de la instancia calificada como const de la colección. |
| [get_Count](./get_count/)() const override | Obtiene el número de elementos contenidos en la [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [get_IsReadOnly](./get_isreadonly/)() const override | Obtiene el valor que indica si la colección es de solo lectura. |
| [GetEnumerator](./getenumerator/)() override | Devuelve un enumerador que recorre la [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [idx_get](./idx_get/)(int32_t) const override | Obtiene el párrafo desde o hacia la colección. |
| [idx_set](./idx_set/)(int32_t, T) override | Establece el párrafo desde o hacia la colección. |
| [IndexOf](./indexof/)(const T\&) const override | Busca el objeto especificado y devuelve el índice basado en cero de la primera aparición dentro de toda la [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [Insert](./insert/)(int32_t, const T\&) override | Inserta un elemento en la [System.Collections.Generic.List](../../system.collections.generic/list/) en el índice especificado. |
| [Remove](./remove/)(const T\&) override | Elimina la primera aparición de un objeto específico de la [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [RemoveAt](./removeat/)(int32_t) override | Elimina el elemento en el índice especificado de la [System.Collections.Generic.List](../../system.collections.generic/list/). |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Establece el n‑ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
| [UpdateBoundsCheckMode](./updateboundscheckmode/)(BoundsCheckMode, double, double) | Actualiza el parámetro boundsCheckMode para la colección inicializada. |
| [UpdateBoundsCheckMode](./updateboundscheckmode/)(BoundsCheckMode) | Actualiza el parámetro boundsCheckMode para la colección inicializada. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtiene el iterador que apunta al primer elemento (si lo hay) de la instancia calificada como const de la colección. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtiene un iterador que apunta al primer elemento (si lo hay) de la colección. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtiene el iterador que apunta justo después del último elemento (si lo hay) de la instancia calificada como const de la colección. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtiene un iterador que apunta justo después del último elemento (si lo hay) de la colección. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [const_iterator](./const_iterator/) | Tipo de iterador const. |
| [iterator](./iterator/) | Tipo de iterador. |
| [iterator_holder_type](./iterator_holder_type/) | Un tipo de colección cuyo tipo de iterador se usa como tipo de iterador en la colección actual. |
| [virtualized_iterator](./virtualized_iterator/) | Tipo virtualizado. |
| [virtualized_iterator_element](./virtualized_iterator_element/) | Tipo de elemento virtualizado. |
## Ver también

* Class [IList](../../system.collections.generic/ilist/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
