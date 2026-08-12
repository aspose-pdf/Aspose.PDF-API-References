---
title: "Aspose::Pdf::LogicalStructure::StructureElement clase"
linktitle: "StructureElement"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::LogicalStructure::StructureElement clase. Representa una clase base para los elementos de estructura en la estructura lógica en C++."
type: docs
weight: 5500
url: /es/cpp/aspose.pdf.logicalstructure/structureelement/
---
## StructureElement class


Representa una clase base para los elementos de estructura en la estructura lógica.

```cpp
class StructureElement : public Aspose::Pdf::LogicalStructure::Element
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ChangeParentElement](./changeparentelement/)(const System::SharedPtr\<StructureElement\>\&, bool) | Cambiar el elemento padre del elemento de estructura actual. |
| [ClearId](./clearid/)() | Borrar ID del elemento de estructura. |
| [GenerateId](./generateid/)() | Generar ID para el elemento de estructura. |
| [get_ActualText](./get_actualtext/)() | Obtiene el texto real del elemento de estructura. |
| [get_AlternativeText](./get_alternativetext/)() | Obtiene el texto alternativo del elemento de estructura. |
| [get_Attributes](./get_attributes/)() const | Obtiene el objeto [T:/Aspose::Pdf::LogicalStructure::StructureAttributeCollection](../). |
| [get_DefaultAttributeOwner](./get_defaultattributeowner/)() const | Obtiene el objeto [T:/Aspose::Pdf::LogicalStructure::AttributeOwnerStandard](../). |
| [get_ExpansionText](./get_expansiontext/)() | Obtiene el texto de expansión del elemento de estructura. |
| [get_ID](./get_id/)() | Obtiene el ID del elemento de estructura. |
| [get_Language](./get_language/)() | Obtiene el idioma del elemento de estructura. |
| [get_Page](./get_page/)() | Obtiene la página en la que se renderizarán algunos o todos los elementos hijos. |
| [get_StructureType](./get_structuretype/)() const | Obtiene el tipo del elemento de estructura. |
| [get_Title](./get_title/)() | Obtiene el título del elemento de estructura. |
| [Remove](./remove/)() | Elimina: un elemento de la estructura, una referencia a él del objeto padre, referencias a él de los objetos hijos, el objeto correspondiente del documento. |
| [RemoveAndMoveItsChildObjectsToItsParent](./removeandmoveitschildobjectstoitsparent/)(bool) | Elimina un elemento de la estructura, una referencia a él del objeto padre, referencias a él de los objetos hijos y el objeto correspondiente del documento. Inserta los objetos hijos del elemento eliminado en la colección de objetos hijos del padre anterior, comenzando en el índice del elemento eliminado. |
| [set_ActualText](./set_actualtext/)(const System::String\&) | Establece el texto real del elemento de estructura. |
| [set_AlternativeText](./set_alternativetext/)(const System::String\&) | Establece el texto alternativo del elemento de estructura. |
| [set_ExpansionText](./set_expansiontext/)(const System::String\&) | Establece el texto de expansión del elemento de estructura. |
| [set_Language](./set_language/)(const System::String\&) | Establece el idioma del elemento de estructura. |
| [set_Title](./set_title/)(const System::String\&) | Establece el título del elemento de estructura. |
| [SetId](./setid/)(const System::String\&) | Establece el ID del elemento de estructura. |
| [SetTag](./settag/)(const System::String\&) | Establece la etiqueta personalizada del elemento de estructura. |
| [Tag](./tag/)(System::SharedPtr\<Operators::BDC\>) override | Vincular un elemento de estructura al operador BDC del flujo de contenido. |
| [Tag](./tag/)(System::SharedPtr\<XForm\>) override | Vincular un elemento de estructura al flujo de contenido [XForm](../../aspose.pdf/xform/). |
| [Tag](./tag/)(System::SharedPtr\<XImage\>) override | Vincular un elemento de estructura al [XImage](../../aspose.pdf/ximage/). |
| [Tag](./tag/)(System::SharedPtr\<Artifact\>) override | Vincular un elemento de estructura al [Artifact](../../aspose.pdf/artifact/). |
| [Tag](./tag/)(System::SharedPtr\<Annotations::Annotation\>) override | Vincular un elemento de estructura a la anotación. |
| [ToString](./tostring/)() const override | Devuelve una cadena que representa el objeto actual. |
## Ver también

* Class [Element](../element/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
