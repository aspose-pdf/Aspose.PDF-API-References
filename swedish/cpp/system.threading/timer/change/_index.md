---
title: "System::Threading::Timer::Change metod"
linktitle: "Ändra"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Timer::Change metod. Schemalägger om eller avbryter timer i C++."
type: docs
weight: 200
url: /sv/cpp/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) method


Schemalägger om eller avbryter timern.

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dueTime | int64_t | [Timeout](../../timeout/) före nästa anrop av återuppringningsfunktion, i millisekunder; negativa värden avbryter timern även om den var schemalagd. |
| period | int64_t | [Timeout](../../timeout/) mellan på varandra följande anrop av återuppringningsfunktion, i millisekunder; icke-positiva värden betyder att timern bara ska köras en gång. |

## Se även

* Class [Timer](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Timer::Change(System::TimeSpan, System::TimeSpan) method


Schemalägger om eller avbryter timern.

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dueTime | System::TimeSpan | [Timeout](../../timeout/) före nästa anrop av återuppringningsfunktion; negativa värden avbryter timern även om den var schemalagd. |
| period | System::TimeSpan | [Timeout](../../timeout/) mellan på varandra följande anrop av återuppringningsfunktion; icke-positiva värden betyder att timern bara ska köras en gång. |

## Se även

* Class [TimeSpan](../../../system/timespan/)
* Class [Timer](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
