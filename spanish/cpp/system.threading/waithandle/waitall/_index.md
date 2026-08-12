---
title: "Método System::Threading::WaitHandle::WaitAll"
linktitle: "WaitAll"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Threading::WaitHandle::WaitAll. Espera a que todos los manejadores se activen en C++."
type: docs
weight: 100
url: /es/cpp/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) method


Espera a que todos los manejadores se activen.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| waitHandles | const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\& | Manejadores a esperar. |

### ReturnValue

Verdadero cuando cada elemento en waitHandles ha recibido una señal; de lo contrario, el método nunca retorna.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) method


Información RTTI.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| waitHandles | const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\& | Manejadores a esperar. |
| millisecondsTimeout | int | [Timeout](../../timeout/) para esperar, en milisegundos; -1 significa espera infinita, 0 significa comprobar y devolver, los valores positivos son tiempos de espera. |

### ReturnValue

Verdadero si todos los manejadores se activaron, falso si se excedió el tiempo de espera.
## Observaciones


Espera a que todos los manejadores se activen.
## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) method


Espera a que todos los manejadores se activen.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| waitHandles | const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\& | Manejadores a esperar. |
| timeout | TimeSpan | Un [System::TimeSpan](../../../system/timespan/) que representa la cantidad de milisegundos a esperar, o un [System::TimeSpan](../../../system/timespan/) que representa -1 milisegundos para esperar indefinidamente. |

### ReturnValue

Verdadero si todos los manejadores se activaron, falso si se excedió el tiempo de espera.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [TimeSpan](../../../system/timespan/)
* Class [WaitHandle](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
