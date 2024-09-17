---
title: Aspose::Pdf::OutlineItemCollection::GetEnumerator method
linktitle: GetEnumerator
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::OutlineItemCollection::GetEnumerator method. Returns an enumerator that iterates through the collection in C++.'
type: docs
weight: 3000
url: /cpp/aspose.pdf/outlineitemcollection/getenumerator/
---
## OutlineItemCollection::GetEnumerator method


Returns an enumerator that iterates through the collection.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<System::Collections::Generic::IEnumerator<System::SharedPtr<OutlineItemCollection>>> Aspose::Pdf::OutlineItemCollection::GetEnumerator() override
```


### ReturnValue

An **System.Collections.IEnumerator** object that can be used to iterate through the collection.
## Remarks


**System.Collections.IEnumerator****System.Collections.IEnumerable.GetEnumerator()** { return new OutlineCollection.OutlinesEnumerator(EngineDict, document); }

Returns an enumerator that iterates through the collection.

## See Also

* Class [OutlineItemCollection](../)
* Class [OutlineItemCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
