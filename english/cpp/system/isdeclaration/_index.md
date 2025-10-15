---
title: System::IsDeclaration method
linktitle: IsDeclaration
second_title: Aspose.PDF for C++ API Reference
description: 'System::IsDeclaration method. Implements ''is'' declaration pattern translation in C++.'
type: docs
weight: 21400
url: /cpp/system/isdeclaration/
---
## System::IsDeclaration method


Implements 'is' declaration pattern translation.

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::IsDeclaration(const ExpressionT &left, ResultT &result)
```


| Parameter | Description |
| --- | --- |
| PatternT | type to check. |
| ExpressionT | left expression type. |
| ResultT | type of result expression. |

| Parameter | Type | Description |
| --- | --- | --- |
| left | const ExpressionT\& | expression which will be checked. |
| result | ResultT\& | variable which will be assigned to checked type. |

### ReturnValue

true if type check is successfull, false otherwise.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
