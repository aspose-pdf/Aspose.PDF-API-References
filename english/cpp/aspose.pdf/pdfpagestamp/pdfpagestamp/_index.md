---
title: Aspose::Pdf::PdfPageStamp::PdfPageStamp constructor
linktitle: PdfPageStamp
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PdfPageStamp::PdfPageStamp constructor. Constructor of PdfPageStamp in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf/pdfpagestamp/pdfpagestamp/
---
## PdfPageStamp::PdfPageStamp(System::SharedPtr\<Page\>) constructor


Constructor of [PdfPageStamp](../).

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::PdfPageStamp::PdfPageStamp(System::SharedPtr<Page> pdfPage)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pdfPage | System::SharedPtr\<Page\> | [Page](../../page/) which is used for stamping. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>pdfPage</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_page" kindref="compound">Page</ref> which is used for stamping.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Page](../../page/)
* Class [PdfPageStamp](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfPageStamp::PdfPageStamp(System::String, int32_t) constructor


Creates [Pdf](../../) page stamp from specifed page of the document in specified file.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::PdfPageStamp::PdfPageStamp(System::String fileName, int32_t pageIndex)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fileName | System::String | Name and page of PDF file. |
| pageIndex | int32_t | Index of the page. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>fileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Name and page of PDF file.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pageIndex</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Index of the page.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfPageStamp](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfPageStamp::PdfPageStamp(System::SharedPtr\<System::IO::Stream\>, int32_t) constructor


Creates [Pdf](../../) page stamp from specifed page in the document from the stream.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::PdfPageStamp::PdfPageStamp(System::SharedPtr<System::IO::Stream> stream, int32_t pageIndex)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | Stream which contains PDF |
| pageIndex | int32_t | Index of the page. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>stream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream which contains PDF </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pageIndex</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Index of the page.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfPageStamp](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
