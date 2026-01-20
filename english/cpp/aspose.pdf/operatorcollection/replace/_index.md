---
title: Aspose::Pdf::OperatorCollection::Replace method
linktitle: Replace
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::OperatorCollection::Replace method. Replace operators in collection with other operators in C++.'
type: docs
weight: 1700
url: /cpp/aspose.pdf/operatorcollection/replace/
---
## OperatorCollection::Replace method


Replace operators in collection with other operators.

```cpp
void Aspose::Pdf::OperatorCollection::Replace(System::SharedPtr<System::Collections::Generic::IList<System::SharedPtr<Operator>>> operators)
```


| Parameter | Type | Description |
| --- | --- | --- |
| operators | System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<Operator\>\>\> | [Operators](../../../aspose.pdf.operators/) list which will replace operators currently contained in the collection. Eash operator from the list must have correct index in range [1..N] where N is count of operators in the collection |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
