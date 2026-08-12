---
title: "Método System::DoTryFinally"
linktitle: "EjecutarTryFinally"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::DoTryFinally método. La función única que emula el comportamiento de la sentencia try[-catch]-finally de C#. Durante la traducción de la sentencia try[-catch]-finally de C# con la opción finally_statement_as_lambda del traductor establecida en true, la sentencia se traduce en la invocación de este método en C++."
type: docs
weight: 17000
url: /es/cpp/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) method


La función única que emula el comportamiento de la sentencia try[-catch]-finally de C#. Durante la traducción de la sentencia try[-catch]-finally de C# con la opción finally_statement_as_lambda del traductor establecida en true, la sentencia se traduce en la invocación de este método.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo del objeto función que implementa la parte try[-catch] de la sentencia try[-catch]-finally que se está emulando |
| F | El tipo del objeto función que implementa la parte finally de la sentencia try[-catch]-finally que se está emulando |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tryBlock | T\&& | El objeto función cuyo cuerpo contiene la implementación de la parte try[-catch] de la sentencia try[-catch]-finally que se está emulando |
| finallyBlock | F\&& | El objeto función cuyo cuerpo contiene la implementación de la parte finally de la sentencia try[-catch]-finally que se está emulando |

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::DoTryFinally(T\&&, F\&&) method


La función única que emula el comportamiento de la sentencia try[-catch]-finally de C#. Durante la traducción de la sentencia try[-catch]-finally de C# con la opción finally_statement_as_lambda del traductor establecida en true, la sentencia se traduce en la invocación de este método. Esta sobrecarga maneja el caso en que el valor de retorno del objeto función que implementa la parte try[-catch] de la sentencia try[-catch]-finally es bool.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo del objeto función que implementa la parte try[-catch] de la sentencia try[-catch]-finally que se está emulando |
| F | El tipo del objeto función que implementa la parte finally de la sentencia try[-catch]-finally que se está emulando |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tryBlock | T\&& | El objeto función cuyo cuerpo contiene la implementación de la parte try[-catch] de la sentencia try[-catch]-finally que se está emulando |
| finallyBlock | F\&& | El objeto función cuyo cuerpo contiene la implementación de la parte finally de la sentencia try[-catch]-finally que se está emulando |

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::DoTryFinally(T\&&, F\&&) method


La función única que emula el comportamiento de la sentencia try[-catch]-finally de C#. Durante la traducción de la sentencia try[-catch]-finally de C# con la opción finally_statement_as_lambda del traductor establecida en true, la sentencia se traduce en la invocación de este método. Esta sobrecarga maneja el caso en que el valor de retorno del objeto función que implementa la parte try[-catch] de la sentencia try[-catch]-finally es bool&.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo del objeto función que implementa la parte try[-catch] de la sentencia try[-catch]-finally que se está emulando |
| F | El tipo del objeto función que implementa la parte finally de la sentencia try[-catch]-finally que se está emulando |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tryBlock | T\&& | El objeto función cuyo cuerpo contiene la implementación de la parte try[-catch] de la sentencia try[-catch]-finally que se está emulando |
| finallyBlock | F\&& | El objeto función cuyo cuerpo contiene la implementación de la parte finally de la sentencia try[-catch]-finally que se está emulando |

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
