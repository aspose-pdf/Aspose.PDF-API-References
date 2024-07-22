---
title: Class PdfConverter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfConverter class. Represents a class to convert a pdf files each page to images supporting BMP JPEG PNG and TIFF now. Supported content in pdfs pictures form comment
type: docs
weight: 2900
url: /net/aspose.pdf.facades/pdfconverter/
---
## PdfConverter class

Represents a class to convert a pdf file's each page to images, supporting BMP, JPEG, PNG and TIFF now. Supported content in pdfs: pictures, form, comment.

```csharp
public sealed class PdfConverter : Facade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfConverter](pdfconverter/#constructor)() | Initializes new `PdfConverter` object. |
| [PdfConverter](pdfconverter/#constructor_1)(Document) | Initializes new `PdfConverter` object on base of the *document*. |

## Properties

| Name | Description |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype/) { get; set; } | Gets or sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage/) { get; set; } | Gets or sets end position which you want to convert. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode/) { get; set; } | Gets or sets form presentation mode. |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount/) { get; } | Gets the page count. |
| [Password](../../aspose.pdf.facades/pdfconverter/password/) { get; set; } | Gets or sets document OwnerPassword. |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions/) { get; set; } | Gets or sets rendering options. |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution/) { get; set; } | Gets or sets resolution during convertting. The higher resolution, the slower convertting speed. The default value is 150. |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage/) { get; set; } | Gets or sets start position which you want to convert. The minimal value is 1. |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword/) { get; set; } | Gets or sets document UserPassword. |

## Methods

| Name | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initializes the facade. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_1)(Stream) | Binds a Pdf Stream for convert. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_2)(string) | Binds a Pdf file for converting. |
| override [Close](../../aspose.pdf.facades/pdfconverter/close/)() | Close the instance of PdfConverter and release the resources. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Disposes the facade. |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert/)() | Do some initial works for converting a pdf document to images. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage)(Stream) | Saves image to stream with default image format - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_9)(string) | Saves image to file with default image format - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_4)(Stream, ImageFormat) | Saves image to stream with given image format. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_1)(Stream, PageSize) | Saves image to stream with given page size. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_13)(string, ImageFormat) | Saves image to file with the givin image format. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_10)(string, PageSize) | Saves image to file with ith given page size and default image format - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_6)(Stream, ImageFormat, int) | Saves image to stream with given image format and quality. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_2)(Stream, PageSize, ImageFormat) | Saves image to stream with given page size. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_15)(string, ImageFormat, int) | Saves image to file with given image format and quality. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_11)(string, PageSize, ImageFormat) | Saves image to file with given page size and image format. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_7)(Stream, ImageFormat, int, int) | Saves image to stream with the givin image format, size and quality. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_3)(Stream, PageSize, ImageFormat, int) | Saves image to stream with given page size, image format and quality. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_16)(string, ImageFormat, int, int) | Saves image to file with the given image format and dimensions. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_12)(string, PageSize, ImageFormat, int) | Saves image to file with given page size, image format and quality. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_5)(Stream, ImageFormat, double, double, int) | Saves image to stream with the givin image format, size and quality. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_8)(Stream, ImageFormat, int, int, int) | Saves image to stream with the givin image format, dimensions and quality. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_14)(string, ImageFormat, double, double, int) | Saves image to file with the givin image format, image size, and quality. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_17)(string, ImageFormat, int, int, int) | Saves image to file with the given image format, dimensions and quality. |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage/)() | Indicates whether the pdf file has more images or not. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff)(Stream) | Converts each pages of a pdf document to images and saves images to a single TIFF stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_10)(string) | Converts each pages of a pdf document to images and saves images to a single TIFF file. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_1)(Stream, CompressionType) | Converts each pages of a pdf document to images and saves images to a single TIFF file. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_4)(Stream, PageSize) | Converts each pages of a pdf document to images with page size and saves images to a single TIFF stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_2)(Stream, TiffSettings) | Converts each pages of a pdf document to images and saves images to a single TIFF stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_11)(string, CompressionType) | Converts each pages of a pdf document to images and saves images to a single TIFF file. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_14)(string, PageSize) | Converts each pages of a pdf document to images with page size and saves images to a single TIFF file. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_12)(string, TiffSettings) | Converts each pages of a pdf document to images with and saves images to a single TIFF file. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_6)(Stream, int, int) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_5)(Stream, PageSize, TiffSettings) | Converts each pages of a pdf document to images with page size and saves images to a single TIFF stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | Converts each pages of a pdf document to images and saves images to a single TIFF stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_16)(string, int, int) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_15)(string, PageSize, TiffSettings) | Converts each pages of a pdf document to images with page size and saves images to a single TIFF file. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | Converts each pages of a pdf document to images with and saves images to a single TIFF file. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_7)(Stream, int, int, CompressionType) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_8)(Stream, int, int, TiffSettings) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_17)(string, int, int, CompressionType) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_18)(string, int, int, TiffSettings) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf)(Stream) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_3)(string) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF file. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_1)(Stream, PageSize) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_4)(string, PageSize) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF file. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_2)(Stream, int, int) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_5)(string, int, int) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF file. |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages/)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | Merges list of image streams as one image stream. Png/jpg/tiff outputs formats are supported, in case of using non supported format output stream encoded as Jpeg by default. |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff/)(List&lt;Stream&gt;) | Merges list of tiff streams as one multiple frames tiff stream. |

### See Also

* class [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


