---
title: Aspose::Pdf::Security::UnsignedContentAbsorber::Result class
linktitle: Result
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Security::UnsignedContentAbsorber::Result class. Encapsulates the result of an operation attempting to extract unsigned content from a PDF document in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.security/unsignedcontentabsorber/result/
---
## Result class


Encapsulates the result of an operation attempting to extract unsigned content from a PDF document.

```cpp
class Result : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Coverage](./get_coverage/)() const | Gets a value indicating the extent to which the document is covered by valid digital signatures. |
| [get_Message](./get_message/)() const | Gets a message describing the outcome of the operation. |
| [get_Success](./get_success/)() const | Gets a value indicating whether the operation to retrieve unsigned content from the document was successful. |
| [get_UnsignedContent](./get_unsignedcontent/)() const | Gets an unsigned content. |
## Remarks


This class provides information about the success of the operation, details of the unsigned content, a message describing the outcome, and the coverage status of the document's signatures. 
## See Also

* Class [Object](../../../system/object/)
* Class [UnsignedContentAbsorber](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
