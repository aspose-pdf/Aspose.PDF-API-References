---
title: Aspose::Pdf::Facades::Form::FillFields method
linktitle: FillFields
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::Form::FillFields method. Fills the text box fields with a text values and save the document. Relevant for signed documents. Notice: Only be applied to Text Box. Both the fields'' name and values are case sensitive in C++.'
type: docs
weight: 900
url: /cpp/aspose.pdf.facades/form/fillfields/
---
## Form::FillFields method


Fills the text box fields with a text values and save the document. Relevant for signed documents. Notice: Only be applied to [Text](../../../aspose.pdf.text/) Box. Both the fields' name and values are case sensitive.

```cpp
bool Aspose::Pdf::Facades::Form::FillFields(System::ArrayPtr<System::String> fieldNames, System::ArrayPtr<System::String> fieldValues, System::SharedPtr<System::IO::Stream> &output)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldNames | System::ArrayPtr\<System::String\> | Names of fields. |
| fieldValues | System::ArrayPtr\<System::String\> | New values of the fields. |
| output | System::SharedPtr\<System::IO::Stream\>\& | Stream where document will be saved. |

### ReturnValue

true if fields was found and successfully filled.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
