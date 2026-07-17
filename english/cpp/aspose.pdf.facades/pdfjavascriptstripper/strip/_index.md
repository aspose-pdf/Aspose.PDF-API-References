---
title: Aspose::Pdf::Facades::PdfJavaScriptStripper::Strip method
linktitle: Strip
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfJavaScriptStripper::Strip method. Remove Java Script from the document in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.facades/pdfjavascriptstripper/strip/
---
## PdfJavaScriptStripper::Strip(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Remove Java Script from the document.

```cpp
bool Aspose::Pdf::Facades::PdfJavaScriptStripper::Strip(const System::SharedPtr<System::IO::Stream> &inStream, const System::SharedPtr<System::IO::Stream> &outStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inStream | const System::SharedPtr\<System::IO::Stream\>\& | Stream containing document. |
| outStream | const System::SharedPtr\<System::IO::Stream\>\& | Stream where the document will be stored. |

### ReturnValue

true if JavaScript was stripped successfully.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfJavaScriptStripper](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfJavaScriptStripper::Strip(const System::String\&, const System::String\&) method


Remove Java Script from document.

```cpp
bool Aspose::Pdf::Facades::PdfJavaScriptStripper::Strip(const System::String &inputFile, const System::String &outputFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | const System::String\& | File containig the document. |
| outputFile | const System::String\& | File where document will be stored. |

### ReturnValue

true if JavaScript was stripped successfully.

## See Also

* Class [String](../../../system/string/)
* Class [PdfJavaScriptStripper](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
