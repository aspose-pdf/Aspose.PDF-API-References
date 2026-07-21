---
title: "System::Threading::Timer::Change método"
linktitle: "Cambio"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Threading::Timer::Change método. Reprograma o cancela el temporizador en C++."
type: docs
weight: 200
url: /es/cpp/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) method


Reprograma o cancela el temporizador.

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dueTime | int64_t | [Timeout](../../timeout/) antes de la siguiente invocación de la función de devolución de llamada, en milisegundos; los valores negativos cancelan el temporizador incluso si estaba programado. |
| period | int64_t | [Timeout](../../timeout/) entre invocaciones consecutivas de la función de devolución de llamada, en milisegundos; los valores no positivos indican que el temporizador solo debe ejecutarse una vez. |

## Ver también

* Class [Timer](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Timer::Change(System::TimeSpan, System::TimeSpan) method


Reprograma o cancela el temporizador.

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dueTime | System::TimeSpan | [Timeout](../../timeout/) antes de la siguiente invocación de la función de devolución de llamada; los valores negativos cancelan el temporizador incluso si estaba programado. |
| period | System::TimeSpan | [Timeout](../../timeout/) entre invocaciones consecutivas de la función de devolución de llamada; los valores no positivos indican que el temporizador solo debe ejecutarse una vez. |

## Ver también

* Class [TimeSpan](../../../system/timespan/)
* Class [Timer](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
