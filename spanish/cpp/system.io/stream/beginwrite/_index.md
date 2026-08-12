---
title: "Método System::IO::Stream::BeginWrite"
linktitle: "BeginWrite"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::IO::Stream::BeginWrite. Inicia una operación de escritura asíncrona en C++."
type: docs
weight: 200
url: /es/cpp/system.io/stream/beginwrite/
---
## Stream::BeginWrite method


Inicia una operación de escritura asíncrona.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | System::ArrayPtr\<uint8_t\> | Un buffer que contiene los datos a escribir. |
| desplazamiento | int | Un desplazamiento basado en cero en **buffer** que indica la posición desde la cual comienzan los datos a escribir. |
| count | int | El número de bytes a escribir. |
| callback | System::AsyncCallback | Una devolución de llamada que se invocará cuando la operación se complete |
| state | System::SharedPtr\<System::Object\> | Datos proporcionados por el usuario utilizados para identificar de forma única cada operación de escritura asíncrona. |

### ReturnValue

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación de escritura asíncrona iniciada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
