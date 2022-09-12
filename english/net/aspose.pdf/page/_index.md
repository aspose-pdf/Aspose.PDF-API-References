---
title: Page
second_title: Aspose.PDF for .NET API Reference
description: Class representing page of PDF document.
type: docs
weight: 5750
url: /net/aspose.pdf/page/
---
## Page class

Class representing page of PDF document.

```csharp
public sealed class Page : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions) { get; } | Gets collection of page properties. |
| [Annotations](../../aspose.pdf/page/annotations) { get; } | Gets collection of page annotations. [`Annotations`](./annotations) |
| [ArtBox](../../aspose.pdf/page/artbox) { get; set; } | Gets or sets art box of the page. |
| [Artifacts](../../aspose.pdf/page/artifacts) { get; } | Gets collection of artifacts on the page. |
| [Background](../../aspose.pdf/page/background) { get; set; } | Gets or sets the background color of the page. |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage) { get; set; } | Gets or sets background image for page (for generator only). |
| [BleedBox](../../aspose.pdf/page/bleedbox) { get; set; } | Gets or sets bleed box of the page. |
| [ColorType](../../aspose.pdf/page/colortype) { get; } | Sets color type of the pages based on information getting from operators SetColor, images and forms. |
| [Contents](../../aspose.pdf/page/contents) { get; } | Gets collection of operators in the content stream of the page. [`OperatorCollection`](../operatorcollection) |
| [CropBox](../../aspose.pdf/page/cropbox) { get; set; } | Gets or sets crop box of the page. |
| [Duration](../../aspose.pdf/page/duration) { get; set; } | Gets of set page display duration. This is time in seconds that page shall be displayed during presentation. Returs -1 if duration is not defined. |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder) { get; } | Gets list of Field object in Tab order on this page. |
| [Footer](../../aspose.pdf/page/footer) { get; set; } | Gets or sets page footer. |
| [Group](../../aspose.pdf/page/group) { get; set; } | Gets or sets a group attributes class specifying the attributes of the page�s page group for use in the transparent imaging model. |
| [Header](../../aspose.pdf/page/header) { get; set; } | Gets or sets page header. |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast) { get; set; } | Gets or sets the addition of paragraphs after the last paragraph of the page |
| [Layers](../../aspose.pdf/page/layers) { get; set; } | Gets or sets layers collection. |
| [MediaBox](../../aspose.pdf/page/mediabox) { get; set; } | Gets or sets media box of the page. |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle) { get; set; } | Gets or sets the line style for notes.(for generator only) |
| [Number](../../aspose.pdf/page/number) { get; } | Get number of the page. |
| [PageInfo](../../aspose.pdf/page/pageinfo) { get; set; } | Gets or sets the page info (for generator only, not filled in when reading file). |
| [Paragraphs](../../aspose.pdf/page/paragraphs) { get; set; } | Gets the paragraphs. |
| [Rect](../../aspose.pdf/page/rect) { get; set; } | Gets or sets rectangle of the page. Page crop box is returned if specified, otherwise page media box is returned. Please note that this property don't consider page rotation. To get page rectangle considering rotation please use ActualRect. |
| [Resources](../../aspose.pdf/page/resources) { get; } | Gets page resources. Resources object contains collections of images, forms and fonts. [`Resources`](./resources) |
| [Rotate](../../aspose.pdf/page/rotate) { get; set; } | Gets or sets rotation of the page. |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix) { get; } | Gets transofmation matrix for the page. |
| [TabOrder](../../aspose.pdf/page/taborder) { get; set; } | Gets or sets tab order of the page. Possible values: Row, Column. Default, Manual |
| [TocInfo](../../aspose.pdf/page/tocinfo) { get; set; } | Gets or sets table of contents info. |
| [TrimBox](../../aspose.pdf/page/trimbox) { get; set; } | Gets or sets trim box of the page. |
| [UserUnit](../../aspose.pdf/page/userunit) { get; set; } | Gets or sets UserUnit value. A positive number giving the size of default user space units, in multiples of 1 ⁄ 72 inch. Default value is 1. Please set zero or negative value in order to clear this entry in page. |
| [Watermark](../../aspose.pdf/page/watermark) { get; set; } | Gets or sets the watermark of the page. |

## Methods

| Name | Description |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept#accept)(AnnotationSelector) | Accepts [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector) visitor object that provides functionality to work with annotations. |
| [Accept](../../aspose.pdf/page/accept#accept_1)(ImagePlacementAbsorber) | Accepts [`ImagePlacementAbsorber`](../imageplacementabsorber) visitor object that provides functionality to work with image placement objects. |
| [Accept](../../aspose.pdf/page/accept#accept_2)(TextAbsorber) | Accepts [`TextAbsorber`](../../aspose.pdf.text/textabsorber) visitor object that provides functionality to work with text objects. |
| [Accept](../../aspose.pdf/page/accept#accept_3)(TextFragmentAbsorber) | Accepts [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber) visitor object that provides functionality to work with text objects. |
| [AddImage](../../aspose.pdf/page/addimage#addimage)(Stream, Rectangle) | Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_2)(string, Rectangle) | Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_3)(string, Stream, Rectangle) | Adds searchable image onto the page and locates it in the middle of specified rectangle saving image's proportion. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_1)(Stream, Rectangle, int, int, bool) | Adds image on page and places it depend on image rectangle position. |
| [AddStamp](../../aspose.pdf/page/addstamp)(Stamp) | Put stamp into page. Stamp can be page number, image or simple text, e.g. some logo. |
| [AsByteArray](../../aspose.pdf/page/asbytearray)(Resolution) | Converts current page as bitmap and than returns array of bytes. |
| [AsXml](../../aspose.pdf/page/asxml)() | Converts current page as xml in utf8 encoding. |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox)() | Calculates bbox value - rectangle containing contents without visible margins. |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream)() | Convert page to PNG for DSR, OMR, OCR image stream. |
| [Dispose](../../aspose.pdf/page/dispose)() | Frees up memory |
| [Flatten](../../aspose.pdf/page/flatten)() | Removes all fields located on the page and place their values instead. |
| [FreeMemory](../../aspose.pdf/page/freememory)() | Clears cached data |
| [GetNotifications](../../aspose.pdf/page/getnotifications)() | Returns notifications about inside operations with page content. (Only notifications about paragraph events in text adding scenarios are supported now.) |
| [GetPageRect](../../aspose.pdf/page/getpagerect)(bool) | Returns rectangle of the page. |
| [IsBlank](../../aspose.pdf/page/isblank)(double) | Gets the flag whether page is blank or not. |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale)() | Converts the page to grayscale. |
| [SendTo](../../aspose.pdf/page/sendto#sendto)(PageDevice, Stream) | Sends page to process with given page device. |
| [SendTo](../../aspose.pdf/page/sendto#sendto_1)(PageDevice, string) | Sends page to process with given page device. |
| [SetPageSize](../../aspose.pdf/page/setpagesize)(double, double) | Sets page size for page. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation)(int) | Translates integer value into corresponding rotation enumeration member. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint)(Rotation) | Translates rotation enumeration member into integer value. |

## Other Members

| Name | Description |
| --- | --- |
| delegate [BeforePageGenerate](page.beforepagegenerate) | Procedure for customize header and footer. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf)
* assembly [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
