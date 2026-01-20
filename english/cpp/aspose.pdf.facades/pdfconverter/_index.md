---
title: Aspose::Pdf::Facades::PdfConverter class
linktitle: PdfConverter
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfConverter class. Represents a class to convert a pdf file''s each page to images, supporting BMP, JPEG, PNG and TIFF now. Supported content in pdfs: pictures, form, comment in C++.'
type: docs
weight: 1800
url: /cpp/aspose.pdf.facades/pdfconverter/
---
## PdfConverter class


Represents a class to convert a pdf file's each page to images, supporting BMP, JPEG, PNG and TIFF now. Supported content in pdfs: pictures, form, comment.

```cpp
class PdfConverter : public Aspose::Pdf::Facades::Facade
```

## Methods

| Method | Description |
| --- | --- |
| [BindPdf](./bindpdf/)(System::String) override | Binds a [Pdf](../../aspose.pdf/) file for converting. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Binds a [Pdf](../../aspose.pdf/) Stream for convert. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<Aspose::Pdf::Document\>) override | Binds a PDF document to the [PdfConverter](./) instance for further processing. |
| [Close](./close/)() override | Close the instance of [PdfConverter](./) and release the resources. |
| [DoConvert](./doconvert/)() | Do some initial works for converting a pdf document to images. |
| [get_CoordinateType](./get_coordinatetype/)() const | Gets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [get_EndPage](./get_endpage/)() | Gets end position which you want to convert. |
| [get_FormPresentationMode](./get_formpresentationmode/)() const | Gets form presentation mode. |
| [get_PageCount](./get_pagecount/)() | Gets the page count. |
| [get_Password](./get_password/)() const | Gets document OwnerPassword. |
| [get_RenderingOptions](./get_renderingoptions/)() const | Gets rendering options. |
| [get_Resolution](./get_resolution/)() const | Gets resolution during convertting. The higher resolution, the slower convertting speed. The default value is 150. |
| [get_ShowHiddenAreas](./get_showhiddenareas/)() const | Gets flag that controls visibility of hidden areas on the page. |
| [get_StartPage](./get_startpage/)() const | Gets start position which you want to convert. The minimal value is 1. |
| [get_UserPassword](./get_userpassword/)() const | Gets document UserPassword. |
| [GetNextImage](./getnextimage/)(System::String) | Saves image to file with default image format - jpeg. |
| [GetNextImage](./getnextimage/)(System::String, System::SharedPtr\<PageSize\>) | Saves image to file with ith given page size and default image format - jpeg. |
| [GetNextImage](./getnextimage/)(System::String, System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>) | Saves image to file with the givin image format. |
| [GetNextImage](./getnextimage/)(System::String, System::SharedPtr\<PageSize\>, System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>) | Saves image to file with given page size and image format. |
| [GetNextImage](./getnextimage/)(System::SharedPtr\<System::IO::Stream\>) | Saves image to stream with default image format - jpeg. |
| [GetNextImage](./getnextimage/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PageSize\>) | Saves image to stream with given page size. |
| [GetNextImage](./getnextimage/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>) | Saves image to stream with given image format. |
| [GetNextImage](./getnextimage/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PageSize\>, System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>) | Saves image to stream with given page size. |
| [GetNextImage](./getnextimage/)(System::String, System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>, int32_t, int32_t, int32_t) | Saves image to file with the given image format, dimensions and quality. |
| [GetNextImage](./getnextimage/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>, int32_t, int32_t, int32_t) | Saves image to stream with the givin image format, dimensions and quality. |
| [GetNextImage](./getnextimage/)(System::String, System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>, double, double, int32_t) | Saves image to file with the givin image format, image size, and quality. |
| [GetNextImage](./getnextimage/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>, double, double, int32_t) | Saves image to stream with the givin image format, size and quality. |
| [GetNextImage](./getnextimage/)(System::String, System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>, int32_t, int32_t) | Saves image to file with the given image format and dimensions. |
| [GetNextImage](./getnextimage/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>, int32_t, int32_t) | Saves image to stream with the givin image format, size and quality. |
| [GetNextImage](./getnextimage/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>, int32_t) | Saves image to stream with given image format and quality. |
| [GetNextImage](./getnextimage/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PageSize\>, System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>, int32_t) | Saves image to stream with given page size, image format and quality. |
| [GetNextImage](./getnextimage/)(System::String, System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>, int32_t) | Saves image to file with given image format and quality. |
| [GetNextImage](./getnextimage/)(System::String, System::SharedPtr\<PageSize\>, System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>, int32_t) | Saves image to file with given page size, image format and quality. |
| [HasNextImage](./hasnextimage/)() | Indicates whether the pdf file has more images or not. |
| static [MergeImages](./mergeimages/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::IO::Stream\>\>\>, Aspose::Pdf::Drawing::ImageFormat, ImageMergeMode, System::Nullable\<int32_t\>, System::Nullable\<int32_t\>) | Merges list of image streams as one image stream. Png/jpg/tiff outputs formats are supported, in case of using non supported format output stream encoded as Jpeg by default. |
| static [MergeImagesAsTiff](./mergeimagesastiff/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::IO::Stream\>\>\>) | Merges list of tiff streams as one multiple frames tiff stream. |
| [PdfConverter](./pdfconverter/)() | Initializes new [PdfConverter](./) object. |
| [PdfConverter](./pdfconverter/)(System::SharedPtr\<Aspose::Pdf::Document\>) | Initializes new [PdfConverter](./) object on base of the *document* . |
| [SaveAsTIFF](./saveastiff/)(System::String) | Converts each pages of a pdf document to images and saves images to a single TIFF file. |
| [SaveAsTIFF](./saveastiff/)(System::String, Devices::CompressionType) | Converts each pages of a pdf document to images and saves images to a single TIFF file. |
| [SaveAsTIFF](./saveastiff/)(System::String, int32_t, int32_t) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file. |
| [SaveAsTIFF](./saveastiff/)(System::String, System::SharedPtr\<PageSize\>) | Converts each pages of a pdf document to images with page size and saves images to a single TIFF file. |
| [SaveAsTIFF](./saveastiff/)(System::String, System::SharedPtr\<PageSize\>, System::SharedPtr\<Devices::TiffSettings\>) | Converts each pages of a pdf document to images with page size and saves images to a single TIFF file. |
| [SaveAsTIFF](./saveastiff/)(System::String, int32_t, int32_t, Devices::CompressionType) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file. |
| [SaveAsTIFF](./saveastiff/)(System::String, int32_t, int32_t, System::SharedPtr\<Devices::TiffSettings\>) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file. |
| [SaveAsTIFF](./saveastiff/)(System::String, int32_t, int32_t, System::SharedPtr\<Devices::TiffSettings\>, System::SharedPtr\<IIndexBitmapConverter\>) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file. |
| [SaveAsTIFF](./saveastiff/)(System::SharedPtr\<System::IO::Stream\>) | Converts each pages of a pdf document to images and saves images to a single TIFF stream. |
| [SaveAsTIFF](./saveastiff/)(System::SharedPtr\<System::IO::Stream\>, Devices::CompressionType) | Converts each pages of a pdf document to images and saves images to a single TIFF file. |
| [SaveAsTIFF](./saveastiff/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PageSize\>) | Converts each pages of a pdf document to images with page size and saves images to a single TIFF stream. |
| [SaveAsTIFF](./saveastiff/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PageSize\>, System::SharedPtr\<Devices::TiffSettings\>) | Converts each pages of a pdf document to images with page size and saves images to a single TIFF stream. |
| [SaveAsTIFF](./saveastiff/)(System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream. |
| [SaveAsTIFF](./saveastiff/)(System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, Devices::CompressionType) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream. |
| [SaveAsTIFF](./saveastiff/)(System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::SharedPtr\<Devices::TiffSettings\>) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream. |
| [SaveAsTIFF](./saveastiff/)(System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::SharedPtr\<Devices::TiffSettings\>, System::SharedPtr\<IIndexBitmapConverter\>) | Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream. |
| [SaveAsTIFF](./saveastiff/)(System::String, System::SharedPtr\<Devices::TiffSettings\>) | Converts each pages of a pdf document to images with and saves images to a single TIFF file. |
| [SaveAsTIFF](./saveastiff/)(System::String, System::SharedPtr\<Devices::TiffSettings\>, System::SharedPtr\<IIndexBitmapConverter\>) | Converts each pages of a pdf document to images with and saves images to a single TIFF file. |
| [SaveAsTIFF](./saveastiff/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Devices::TiffSettings\>) | Converts each pages of a pdf document to images and saves images to a single TIFF stream. |
| [SaveAsTIFF](./saveastiff/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Devices::TiffSettings\>, System::SharedPtr\<IIndexBitmapConverter\>) | Converts each pages of a pdf document to images and saves images to a single TIFF stream. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(System::String, int32_t, int32_t) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF file. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(System::String, System::SharedPtr\<PageSize\>) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF file. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PageSize\>) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(System::String) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF file. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(System::SharedPtr\<System::IO::Stream\>) | Converts each pages of a pdf document to images and save images to a single TIFF ClassF stream. |
| [set_CoordinateType](./set_coordinatetype/)(PageCoordinateType) | Sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [set_EndPage](./set_endpage/)(int32_t) | Sets end position which you want to convert. |
| [set_FormPresentationMode](./set_formpresentationmode/)(Aspose::Pdf::Devices::FormPresentationMode) | Sets form presentation mode. |
| [set_Password](./set_password/)(System::String) | Sets document OwnerPassword. |
| [set_RenderingOptions](./set_renderingoptions/)(System::SharedPtr\<Aspose::Pdf::RenderingOptions\>) | Sets rendering options. |
| [set_Resolution](./set_resolution/)(System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>) | Sets resolution during convertting. The higher resolution, the slower convertting speed. The default value is 150. |
| [set_ShowHiddenAreas](./set_showhiddenareas/)(bool) | Sets flag that controls visibility of hidden areas on the page. |
| [set_StartPage](./set_startpage/)(int32_t) | Sets start position which you want to convert. The minimal value is 1. |
| [set_UserPassword](./set_userpassword/)(System::String) | Sets document UserPassword. |
## See Also

* Class [Facade](../facade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
