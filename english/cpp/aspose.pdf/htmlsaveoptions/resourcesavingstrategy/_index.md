---
title: Aspose::Pdf::HtmlSaveOptions::ResourceSavingStrategy typedef
linktitle: ResourceSavingStrategy
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::HtmlSaveOptions::ResourceSavingStrategy typedef. To this property You can assign delegate created from custom method that implements processing of external resource(Font or Image) that was extracted from PDF and must be saved as external resource during conversion of PDF to HTML. In such case processing (like saving in stream or disk) can be done in that custom code and that custom code must return path(or any another string without quotemarks) that will be afterwards incorporated into generated HTML instead of original supposed path to that image resource. In such case All the necessary actions for saving of image must be undertaken in code of supplied method, because saving of result in code of converter will be not in use . If processing for this or that file for some reason must be done by converter''s code itself, not in custom code, please set in custom code flag ''CustomProcessingCancelled'' of ''resourceSavingInfo'' parameter''s variable It signals to converter that all the necessary steps for processing of that resource must be done in converter itself as if there was no any external custom code  in C++.'
type: docs
weight: 5000
url: /cpp/aspose.pdf/htmlsaveoptions/resourcesavingstrategy/
---
## ResourceSavingStrategy typedef


To this property You can assign delegate created from custom method that implements processing of external resource(Font or Image) that was extracted from PDF and must be saved as external resource during conversion of PDF to HTML. In such case processing (like saving in stream or disk) can be done in that custom code and that custom code must return path(or any another string without quotemarks) that will be afterwards incorporated into generated HTML instead of original supposed path to that image resource. In such case All the necessary actions for saving of image must be undertaken in code of supplied method, because saving of result in code of converter will be not in use . If processing for this or that file for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'resourceSavingInfo' parameter's variable It signals to converter that all the necessary steps for processing of that resource must be done in converter itself as if there was no any external custom code .

```cpp
using Aspose::Pdf::HtmlSaveOptions::ResourceSavingStrategy =  System::MulticastDelegate<System::String(System::SharedPtr<Aspose::Pdf::SaveOptions::ResourceSavingInfo>)>
```


## See Also

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
