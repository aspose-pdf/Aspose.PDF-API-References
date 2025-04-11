---
title: Class TableElement
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.LogicalStructure.TableElement. Representa el elemento de estructura de tabla en la estructura lógica
type: docs
weight: 6780
url: /es/net/aspose.pdf.logicalstructure/tableelement/
---
## Clase TableElement

Representa el elemento de estructura de tabla en la estructura lógica.

```csharp
public sealed class TableElement : BLSElement, IAdjustPosition
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Obtiene o establece el texto real para el elemento de estructura. |
| [Alignment](../../aspose.pdf.logicalstructure/tableelement/alignment/) { get; set; } | Obtiene o establece la alineación de la tabla. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Obtiene o establece el texto alternativo para el elemento de estructura. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Obtiene el objeto StructureAttributeCollection. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tableelement/backgroundcolor/) { get; set; } | Obtiene o establece el color de fondo de la tabla. |
| [Border](../../aspose.pdf.logicalstructure/tableelement/border/) { get; set; } | Obtiene o establece el borde de la tabla. |
| [Broken](../../aspose.pdf.logicalstructure/tableelement/broken/) { get; set; } | Obtiene o establece si la tabla está rota verticalmente; |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Obtiene la colección de elementos hijos de objetos Element. |
| [ColumnAdjustment](../../aspose.pdf.logicalstructure/tableelement/columnadjustment/) { get; set; } | Obtiene o establece el ajuste de columna de la tabla. |
| [ColumnWidths](../../aspose.pdf.logicalstructure/tableelement/columnwidths/) { get; set; } | Obtiene los anchos de columna de la tabla. |
| [CornerStyle](../../aspose.pdf.logicalstructure/tableelement/cornerstyle/) { get; set; } | Obtiene o establece los estilos de las esquinas del borde |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Obtiene el objeto AttributeOwnerStandard. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tableelement/defaultcellborder/) { get; set; } | Obtiene el borde de celda predeterminado. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tableelement/defaultcellpadding/) { get; set; } | Obtiene o establece el relleno de celda predeterminado. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tableelement/defaultcelltextstate/) { get; set; } | Obtiene o establece el estado de texto de celda predeterminado. |
| [DefaultColumnWidth](../../aspose.pdf.logicalstructure/tableelement/defaultcolumnwidth/) { get; set; } | Obtiene o establece el ancho de columna predeterminado. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Obtiene o establece el texto de expansión para el elemento de estructura. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Obtiene el ID para el elemento de estructura. |
| [IsBordersIncluded](../../aspose.pdf.logicalstructure/tableelement/isbordersincluded/) { get; set; } | Obtiene o establece si el borde está incluido en los anchos de columna. |
| [IsBroken](../../aspose.pdf.logicalstructure/tableelement/isbroken/) { get; set; } | Obtiene o establece si la tabla está rota - se truncará para la siguiente página. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Obtiene o establece el idioma para el elemento de estructura. |
| [Left](../../aspose.pdf.logicalstructure/tableelement/left/) { get; set; } | Obtiene o establece la coordenada izquierda de la tabla. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Obtiene la página en la que se renderizarán algunos o todos los elementos hijos. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Obtiene el elemento padre. |
| [RepeatingColumnsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingcolumnscount/) { get; set; } | Obtiene o establece el número máximo de columnas para la tabla. |
| [RepeatingRowsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingrowscount/) { get; set; } | Obtiene el número de filas que se repiten en varias páginas. |
| [RepeatingRowsStyle](../../aspose.pdf.logicalstructure/tableelement/repeatingrowsstyle/) { get; set; } | Obtiene el estilo para las filas repetidas. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Obtiene el tipo de elemento de estructura. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Obtiene o establece el título para el elemento de estructura. |
| [Top](../../aspose.pdf.logicalstructure/tableelement/top/) { get; set; } | Obtiene o establece la coordenada superior de la tabla. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/tableelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Agrega Elemento a la colección de hijos. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Cambia el elemento padre para el elemento de estructura actual |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Limpia todos los hijos. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Limpia el ID para el elemento de estructura. |
| [CreateTBody](../../aspose.pdf.logicalstructure/tableelement/createtbody/)() | Crea [`TableTHeadElement`](../tabletheadelement/) y lo agrega a la tabla actual. |
| [CreateTFoot](../../aspose.pdf.logicalstructure/tableelement/createtfoot/)() | Crea [`TableTFootElement`](../tabletfootelement/) y lo agrega a la tabla actual. |
| [CreateTHead](../../aspose.pdf.logicalstructure/tableelement/createthead/)() | Crea [`TableTHeadElement`](../tabletheadelement/) y lo agrega a la tabla actual. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Encuentra elementos de un tipo dado |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Genera un ID para el elemento de estructura. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Inserta Elemento en la colección de hijos en el índice especificado. |
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

* clase [BLSElement](../blselement/)
* interfaz [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* espacio de nombres [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* ensamblado [Aspose.PDF](../../)