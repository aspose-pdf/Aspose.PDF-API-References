---
title: Aspose::Pdf::HtmlSaveOptions::CssSavingStrategy typedef
linktitle: CssSavingStrategy
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::HtmlSaveOptions::CssSavingStrategy typedef. You can assign to this property custom strategy that implements processing or/and saving of one CSS''s part that was created during conversion of PDF to HTML . In such case processing (like saving to stream or disk) must be done in that custom code in C++.'
type: docs
weight: 4700
url: /cpp/aspose.pdf/htmlsaveoptions/csssavingstrategy/
---
## CssSavingStrategy typedef


You can assign to this property custom strategy that implements processing or/and saving of one CSS's part that was created during conversion of PDF to HTML . In such case processing (like saving to stream or disk) must be done in that custom code.

```cpp
using Aspose::Pdf::HtmlSaveOptions::CssSavingStrategy =  System::MulticastDelegate<void(System::SharedPtr<Aspose::Pdf::HtmlSaveOptions::CssSavingInfo>)>
```


## See Also

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
