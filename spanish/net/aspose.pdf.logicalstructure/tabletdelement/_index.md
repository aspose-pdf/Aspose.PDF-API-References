---
title: Class TableTDElement
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.LogicalStructure.TableTDElement. Representa el elemento de estructura TD en la estructura lógica de la tabla
type: docs
weight: 6810
url: /es/net/aspose.pdf.logicalstructure/tabletdelement/
---
## Clase TableTDElement

Representa el elemento de estructura TD en la estructura lógica de la tabla.

```csharp
public sealed class TableTDElement : TableCellElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Obtiene o establece el texto real para el elemento de estructura. |
| [Alignment](../../aspose.pdf.logicalstructure/tablecellelement/alignment/) { get; set; } | Obtiene o establece la alineación de la celda. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Obtiene o establece el texto alternativo para el elemento de estructura. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Obtiene el objeto StructureAttributeCollection. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tablecellelement/backgroundcolor/) { get; set; } | Obtiene o establece el color de fondo de la celda. |
| [Border](../../aspose.pdf.logicalstructure/tablecellelement/border/) { get; set; } | Obtiene o establece el borde de la celda. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Obtiene la colección de hijos de objetos Element. |
| [ColSpan](../../aspose.pdf.logicalstructure/tablecellelement/colspan/) { get; set; } | Obtiene o establece el alcance de la columna. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Obtiene el objeto AttributeOwnerStandard. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tablecellelement/defaultcelltextstate/) { get; set; } | Obtiene o establece el estado de texto de celda predeterminado. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Obtiene o establece el texto de expansión para el elemento de estructura. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Obtiene el ID para el elemento de estructura. |
| [IsNoBorder](../../aspose.pdf.logicalstructure/tablecellelement/isnoborder/) { get; set; } | Obtiene o establece si la celda tiene borde. |
| [IsWordWrapped](../../aspose.pdf.logicalstructure/tablecellelement/iswordwrapped/) { get; set; } | Obtiene o establece si el texto de la celda está ajustado. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Obtiene o establece el idioma para el elemento de estructura. |
| [Margin](../../aspose.pdf.logicalstructure/tablecellelement/margin/) { get; set; } | Obtiene o establece el relleno. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Obtiene la página en la que se renderizarán algunos o todos los elementos hijos. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Obtiene el elemento padre. |
| [RowSpan](../../aspose.pdf.logicalstructure/tablecellelement/rowspan/) { get; set; } | Obtiene o establece el alcance de la fila. |
| [StructureTextState](../../aspose.pdf.logicalstructure/tablecellelement/structuretextstate/) { get; } | Obtiene el objeto StructureTextState para el elemento actual. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Obtiene el tipo de elemento de estructura. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Obtiene o establece el título para el elemento de estructura. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tablecellelement/verticalalignment/) { get; set; } | Obtiene o establece la alineación vertical. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/tablecellelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Agrega un Elemento a la colección de hijos. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Cambia el elemento padre para el elemento de estructura actual |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Limpia todos los hijos. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Limpia el ID para el elemento de estructura. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Encuentra elementos de un tipo dado |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Genera un ID para el elemento de estructura. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Inserta un Elemento en la colección de hijos en el índice especificado. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Elimina: un elemento de la estructura, una referencia a él del objeto padre, referencias a él de objetos hijos, el objeto correspondiente del documento. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Elimina un elemento de la estructura, una referencia a él del objeto padre, referencias a él de objetos hijos, y el objeto correspondiente del documento. Inserta los objetos hijos del objeto eliminado en la colección de objetos hijos de su antiguo padre comenzando en el índice del objeto eliminado. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Elimina el hijo en. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Establece el ID para el elemento de estructura. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Establece una etiqueta personalizada para el elemento de estructura. |
| [SetText](../../aspose.pdf.logicalstructure/tablecellelement/settext/)(string) |  |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Vincula un elemento de estructura a la Anotación. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Vincula un elemento de estructura al Artefacto. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Vincula un elemento de estructura al operador BDC del flujo de contenido. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Vincula un elemento de estructura al XForm del flujo de contenido. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Vincula un elemento de estructura a la XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Devuelve una cadena que representa el objeto actual. |

### Véase también

* clase [TableCellElement](../tablecellelement/)
* espacio de nombres [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* ensamblaje [Aspose.PDF](../../)