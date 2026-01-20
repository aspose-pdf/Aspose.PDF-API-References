---
title: Aspose::Pdf::LoadOptions::ResourceLoadingStrategy typedef
linktitle: ResourceLoadingStrategy
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LoadOptions::ResourceLoadingStrategy typedef. Sometimes it''s necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method, that will get requested resources from somewhere. For example during usage of Aspose.Pdf in cloud direct access to referenced files impossible, and some custome code put into special method should be used. This delegate defines signature of such custom method in C++.'
type: docs
weight: 700
url: /cpp/aspose.pdf/loadoptions/resourceloadingstrategy/
---
## ResourceLoadingStrategy typedef


Sometimes it's necessary to avoid usage of internal loader of external resources(like images or CSSes) and supply custom method, that will get requested resources from somewhere. For example during usage of [Aspose.Pdf](../../) in cloud direct access to referenced files impossible, and some custome code put into special method should be used. This delegate defines signature of such custom method.

```cpp
using Aspose::Pdf::LoadOptions::ResourceLoadingStrategy =  System::MulticastDelegate<System::SharedPtr<Aspose::Pdf::LoadOptions::ResourceLoadingResult>(System::String)>
```


## See Also

* Class [LoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
