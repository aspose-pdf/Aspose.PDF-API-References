---
title: System::Net::Sockets::UdpClient::Connect method
linktitle: Connect
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::UdpClient::Connect method. Establishes a connection to the specified port on the specified host in C++.'
type: docs
weight: 300
url: /cpp/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) method


Establishes a connection to the specified port on the specified host.

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```


| Parameter | Type | Description |
| --- | --- | --- |
| hostname | String | The name of the remote DNS host to which you intend to connect. |
| port | int32_t | The local port number from which you intend to communicate. |

## See Also

* Class [String](../../../system/string/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) method


Establishes a connection with the host at the specified address on the specified port.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```


| Parameter | Type | Description |
| --- | --- | --- |
| addr | System::SharedPtr\<IPAddress\> | The [IPAddress](../../../system.net/ipaddress/) of the remote host to which to send data. |
| port | int32_t | The local port number from which you intend to communicate. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPAddress](../../../system.net/ipaddress/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) method


Establishes a connection to a remote end point.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```


| Parameter | Type | Description |
| --- | --- | --- |
| endPoint | System::SharedPtr\<IPEndPoint\> | the endpoint to which you bind the UDP connection. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
