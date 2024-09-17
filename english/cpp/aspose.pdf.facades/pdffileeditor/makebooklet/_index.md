---
title: Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet method
linktitle: MakeBooklet
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet method. Makes booklet from the input file to output file in C++.'
type: docs
weight: 5300
url: /cpp/aspose.pdf.facades/pdffileeditor/makebooklet/
---
## PdfFileEditor::MakeBooklet(System::String, System::String) method


Makes booklet from the input file to output file.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(System::String inputFile, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Input pdf file path and name. |
| outputFile | System::String | Output pdf file path and name. |

### ReturnValue

boolean - True for success, or false.
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
</parameterlist>
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>) method


Makes booklet from the InputStream to outputStream.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(System::SharedPtr<System::IO::Stream> inputStream, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input pdf stream. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | output pdf stream. |

### ReturnValue

True if operation was succeeded.
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
      <para>output pdf stream. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(System::String, System::String, System::SharedPtr\<PageSize\>) method


Makes booklet from the inputFile to outputFile.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(System::String inputFile, System::String outputFile, System::SharedPtr<PageSize> pageSize)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Input pdf file path and name. |
| outputFile | System::String | Output pdf file path and name. |
| pageSize | System::SharedPtr\<PageSize\> | The page size of the output pdf file. |

### ReturnValue

True if operation is succeeded.
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
      <parametername>pageSize</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The page size of the output pdf file. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PageSize\>) method


Makes booklet from the input stream and save result into output stream.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(System::SharedPtr<System::IO::Stream> inputStream, System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<PageSize> pageSize)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input PDF stream. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | output pdf stream. |
| pageSize | System::SharedPtr\<PageSize\> | The page size of the output pdf file. |

### ReturnValue

True if operation was succeeded.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input PDF stream. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>output pdf stream. </para>
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

## See Also

* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(System::String, System::String, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<int32_t\>) method


Makes customized booklet from the firstInputFile to outputFile.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(System::String inputFile, System::String outputFile, System::ArrayPtr<int32_t> leftPages, System::ArrayPtr<int32_t> rightPages)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | The input file. |
| outputFile | System::String | Output pdf file path and name. |
| leftPages | System::ArrayPtr\<int32_t\> | The left pages of the booklet. |
| rightPages | System::ArrayPtr\<int32_t\> | The right pages of the booklet. |

### ReturnValue

boolean - True for success, or false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The input file.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output pdf file path and name.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>leftPages</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The left pages of the booklet.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>rightPages</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The right pages of the booklet.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<int32_t\>) method


Makes customized booklet from the firstInputStream to outputStream.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(System::SharedPtr<System::IO::Stream> inputStream, System::SharedPtr<System::IO::Stream> outputStream, System::ArrayPtr<int32_t> leftPages, System::ArrayPtr<int32_t> rightPages)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | The input stream. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | output pdf stream. |
| leftPages | System::ArrayPtr\<int32_t\> | The left pages. |
| rightPages | System::ArrayPtr\<int32_t\> | The right pages. |

### ReturnValue

boolean - True for success, or false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The input stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>output pdf stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>leftPages</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The left pages.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>rightPages</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The right pages.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(System::String, System::String, System::SharedPtr\<PageSize\>, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<int32_t\>) method


Makes customized booklet from the firstInputFile to outputFile.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(System::String inputFile, System::String outputFile, System::SharedPtr<PageSize> pageSize, System::ArrayPtr<int32_t> leftPages, System::ArrayPtr<int32_t> rightPages)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | The input file. |
| outputFile | System::String | Output pdf file path and name. |
| pageSize | System::SharedPtr\<PageSize\> | The page size of the output pdf file. |
| leftPages | System::ArrayPtr\<int32_t\> | The left pages. |
| rightPages | System::ArrayPtr\<int32_t\> | The right pages. |

### ReturnValue

boolean - True for success, or false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The input file.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output pdf file path and name.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pageSize</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The page size of the output pdf file.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>leftPages</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The left pages.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>rightPages</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The right pages.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PageSize\>, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<int32_t\>) method


Makes booklet from the firstInputStream to outputStream.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(System::SharedPtr<System::IO::Stream> inputStream, System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<PageSize> pageSize, System::ArrayPtr<int32_t> leftPages, System::ArrayPtr<int32_t> rightPages)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | The input stream. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | output pdf stream. |
| pageSize | System::SharedPtr\<PageSize\> | The page size of the output pdf file. |
| leftPages | System::ArrayPtr\<int32_t\> | The left pages. |
| rightPages | System::ArrayPtr\<int32_t\> | The right pages. |

### ReturnValue

boolean - True for success, or false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The input stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>output pdf stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pageSize</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The page size of the output pdf file.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>leftPages</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The left pages.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>rightPages</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The right pages.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(System::String, System::SharedPtr\<PageSize\>, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Makes booklet from source file and stores result into HttpResponse objects.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(System::String inputFile, System::SharedPtr<PageSize> pageSize, System::ArrayPtr<int32_t> leftPages, System::ArrayPtr<int32_t> rightPages, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Source file path. |
| pageSize | System::SharedPtr\<PageSize\> | Desired page size. |
| leftPages | System::ArrayPtr\<int32_t\> | Aray of page numbers to be placed in left. |
| rightPages | System::ArrayPtr\<int32_t\> | Array of page numbers to be placed in right. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object where result will be stored. |

### ReturnValue

True if operation was succeeded.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Source file path.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pageSize</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Desired page size.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>leftPages</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Aray of page numbers to be placed in left.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>rightPages</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Array of page numbers to be placed in right.</para>
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
## See Also

* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PageSize\>, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Make booklet from PDF file and stores it into HttpResponse.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(System::SharedPtr<System::IO::Stream> inputStream, System::SharedPtr<PageSize> pageSize, System::ArrayPtr<int32_t> leftPages, System::ArrayPtr<int32_t> rightPages, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input document stream. |
| pageSize | System::SharedPtr\<PageSize\> | Desired page size. |
| leftPages | System::ArrayPtr\<int32_t\> | Array of page numbers which will be placed in left. |
| rightPages | System::ArrayPtr\<int32_t\> | Array of page numbers which will b eplaced in right. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object. |

### ReturnValue

True if operation was succeeded.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input document stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pageSize</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Desired page size.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>leftPages</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Array of page numbers which will be placed in left.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>rightPages</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Array of page numbers which will b eplaced in right.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>response</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>HttpResponse object.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(System::String, System::SharedPtr\<PageSize\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Makes booklet from source file and stores result into HttpResponse objects.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(System::String inputFile, System::SharedPtr<PageSize> pageSize, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Source file path. |
| pageSize | System::SharedPtr\<PageSize\> | Desired page size in output file. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object where result will be stored. |

### ReturnValue

True if operation is succeeded.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Source file path.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pageSize</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Desired page size in output file.</para>
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
## See Also

* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::MakeBooklet(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PageSize\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Makes booklet from source file and stores result into HttpResponse.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::MakeBooklet(System::SharedPtr<System::IO::Stream> inputStream, System::SharedPtr<PageSize> pageSize, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input document stream. |
| pageSize | System::SharedPtr\<PageSize\> | Desired page size in output file. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | Respose object where resut will be saved. |

### ReturnValue

true if booklet was built successfully.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input document stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pageSize</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Desired page size in output file.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>response</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Respose object where resut will be saved.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PageSize](../../../aspose.pdf/pagesize/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
