---
title: System::Net::Sockets::UdpClient::Send method
linktitle: Send
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::UdpClient::Send method. Sends a UDP datagram to a remote host in C++.'
type: docs
weight: 700
url: /cpp/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) method


Sends a UDP datagram to a remote host.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```


| Parameter | Type | Description |
| --- | --- | --- |
| dgram | System::ArrayPtr\<uint8_t\> | An array of type [Byte](../../../system/byte/) to send. |
| bytes | int32_t | The number of bytes in the datagram. |

### ReturnValue

The number of bytes that are sent.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) method


Sends a UDP datagram to the specified port on the specified remote host.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```


| Parameter | Type | Description |
| --- | --- | --- |
| dgram | System::ArrayPtr\<uint8_t\> | An array of type [Byte](../../../system/byte/) to send |
| bytes | int32_t | The number of bytes in the datagram. |
| hostname | String | A name of the remote host. |
| port | int32_t | A remote port number. |

### ReturnValue

The number of bytes that are sent.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) method


Sends a UDP datagram to the host at the remote end point.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```


| Parameter | Type | Description |
| --- | --- | --- |
| dgram | System::ArrayPtr\<uint8_t\> | An array of type [Byte](../../../system/byte/) to send |
| bytes | int32_t | The number of bytes in the datagram. |
| endPoint | System::SharedPtr\<IPEndPoint\> | An [IPEndPoint](../../../system.net/ipendpoint/) that represents the host and port to which to send the datagram. |

### ReturnValue

The number of bytes that are sent.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
