---
title: "System::Net::Sockets::Socket::EndReceive método"
linktitle: "EndReceive"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Sockets::Socket::EndReceive método. Espera hasta que la operación de recepción asíncrona especificada se complete en C++."
type: docs
weight: 1500
url: /es/cpp/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) method


Espera hasta que la operación de recepción asíncrona especificada se complete.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa una operación de recepción asíncrona. |

### ReturnValue

El número de bytes que se reciben.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) method


Espera hasta que la operación de recepción asíncrona especificada se complete.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa una operación de recepción asíncrona. |
| errorCode | SocketError\& | El parámetro de salida donde se asignará el código de error cuando falle la operación de recepción. |

### ReturnValue

El número de bytes recibidos.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
