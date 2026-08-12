---
title: "Método System::Threading::Mutex::WaitOne"
linktitle: "WaitOne"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Threading::Mutex::WaitOne. Bloquea el mutex. Realiza una espera ilimitada si es necesario en C++."
type: docs
weight: 500
url: /es/cpp/system.threading/mutex/waitone/
---
## Mutex::WaitOne() method


Bloquea el mutex. Realiza una espera ilimitada si es necesario.

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```


### ReturnValue

Siempre devuelve true ya que no retorna hasta que el mutex esté bloqueado.

## Ver también

* Class [Mutex](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Mutex::WaitOne(int) method


Bloquea el mutex. Realiza una espera si es necesario.

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| millisecondsTimeout | int | Tiempo de espera en milisegundos. |

### ReturnValue

Devuelve true si el mutex estaba bloqueado o false si se superó el tiempo de espera.

## Ver también

* Class [Mutex](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Mutex::WaitOne(TimeSpan) method


Bloquea el mutex. Realiza una espera si es necesario.

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| timeout | TimeSpan | Un [System::TimeSpan](../../../system/timespan/) que representa la cantidad de milisegundos a esperar, o un [System::TimeSpan](../../../system/timespan/) que representa -1 milisegundos para esperar indefinidamente. |

### ReturnValue

Devuelve true si el mutex estaba bloqueado o false si se superó el tiempo de espera.

## Ver también

* Class [TimeSpan](../../../system/timespan/)
* Class [Mutex](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
