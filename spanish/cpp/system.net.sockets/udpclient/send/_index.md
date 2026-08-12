---
title: "Método System::Net::Sockets::UdpClient::Send"
linktitle: "Enviar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Net::Sockets::UdpClient::Send. Envía un datagrama UDP a un host remoto en C++."
type: docs
weight: 700
url: /es/cpp/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) method


Envía un datagrama UDP a un host remoto.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dgram | System::ArrayPtr\<uint8_t\> | Una matriz del tipo [Byte](../../../system/byte/) para enviar. |
| bytes | int32_t | El número de bytes en el datagrama. |

### ReturnValue

El número de bytes que se envían.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) method


Envía un datagrama UDP al puerto especificado en el host remoto especificado.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dgram | System::ArrayPtr\<uint8_t\> | Una matriz del tipo [Byte](../../../system/byte/) para enviar |
| bytes | int32_t | El número de bytes en el datagrama. |
| hostname | String | Un nombre del host remoto. |
| puerto | int32_t | Un número de puerto remoto. |

### ReturnValue

El número de bytes que se envían.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) method


Envía un datagrama UDP al host en el punto final remoto.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dgram | System::ArrayPtr\<uint8_t\> | Una matriz del tipo [Byte](../../../system/byte/) para enviar |
| bytes | int32_t | El número de bytes en el datagrama. |
| endPoint | System::SharedPtr\<IPEndPoint\> | Un [IPEndPoint](../../../system.net/ipendpoint/) que representa el host y el puerto a los que enviar el datagrama. |

### ReturnValue

El número de bytes que se envían.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
