---
title: "PdfConverter Class"
linktitle: "PdfConverter"
articleTitle: "PdfConverter"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.PdfConverter class. Represents a class to convert a pdf file's each page to images, supporting BMP, JPEG, PNG and TIFF now. Supported cont..."
type: docs
weight: 330
url: "/net/aspose.pdf.facades/pdfconverter/"
keywords: "PdfConverter, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfConverter class

Represents a class to convert a pdf file's each page to images, supporting BMP, JPEG, PNG and TIFF now.
 Supported content in pdfs: pictures, form, comment.

```csharp
public sealed class PdfConverter : Facade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfConverter](./pdfconverter/#constructor) | Initializes new [`PdfConverter`](../../aspose.pdf.facades/pdfconverter/) object. |
| [PdfConverter](./pdfconverter/#constructor_1)(*[Document](../../aspose.pdf/document/)*) | Initializes new [`PdfConverter`](../../aspose.pdf.facades/pdfconverter/) object on base of the *document*. |

## Properties

| Name | Description |
| --- | --- |
| [CoordinateType](./coordinatetype/) { get; set; } | Gets or sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. *(Inherited from Facade)* |
| [EndPage](./endpage/) { get; set; } | Gets or sets end position which you want to convert. |
| [FormPresentationMode](./formpresentationmode/) { get; set; } | Gets or sets form presentation mode. |
| [PageCount](./pagecount/) { get; } | Gets the page count. |
| [Password](./password/) { get; set; } | Gets or sets document OwnerPassword. |
| [RenderingOptions](./renderingoptions/) { get; set; } | Gets or sets rendering options. |
| [Resolution](./resolution/) { get; set; } | Gets or sets resolution during convertting. The higher resolution, the slower convertting speed. The default value is 150. |
| [ShowHiddenAreas](./showhiddenareas/) { get; set; } | Gets or sets flag that controls visibility of hidden areas on the page. |
| [StartPage](./startpage/) { get; set; } | Gets or sets start position which you want to convert. The minimal value is 1. |
| [UserPassword](./userpassword/) { get; set; } | Gets or sets document UserPassword. |

## Methods

| Name | Description |
| --- | --- |
| [BindPdf](./bindpdf/)(*string*) | Binds a Pdf file for converting. |
| [BindPdf](./bindpdf/)(*Stream*) | Binds a Pdf Stream for convert. |
| [BindPdf](./bindpdf/)(*Document*) | Binds a PDF document to the [`PdfConverter`](../../aspose.pdf.facades/pdfconverter/) instance for further processing. |
| [Close](./close/) | Close the instance of PdfConverter and release the resources. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/) | Disposes the facade. *(Inherited from Facade)* |
| [DoConvert](./doconvert/) | Do some initial works for converting a pdf document to images. |
| [GetNextImage](./getnextimage/)(*string*) | Saves image to file with default image format - jpeg. |
| [GetNextImage](./getnextimage/)(*Stream*) | Saves image to stream with default image format - jpeg. |
| [GetNextImage](./getnextimage/)(*string, PageSize*) | Saves image to file with ith given page size and default image format - jpeg. |
| [GetNextImage](./getnextimage/)(*string, ImageFormat*) | Saves image to file with the givin image format. |
| [GetNextImage](./getnextimage/)(*Stream, PageSize*) | Saves image to stream with given page size. |
| [GetNextImage](./getnextimage/)(*Stream, ImageFormat*) | Saves image to stream with given image format. |
| [GetNextImage](./getnextimage/)(*string, PageSize, ImageFormat*) | Saves image to file with given page size and image format. |
| [GetNextImage](./getnextimage/)(*Stream, PageSize, ImageFormat*) | Saves image to stream with given page size. |
| [GetNextImage](./getnextimage/)(*Stream, ImageFormat, int*) | Saves image to stream with given image format and quality. |
| [GetNextImage](./getnextimage/)(*string, ImageFormat, int*) | Saves image to file with given image format and quality. |
| [GetNextImage](./getnextimage/)(*string, ImageFormat, int, int*) | Saves image to file with the given image format and dimensions. |
| [GetNextImage](./getnextimage/)(*Stream, ImageFormat, int, int*) | Saves image to stream with the givin image format, size and quality. |
| [GetNextImage](./getnextimage/)(*Stream, PageSize, ImageFormat, int*) | Saves image to stream with given page size, image format and quality. |
| [GetNextImage](./getnextimage/)(*string, PageSize, ImageFormat, int*) | Saves image to file with given page size, image format and quality. |
| [GetNextImage](./getnextimage/)(*string, ImageFormat, int, int, int*) | Saves image to file with the given image format, dimensions and quality. |
| [GetNextImage](./getnextimage/)(*Stream, ImageFormat, int, int, int*) | Saves image to stream with the givin image format, dimensions and quality. |
| [GetNextImage](./getnextimage/)(*string, ImageFormat, double, double, int*) | Saves image to file with the givin image format, image size, and quality. |
| [GetNextImage](./getnextimage/)(*Stream, ImageFormat, double, double, int*) | Saves image to stream with the givin image format, size and quality. |
| [HasNextImage](./hasnextimage/) | Indicates whether the pdf file has more images or not. |
| [MergeImages](./mergeimages/)(*List<Stream>, ImageFormat, ImageMergeMode, Nullable<int>, Nullable<int>*) | Merges list of image streams as one image stream. Png/jpg/tiff outputs formats are supported, in case of using non supported format output stream encoded as Jpeg by default. |
| [MergeImagesAsTiff](./mergeimagesastiff/)(*List<Stream>*) | Merges list of tiff streams as one multiple frames tiff stream. |
| [SaveAsTIFF](./saveastiff/)(*string*) | Converts each pages of a pdf document to images and saves images to a single TIFF file. |
| [SaveAsTIFF](./saveastiff/)(*Stream*) | Converts each pages of a pdf document to images and saves images to a single TIFF stream. |
| [SaveAsTIFF](./saveastiff/)(*string, CompressionType*) | Converts each pages of a pdf document to images and saves images to a single TIFF file. |
| [SaveAsTIFF](./saveastiff/)(*string, PageSize*) | Converts each pages of a pdf document to images with page size and saves images to a single TIFF file. |
| [SaveAsTIFF](./saveastiff/)(*Stream, CompressionType*) | Converts each pages of a pdf document to images and saves images to a single TIFF file. |
| [SaveAsTIFF](./saveastiff/)(*Stream, PageSize*) | Converts each pages of a pdf document to images with page size and saves images to a single TIFF stream. |
| [SaveAsTIFF](./saveastiff/)(*string, TiffSettings*) | Converts each pages of a pdf document to images with and saves images to a single TIFF file. |
| [SaveAsTIFF](./saveastiff/)(*Stream, TiffSettings*) | Converts each pages of a pdf document to images and saves images to a single TIFF stream. |
| [SaveAsTIFF](./saveastiff/)(*string, int, int*) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file. |
| [SaveAsTIFF](./saveastiff/)(*string, PageSize, TiffSettings*) | Converts each pages of a pdf document to images with page size and saves images to a single TIFF file. |
| [SaveAsTIFF](./saveastiff/)(*Stream, PageSize, TiffSettings*) | Converts each pages of a pdf document to images with page size and saves images to a single TIFF stream. |
| [SaveAsTIFF](./saveastiff/)(*Stream, int, int*) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream. |
| [SaveAsTIFF](./saveastiff/)(*string, TiffSettings, IIndexBitmapConverter*) | Converts each pages of a pdf document to images with and saves images to a single TIFF file. |
| [SaveAsTIFF](./saveastiff/)(*Stream, TiffSettings, IIndexBitmapConverter*) | Converts each pages of a pdf document to images and saves images to a single TIFF stream. |
| [SaveAsTIFF](./saveastiff/)(*string, int, int, CompressionType*) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file. |
| [SaveAsTIFF](./saveastiff/)(*string, int, int, TiffSettings*) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file. |
| [SaveAsTIFF](./saveastiff/)(*Stream, int, int, CompressionType*) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream. |
| [SaveAsTIFF](./saveastiff/)(*Stream, int, int, TiffSettings*) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream. |
| [SaveAsTIFF](./saveastiff/)(*string, int, int, TiffSettings, IIndexBitmapConverter*) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file. |
| [SaveAsTIFF](./saveastiff/)(*Stream, int, int, TiffSettings, IIndexBitmapConverter*) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(*string*) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF file. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(*Stream*) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(*string, PageSize*) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF file. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(*Stream, PageSize*) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(*string, int, int*) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF file. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(*Stream, int, int*) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream. |

### See Also

* class [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

