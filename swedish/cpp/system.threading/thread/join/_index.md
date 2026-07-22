---
title: "System::Threading::Thread::Join metod"
linktitle: "Join"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Thread::Join metod. Väntar på den hanterade tråden. Utför obegränsad väntan om det behövs i C++."
type: docs
weight: 1400
url: /sv/cpp/system.threading/thread/join/
---
## Thread::Join() method


Väntar på hanterad tråd. Utför obegränsad väntan om det behövs.

```cpp
void System::Threading::Thread::Join()
```

## Se även

* Class [Thread](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Thread::Join(int) method


Väntar på hanterad tråd. Utför begränsad väntan.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| millisecondsTimeout | int | Väntetidsgräns i millisekunder. |

### ReturnValue

Sant om tråden framgångsrikt anslöts, falskt om tidsgränsen överskreds.

## Se även

* Class [Thread](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Thread::Join(TimeSpan) method


Väntar på hanterad tråd. Utför begränsad väntan.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| timeout | TimeSpan | En [TimeSpan](../../../system/timespan/) som anger hur lång tid som ska vänta på att tråden ska avslutas. |

### ReturnValue

Sant om tråden framgångsrikt anslöts, falskt om tidsgränsen överskreds.

## Se även

* Class [TimeSpan](../../../system/timespan/)
* Class [Thread](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
