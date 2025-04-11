---
title: Class MCRElement
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.LogicalStructure.MCRElement. Representa un objeto de referencia de contenido marcado en la estructura lógica
type: docs
weight: 6500
url: /es/net/aspose.pdf.logicalstructure/mcrelement/
---
## Clase MCRElement

Representa un objeto de referencia de contenido marcado en la estructura lógica.

```csharp
public sealed class MCRElement : Element
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Obtiene la colección de hijos de objetos Element. |
| [MCID](../../aspose.pdf.logicalstructure/mcrelement/mcid/) { get; } | Obtiene el MCID del objeto de referencia de contenido marcado. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Obtiene el elemento padre. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Agrega un Element a la colección de hijos. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Limpia todos los hijos. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Encuentra elementos de un tipo dado |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Inserta un Element en la colección de hijos en el índice especificado. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Elimina el hijo en. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_2)(Annotation) | Vincula un elemento de estructura a la Anotación. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag)(Artifact) | Vincula un elemento de estructura al Artefacto. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_1)(BDC) | Vincula un elemento de estructura al operador BDC del flujo de contenido. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_3)(XForm) | Vincula un elemento de estructura al flujo de contenido XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_4)(XImage) | Vincula un elemento de estructura a la XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/mcrelement/tostring/)() | Devuelve una cadena que representa el objeto actual. |

### Véase también

* clase [Element](../element/)
* espacio de nombres [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* ensamblaje [Aspose.PDF](../../)