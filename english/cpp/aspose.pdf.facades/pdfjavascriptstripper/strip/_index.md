---
title: Aspose::Pdf::Facades::PdfJavaScriptStripper::Strip method
linktitle: Strip
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfJavaScriptStripper::Strip method. Remove Java Script from document in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.facades/pdfjavascriptstripper/strip/
---
## PdfJavaScriptStripper::Strip(System::String, System::String) method


Remove Java Script from document.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfJavaScriptStripper::Strip(System::String inputFile, System::String outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | System::String | File containig the document. |
| outputFile | System::String | File where document will be stored. |

### ReturnValue

true if JavaScript was stripped successfully.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>File containig the document.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outputFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>File where document will be stored.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfJavaScriptStripper](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfJavaScriptStripper::Strip(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>) method


Remove Java Script from the document.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::PdfJavaScriptStripper::Strip(System::SharedPtr<System::IO::Stream> inStream, System::SharedPtr<System::IO::Stream> outStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inStream | System::SharedPtr\<System::IO::Stream\> | Stream containing document. |
| outStream | System::SharedPtr\<System::IO::Stream\> | Stream where the document will be stored. |

### ReturnValue

true if JavaScript was stripped successfully.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream containing document.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>outStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream where the document will be stored.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfJavaScriptStripper](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
