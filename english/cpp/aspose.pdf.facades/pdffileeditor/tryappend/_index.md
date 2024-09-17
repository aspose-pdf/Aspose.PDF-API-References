---
title: Aspose::Pdf::Facades::PdfFileEditor::TryAppend method
linktitle: TryAppend
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::TryAppend method. Appends pages, which are chosen from array of documents in portStreams. The result document includes firstInputFile and all portStreams documents pages in the range startPage to endPage in C++.'
type: docs
weight: 6300
url: /cpp/aspose.pdf.facades/pdffileeditor/tryappend/
---
## PdfFileEditor::TryAppend(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) method


Appends pages, which are chosen from array of documents in portStreams. The result document includes firstInputFile and all portStreams documents pages in the range startPage to endPage.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::TryAppend(System::SharedPtr<System::IO::Stream> inputStream, System::ArrayPtr<System::SharedPtr<System::IO::Stream>> portStreams, int32_t startPage, int32_t endPage, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input [Pdf](../../../aspose.pdf/) stream. |
| portStreams | System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\> | Documents to copy pages from. |
| startPage | int32_t | [Page](../../../aspose.pdf/page/) starts in portStreams documents. |
| endPage | int32_t | [Page](../../../aspose.pdf/page/) ends in portStreams documents . |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output [Pdf](../../../aspose.pdf/) stream. |

### ReturnValue

True for success, or false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input <ref refid="namespace_aspose_1_1_pdf" kindref="compound">Pdf</ref> stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>portStreams</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Documents to copy pages from.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>startPage</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_page" kindref="compound">Page</ref> starts in portStreams documents.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>endPage</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_page" kindref="compound">Page</ref> ends in portStreams documents .</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output <ref refid="namespace_aspose_1_1_pdf" kindref="compound">Pdf</ref> stream.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

The TryAppend method is like the Append method, except the TryAppend method does not throw an exception if the operation fails. 
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryAppend(System::String, System::ArrayPtr\<System::String\>, int32_t, int32_t, System::String) method


Appends pages, which are chosen from portFiles documents. The result document includes firstInputFile and all portFiles documents pages in the range startPage to endPage.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::TryAppend(System::String inputFile, System::ArrayPtr<System::String> portFiles, int32_t startPage, int32_t endPage, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Input [Pdf](../../../aspose.pdf/) file. |
| portFiles | System::ArrayPtr\<System::String\> | Documents to copy pages from. |
| startPage | int32_t | [Page](../../../aspose.pdf/page/) starts in portFiles documents. |
| endPage | int32_t | [Page](../../../aspose.pdf/page/) ends in portFiles documents . |
| outputFile | System::String | Output [Pdf](../../../aspose.pdf/) document. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input <ref refid="namespace_aspose_1_1_pdf" kindref="compound">Pdf</ref> file.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>portFiles</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Documents to copy pages from.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>startPage</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_page" kindref="compound">Page</ref> starts in portFiles documents.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>endPage</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_page" kindref="compound">Page</ref> ends in portFiles documents .</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output <ref refid="namespace_aspose_1_1_pdf" kindref="compound">Pdf</ref> document.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

The TryAppend method is like the Append method, except the TryAppend method does not throw an exception if the operation fails. 
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryAppend(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>, int32_t, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) method


Appends documents to source document and saves result into response object.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::TryAppend(System::SharedPtr<System::IO::Stream> inputStream, System::ArrayPtr<System::SharedPtr<System::IO::Stream>> portStreams, int32_t startPage, int32_t endPage, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Stream which contains source document. |
| portStreams | System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\> | Array of streams with documents to be appended. |
| startPage | int32_t | Start page of appended page. |
| endPage | int32_t | End page of appended pages. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | Response object where document will be saved. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream which contains source document.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>portStreams</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Array of streams with documents to be appended.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>startPage</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Start page of appended page.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>endPage</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>End page of appended pages.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>response</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Response object where document will be saved.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

The TryAppend method is like the Append method, except the TryAppend method does not throw an exception if the operation fails. 
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryAppend(System::String, System::ArrayPtr\<System::String\>, int32_t, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) method


Appends documents to source document and saves result into HttpResponse object.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::TryAppend(System::String inputFile, System::ArrayPtr<System::String> portFiles, int32_t startPage, int32_t endPage, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Name of file containing source document. |
| portFiles | System::ArrayPtr\<System::String\> | Array of file names containing appended documents. |
| startPage | int32_t | Start page of appended pages. |
| endPage | int32_t | End page of appended pages. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | Response object where document will be saved. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Name of file containing source document.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>portFiles</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Array of file names containing appended documents.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>startPage</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Start page of appended pages.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>endPage</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>End page of appended pages.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>response</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Response object where document will be saved.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

The TryAppend method is like the Append method, except the TryAppend method does not throw an exception if the operation fails. 
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
