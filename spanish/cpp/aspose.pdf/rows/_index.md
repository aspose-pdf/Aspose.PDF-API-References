---
title: "Clase Aspose::Pdf::Rows"
linktitle: "Rows"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Rows. Representa una colección de filas de tabla en C++."
type: docs
weight: 16900
url: /es/cpp/aspose.pdf/rows/
---
## Rows class


Representa una colección de filas de la tabla.

```cpp
class Rows : public System::Collections::Generic::IEnumerable<System::SharedPtr<Row>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)() | Agregar fila a la colección. |
| [Add](./add/)(const System::SharedPtr\<Row\>\&) | Agregar fila a la colección. |
| [begin](./begin/)() | Obtiene un iterador que apunta al primer elemento (si lo hay) de la colección. |
| [begin](./begin/)() const | Obtiene un iterador que apunta al primer elemento (si lo hay) de la instancia calificada como const de la colección. |
| [cbegin](./cbegin/)() const | Obtiene un iterador que apunta al primer elemento calificado como const (si lo hay) de la colección. |
| [cend](./cend/)() const | Obtiene un iterador que apunta justo después del último elemento calificado como const (si lo hay) de la colección. |
| [Dispose](./dispose/)() | Liberar. |
| [end](./end/)() | Obtiene un iterador que apunta justo después del último elemento (si lo hay) de la colección. |
| [end](./end/)() const | Obtiene un iterador que apunta justo después del último elemento (si lo hay) de la instancia calificada como const de la colección. |
| [get_Count](./get_count/)() | El recuento de elementos. |
| [GetEnumerator](./getenumerator/)() override | Obtiene el enumerador de la colección. |
| [idx_get](./idx_get/)(int32_t) | Obtiene fila. |
| [idx_set](./idx_set/)(int32_t, const System::SharedPtr\<Row\>\&) | Establece la fila. |
| [IndexOf](./indexof/)(const System::SharedPtr\<Row\>\&) | Devuelve el índice de la fila en la colección. |
| [Remove](./remove/)(const System::SharedPtr\<Row\>\&) | Elimina la fila de la colección. |
| [RemoveAt](./removeat/)(int32_t) | Elimina la fila en la posición de la colección. |
| [RemoveRange](./removerange/)(int32_t, int32_t) | Elimina el conjunto de filas de la colección. |
| [Rows](./rows/)() |  |
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
