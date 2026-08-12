---
title: "Clase Aspose::Pdf::Cells"
linktitle: "Cells"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Cells. Representa una colección de celdas de una fila en C++."
type: docs
weight: 1800
url: /es/cpp/aspose.pdf/cells/
---
## Cells class


Representa una colección de celdas de la fila.

```cpp
class Cells : public System::Collections::Generic::IEnumerable<System::SharedPtr<Cell>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)() | Agregar celda a la colección. |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<Text::TextState\>\&) | Agregar celda a la colección. |
| [Add](./add/)(const System::String\&) | Agregar celda a la colección. |
| [Add](./add/)(const System::SharedPtr\<Text::TextFragment\>\&) | Agregar celda a la colección. |
| [Add](./add/)(const System::SharedPtr\<Cell\>\&) | Agregar celda a la colección. |
| [begin](./begin/)() | Obtiene un iterador que apunta al primer elemento (si lo hay) de la colección. |
| [begin](./begin/)() const | Obtiene un iterador que apunta al primer elemento (si lo hay) de la instancia calificada como const de la colección. |
| [cbegin](./cbegin/)() const | Obtiene un iterador que apunta al primer elemento calificado como const (si lo hay) de la colección. |
| [Cells](./cells/)() |  |
| [cend](./cend/)() const | Obtiene un iterador que apunta justo después del último elemento calificado como const (si lo hay) de la colección. |
| [Dispose](./dispose/)() | Método Dispose. |
| [end](./end/)() | Obtiene un iterador que apunta justo después del último elemento (si lo hay) de la colección. |
| [end](./end/)() const | Obtiene un iterador que apunta justo después del último elemento (si lo hay) de la instancia calificada como const de la colección. |
| [get_Count](./get_count/)() | El recuento de elementos. |
| [GetEnumerator](./getenumerator/)() override | Obtiene el enumerador de la colección. |
| [idx_get](./idx_get/)(int32_t) | Obtiene celdas. |
| [idx_set](./idx_set/)(int32_t, const System::SharedPtr\<Cell\>\&) | Establece celdas. |
| [Insert](./insert/)(int32_t, const System::SharedPtr\<Cell\>\&) | Insertar celda en la colección. |
| [Remove](./remove/)(const System::SharedPtr\<Cell\>\&) | Eliminar conjunto de celdas de la colección. |
| [RemoveRange](./removerange/)(int32_t, int32_t) | Eliminar conjunto de celdas de la colección. |
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
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
