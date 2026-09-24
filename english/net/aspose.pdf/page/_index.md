---
title: "Page Class"
linktitle: "Page"
articleTitle: "Page"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Page class. Class representing page of PDF document."
type: docs
weight: 2110
url: "/net/aspose.pdf/page/"
keywords: "Page, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Page class

Class representing page of PDF document.

```csharp
public sealed class Page : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [Actions](./actions/) { get; } | Gets collection of page properties. |
| [Annotations](./annotations/) { get; } | Gets collection of page annotations. |
| [ArtBox](./artbox/) { get; set; } | Gets or sets art box of the page. |
| [Artifacts](./artifacts/) { get; } | Gets collection of artifacts on the page. |
| [Background](./background/) { get; set; } | Gets or sets the background color of the page. |
| [BackgroundImage](./backgroundimage/) { get; set; } | Gets or sets background image for page (for generator only, not filled in when reading document). |
| [BleedBox](./bleedbox/) { get; set; } | Gets or sets bleed box of the page. |
| [ColorType](./colortype/) { get; } | Sets color type of the pages based on information getting from operators SetColor,. |
| [Contents](./contents/) { get; } | Gets collection of operators in the content stream of the page. |
| [CropBox](./cropbox/) { get; set; } | Gets or sets crop box of the page. |
| [Duration](./duration/) { get; set; } | Gets of set page display duration. This is time in seconds that page shall be displayed during presentation. |
| [FieldsInTabOrder](./fieldsintaborder/) { get; } | Gets list of Field object in Tab order on this page. |
| [Footer](./footer/) { get; set; } | Gets or sets page footer. |
| [Group](./group/) { get; set; } | Gets or sets a group attributes class specifying the attributes of the page's page group for use in the transparent imaging model. |
| [Header](./header/) { get; set; } | Gets or sets page header. |
| [IsAddParagraphsAfterLast](./isaddparagraphsafterlast/) { get; set; } | Gets or sets the addition of paragraphs after the last paragraph of the page. |
| [Layers](./layers/) { get; set; } | Gets or sets layers collection. |
| [MediaBox](./mediabox/) { get; set; } | Gets or sets media box of the page. |
| [NoteLineStyle](./notelinestyle/) { get; set; } | Gets or sets the line style for notes.(for generator only, not filled in when reading document). |
| [Number](./number/) { get; } | Get number of the page. |
| [PageInfo](./pageinfo/) { get; set; } | Gets or sets the page info (for generator only, not filled in when reading document). |
| [Paragraphs](./paragraphs/) { get; set; } | Gets the paragraphs. |
| [Rect](./rect/) { get; set; } | Gets or sets rectangle of the page. |
| [Resources](./resources/) { get; } | Gets page resources. Resources object contains collections of images, forms and fonts. |
| [Rotate](./rotate/) { get; set; } | Gets or sets rotation of the page. |
| [RotationMatrix](./rotationmatrix/) { get; } | Gets transofmation matrix for the page. |
| [TabOrder](./taborder/) { get; set; } | Gets or sets tab order of the page. |
| [TocInfo](./tocinfo/) { get; set; } | Gets or sets table of contents info. |
| [TrimBox](./trimbox/) { get; set; } | Gets or sets trim box of the page. |
| [UserUnit](./userunit/) { get; set; } | Gets or sets UserUnit value. A positive number giving the size of default user space units, in multiples of 1 / 72 inch. |
| [Watermark](./watermark/) { get; set; } | Gets or sets the watermark of the page. |

## Methods

| Name | Description |
| --- | --- |
| [Accept](./accept/)(*AnnotationSelector*) | Accepts [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) visitor object that provides functionality to work with annotations. |
| [Accept](./accept/)(*TextFragmentAbsorber*) | Accepts [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) visitor object that provides functionality to work with text objects. |
| [Accept](./accept/)(*ImagePlacementAbsorber*) | Accepts [`ImagePlacementAbsorber`](../../aspose.pdf/imageplacementabsorber/) visitor object that provides functionality to work with image placement objects. |
| [Accept](./accept/)(*TextAbsorber*) | Accepts [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) visitor object that provides functionality to work with text objects. |
| [Accept](./accept/)(*OcrTextAbsorber*) | Accepts an [`OcrTextAbsorber`](../../aspose.pdf.ocr/ocrtextabsorber/) that extracts plain text from this page using OCR. |
| [AddGraphics](./addgraphics/)(*GraphicElementCollection, Rectangle*) | Adds graphics to the page. |
| [AddImage](./addimage/)(*string, Rectangle*) | Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [AddImage](./addimage/)(*Stream, Rectangle, Rectangle, bool*) | Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [AddImage](./addimage/)(*string, Stream, Rectangle, Rectangle*) | Adds searchable image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [AddImage](./addimage/)(*Stream, Rectangle, int, int, bool, Rectangle*) | Adds image on page and places it depend on image rectangle position. |
| [AddStamp](./addstamp/)(*Stamp*) | Put stamp into page. Stamp can be page number, image or simple text, e.g. some logo. |
| [AsByteArray](./asbytearray/)(*Resolution*) | Converts current page as bitmap and than returns array of bytes. |
| [AsXml](./asxml/) | Converts current page as xml in utf8 encoding. |
| [CalculateContentBBox](./calculatecontentbbox/) | Calculates bbox value - rectangle containing contents without visible margins. |
| [ConvertToPNGMemoryStream](./converttopngmemorystream/) | Convert page to PNG for DSR, OMR, OCR image stream. |
| [DeleteGraphics](./deletegraphics/)(*GraphicElementCollection*) | Deletes graphics from the page. |
| [Dispose](./dispose/) | Frees up memory. |
| [Flatten](./flatten/) | Removes all fields located on the page and place their values instead. |
| [FreeMemory](./freememory/) | Clears cached data. |
| [GetNotifications](./getnotifications/) | Returns notifications about inside operations with page content. (Only notifications about paragraph events in text adding scenarios are supported now.). |
| [GetPageRect](./getpagerect/)(*bool*) | Returns rectangle of the page according to its CropBox (or MediaBox if CropBox null). |
| [GetResources](./getresources/) | Retrieves the resources associated with the page. |
| [HasVectorGraphics](./hasvectorgraphics/) | Detect of the presence of vector graphics, if it is present on the page. |
| [IntToRotation](./inttorotation/)(*int*) | Translates integer value into corresponding rotation enumeration member. |
| [IsBlank](./isblank/)(*double*) | Gets the flag whether page is blank or not. |
| [MakeGrayscale](./makegrayscale/) | Converts the page to grayscale. |
| [MergeLayers](./mergelayers/)(*string*) | Merges all layers on the page into a single layer with the specified new layer name. |
| [MergeLayers](./mergelayers/)(*string, string*) | Merges all layers on the page into a single layer with the specified new layer name and optional content group Id. |
| [Resize](./resize/)(*PageSize*) | Resizes the page. |
| [RotationToInt](./rotationtoint/)(*Rotation*) | Translates rotation enumeration member into integer value. |
| [SendTo](./sendto/)(*PageDevice, Stream*) | Sends page to process with given page device. |
| [SendTo](./sendto/)(*PageDevice, string*) | Sends page to process with given page device. |
| [SetPageSize](./setpagesize/)(*double, double*) | Sets page size for page. |
| [TrySaveVectorGraphics](./trysavevectorgraphics/)(*string*) | Tries to save vector graphics if they are present on the page. The save format is SVG. |

## Events

| Name | Description |
| --- | --- |
| event [OnBeforePageGenerate](./onbeforepagegenerate/) | Event for customize header and footer. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

