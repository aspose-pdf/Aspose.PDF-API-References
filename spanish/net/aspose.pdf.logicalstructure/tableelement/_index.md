---
title: TableElement
second_title: Referencia de API de Aspose.PDF para .NET
description: Representa el elemento de estructura de la tabla en la estructura lógica.
type: docs
weight: 4610
url: /es/net/aspose.pdf.logicalstructure/tableelement/
---
## TableElement class

Representa el elemento de estructura de la tabla en la estructura lógica.

```csharp
public sealed class TableElement : BLSElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext) { get; set; } | Obtiene o establece el texto real para el elemento de estructura. |
| [Alignment](../../aspose.pdf.logicalstructure/tableelement/alignment) { get; set; } | Obtiene o establece la alineación de la tabla. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext) { get; set; } | Obtiene o establece el texto alternativo para el elemento de estructura. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes) { get; } | ObtieneStructureAttributeCollection objeto. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tableelement/backgroundcolor) { get; set; } | Obtiene o establece el color de fondo de la tabla. |
| [Border](../../aspose.pdf.logicalstructure/tableelement/border) { get; set; } | Obtiene o establece el borde de la tabla. |
| [Broken](../../aspose.pdf.logicalstructure/tableelement/broken) { get; set; } | Obtiene o establece la tabla vertical rota; |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements) { get; } | Obtiene la colección secundaria deElement objetos. |
| [ColumnAdjustment](../../aspose.pdf.logicalstructure/tableelement/columnadjustment) { get; set; } | Obtiene o establece el ajuste de la columna de la tabla. |
| [ColumnWidths](../../aspose.pdf.logicalstructure/tableelement/columnwidths) { get; set; } | Obtiene los anchos de columna de la tabla. |
| [CornerStyle](../../aspose.pdf.logicalstructure/tableelement/cornerstyle) { get; set; } | Obtiene o establece los estilos de las esquinas del borde |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner) { get; } | ObtieneAttributeOwnerStandard objeto. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tableelement/defaultcellborder) { get; set; } | Obtiene el borde de celda predeterminado. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tableelement/defaultcellpadding) { get; set; } | Obtiene o establece el relleno de celda predeterminado. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tableelement/defaultcelltextstate) { get; set; } | Obtiene o establece el estado de texto de celda predeterminado. |
| [DefaultColumnWidth](../../aspose.pdf.logicalstructure/tableelement/defaultcolumnwidth) { get; set; } | Obtiene o establece el ancho de columna predeterminado. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext) { get; set; } | Obtiene o establece el texto de expansión para el elemento de estructura. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id) { get; } | Obtiene el ID del elemento de estructura. |
| [IsBordersIncluded](../../aspose.pdf.logicalstructure/tableelement/isbordersincluded) { get; set; } | Obtiene o establece el borde incluido en los anchos de columna. |
| [IsBroken](../../aspose.pdf.logicalstructure/tableelement/isbroken) { get; set; } | Obtiene o establece que la tabla está rota: se truncará para la página siguiente. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language) { get; set; } | Obtiene o establece el idioma del elemento de estructura. |
| [Left](../../aspose.pdf.logicalstructure/tableelement/left) { get; set; } | Obtiene o establece la coordenada izquierda de la tabla. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement) { get; } | Obtener elemento padre. |
| [RepeatingColumnsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingcolumnscount) { get; set; } | Obtiene o establece el número máximo de columnas para la tabla. |
| [RepeatingRowsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingrowscount) { get; set; } | Obtiene el recuento de las primeras filas repetido en varias páginas. |
| [RepeatingRowsStyle](../../aspose.pdf.logicalstructure/tableelement/repeatingrowsstyle) { get; set; } | Obtiene el estilo para filas repetidas. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype) { get; } | Obtiene el tipo de elemento de estructura. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title) { get; set; } | Obtiene o establece el título del elemento de estructura. |
| [Top](../../aspose.pdf.logicalstructure/tableelement/top) { get; set; } | Obtiene o establece la coordenada superior de la mesa. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild)(Element) | AgregarElement a la colección de niños. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement)(StructureElement) | Cambiar elemento principal para estructura actual elemento |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid)() | Borrar ID para elemento de estructura. |
| [CreateTBody](../../aspose.pdf.logicalstructure/tableelement/createtbody)() | Crea[`TableTHeadElement`](../tabletheadelement) y lo agregó a la tabla actual. |
| [CreateTFoot](../../aspose.pdf.logicalstructure/tableelement/createtfoot)() | Crea[`TableTFootElement`](../tabletfootelement) y lo agregó a la tabla actual. |
| [CreateTHead](../../aspose.pdf.logicalstructure/tableelement/createthead)() | Crea[`TableTHeadElement`](../tabletheadelement) y lo agregó a la tabla actual. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements)(bool) | Buscar elementos de un tipo dado |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid)() | Generar ID para elemento de estructura. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid)(string) | Establece ID para elemento de estructura. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag)(string) | Establece una etiqueta personalizada para el elemento de estructura. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring)() | Devuelve una cadena que representa el objeto actual. |

### Ver también

* class [BLSElement](../blselement)
* espacio de nombres [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
