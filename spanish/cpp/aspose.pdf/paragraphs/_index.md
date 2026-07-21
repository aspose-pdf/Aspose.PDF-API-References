---
title: "Aspose::Pdf::Paragraphs class"
linktitle: "Párrafos"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Paragraphs. Esta clase representa una colección de párrafos en C++."
type: docs
weight: 14600
url: /es/cpp/aspose.pdf/paragraphs/
---
## Paragraphs class


Esta clase representa una colección de párrafos.

```cpp
class Paragraphs : public System::Collections::Generic::IEnumerable<System::SharedPtr<BaseParagraph>>,
                   public System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<BaseParagraph\>\&) | Agregar párrafo a la colección. |
| [begin](./begin/)() | Obtiene un iterador que apunta al primer elemento (si lo hay) de la colección. |
| [begin](./begin/)() const | Obtiene un iterador que apunta al primer elemento (si lo hay) de la instancia calificada como const de la colección. |
| [cbegin](./cbegin/)() const | Obtiene un iterador que apunta al primer elemento calificado como const (si lo hay) de la colección. |
| [cend](./cend/)() const | Obtiene un iterador que apunta justo después del último elemento calificado como const (si lo hay) de la colección. |
| [Clear](./clear/)() | Borrar párrafos. |
| [Clone](./clone/)() override | Clona un nuevo objeto [Clone](./clone/). |
| [cpp_switch_last_paragraph_to_week](./cpp_switch_last_paragraph_to_week/)() |  |
| [end](./end/)() | Obtiene un iterador que apunta justo después del último elemento (si lo hay) de la colección. |
| [end](./end/)() const | Obtiene un iterador que apunta justo después del último elemento (si lo hay) de la instancia calificada como const de la colección. |
| [get_Count](./get_count/)() | Obtener el recuento de párrafos. |
| [GetEnumerator](./getenumerator/)() override | Obtiene el enumerador. |
| [GetRange](./getrange/)(int32_t, int32_t) | Eliminar rango de párrafos. |
| [idx_get](./idx_get/)(int32_t) | Obtiene el párrafo desde o hacia la colección. |
| [idx_set](./idx_set/)(int32_t, const System::SharedPtr\<BaseParagraph\>\&) | Establece el párrafo desde o hacia la colección. |
| [Insert](./insert/)(int32_t, const System::SharedPtr\<BaseParagraph\>\&) | Insertar párrafo en la colección. |
| [InsertRange](./insertrange/)(int32_t, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<BaseParagraph\>\>\>\&) | Inserta los elementos de una colección en la lista en el índice especificado. |
| [Paragraphs](./paragraphs/)() |  |
| [Remove](./remove/)(const System::SharedPtr\<BaseParagraph\>\&) | Eliminar párrafo de la colección. |
| [RemoveRange](./removerange/)(int32_t, int32_t) | Eliminar rango de párrafos. |
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
* Class [ICloneable](../../system/icloneable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
