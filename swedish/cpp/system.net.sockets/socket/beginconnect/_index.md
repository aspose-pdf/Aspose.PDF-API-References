---
title: "System::Net::Sockets::Socket::BeginConnect metod"
linktitle: "BeginConnect"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::Socket::BeginConnect metod. Initierar en asynkron anslutningsoperation i C++."
type: docs
weight: 700
url: /sv/cpp/system.net.sockets/socket/beginconnect/
---
## Socket::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method


Initierar en asynkron anslutningsoperation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| host | String | Det fjärrvärdens namn. |
| port | int32_t | Portnumret för fjärrvärden. |
| requestCallback | AsyncCallback | En återuppringning som kommer att anropas när operationen är klar. |
| state | System::SharedPtr\<Object\> | Användarlevererade data som används för att unikt identifiera varje asynkron anslutningsoperation. |

### ReturnValue

Ett [IAsyncResult](../../../system/iasyncresult/)‑objekt som representerar den initierade asynkrona anslutningsoperationen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [String](../../../system/string/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method


Initierar en asynkron anslutningsoperation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| addresses | System::ArrayPtr\<System::SharedPtr\<IPAddress\>\> | IP-adresserna för fjärrvärden. |
| port | int32_t | Portnumret för fjärrvärden. |
| requestCallback | AsyncCallback | En återuppringning som kommer att anropas när operationen är klar. |
| state | System::SharedPtr\<Object\> | Användarlevererade data som används för att unikt identifiera varje asynkron anslutningsoperation. |

### ReturnValue

Ett [IAsyncResult](../../../system/iasyncresult/)‑objekt som representerar den initierade asynkrona anslutningsoperationen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPAddress](../../../system.net/ipaddress/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::BeginConnect(System::SharedPtr\<EndPoint\>, AsyncCallback, System::SharedPtr\<Object\>) method


Initierar en asynkron anslutningsoperation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<EndPoint> remoteEP, AsyncCallback callback, System::SharedPtr<Object> state)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| remoteEP | System::SharedPtr\<EndPoint\> | Den fjärrslutpunkten. |
| callback | AsyncCallback | En återuppringning som kommer att anropas när operationen är klar. |
| state | System::SharedPtr\<Object\> | Användarlevererade data som används för att unikt identifiera varje asynkron anslutningsoperation. |

### ReturnValue

Ett [IAsyncResult](../../../system/iasyncresult/)‑objekt som representerar den initierade asynkrona anslutningsoperationen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [EndPoint](../../../system.net/endpoint/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method


Initierar en asynkron anslutningsoperation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| adress | System::SharedPtr\<IPAddress\> | Fjärrvärdens IP-adress. |
| port | int32_t | Portnumret för fjärrvärden. |
| requestCallback | AsyncCallback | En återuppringning som kommer att anropas när operationen är klar. |
| state | System::SharedPtr\<Object\> | Användarlevererade data som används för att unikt identifiera varje asynkron anslutningsoperation. |

### ReturnValue

Ett [IAsyncResult](../../../system/iasyncresult/)‑objekt som representerar den initierade asynkrona anslutningsoperationen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [IPAddress](../../../system.net/ipaddress/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
