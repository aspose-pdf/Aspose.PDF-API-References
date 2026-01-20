---
title: Aspose::Pdf::OperatorCollection::Add method
linktitle: Add
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::OperatorCollection::Add method. Add operators at the end of the contents operators in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf/operatorcollection/add/
---
## OperatorCollection::Add(const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\&) method


Add operators at the end of the contents operators.

```cpp
void Aspose::Pdf::OperatorCollection::Add(const System::ArrayPtr<System::SharedPtr<Operator>> &ops)
```


| Parameter | Type | Description |
| --- | --- | --- |
| ops | const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\& | Array of operators to be added. Each operator can have any index (by default -1) because they come to the end of the contents operators i.e. indices are assigned automatically. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## OperatorCollection::Add(const System::SharedPtr\<Operator\>\&) method


Adds new operator into collection.

```cpp
void Aspose::Pdf::OperatorCollection::Add(const System::SharedPtr<Operator> &op) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| op | const System::SharedPtr\<Operator\>\& | [Operator](../../operator/) which must be added |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## OperatorCollection::Add(const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Operator\>\>\>\&) method


Adds to collection all operators from other collection.

```cpp
void Aspose::Pdf::OperatorCollection::Add(const System::SharedPtr<System::Collections::Generic::ICollection<System::SharedPtr<Operator>>> &ops)
```


| Parameter | Type | Description |
| --- | --- | --- |
| ops | const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Operator\>\>\>\& | collection whitch contains operators which will be added. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICollection](../../../system.collections.generic/icollection/)
* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
