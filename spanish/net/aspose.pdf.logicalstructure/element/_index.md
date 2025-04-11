---
title: Class Element
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.LogicalStructure.Element. Representa una clase base para elementos en la estructura lógica
type: docs
weight: 6320
url: /es/net/aspose.pdf.logicalstructure/element/
---
## Clase Elemento

Representa una clase base para elementos en la estructura lógica.

```csharp
public abstract class Element
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Obtiene la colección de hijos de objetos Element. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Obtiene el elemento padre. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Agrega un Element a la colección de hijos. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Limpia todos los hijos. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Encuentra elementos de un tipo dado |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Inserta un Element en la colección de hijos en el índice especificado. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Elimina el hijo en. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_2)(Annotation) | Vincula un elemento de estructura a la Anotación. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag)(Artifact) | Vincula un elemento de estructura al Artefacto. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_1)(BDC) | Vincula un elemento de estructura al operador BDC del flujo de contenido. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_3)(XForm) | Vincula un elemento de estructura al flujo de contenido XForm. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_4)(XImage) | Vincula un elemento de estructura a la XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/element/tostring/)() | Devuelve una cadena que representa el objeto actual. |

### Ver También

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)