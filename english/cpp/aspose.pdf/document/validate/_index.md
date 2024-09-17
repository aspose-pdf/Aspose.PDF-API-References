---
title: Aspose::Pdf::Document::Validate method
linktitle: Validate
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Document::Validate method. Validate document into the specified file in C++.'
type: docs
weight: 8900
url: /cpp/aspose.pdf/document/validate/
---
## Document::Validate(System::String, Aspose::Pdf::PdfFormat) method


Validate document into the specified file.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Document::Validate(System::String outputLogFileName, Aspose::Pdf::PdfFormat format)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputLogFileName | System::String | Path to file where the comments will be stored. |
| format | Aspose::Pdf::PdfFormat | The pdf format. |

### ReturnValue

The operation result
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>outputLogFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Path to file where the comments will be stored.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>format</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The pdf format.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Enum [PdfFormat](../../pdfformat/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Validate(System::SharedPtr\<System::IO::Stream\>, Aspose::Pdf::PdfFormat) method


Validate document into the specified file.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Document::Validate(System::SharedPtr<System::IO::Stream> outputLogStream, Aspose::Pdf::PdfFormat format)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputLogStream | System::SharedPtr\<System::IO::Stream\> | Stream where the comments will be stored. |
| format | Aspose::Pdf::PdfFormat | The pdf format. |

### ReturnValue

The operation result
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>outputLogStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream where the comments will be stored.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>format</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The pdf format.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Enum [PdfFormat](../../pdfformat/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Validate(System::SharedPtr\<PdfFormatConversionOptions\>) method


Validate document into the specified file.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Document::Validate(System::SharedPtr<PdfFormatConversionOptions> options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| options | System::SharedPtr\<PdfFormatConversionOptions\> | set of options for convert PDF document |

### ReturnValue

The operation result
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>options</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>set of options for convert PDF document</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
