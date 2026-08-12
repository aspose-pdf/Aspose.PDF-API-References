---
title: "System::Threading::WaitHandle::WaitOne metod"
linktitle: "WaitOne"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::WaitHandle::WaitOne metod. Väntar på att handtaget ska avfyras under obegränsad period i C++."
type: docs
weight: 600
url: /sv/cpp/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() method


Väntar på att handtaget ska avfyras under obegränsad tid.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```


### ReturnValue

Returnerar alltid sant eftersom ingen tidsgräns inträffar.

## Se även

* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## WaitHandle::WaitOne(int) method


Väntar på att handtaget ska avfyras.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) att vänta på, i millisekunder; -1 betyder oändlig väntan, 0 betyder kontroll‑och‑retur, positiva värden är tidsgränser. |

### ReturnValue

Sant om handtaget avfyrades, falskt om tidsgränsen överskreds.

## Se även

* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## WaitHandle::WaitOne(int, bool) method


Väntar på att handtaget ska avfyras.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) att vänta på, i millisekunder; -1 betyder oändlig väntan, 0 betyder kontroll‑och‑retur, positiva värden är tidsgränser. |
| exitContext | bool | Om sant ska väntan släppa låset på handtaget innan den väntar på det. |

### ReturnValue

Sant om handtaget avfyrades, falskt om tidsgränsen överskreds.

## Se även

* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## WaitHandle::WaitOne(TimeSpan) method


Väntar på att handtaget ska avfyras.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| timeout | TimeSpan | Ett [System::TimeSpan](../../../system/timespan/) som representerar antalet millisekunder att vänta, eller ett [System::TimeSpan](../../../system/timespan/) som representerar -1 millisekunder för att vänta på obestämd tid. |

### ReturnValue

Sant om handtaget avfyrades, falskt om tidsgränsen överskreds.

## Se även

* Class [TimeSpan](../../../system/timespan/)
* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
