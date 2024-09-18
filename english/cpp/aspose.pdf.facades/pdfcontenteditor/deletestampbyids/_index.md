---
title: Aspose::Pdf::Facades::PdfContentEditor::DeleteStampByIds method
linktitle: DeleteStampByIds
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfContentEditor::DeleteStampByIds method. Deletes stamps with specified IDs from all pages of the document in C++.'
type: docs
weight: 4200
url: /cpp/aspose.pdf.facades/pdfcontenteditor/deletestampbyids/
---
## PdfContentEditor::DeleteStampByIds(System::ArrayPtr\<int32_t\>) method


Deletes stamps with specified IDs from all pages of the document.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfContentEditor::DeleteStampByIds(System::ArrayPtr<int32_t> stampIds)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stampIds | System::ArrayPtr\<int32_t\> | Array of stamp IDs. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>stampIds</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Array of stamp IDs.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::DeleteStampByIds(int32_t, System::ArrayPtr\<int32_t\>) method


Deletes stamps on the specified page by multiple stamp IDs.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfContentEditor::DeleteStampByIds(int32_t pageNumber, System::ArrayPtr<int32_t> stampIds)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int32_t | [Page](../../../aspose.pdf/page/) number where stamps will be deleted. |
| stampIds | System::ArrayPtr\<int32_t\> | Array of stamp IDs. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>pageNumber</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_page" kindref="compound">Page</ref> number where stamps will be deleted.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>stampIds</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Array of stamp IDs.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
