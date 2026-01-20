---
title: System::Data::DataRow::GetChildRows method
linktitle: GetChildRows
second_title: Aspose.PDF for C++ API Reference
description: 'System::Data::DataRow::GetChildRows method. Gets rows which are considered child through specified relation in C++.'
type: docs
weight: 200
url: /cpp/system.data/datarow/getchildrows/
---
## DataRow::GetChildRows method


Gets rows which are considered child through specified relation.

```cpp
System::ArrayPtr<System::SharedPtr<System::Data::DataRow>> System::Data::DataRow::GetChildRows(const System::SharedPtr<System::Data::DataRelation> &relation)
```


| Parameter | Type | Description |
| --- | --- | --- |
| relation | const System::SharedPtr\<System::Data::DataRelation\>\& | Relation object to specify parent row - child row relation. |

### ReturnValue

[Array](../../../system/array/) of child rows retreived.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DataRow](../)
* Class [DataRelation](../../datarelation/)
* Class [DataRow](../)
* Namespace [System::Data](../../)
* Library [Aspose.PDF for C++](../../../)
