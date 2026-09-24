---
title: "Artifact Class"
linktitle: "Artifact"
articleTitle: "Artifact"
second_title: "Aspose.PDF for .NET"
description: "Class represents PDF Artifact object."
type: docs
weight: 50
url: "/net/aspose.pdf/artifact/"
keywords: "Artifact, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Artifact class

Class represents PDF Artifact object.

```csharp
public class Artifact : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [Artifact](./artifact/#constructor)(*string, string*) | Constructor of artifact with specified type and subtype. |
| [Artifact](./artifact/#constructor_1)(*ArtifactType, ArtifactSubtype*) | Initializes a new instance of the Artifact class. |

## Properties

| Name | Description |
| --- | --- |
| [ArtifactHorizontalAlignment](./artifacthorizontalalignment/) { get; set; } | Horizontal alignment of artifact. |
| [ArtifactVerticalAlignment](./artifactverticalalignment/) { get; set; } | Vertical alignment of artifact. |
| [BottomMargin](./bottommargin/) { get; set; } | Bottom margin of artifact. |
| [Contents](./contents/) { get; } | Gets collection of artifact internal operators. |
| [CustomSubtype](./customsubtype/) { get; set; } | Gets name of artifact subtype. May be used if artifact subtype is not standard subtype. |
| [CustomType](./customtype/) { get; set; } | Gets name of artifact type. May be used if artifact type is non standard. |
| [Form](./form/) { get; } | Gets XForm of the artifact (if XForm is used). |
| [Image](./image/) { get; } | Gets image of the artifact (if presents). |
| [IsBackground](./isbackground/) { get; set; } | If true Artifact is placed behind page contents. |
| [LeftMargin](./leftmargin/) { get; set; } | Left margin of artifact. |
| [Lines](./lines/) { get; } | Lines of multiline text artifact. |
| [Opacity](./opacity/) { get; set; } | Gets or sets opacity of the artifact. Possible values are in range 0..1. |
| [Position](./position/) { get; set; } | Gets or sets artifact position. |
| [Rectangle](./rectangle/) { get; } | Gets rectangle of the artifact. |
| [RightMargin](./rightmargin/) { get; set; } | Right margin of artifact. |
| [Rotation](./rotation/) { get; set; } | Gets or sets artifact rotation angle. |
| [Subtype](./subtype/) { get; set; } | Gets artifact subtype. If artifact has non-standard subtype, name of the subtype may be read via CustomSubtype. |
| [Text](./text/) { get; set; } | Gets text of the artifact. |
| [TextState](./textstate/) { get; set; } | Text state for artifact text. |
| [TopMargin](./topmargin/) { get; set; } | Top margin of artifact. |
| [Type](./type/) { get; set; } | Gets artifact type. |

## Methods

| Name | Description |
| --- | --- |
| [BeginUpdates](./beginupdates/) | Start delated updates. Use this feature if you need make several changes to the same artifact to improve performance. |
| [Dispose](./dispose/) | Dispose the artifact. |
| [GetValue](./getvalue/)(*string*) | Gets custom value of artifact. |
| [RemoveValue](./removevalue/)(*string*) | Remove custom value from the artifact. |
| [SaveUpdates](./saveupdates/) | Saves all updates in artifact which were made after BeginUpdates() call. |
| [SetImage](./setimage/)(*Stream*) | Sets image of the artifact. |
| [SetImage](./setimage/)(*string*) | Sets image of the artifact. |
| [SetLinesAndState](./setlinesandstate/)(*string[], TextState*) | Set text and text properties of the artifact. Allows to specify multiple lines. |
| [SetPageNumberReplacementString](./setpagenumberreplacementstring/)(*string*) | Sets what string will be replaced with the page number. |
| [SetPdfPage](./setpdfpage/)(*Page*) | Sets PDF page which is placed on the document page as artifact. |
| [SetText](./settext/)(*FormattedText*) | Sets text of the artifact. |
| [SetTextAndState](./settextandstate/)(*string, TextState*) | Set text and text properties of the artifact. |
| [SetValue](./setvalue/)(*string, string*) | Sets custom value of artifact. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

