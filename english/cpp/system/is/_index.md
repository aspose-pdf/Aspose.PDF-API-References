---
title: System::Is method
linktitle: Is
second_title: Aspose.PDF for C++ API Reference
description: 'System::Is method. Top-level matching function. Applies a pattern to a value in C++.'
type: docs
weight: 21900
url: /cpp/system/is/
---
## System::Is(const E\&, const A\&) method


Top-level matching function. Applies a pattern to a value.

```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```


| Parameter | Description |
| --- | --- |
| A | Pattern type (must inherit from Details::Pattern). |
| E | Type of the value to match. |

| Parameter | Type | Description |
| --- | --- | --- |
| e | const E\& | Value to match against. |
| a | const A\& | Pattern to apply. |

### ReturnValue

true if the pattern matches the value.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Is(const ExpressionT\&, const ConstantT\&) method


Implements 'is' constant pattern translation.

```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```


| Parameter | Description |
| --- | --- |
| ExpressionT | left expression type. |
| ConstantT | type of constant expression. |

| Parameter | Type | Description |
| --- | --- | --- |
| left | const ExpressionT\& | expression which will be checked. |
| constant | const ConstantT\& | expression which will be compared with left one. |

### ReturnValue

true if type check is successfull, false otherwise.

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Is(const ExpressionT\&, ResultT\&) method


Implements 'is' declaration pattern translation.

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
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
