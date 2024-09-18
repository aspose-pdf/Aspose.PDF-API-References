---
title: Aspose::Pdf::Facades::PdfFileEditor::Concatenate method
linktitle: Concatenate
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::Concatenate method. Concatenates two files in C++.'
type: docs
weight: 4600
url: /cpp/aspose.pdf.facades/pdffileeditor/concatenate/
---
## PdfFileEditor::Concatenate(System::String, System::String, System::String) method


Concatenates two files.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::Concatenate(System::String firstInputFile, System::String secInputFile, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | System::String | First file to concatenate. |
| secInputFile | System::String | Second file to concatenate. |
| outputFile | System::String | Output file. |

### ReturnValue

True if operation was succeeded.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>firstInputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>First file to concatenate.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>secInputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Second file to concatenate.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output file.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Concatenate(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>) method


Concatenates two files.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::Concatenate(System::SharedPtr<System::IO::Stream> firstInputStream, System::SharedPtr<System::IO::Stream> secInputStream, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | System::SharedPtr\<System::IO::Stream\> | Stream of first file. |
| secInputStream | System::SharedPtr\<System::IO::Stream\> | Stream of second file. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Stream where result file will be stored. |

### ReturnValue

True if operation was succeeded.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>firstInputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream of first file.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>secInputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream of second file.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream where result file will be stored.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Concatenate(System::ArrayPtr\<System::SharedPtr\<Document\>\>, System::SharedPtr\<Document\>) method


Concatenates documents.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::Concatenate(System::ArrayPtr<System::SharedPtr<Document>> src, System::SharedPtr<Document> dest)
```


| Parameter | Type | Description |
| --- | --- | --- |
| src | System::ArrayPtr\<System::SharedPtr\<Document\>\> | Array of source documents. |
| dest | System::SharedPtr\<Document\> | Destination document. |

### ReturnValue

True if concatenation is successful.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>src</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Array of source documents.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>dest</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Destination document.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../../../aspose.pdf/document/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Concatenate(System::ArrayPtr\<System::String\>, System::String) method


Concatenates files into one file.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::Concatenate(System::ArrayPtr<System::String> inputFiles, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | System::ArrayPtr\<System::String\> | Array of files to concatenate. |
| outputFile | System::String | Name of output file. |

### ReturnValue

True if operation was succeeded.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputFiles</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Array of files to concatenate.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Name of output file.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Concatenate(System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>, System::SharedPtr\<System::IO::Stream\>) method


Concatenates files.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::Concatenate(System::ArrayPtr<System::SharedPtr<System::IO::Stream>> inputStream, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\> | Array of streams to be concatenated. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Stream where result file will be stored. |

### ReturnValue

True if operation was succeeded.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Array of streams to be concatenated.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream where result file will be stored.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Concatenate(System::String, System::String, System::String, System::String) method


Merges two [Pdf](../../../aspose.pdf/) documents into a new [Pdf](../../../aspose.pdf/) document with pages in alternate ways and fill the blank places with blank pages. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'. Merging the two [Pdf](../../../aspose.pdf/) document will produce the result document with pages:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::Concatenate(System::String firstInputFile, System::String secInputFile, System::String blankPageFile, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | System::String | First file. |
| secInputFile | System::String | Second file. |
| blankPageFile | System::String | PDF file with blank page. |
| outputFile | System::String | Result file. |

### ReturnValue

True if operation was succeeded.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>firstInputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>First file.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>secInputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Second file.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>blankPageFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>PDF file with blank page.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Result file.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Concatenate(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>) method


Merges two [Pdf](../../../aspose.pdf/) documents into a new [Pdf](../../../aspose.pdf/) document with pages in alternate ways and fill the blank places with blank pages. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'. Merging the two [Pdf](../../../aspose.pdf/) document will produce the result document with pages:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::Concatenate(System::SharedPtr<System::IO::Stream> firstInputStream, System::SharedPtr<System::IO::Stream> secInputStream, System::SharedPtr<System::IO::Stream> blankPageStream, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | System::SharedPtr\<System::IO::Stream\> | The first [Pdf](../../../aspose.pdf/) Stream. |
| secInputStream | System::SharedPtr\<System::IO::Stream\> | The second [Pdf](../../../aspose.pdf/) Stream. |
| blankPageStream | System::SharedPtr\<System::IO::Stream\> | The [Pdf](../../../aspose.pdf/) Stream with blank page. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output [Pdf](../../../aspose.pdf/) Stream. |

### ReturnValue

True if operation was succeeded.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>firstInputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The first <ref refid="namespace_aspose_1_1_pdf" kindref="compound">Pdf</ref> Stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>secInputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The second <ref refid="namespace_aspose_1_1_pdf" kindref="compound">Pdf</ref> Stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>blankPageStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The <ref refid="namespace_aspose_1_1_pdf" kindref="compound">Pdf</ref> Stream with blank page.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output <ref refid="namespace_aspose_1_1_pdf" kindref="compound">Pdf</ref> Stream.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Concatenate(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Concatenates files and saves reslt into HttpResposnse object.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::Concatenate(System::ArrayPtr<System::String> inputFiles, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | System::ArrayPtr\<System::String\> | Array of files to concatenate. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | Response object. |

### ReturnValue

true if concatenation was successful.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputFiles</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Array of files to concatenate.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>response</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Response object.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Concatenate(System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Concatenates files and stores result into HttpResponse object.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::Concatenate(System::ArrayPtr<System::SharedPtr<System::IO::Stream>> inputStream, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\> | Streams array which contain files to concatenate. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | Response object/ |

### ReturnValue

true if operation was succeeded.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Streams array which contain files to concatenate.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>response</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Response object/</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
