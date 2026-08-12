---
title: "System::Threading::WaitHandle::WaitAll metod"
linktitle: "WaitAll"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::WaitHandle::WaitAll metod. Väntar på att alla handtag ska avfyras i C++."
type: docs
weight: 100
url: /sv/cpp/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) method


Väntar på att alla handtag ska avfyras.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| waitHandles | const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\& | Handtag att vänta på. |

### ReturnValue

Sant när varje element i waitHandles har mottagit en signal; annars returnerar metoden aldrig.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) method


RTTI-information.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| waitHandles | const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\& | Handtag att vänta på. |
| millisecondsTimeout | int | [Timeout](../../timeout/) att vänta på, i millisekunder; -1 betyder oändlig väntan, 0 betyder kontroll‑och‑retur, positiva värden är tidsgränser. |

### ReturnValue

Sant om alla handtag avfyrades, falskt om tidsgränsen överskreds.
## Anmärkningar


Väntar på att alla handtag ska avfyras.
## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) method


Väntar på att alla handtag ska avfyras.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| waitHandles | const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\& | Handtag att vänta på. |
| timeout | TimeSpan | Ett [System::TimeSpan](../../../system/timespan/) som representerar antalet millisekunder att vänta, eller ett [System::TimeSpan](../../../system/timespan/) som representerar -1 millisekunder för att vänta på obestämd tid. |

### ReturnValue

Sant om alla handtag avfyrades, falskt om tidsgränsen överskreds.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [TimeSpan](../../../system/timespan/)
* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
