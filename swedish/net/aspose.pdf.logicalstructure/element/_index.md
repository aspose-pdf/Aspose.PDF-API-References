---
title: "Klass Element"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.LogicalStructure.Element klass. Representerar en basklass för element i logisk struktur"
type: docs
weight: 6460
url: /sv/net/aspose.pdf.logicalstructure/element/
---
## Element class

Representerar en basklass för element i logisk struktur.

```csharp
public abstract class Element
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Hämtar samlingen av barn‑Element‑objekt. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Hämta föräldraelementet. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Lägg till Element i samlingen av barn. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Rensa alla barn. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Hitta element av en given typ |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Infoga element i samling av barn på angivet index. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Ta bort barn vid. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_2)(Annotation) | Koppla ett strukturelement till Annotation. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag)(Artifact) | Koppla ett strukturelement till Artifact. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_1)(BDC) | Koppla ett strukturelement till innehållsströmmen BDC-operatorn. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_3)(XForm) | Koppla ett strukturelement till innehållsströmmen XForm. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_4)(XImage) | Koppla ett strukturelement till XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/element/tostring/)() | Returnerar en sträng som representerar det aktuella objektet. |

### Se även

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


