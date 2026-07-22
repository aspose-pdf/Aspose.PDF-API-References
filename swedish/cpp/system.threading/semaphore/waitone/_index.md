---
title: "System::Threading::Semaphore::WaitOne‑metod"
linktitle: "WaitOne"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Semaphore::WaitOne‑metod. Låser semaforen. Utför obegränsad väntan om nödvändigt i C++."
type: docs
weight: 500
url: /sv/cpp/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() method


Låser semafor. Utför obegränsad väntan om nödvändigt.

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```


### ReturnValue

Returnerar alltid true eftersom den inte återvänder förrän semaforen är låst.

## Se även

* Class [Semaphore](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Semaphore::WaitOne(int) method


Låser semafor. Utför väntan om nödvändigt.

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| millisecondsTimeout | int | Väntetidsgräns i millisekunder. |

### ReturnValue

Returnerar true om semaforen var låst eller false om tidsgränsen överskreds.

## Se även

* Class [Semaphore](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
