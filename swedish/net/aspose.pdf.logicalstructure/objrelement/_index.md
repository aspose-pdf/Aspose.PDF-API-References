---
title: Class OBJRElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.OBJRElement klass. Representerar objektreferensentitet i logisk struktur
type: docs
weight: 6530
url: /sv/net/aspose.pdf.logicalstructure/objrelement/
---
## OBJRElement klass

Representerar objektreferensentitet i logisk struktur.

```csharp
public sealed class OBJRElement : Element
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Hämtar barnkollektionen av Element-objekt. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Hämtar föräldraelementet. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Lägger till Element i barnkollektionen. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Rensar alla barn. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Hittar Element av en given typ |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Infogar Element i barnkollektionen vid angiven index. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Tar bort barn vid. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag_2)(Annotation) | Binder ett struktur-element till Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag)(Artifact) | Binder ett struktur-element till Artifact. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag_1)(BDC) | Binder ett struktur-element till innehållsström BDC-operator. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag_3)(XForm) | Binder ett struktur-element till innehållsström XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag_4)(XImage) | Binder ett struktur-element till XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/objrelement/tostring/)() | Returnerar en sträng som representerar det aktuella objektet. |

### Se Även

* klass [Element](../element/)
* namnrymd [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* sammansättning [Aspose.PDF](../../)