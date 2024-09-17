---
title: Aspose::Pdf::Facades::PdfFileEditor::Delete method
linktitle: Delete
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::Delete method. Deletes pages specified by number array from input file, saves as a new Pdf file in C++.'
type: docs
weight: 4900
url: /cpp/aspose.pdf.facades/pdffileeditor/delete/
---
## PdfFileEditor::Delete(System::String, System::ArrayPtr\<int32_t\>, System::String) method


Deletes pages specified by number array from input file, saves as a new [Pdf](../../../aspose.pdf/) file.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::Delete(System::String inputFile, System::ArrayPtr<int32_t> pageNumber, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Input file path. |
| pageNumber | System::ArrayPtr\<int32_t\> | Index of page out of the input file. |
| outputFile | System::String | Output file path. |

### ReturnValue

True if operation was succeeded.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input file path.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pageNumber</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Index of page out of the input file.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output file path.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Delete(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::IO::Stream\>) method


Deletes pages specified by number array from input file, saves as a new [Pdf](../../../aspose.pdf/) file.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::Delete(System::SharedPtr<System::IO::Stream> inputStream, System::ArrayPtr<int32_t> pageNumber, System::SharedPtr<System::IO::Stream> outputStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Input file Stream. |
| pageNumber | System::ArrayPtr\<int32_t\> | Index of page out of the input file. |
| outputStream | System::SharedPtr\<System::IO::Stream\> | Output file stream. |

### ReturnValue

True for success, or false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input file Stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pageNumber</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Index of page out of the input file.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output file stream.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Delete(System::String, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Deletes specified pages from document and stores result into HttpResponse object.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::Delete(System::String inputFile, System::ArrayPtr<int32_t> pageNumber, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | Path of source file. |
| pageNumber | System::ArrayPtr\<int32_t\> | Array of page numbers which must be deleted. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | Response object where result document will be stored. |

### ReturnValue

True if operation was succeeded.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Path of source file.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pageNumber</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Array of page numbers which must be deleted.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>response</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Response object where result document will be stored.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Delete(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Deletes specified pages from document and saves result into HttpResponse object.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::Delete(System::SharedPtr<System::IO::Stream> inputStream, System::ArrayPtr<int32_t> pageNumber, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | System::SharedPtr\<System::IO::Stream\> | Source document stream. |
| pageNumber | System::ArrayPtr\<int32_t\> | Array of page numbers which will be deleted. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object |

### ReturnValue

True if operation succeded.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Source document stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pageNumber</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Array of page numbers which will be deleted.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>response</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>HttpResponse object</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
