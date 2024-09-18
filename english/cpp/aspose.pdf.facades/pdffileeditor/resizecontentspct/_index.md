---
title: Aspose::Pdf::Facades::PdfFileEditor::ResizeContentsPct method
linktitle: ResizeContentsPct
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::ResizeContentsPct method. Resizes contents of document pages. Shrinks contents of page and adds margins. New contents size is specified in percents in C++.'
type: docs
weight: 5800
url: /cpp/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## PdfFileEditor::ResizeContentsPct(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, double, double) method


Resizes contents of document pages. Shrinks contents of page and adds margins. New contents size is specified in percents.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContentsPct(System::SharedPtr<System::IO::Stream> source, System::SharedPtr<System::IO::Stream> destination, System::ArrayPtr<int32_t> pages, double newWidth, double newHeight)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | System::SharedPtr\<System::IO::Stream\> | Stream which contains source document. |
| destination | System::SharedPtr\<System::IO::Stream\> | Stream where resultant document will be saved. |
| pages | System::ArrayPtr\<int32_t\> | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in percents. |
| newHeight | double | New height of page contents in percetns. |

### ReturnValue

true if resized sucessfully.
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
      <para>New width of page contents in percents.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>newHeight</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>New height of page contents in percetns.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContentsPct(System::String, System::String, System::ArrayPtr\<int32_t\>, double, double) method


Resizes contents of document pages. Shrinks contents of page and adds margins. New contents size is specified in percents.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContentsPct(System::String source, System::String destination, System::ArrayPtr<int32_t> pages, double newWidth, double newHeight)
```


| Parameter | Type | Description |
| --- | --- | --- |
| source | System::String | Path to source document. |
| destination | System::String | Path where resultant document will be saved. |
| pages | System::ArrayPtr\<int32_t\> | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in percents. |
| newHeight | double | New height of page contents in percetns. |

### ReturnValue

true if resize was successful.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>source</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Path to source document.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>destination</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Path where resultant document will be saved.</para>
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
      <para>New width of page contents in percents.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>newHeight</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>New height of page contents in percetns.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
