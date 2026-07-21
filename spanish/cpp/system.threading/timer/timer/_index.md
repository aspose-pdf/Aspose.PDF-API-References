---
title: "Constructor de System::Threading::Timer::Timer"
linktitle: "Timer"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Constructor de System::Threading::Timer::Timer. Constructor en C++."
type: docs
weight: 100
url: /es/cpp/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) constructor


Constructor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | TimerCallback | Función que será llamada por el temporizador. |

## Ver también

* Typedef [TimerCallback](../../timercallback/)
* Class [Timer](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) constructor


Constructor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | TimerCallback | Función que será llamada por el temporizador. |
| state | const System::SharedPtr\<System::Object\>\& | Argumento de la función de devolución de llamada. |
| dueTime | int64_t | [Timeout](../../timeout/) antes de la primera invocación de la función de devolución de llamada, en milisegundos; los valores negativos no programan el temporizador después de la creación, por lo que puede reprogramarse más tarde. |
| period | int64_t | [Timeout](../../timeout/) entre invocaciones consecutivas de la función de devolución de llamada, en milisegundos; los valores no positivos indican que el temporizador solo debe ejecutarse una vez. |

## Ver también

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Timer](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) constructor


Constructor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | TimerCallback | Función que será llamada por el temporizador. |
| state | const System::SharedPtr\<System::Object\>\& | Argumento de la función de devolución de llamada. |
| dueTime | System::TimeSpan | [Timeout](../../timeout/) antes de la primera invocación de la función de devolución de llamada; los valores negativos no programan el temporizador después de la creación, por lo que puede reprogramarse más tarde. |
| period | System::TimeSpan | [Timeout](../../timeout/) entre invocaciones consecutivas de la función de devolución de llamada; los valores no positivos indican que el temporizador solo debe ejecutarse una vez. |

## Ver también

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Timer](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
