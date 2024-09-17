---
title: Aspose::Pdf::Facades::PdfPageEditor::GetPageBoxSize method
linktitle: GetPageBoxSize
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfPageEditor::GetPageBoxSize method. Returns size of specified box in document in C++.'
type: docs
weight: 2600
url: /cpp/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## PdfPageEditor::GetPageBoxSize method


Returns size of specified box in document.

```cpp
ASPOSE_PDF_SHARED_API System::Drawing::Rectangle Aspose::Pdf::Facades::PdfPageEditor::GetPageBoxSize(int32_t page, System::String pageBoxName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | int32_t | [Page](../../../aspose.pdf/page/) index. [Document](../../../aspose.pdf/document/) pages are numbered from 1. |
| pageBoxName | System::String | Box type name. Valid values are: "art", "bleed", "crop", "media", "trim". |

### ReturnValue

[Rectangle](../../../aspose.pdf/rectangle/) which contains requested box.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>page</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_page" kindref="compound">Page</ref> index. <ref refid="class_aspose_1_1_pdf_1_1_document" kindref="compound">Document</ref> pages are numbered from 1.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pageBoxName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Box type name. Valid values are: "art", "bleed", "crop", "media", "trim".</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfPageEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
