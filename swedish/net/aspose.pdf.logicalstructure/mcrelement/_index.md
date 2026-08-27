---
title: "Klass MCRElement"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.LogicalStructure.MCRElement-klass. Representerar markerat innehållsreferensobjekt i logisk struktur."
type: docs
weight: 6640
url: /sv/net/aspose.pdf.logicalstructure/mcrelement/
---
## MCRElement class

Representerar markerat-innehållsreferensobjekt i logisk struktur.

```csharp
public sealed class MCRElement : Element
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Hämtar samlingen av barn‑Element‑objekt. |
| [MCID](../../aspose.pdf.logicalstructure/mcrelement/mcid/) { get; } | Hämtar MCID för markerat innehållsreferensobjekt. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Hämta föräldraelementet. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Lägg till Element i samlingen av barn. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Rensa alla barn. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Hitta element av en given typ |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Infoga element i samling av barn på angivet index. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Ta bort barn vid. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_2)(Annotation) | Koppla ett strukturelement till Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag)(Artifact) | Koppla ett strukturelement till Artifact. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_1)(BDC) | Koppla ett strukturelement till innehållsströmmen BDC-operatorn. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_3)(XForm) | Koppla ett strukturelement till innehållsströmmen XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_4)(XImage) | Koppla ett strukturelement till XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/mcrelement/tostring/)() | Returnerar en sträng som representerar det aktuella objektet. |

### Se även

* class [Element](../element/)
* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


