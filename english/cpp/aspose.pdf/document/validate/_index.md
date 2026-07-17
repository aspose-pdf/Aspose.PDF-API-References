---
title: Aspose::Pdf::Document::Validate method
linktitle: Validate
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Document::Validate method. Validate document into the specified file in C++.'
type: docs
weight: 11600
url: /cpp/aspose.pdf/document/validate/
---
## Document::Validate(const System::SharedPtr\<PdfFormatConversionOptions\>\&) method


Validate document into the specified file.

```cpp
bool Aspose::Pdf::Document::Validate(const System::SharedPtr<PdfFormatConversionOptions> &options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| options | const System::SharedPtr\<PdfFormatConversionOptions\>\& | set of options for convert PDF document |

### ReturnValue

The operation result

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Validate(const System::SharedPtr\<System::IO::Stream\>\&, Aspose::Pdf::PdfFormat) method


Validate document into the specified file.

```cpp
bool Aspose::Pdf::Document::Validate(const System::SharedPtr<System::IO::Stream> &outputLogStream, Aspose::Pdf::PdfFormat format)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputLogStream | const System::SharedPtr\<System::IO::Stream\>\& | Stream where the comments will be stored. |
| format | Aspose::Pdf::PdfFormat | The pdf format. |

### ReturnValue

The operation result

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [PdfFormat](../../pdfformat/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Validate(const System::String\&, Aspose::Pdf::PdfFormat) method


Validate document into the specified file.

```cpp
bool Aspose::Pdf::Document::Validate(const System::String &outputLogFileName, Aspose::Pdf::PdfFormat format)
```


| Parameter | Type | Description |
| --- | --- | --- |
| outputLogFileName | const System::String\& | Path to file where the comments will be stored. |
| format | Aspose::Pdf::PdfFormat | The pdf format. |

### ReturnValue

The operation result

## See Also

* Class [String](../../../system/string/)
* Enum [PdfFormat](../../pdfformat/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
