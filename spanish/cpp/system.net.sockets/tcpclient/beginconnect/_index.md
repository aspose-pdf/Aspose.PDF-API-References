---
title: "System::Net::Sockets::TcpClient::BeginConnect método"
linktitle: "BeginConnect"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Sockets::TcpClient::BeginConnect método. Inicia una operación de conexión asíncrona en C++."
type: docs
weight: 300
url: /es/cpp/system.net.sockets/tcpclient/beginconnect/
---
## TcpClient::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method


Inicia una operación de conexión asíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| host | String | Un nombre de host remoto. |
| puerto | int32_t | Un puerto del host remoto. |
| requestCallback | AsyncCallback | Una callback que será llamada cuando la operación se complete. |
| state | System::SharedPtr\<Object\> | Datos proporcionados por el usuario utilizados para identificar de forma única cada operación de conexión asíncrona. |

### ReturnValue

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación de conexión asíncrona iniciada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [String](../../../system/string/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [TcpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## TcpClient::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method


Inicia una operación de conexión asíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| addresses | System::ArrayPtr\<System::SharedPtr\<IPAddress\>\> | Las direcciones IP de un host remoto. |
| puerto | int32_t | Un puerto del host remoto. |
| requestCallback | AsyncCallback | Una callback que será llamada cuando la operación se complete. |
| state | System::SharedPtr\<Object\> | Datos proporcionados por el usuario utilizados para identificar de forma única cada operación de conexión asíncrona. |

### ReturnValue

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación de conexión asíncrona iniciada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPAddress](../../../system.net/ipaddress/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [TcpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## TcpClient::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method


Inicia una operación de conexión asíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dirección | System::SharedPtr\<IPAddress\> | La dirección IP de un host remoto. |
| puerto | int32_t | Un puerto del host remoto. |
| requestCallback | AsyncCallback | Una callback que será llamada cuando la operación se complete. |
| state | System::SharedPtr\<Object\> | Datos proporcionados por el usuario utilizados para identificar de forma única cada operación de conexión asíncrona. |

### ReturnValue

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación de conexión asíncrona iniciada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [IPAddress](../../../system.net/ipaddress/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [TcpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
