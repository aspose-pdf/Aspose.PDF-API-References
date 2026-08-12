---
title: "System::Net::Sockets::Socket::EndSend método"
linktitle: "EndSend"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Sockets::Socket::EndSend método. Espera hasta que la operación de envío asíncrona especificada se complete en C++."
type: docs
weight: 1600
url: /es/cpp/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) method


Espera hasta que la operación de envío asíncrona especificada se complete.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa una operación de envío asíncrona. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) method


Espera hasta que la operación de envío asíncrona especificada se complete.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa una operación de envío asíncrona. |
| errorCode | SocketError\& | El parámetro de salida donde se asignará el código de error cuando la operación de envío falle. |

### ReturnValue

El número de bytes enviados.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
