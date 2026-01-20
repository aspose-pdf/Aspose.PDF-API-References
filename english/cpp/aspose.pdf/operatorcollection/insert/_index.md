---
title: Aspose::Pdf::OperatorCollection::Insert method
linktitle: Insert
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::OperatorCollection::Insert method. Insert operators at the the given position in C++.'
type: docs
weight: 1500
url: /cpp/aspose.pdf/operatorcollection/insert/
---
## OperatorCollection::Insert(int32_t, System::ArrayPtr\<System::SharedPtr\<Operator\>\>) method


Insert operators at the the given position.

```cpp
void Aspose::Pdf::OperatorCollection::Insert(int32_t at, System::ArrayPtr<System::SharedPtr<Operator>> ops)
```


| Parameter | Type | Description |
| --- | --- | --- |
| at | int32_t | Index from which operators are being started to insert. |
| ops | System::ArrayPtr\<System::SharedPtr\<Operator\>\> | Array of operators to be inserted. Each operator can have any index (by default -1) because their indices adjusted automatically starting from *at* . |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## OperatorCollection::Insert(int32_t, System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<Operator\>\>\>) method


Insert operators at the the given position.

```cpp
void Aspose::Pdf::OperatorCollection::Insert(int32_t at, System::SharedPtr<System::Collections::Generic::IList<System::SharedPtr<Operator>>> ops)
```


| Parameter | Type | Description |
| --- | --- | --- |
| at | int32_t | Index from which operators are being started to insert. |
| ops | System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<Operator\>\>\> | Array of operators to be inserted. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## OperatorCollection::Insert(int32_t, System::SharedPtr\<Operator\>) method


Inserts operator into collection.

```cpp
void Aspose::Pdf::OperatorCollection::Insert(int32_t index, System::SharedPtr<Operator> op) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| index | int32_t | Index where new operator must be added |
| op | System::SharedPtr\<Operator\> | [Operator](../../operator/) which will be insterted |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
