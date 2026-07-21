---
title: "Método System::Threading::Semaphore::WaitOne"
linktitle: "WaitOne"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Threading::Semaphore::WaitOne. Bloquea el semáforo. Realiza una espera ilimitada si es necesario en C++."
type: docs
weight: 500
url: /es/cpp/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() method


Bloquea el semáforo. Realiza una espera ilimitada si es necesario.

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```


### ReturnValue

Siempre devuelve true ya que no retorna hasta que el semáforo esté bloqueado.

## Ver también

* Class [Semaphore](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## Semaphore::WaitOne(int) method


Bloquea el semáforo. Realiza una espera si es necesario.

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| millisecondsTimeout | int | Tiempo de espera en milisegundos. |

### ReturnValue

Devuelve true si el semáforo estaba bloqueado o false si se superó el tiempo de espera.

## Ver también

* Class [Semaphore](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
