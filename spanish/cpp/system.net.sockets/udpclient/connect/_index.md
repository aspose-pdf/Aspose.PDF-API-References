---
title: "System::Net::Sockets::UdpClient::Connect método"
linktitle: "Connect"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Sockets::UdpClient::Connect método. Establece una conexión al puerto especificado en el host especificado en C++."
type: docs
weight: 300
url: /es/cpp/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) method


Establece una conexión al puerto especificado en el host especificado.

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hostname | String | El nombre del host DNS remoto al que pretende conectarse. |
| puerto | int32_t | El número de puerto local desde el cual pretende comunicarse. |

## Ver también

* Class [String](../../../system/string/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) method


Establece una conexión con el host en la dirección especificada y el puerto especificado.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| addr | System::SharedPtr\<IPAddress\> | La [IPAddress](../../../system.net/ipaddress/) del host remoto al que enviar datos. |
| puerto | int32_t | El número de puerto local desde el cual pretende comunicarse. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPAddress](../../../system.net/ipaddress/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) method


Establece una conexión a un punto final remoto.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| endPoint | System::SharedPtr\<IPEndPoint\> | el punto final al que enlaza la conexión UDP. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
