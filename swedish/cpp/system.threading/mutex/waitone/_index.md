---
title: "System::Threading::Mutex::WaitOne-metod"
linktitle: "WaitOne"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Mutex::WaitOne-metod. Låser mutexen. Utför obegränsad väntan om nödvändigt i C++."
type: docs
weight: 500
url: /sv/cpp/system.threading/mutex/waitone/
---
## Mutex::WaitOne() method


Låser mutexen. Utför obegränsad väntan om nödvändigt.

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```


### ReturnValue

Returnerar alltid true eftersom den inte returnerar förrän mutexen är låst.

## Se även

* Class [Mutex](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Mutex::WaitOne(int) method


Låser mutexen. Utför väntan om nödvändigt.

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| millisecondsTimeout | int | Väntetidsgräns i millisekunder. |

### ReturnValue

Returnerar true om mutexen var låst eller false om tidsgränsen överskreds.

## Se även

* Class [Mutex](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Mutex::WaitOne(TimeSpan) method


Låser mutexen. Utför väntan om nödvändigt.

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| timeout | TimeSpan | Ett [System::TimeSpan](../../../system/timespan/) som representerar antalet millisekunder att vänta, eller ett [System::TimeSpan](../../../system/timespan/) som representerar -1 millisekunder för att vänta på obestämd tid. |

### ReturnValue

Returnerar true om mutexen var låst eller false om tidsgränsen överskreds.

## Se även

* Class [TimeSpan](../../../system/timespan/)
* Class [Mutex](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
