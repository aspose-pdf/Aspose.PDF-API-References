---
title: "Aspose::Pdf::Structure::ElementCollection clase"
linktitle: "ElementCollection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Structure::ElementCollection clase. Colección de elementos base de la estructura lógica en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf.structure/elementcollection/
---
## ElementCollection class


[Collection](../../aspose.pdf/collection/) of base logical structure elements.

```cpp
class ElementCollection : public System::Collections::Generic::IEnumerable<System::SharedPtr<Element>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [begin](./begin/)() | Obtiene un iterador que apunta al primer elemento (si lo hay) de la colección. |
| [begin](./begin/)() const | Obtiene un iterador que apunta al primer elemento (si lo hay) de la instancia calificada como const de la colección. |
| [cbegin](./cbegin/)() const | Obtiene un iterador que apunta al primer elemento calificado como const (si lo hay) de la colección. |
| [cend](./cend/)() const | Obtiene un iterador que apunta justo después del último elemento calificado como const (si lo hay) de la colección. |
| [end](./end/)() | Obtiene un iterador que apunta justo después del último elemento (si lo hay) de la colección. |
| [end](./end/)() const | Obtiene un iterador que apunta justo después del último elemento (si lo hay) de la instancia calificada como const de la colección. |
| [get_Count](./get_count/)() | Recuento de elementos. |
| [GetEnumerator](./getenumerator/)() override | Devuelve un enumerador que recorre la colección. |
| [idx_get](./idx_get/)(int32_t) | Obtiene [Element](../element/) por índice. |
| [Remove](./remove/)(const System::SharedPtr\<Element\>\&) | Elimina el elemento de la colección. |
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

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [Aspose::Pdf::Structure](../)
* Library [Aspose.PDF for C++](../../)
