---
title: Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents method
linktitle: TryResizeContents
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents method. Resizes contents of pages of the document in C++.'
type: docs
weight: 7100
url: /cpp/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## PdfFileEditor::TryResizeContents(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>) method


Resizes contents of pages of the document.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(System::SharedPtr<System::IO::Stream> source, System::SharedPtr<System::IO::Stream> destination, System::ArrayPtr<int32_t> pages, System::SharedPtr<PdfFileEditor::ContentsResizeParameters> parameters)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | System::SharedPtr\<System::IO::Stream\> | Stream with source document. |
| destination | System::SharedPtr\<System::IO::Stream\> | Stream with the destination document. |
| pages | System::ArrayPtr\<int32_t\> | Array of page indexes. |
| parameters | System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\> | Resize parameters. |

### ReturnValue

Returns true if success.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>source</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream with source document.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>destination</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream with the destination document.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pages</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Array of page indexes.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>parameters</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Resize parameters.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

The TryResizeContents method is like the ResizeContents method, except the TryResizeContents method does not throw an exception if the operation fails. 
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryResizeContents(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, double, double) method


Resizes contents of document pages. Shrinks contents of page and adds margins. New size of contents is specified in default space units.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(System::SharedPtr<System::IO::Stream> source, System::SharedPtr<System::IO::Stream> destination, System::ArrayPtr<int32_t> pages, double newWidth, double newHeight)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | System::SharedPtr\<System::IO::Stream\> | Stream which contains source document. |
| destination | System::SharedPtr\<System::IO::Stream\> | Stream where resultant document will be saved. |
| pages | System::ArrayPtr\<int32_t\> | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in default space units. |
| newHeight | double | New height of page contents in default space units. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>source</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream which contains source document.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>destination</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream where resultant document will be saved.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pages</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Array of page indexes. If null then all document pages will be processed.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>newWidth</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>New width of page contents in default space units.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>newHeight</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>New height of page contents in default space units.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

The TryResizeContents method is like the ResizeContents method, except the TryResizeContents method does not throw an exception if the operation fails. 
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryResizeContents(System::String, System::String, System::ArrayPtr\<int32_t\>, System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>) method


Resizes contents of pages in document. If page is shrinked blank margins are added around the page.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(System::String source, System::String destination, System::ArrayPtr<int32_t> pages, System::SharedPtr<PdfFileEditor::ContentsResizeParameters> parameters)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | System::String | Source document path. |
| destination | System::String | Destination document path. |
| pages | System::ArrayPtr\<int32_t\> | Array of page indexes (page index starts from 1). |
| parameters | System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\> | Parameters of page resize. |

### ReturnValue

true if resize was successful.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>source</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Source document path.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>destination</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Destination document path.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pages</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Array of page indexes (page index starts from 1).</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>parameters</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Parameters of page resize.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

The TryResizeContents method is like the ResizeContents method, except the TryResizeContents method does not throw an exception if the operation fails. 
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryResizeContents(System::String, System::ArrayPtr\<int32_t\>, System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Resizes contents of pages in document. If page is shrinked blank margins are added around the page. Result is stored into HttpResponse object.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(System::String source, System::ArrayPtr<int32_t> pages, System::SharedPtr<PdfFileEditor::ContentsResizeParameters> parameters, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | System::String | Path to source file. |
| pages | System::ArrayPtr\<int32_t\> | Array of pages to be resized. |
| parameters | System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\> | Resize parameters. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object where result is saved. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>source</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Path to source file.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pages</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Array of pages to be resized.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>parameters</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Resize parameters.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>response</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>HttpResponse object where result is saved.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

The TryResizeContents method is like the ResizeContents method, except the TryResizeContents method does not throw an exception if the operation fails. 
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryResizeContents(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>, System::SharedPtr\<System::Web::HttpResponse\>) method


Resizes contents of pages in document. If page is shrinked blank margins are added around the page. Result is stored into HttpResponse object.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(System::SharedPtr<System::IO::Stream> source, System::ArrayPtr<int32_t> pages, System::SharedPtr<PdfFileEditor::ContentsResizeParameters> parameters, System::SharedPtr<System::Web::HttpResponse> response)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | System::SharedPtr\<System::IO::Stream\> | Stream of source file. |
| pages | System::ArrayPtr\<int32_t\> | Array of pages to be resized. |
| parameters | System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\> | Resize parameters. |
| response | System::SharedPtr\<System::Web::HttpResponse\> | HttpResponse object where result is saved. |

### ReturnValue

true if operation completed successfully; otherwise, false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>source</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream of source file.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pages</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Array of pages to be resized.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>parameters</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Resize parameters.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>response</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>HttpResponse object where result is saved.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>

The TryResizeContents method is like the ResizeContents method, except the TryResizeContents method does not throw an exception if the operation fails. 
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
