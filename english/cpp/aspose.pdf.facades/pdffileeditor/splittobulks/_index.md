---
title: Aspose::Pdf::Facades::PdfFileEditor::SplitToBulks method
linktitle: SplitToBulks
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::SplitToBulks method. Splits the Pdf file into several documents.The documents can be single-page or multi-pages in C++.'
type: docs
weight: 5600
url: /cpp/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## PdfFileEditor::SplitToBulks(System::String, System::ArrayPtr\<System::ArrayPtr\<int32_t\>\>) method


Splits the [Pdf](../../../aspose.pdf/) file into several documents.The documents can be single-page or multi-pages.

```cpp
ASPOSE_PDF_SHARED_API System::ArrayPtr<System::SharedPtr<System::IO::MemoryStream>> Aspose::Pdf::Facades::PdfFileEditor::SplitToBulks(System::String inputFile, System::ArrayPtr<System::ArrayPtr<int32_t>> numberOfPage)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Input PDF file. |
| numberOfPage | System::ArrayPtr\<System::ArrayPtr\<int32_t\>\> | Array which contains array of double elements, which is start and end pages of document. |

### ReturnValue

Output PDF streams, each stream buffers a PDF document.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input PDF file.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>numberOfPage</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Array which contains array of double elements, which is start and end pages of document.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToBulks(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<System::ArrayPtr\<int32_t\>\>) method


Splits the [Pdf](../../../aspose.pdf/) file into several documents.The documents can be single-page or multi-pages.

```cpp
ASPOSE_PDF_SHARED_API System::ArrayPtr<System::SharedPtr<System::IO::MemoryStream>> Aspose::Pdf::Facades::PdfFileEditor::SplitToBulks(System::SharedPtr<System::IO::Stream> inputStream, System::ArrayPtr<System::ArrayPtr<int32_t>> numberOfPage)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input PDF stream. |
| numberOfPage | System::ArrayPtr\<System::ArrayPtr\<int32_t\>\> | The start page and the end page of each document. |

### ReturnValue

Output PDF streams, each stream buffers a PDF document.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input PDF stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>numberOfPage</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The start page and the end page of each document.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
