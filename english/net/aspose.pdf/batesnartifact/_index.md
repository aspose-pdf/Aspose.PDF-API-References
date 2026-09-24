---
title: "BatesNArtifact Class"
linktitle: "BatesNArtifact"
articleTitle: "BatesNArtifact"
second_title: "Aspose.PDF for .NET"
description: "Class describes Bates Numbering artifact."
type: docs
weight: 140
url: "/net/aspose.pdf/batesnartifact/"
keywords: "BatesNArtifact, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## BatesNArtifact class

Class describes Bates Numbering artifact.

```csharp
public class BatesNArtifact : PaginationArtifact
```

## Constructors

| Name | Description |
| --- | --- |
| [BatesNArtifact](./batesnartifact/#constructor) | Initializes a new instance of the [`BatesNArtifact`](../../aspose.pdf/batesnartifact/) class. |

## Properties

| Name | Description |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Horizontal alignment of artifact. *(Inherited from Artifact)* |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Vertical alignment of artifact. *(Inherited from Artifact)* |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Bottom margin of artifact. *(Inherited from Artifact)* |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Gets collection of artifact internal operators. *(Inherited from Artifact)* |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Gets name of artifact subtype. May be used if artifact subtype is not standard subtype. *(Inherited from Artifact)* |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Gets name of artifact type. May be used if artifact type is non standard. *(Inherited from Artifact)* |
| [EndPage](../../aspose.pdf/paginationartifact/endpage/) { get; set; } | Gets or sets the ending page number for the artifact. *(Inherited from PaginationArtifact)* |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Gets XForm of the artifact (if XForm is used). *(Inherited from Artifact)* |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Gets image of the artifact (if presents). *(Inherited from Artifact)* |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | If true Artifact is placed behind page contents. *(Inherited from Artifact)* |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Left margin of artifact. *(Inherited from Artifact)* |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Lines of multiline text artifact. *(Inherited from Artifact)* |
| [NumberOfDigits](./numberofdigits/) { get; set; } | Gets or sets the number of digits for Bates numbering. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Gets or sets opacity of the artifact. Possible values are in range 0..1. *(Inherited from Artifact)* |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Gets or sets artifact position. *(Inherited from Artifact)* |
| [Prefix](./prefix/) { get; set; } | Gets or sets the prefix to be added to the Bates number. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Gets rectangle of the artifact. *(Inherited from Artifact)* |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Right margin of artifact. *(Inherited from Artifact)* |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Gets or sets artifact rotation angle. *(Inherited from Artifact)* |
| [StartNumber](./startnumber/) { get; set; } | Gets or sets the starting number for Bates numbering. |
| [StartPage](../../aspose.pdf/paginationartifact/startpage/) { get; set; } | Gets or sets the starting page number for the artifact. *(Inherited from PaginationArtifact)* |
| [Subset](../../aspose.pdf/paginationartifact/subset/) { get; set; } | Gets or sets the subset of pages to which the artifact applies (e.g., all pages, even pages, odd pages). *(Inherited from PaginationArtifact)* |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Gets artifact subtype. If artifact has non-standard subtype, name of the subtype may be read via CustomSubtype. *(Inherited from Artifact)* |
| [Suffix](./suffix/) { get; set; } | Gets or sets the suffix to be added to the Bates number. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Gets text of the artifact. *(Inherited from Artifact)* |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Text state for artifact text. *(Inherited from Artifact)* |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Top margin of artifact. *(Inherited from Artifact)* |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Gets artifact type. *(Inherited from Artifact)* |

## Methods

| Name | Description |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/) | Start delated updates. Use this feature if you need make several changes to the same artifact to improve performance. *(Inherited from Artifact)* |
| [Dispose](../../aspose.pdf/artifact/dispose/) | Dispose the artifact. *(Inherited from Artifact)* |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(*string*) | Gets custom value of artifact. *(Inherited from Artifact)* |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(*string*) | Remove custom value from the artifact. *(Inherited from Artifact)* |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/) | Saves all updates in artifact which were made after BeginUpdates() call. *(Inherited from Artifact)* |
| [SetImage](../../aspose.pdf/artifact/setimage/)(*Stream*) | Sets image of the artifact. *(Inherited from Artifact)* |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(*string[], TextState*) | Set text and text properties of the artifact. Allows to specify multiple lines. *(Inherited from Artifact)* |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(*string*) | Sets what string will be replaced with the page number. *(Inherited from Artifact)* |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(*Page*) | Sets PDF page which is placed on the document page as artifact. *(Inherited from Artifact)* |
| [SetText](../../aspose.pdf/artifact/settext/)(*FormattedText*) | Sets text of the artifact. *(Inherited from Artifact)* |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(*string, TextState*) | Set text and text properties of the artifact. *(Inherited from Artifact)* |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(*string, string*) | Sets custom value of artifact. *(Inherited from Artifact)* |

### See Also

* class [PaginationArtifact](../paginationartifact/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

