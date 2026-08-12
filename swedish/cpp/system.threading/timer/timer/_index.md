---
title: "System::Threading::Timer::Timer konstruktor"
linktitle: "Timer"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Timer::Timer konstruktor. Konstruktor i C++."
type: docs
weight: 100
url: /sv/cpp/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) constructor


Konstruktor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | TimerCallback | Funktion som ska anropas av timern. |

## Se även

* Typedef [TimerCallback](../../timercallback/)
* Class [Timer](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) constructor


Konstruktor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | TimerCallback | Funktion som ska anropas av timern. |
| state | const System::SharedPtr\<System::Object\>\& | Argument till callback-funktion. |
| dueTime | int64_t | [Timeout](../../timeout/) före första anropet av återuppringningsfunktion, i millisekunder; negativa värden schemalägger inte timern efter skapandet så den kan schemaläggas om senare. |
| period | int64_t | [Timeout](../../timeout/) mellan på varandra följande anrop av återuppringningsfunktion, i millisekunder; icke-positiva värden betyder att timern bara ska köras en gång. |

## Se även

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Timer](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) constructor


Konstruktor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | TimerCallback | Funktion som ska anropas av timern. |
| state | const System::SharedPtr\<System::Object\>\& | Argument till callback-funktion. |
| dueTime | System::TimeSpan | [Timeout](../../timeout/) före första anropet av återuppringningsfunktion; negativa värden schemalägger inte timern efter skapandet så den kan schemaläggas om senare. |
| period | System::TimeSpan | [Timeout](../../timeout/) mellan på varandra följande anrop av återuppringningsfunktion; icke-positiva värden betyder att timern bara ska köras en gång. |

## Se även

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TimeSpan](../../../system/timespan/)
* Class [Timer](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
