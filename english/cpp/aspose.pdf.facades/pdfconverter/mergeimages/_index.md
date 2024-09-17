---
title: Aspose::Pdf::Facades::PdfConverter::MergeImages method
linktitle: MergeImages
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfConverter::MergeImages method. Merges list of image streams as one image stream. Png/jpg/tiff outputs formats are supported, in case of using non supported format output stream encoded as Jpeg by default in C++.'
type: docs
weight: 2800
url: /cpp/aspose.pdf.facades/pdfconverter/mergeimages/
---
## PdfConverter::MergeImages method


Merges list of image streams as one image stream. Png/jpg/tiff outputs formats are supported, in case of using non supported format output stream encoded as Jpeg by default.

```cpp
static ASPOSE_PDF_SHARED_API System::SharedPtr<System::IO::Stream> Aspose::Pdf::Facades::PdfConverter::MergeImages(System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::IO::Stream>>> inputImagesStreams, Aspose::Pdf::Drawing::ImageFormat outputImageFormat, ImageMergeMode mergeMode, System::Nullable<int32_t> horizontal, System::Nullable<int32_t> vertical)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputImagesStreams | System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::IO::Stream\>\>\> | The list of image streams to merge. |
| outputImageFormat | Aspose::Pdf::Drawing::ImageFormat | [Image](../../../aspose.pdf/image/) output format for merged stream. |
| mergeMode | ImageMergeMode | Merge mode. Used for Png/Jpg formats. |
| horizontal | System::Nullable\<int32_t\> | Horizontal ratio to set canvas width for output image stream. Used for Png/Jpg formats with [ImageMergeMode.Center](../../imagemergemode/) only. |
| vertical | System::Nullable\<int32_t\> | Vertical ratio to set canvas height for output image stream. Used for Png/Jpg formats with [ImageMergeMode.Center](../../imagemergemode/) only. |

### ReturnValue

[Image](../../../aspose.pdf/image/) stream encoded as output image format.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputImagesStreams</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The list of image streams to merge.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputImageFormat</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_image" kindref="compound">Image</ref> output format for merged stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>mergeMode</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Merge mode. Used for Png/Jpg formats.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>horizontal</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Horizontal ratio to set canvas width for output image stream. Used for Png/Jpg formats with <ref refid="namespace_aspose_1_1_pdf_1_1_facades_1aa778c9b7ef0d884eb6bb5a7999c3023ca4f1f6016fc9f3f2353c0cc7c67b292bd" kindref="member">ImageMergeMode.Center</ref> only.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>vertical</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Vertical ratio to set canvas height for output image stream. Used for Png/Jpg formats with <ref refid="namespace_aspose_1_1_pdf_1_1_facades_1aa778c9b7ef0d884eb6bb5a7999c3023ca4f1f6016fc9f3f2353c0cc7c67b292bd" kindref="member">ImageMergeMode.Center</ref> only.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* Enum [ImageMergeMode](../../imagemergemode/)
* Class [PdfConverter](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
