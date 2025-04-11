---
title: Class OBJRElement
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.LogicalStructure.OBJRElement. Representa la entidad de referencia de objeto en la estructura lógica
type: docs
weight: 6530
url: /es/net/aspose.pdf.logicalstructure/objrelement/
---
## Clase OBJRElement

Representa la entidad de referencia de objeto en la estructura lógica.

```csharp
public sealed class OBJRElement : Element
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Obtiene la colección de hijos de objetos Element. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Obtiene el elemento padre. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Agrega Element a la colección de hijos. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Limpia todos los hijos. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Encuentra Elementos de un tipo dado |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Inserta Element en la colección de hijos en el índice especificado. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Elimina el hijo en. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag_2)(Annotation) | Vincula un elemento de estructura a la Anotación. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag)(Artifact) | Vincula un elemento de estructura al Artefacto. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag_1)(BDC) | Vincula un elemento de estructura al operador BDC del flujo de contenido. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag_3)(XForm) | Vincula un elemento de estructura al flujo de contenido XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag_4)(XImage) | Vincula un elemento de estructura al XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/objrelement/tostring/)() | Devuelve una cadena que representa el objeto actual. |

### Véase también

* clase [Element](../element/)
* espacio de nombres [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* ensamblaje [Aspose.PDF](../../)