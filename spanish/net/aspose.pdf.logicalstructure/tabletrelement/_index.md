---
title: Class TableTRElement
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.LogicalStructure.TableTRElement. Representa el elemento de estructura TR en la estructura lógica de la tabla
type: docs
weight: 6850
url: /es/net/aspose.pdf.logicalstructure/tabletrelement/
---
## Clase TableTRElement

Representa el elemento de estructura TR en la estructura lógica de la tabla.

```csharp
public sealed class TableTRElement : TableChildElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Obtiene o establece el texto real para el elemento de estructura. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Obtiene o establece el texto alternativo para el elemento de estructura. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | Obtiene el objeto StructureAttributeCollection. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tabletrelement/backgroundcolor/) { get; set; } | Obtiene o establece el color de fondo de la fila. |
| [Border](../../aspose.pdf.logicalstructure/tabletrelement/border/) { get; set; } | Obtiene o establece el borde de la fila. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Obtiene la colección de hijos de objetos Element. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | Obtiene el objeto AttributeOwnerStandard. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellborder/) { get; set; } | Obtiene el borde de celda predeterminado. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellpadding/) { get; set; } | Obtiene o establece el margen predeterminado para las celdas de la fila. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tabletrelement/defaultcelltextstate/) { get; set; } | Obtiene o establece el estado de texto predeterminado para las celdas de la fila. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Obtiene o establece el texto de expansión para el elemento de estructura. |
| [FixedRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/fixedrowheight/) { get; set; } | Obtiene la altura fija de la fila - la fila puede tener una altura fija. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Obtiene el ID para el elemento de estructura. |
| [IsInNewPage](../../aspose.pdf.logicalstructure/tabletrelement/isinnewpage/) { get; set; } | Obtiene si la fila fija está en una nueva página - la página con esta propiedad debe imprimirse en la siguiente página. Predeterminado falso. |
| [IsRowBroken](../../aspose.pdf.logicalstructure/tabletrelement/isrowbroken/) { get; set; } | Obtiene si la fila puede ser dividida entre dos páginas. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Obtiene o establece el idioma para el elemento de estructura. |
| [MinRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/minrowheight/) { get; set; } | Obtiene la altura para la fila. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Obtiene la página en la que se renderizarán algunos o todos los elementos hijos. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Obtiene el elemento padre. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Obtiene el tipo de elemento de estructura. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Obtiene o establece el título para el elemento de estructura. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tabletrelement/verticalalignment/) { get; set; } | Obtiene o establece la alineación vertical. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Agrega un Element a la colección de hijos. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Cambia el elemento padre para el elemento de estructura actual. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Limpia todos los hijos. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Limpia el ID para el elemento de estructura. |
| [CreateTD](../../aspose.pdf.logicalstructure/tabletrelement/createtd/)() | Crea un [`TableTHElement`](../tablethelement/) y lo agrega a la tabla actual. |
| [CreateTH](../../aspose.pdf.logicalstructure/tabletrelement/createth/)() | Crea un [`TableTHElement`](../tablethelement/) y lo agrega a la tabla actual. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Encuentra elementos de un tipo dado. |
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

* clase [TableChildElement](../tablechildelement/)
* espacio de nombres [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* ensamblado [Aspose.PDF](../../)