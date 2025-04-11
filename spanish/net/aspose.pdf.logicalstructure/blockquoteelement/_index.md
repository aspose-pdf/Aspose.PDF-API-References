---
title: Class BlockQuoteElement
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.LogicalStructure.BlockQuoteElement. Representa el elemento de estructura BlockQuote en la estructura lógica
type: docs
weight: 6270
url: /es/net/aspose.pdf.logicalstructure/blockquoteelement/
---
## Clase BlockQuoteElement

Representa el elemento de estructura BlockQuote en la estructura lógica.

```csharp
public sealed class BlockQuoteElement : GroupingElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Obtiene o establece el texto real para el elemento de estructura. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Obtiene o establece el texto alternativo para el elemento de estructura. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Obtiene el objeto StructureAttributeCollection. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Obtiene la colección de hijos de objetos Element. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Obtiene el objeto AttributeOwnerStandard. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Obtiene o establece el texto de expansión para el elemento de estructura. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Obtiene el ID para el elemento de estructura. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Obtiene o establece el idioma para el elemento de estructura. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Obtiene la página en la que se renderizarán algunos o todos los elementos hijos. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Obtiene el elemento padre. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Obtiene el tipo de elemento de estructura. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Obtiene o establece el título para el elemento de estructura. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Agrega un Element a la colección de hijos. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Cambia el elemento padre para el elemento de estructura actual |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Limpia todos los hijos. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Limpia el ID para el elemento de estructura. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Encuentra elementos de un tipo dado |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Genera un ID para el elemento de estructura. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Inserta un Element en la colección de hijos en el índice especificado. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Elimina: un elemento de la estructura, una referencia a él del objeto padre, referencias a él de objetos hijos, el objeto correspondiente del documento. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Elimina un elemento de la estructura, una referencia a él del objeto padre, referencias a él de objetos hijos, y el objeto correspondiente del documento. Inserta los objetos hijos del objeto eliminado en la colección de objetos hijos de su antiguo padre comenzando en el índice del objeto eliminado. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Elimina el hijo en. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Establece el ID para el elemento de estructura. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Establece una etiqueta personalizada para el elemento de estructura. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Vincula un elemento de estructura a la Anotación. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Vincula un elemento de estructura al Artefacto. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Vincula un elemento de estructura al operador BDC del flujo de contenido. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Vincula un elemento de estructura al flujo de contenido XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Vincula un elemento de estructura a la XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Devuelve una cadena que representa el objeto actual. |

### Ver También

* clase [GroupingElement](../groupingelement/)
* espacio de nombres [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* ensamblaje [Aspose.PDF](../../)