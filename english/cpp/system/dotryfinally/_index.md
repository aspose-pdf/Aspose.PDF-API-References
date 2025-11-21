---
title: System::DoTryFinally method
linktitle: DoTryFinally
second_title: Aspose.PDF for C++ API Reference
description: 'System::DoTryFinally method. The sigle function that emulates behavior of C#''s try[-catch]-finally statement. During translation of C#''s try[-catch]-finally statement with translator''s option finally_statement_as_lambda set to true, the statement is translated into the invocation of this method in C++.'
type: docs
weight: 16500
url: /cpp/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) method


The sigle function that emulates behavior of C#'s try[-catch]-finally statement. During translation of C#'s try[-catch]-finally statement with translator's option finally_statement_as_lambda set to true, the statement is translated into the invocation of this method.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


| Parameter | Description |
| --- | --- |
| T | The type of the function object that implements the try[-catch] part of the try[-catch]-finally statement being emulated |
| F | The type of the function object that implements the finally part of the try[-catch]-finally statement being emulated |

| Parameter | Type | Description |
| --- | --- | --- |
| tryBlock | T\&& | The function object whose body contains the implementation of the try[-catch] part of the try[-catch]-finally statemet being emulated |
| finallyBlock | F\&& | The function object whose body contains the implementation of the finally part of the try[-catch]-finally statement being emulated |

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::DoTryFinally(T\&&, F\&&) method


The sigle function that emulates behavior of C#'s try[-catch]-finally statement. During translation of C#'s try[-catch]-finally statement with translator's option finally_statement_as_lambda set to true, the statement is translated into the invocation of this method. This overload handles the case in which the return value of the function object that implements the try[-catch] part of the try[-catch]-finally statement is bool.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


| Parameter | Description |
| --- | --- |
| T | The type of the function object that implements the try[-catch] part of the try[-catch]-finally statement being emulated |
| F | The type of the function object that implements the finally part of the try[-catch]-finally statement being emulated |

| Parameter | Type | Description |
| --- | --- | --- |
| tryBlock | T\&& | The function object whose body contains the implementation of the try[-catch] part of the try[-catch]-finally statemet being emulated |
| finallyBlock | F\&& | The function object whose body contains the implementation of the finally part of the try[-catch]-finally statement being emulated |

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::DoTryFinally(T\&&, F\&&) method


The sigle function that emulates behavior of C#'s try[-catch]-finally statement. During translation of C#'s try[-catch]-finally statement with translator's option finally_statement_as_lambda set to true, the statement is translated into the invocation of this method. This overload handles the case in which the return value of the function object that implements the try[-catch] part of the try[-catch]-finally statement is bool&.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


| Parameter | Description |
| --- | --- |
| T | The type of the function object that implements the try[-catch] part of the try[-catch]-finally statement being emulated |
| F | The type of the function object that implements the finally part of the try[-catch]-finally statement being emulated |

| Parameter | Type | Description |
| --- | --- | --- |
| tryBlock | T\&& | The function object whose body contains the implementation of the try[-catch] part of the try[-catch]-finally statemet being emulated |
| finallyBlock | F\&& | The function object whose body contains the implementation of the finally part of the try[-catch]-finally statement being emulated |

## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
