---
title: Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp method
linktitle: TryMakeNUp
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp method. Makes N-Up document from the firstInputFile to outputFile in C++.'
type: docs
weight: 7000
url: /cpp/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## PdfFileEditor::TryMakeNUp(System::String, System::String, int32_t, int32_t) method


Makes N-Up document from the firstInputFile to outputFile.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(System::String inputFile, System::String outputFile, int32_t x, int32_t y)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Input pdf file path and name. |
| outputFile | System::String | Output pdf file path and name. |
| x | int32_t | Number of columns. |
| y | int32_t | Number of rows. |

### ReturnValue

true if operation was completed successfully; otherwise, false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input pdf file path and name. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output pdf file path and name. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>x</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Number of columns. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>y</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Number of rows. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails. 
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t) method


Makes N-Up document from the input stream and saves result into output stream.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(System::SharedPtr<System::IO::Stream> inputStream, System::SharedPtr<System::IO::Stream> outputStream, int32_t x, int32_t y)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input pdf stream. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output pdf stream. |
| x | int32_t | Number of columns. |
| y | int32_t | Number of rows. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input pdf stream. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output pdf stream. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>x</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Number of columns. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>y</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Number of rows. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails. 
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::SharedPtr\<PageSize\>) method


Makes N-Up document from the first input stream to output stream.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(System::SharedPtr<System::IO::Stream> inputStream, System::SharedPtr<System::IO::Stream> outputStream, int32_t x, int32_t y, System::SharedPtr<PageSize> pageSize)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input pdf stream. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output pdf stream. |
| x | int32_t | Number of columns. |
| y | int32_t | Number of rows. |
| pageSize | System::SharedPtr\<PageSize\> | The page size of the output pdf file. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input pdf stream. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output pdf stream. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>x</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Number of columns. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>y</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Number of rows. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pageSize</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The page size of the output pdf file. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails. 
## See Also

* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(System::String, System::String, System::String) method


Makes N-Up document from the two input PDF files to outputFile. Each page of outputFile will contain two pages, one page is from the first input file and another is from the second input file. The two pages are piled up horizontally.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(System::String firstInputFile, System::String secondInputFile, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | System::String | first input file. |
| secondInputFile | System::String | second input file. |
| outputFile | System::String | Output pdf file path and name. |

### ReturnValue

true if operation was completed successfully; otherwise, false
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>firstInputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>first input file. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>secondInputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>second input file. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output pdf file path and name. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails. 
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>) method


Makes N-Up document from the two input PDF streams to outputStream.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(System::SharedPtr<System::IO::Stream> firstInputStream, System::SharedPtr<System::IO::Stream> secondInputStream, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | System::SharedPtr\<System::IO::Stream\> | first input stream. |
| secondInputStream | System::SharedPtr\<System::IO::Stream\> | second input stream. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output pdf stream. |

### ReturnValue

true if operation was completed successfully; otherwise, false
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>firstInputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>first input stream. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>secondInputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>second input stream. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output pdf stream. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails. 
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(System::ArrayPtr\<System::String\>, System::String, bool) method


Makes N-Up document from the multi input PDF files to outputFile. Each page of outputFile will contain multi pages, which are combination with pages in the input files of the same page number. The multi pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(System::ArrayPtr<System::String> inputFiles, System::String outputFile, bool isSidewise)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | System::ArrayPtr\<System::String\> | Input [Pdf](../../../aspose.pdf/) files. |
| outputFile | System::String | Output pdf file path and name. |
| isSidewise | bool | Piled up way, true for horizontally and false for vertically. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputFiles</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input <ref refid="namespace_aspose_1_1_pdf" kindref="compound">Pdf</ref> files.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output pdf file path and name. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>isSidewise</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Piled up way, true for horizontally and false for vertically.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails. 
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>, System::SharedPtr\<System::IO::Stream\>, bool) method


Makes N-Up document from the multi input PDF streams to outputStream. Each page of outputStream will contain multi pages, which are combination with pages in the input streams of the same page number. The multi-pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(System::ArrayPtr<System::SharedPtr<System::IO::Stream>> inputStreams, System::SharedPtr<System::IO::Stream> outputStream, bool isSidewise)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStreams | System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\> | Input [Pdf](../../../aspose.pdf/) streams. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output pdf stream. |
| isSidewise | bool | Piled up way, true for horizontally and false for vertically. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputStreams</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input <ref refid="namespace_aspose_1_1_pdf" kindref="compound">Pdf</ref> streams.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output pdf stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>isSidewise</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Piled up way, true for horizontally and false for vertically.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails. 
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(System::String, System::String, int32_t, int32_t, System::SharedPtr\<PageSize\>) method


Makes N-Up document from the input file to outputFile.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(System::String inputFile, System::String outputFile, int32_t x, int32_t y, System::SharedPtr<PageSize> pageSize)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Input pdf file path and name. |
| outputFile | System::String | Output pdf file path and name. |
| x | int32_t | Number of columns. |
| y | int32_t | Number of rows. |
| pageSize | System::SharedPtr\<PageSize\> | The page size of the output pdf file. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input pdf file path and name. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output pdf file path and name. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>x</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Number of columns. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>y</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Number of rows. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pageSize</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The page size of the output pdf file. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails. 
## See Also

* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(System::String, int32_t, int32_t, System::SharedPtr\<PageSize\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Makes N-up document and stores result into HttpResponse object.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(System::String inputFile, int32_t x, int32_t y, System::SharedPtr<PageSize> pageSize, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Path to source file. |
| x | int32_t | Number of columns. |
| y | int32_t | Number of rows. |
| pageSize | System::SharedPtr\<PageSize\> | [Page](../../../aspose.pdf/page/) size in result file. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object where result will be stored. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Path to source file.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>x</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Number of columns.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>y</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Number of rows.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pageSize</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_page" kindref="compound">Page</ref> size in result file.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>response</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>HttpResponse object where result will be stored.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails. 
## See Also

* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::SharedPtr\<PageSize\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Makes N-up document and stores result into HttpResponse object.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(System::SharedPtr<System::IO::Stream> inputStream, int32_t x, int32_t y, System::SharedPtr<PageSize> pageSize, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Stream of source document. |
| x | int32_t | Number of columns. |
| y | int32_t | Number of rows. |
| pageSize | System::SharedPtr\<PageSize\> | [Page](../../../aspose.pdf/page/) size in result file. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object where result will be stored. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream of source document.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>x</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Number of columns.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>y</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Number of rows.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pageSize</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_page" kindref="compound">Page</ref> size in result file.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>response</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>HttpResponse object where result will be stored.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails. 
## See Also

* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(System::String, int32_t, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) method


Makes N-up document and stores result into HttpResponse.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(System::String inputFile, int32_t x, int32_t y, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Source file name. |
| x | int32_t | Number of columns. |
| y | int32_t | Number of rows. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object where result will be stored. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Source file name.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>x</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Number of columns.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>y</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Number of rows.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>response</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>HttpResponse object where result will be stored.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails. 
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryMakeNUp(System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) method


Makes N-up document and stores result into HttpResponse.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::TryMakeNUp(System::SharedPtr<System::IO::Stream> inputStream, int32_t x, int32_t y, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Stream of input document. |
| x | int32_t | Number of columns. |
| y | int32_t | Number of rows. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse where result will be stored. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream of input document.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>x</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Number of columns.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>y</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Number of rows.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>response</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>HttpResponse where result will be stored.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

The TryMakeNUp method is like the MakeNUp method, except the TryMakeNUp method does not throw an exception if the operation fails. 
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
