---
title: Aspose::Pdf::Forms::SignatureField::ExtractImage method
linktitle: ExtractImage
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::SignatureField::ExtractImage method. Extracts signature''s image as jpeg encoded stream in C++.'
type: docs
weight: 400
url: /cpp/aspose.pdf.forms/signaturefield/extractimage/
---
## SignatureField::ExtractImage() method


Extracts signature's image as jpeg encoded stream.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<System::IO::Stream> Aspose::Pdf::Forms::SignatureField::ExtractImage()
```


### ReturnValue

If image was successfully found than returns jpeg encoded stream object; otherwise, null.

## See Also

* Class [SignatureField](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## SignatureField::ExtractImage(System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>) method


Extracts signature's image as encoded stream.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<System::IO::Stream> Aspose::Pdf::Forms::SignatureField::ExtractImage(System::SharedPtr<System::Drawing::Imaging::ImageFormat> format)
```


| Parameter | Type | Description |
| --- | --- | --- |
| format | System::SharedPtr\<System::Drawing::Imaging::ImageFormat\> | [Image](../../../aspose.pdf/image/) format for encoding. |

### ReturnValue

If image was successfully found than returns encodedstream object; otherwise, null.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>format</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_image" kindref="compound">Image</ref> format for encoding.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [SignatureField](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
