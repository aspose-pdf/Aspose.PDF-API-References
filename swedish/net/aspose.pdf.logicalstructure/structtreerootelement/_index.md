---
title: Class StructTreeRootElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.StructTreeRootElement klass. Representerar StructTreeRoot-objektet i den logiska strukturen
type: docs
weight: 6660
url: /sv/net/aspose.pdf.logicalstructure/structtreerootelement/
---
## StructTreeRootElement klass

Representerar StructTreeRoot-objektet i den logiska strukturen.

```csharp
public sealed class StructTreeRootElement : Element
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
| override [Tag](../../aspose.pdf.logicalstructure/structtreerootelement/tag/#tag_2)(Annotation) | Binder ett strukturelement till Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/structtreerootelement/tag/#tag)(Artifact) | Binder ett strukturelement till Artifact. |
| override [Tag](../../aspose.pdf.logicalstructure/structtreerootelement/tag/#tag_1)(BDC) | Binder ett strukturelement till innehållsström BDC-operator. |
| override [Tag](../../aspose.pdf.logicalstructure/structtreerootelement/tag/#tag_3)(XForm) | Binder ett strukturelement till innehållsström XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/structtreerootelement/tag/#tag_4)(XImage) | Binder ett strukturelement till XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/element/tostring/)() | Returnerar en sträng som representerar det aktuella objektet. |

### Se Även

* klass [Element](../element/)
* namnrymd [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)