---
title: System::Net::Sockets::SocketOptionName enum
linktitle: SocketOptionName
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::SocketOptionName enum. Defines socket option names for the Socket class in C++.'
type: docs
weight: 1600
url: /cpp/system.net.sockets/socketoptionname/
---
## SocketOptionName enum


Defines socket option names for the [Socket](../socket/) class.

```cpp
enum class SocketOptionName
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Debug | 1 | Record debugging information. |
| AcceptConnection | 2 | Indicates if a socket is listening for an incoming connection. |
| ReuseAddress | 4 | Indicates if a socket can be bound to the address that is already in use. |
| KeepAlive | 8 | Enables the 'Keep-Alive' packets for a socket connection. |
| DontRoute | 16 | Indicates if a packet is sent directly to the interface addresses. |
| Broadcast | 32 | Indicates if a socket can send the broadcast messages. |
| UseLoopback | 64 | Bypass hardware when possible. |
| Linger | 128 | The system will block the process on the close attempt until it is able to transmit the data. |
| OutOfBandInline | 256 | Receives out-of-band data in the normal data stream. |
| DontLinger | n/a | Indicates if a socket will be closed without lingering. |
| ExclusiveAddressUse | n/a | A socket will use the bound address exclusively. |
| SendBuffer | 4097 | Specifies the send buffer size. |
| ReceiveBuffer | 4098 | Specifies the receive buffer size. |
| SendLowWater | 4099 | Specifies the minimum amount of data for the send operations. |
| ReceiveLowWater | 4100 | Specifies the minimum amount of data for the receive operations. |
| SendTimeout | 4101 | Specifies the timeout for the synchronous send operations. |
| ReceiveTimeout | 4102 | Specifies the timeout for the synchronous receive operations. |
| Error | 4103 | Returns the error status and clear. |
| Type | 4104 | Returns a socket type. |
| ReuseUnicastPort | 12295 | Indicates if the system should defer the ephemeral port allocation for the outbound connections. |
| MaxConnections | 2147483647 | This option is not supported. It was used to specify the maximum queue length for listening. |
| IPOptions | 1 | Specifies the IP option that must be inserted to outgoing datagrams. |
| HeaderIncluded | 2 | The header is included to outgoing datagrams. |
| TypeOfService | 3 | Change the IP header type of the service field. |
| IpTimeToLive | 4 | The IP time to live. |
| MulticastInterface | 9 | Set the interface for the outgoing multicast packets. |
| MulticastTimeToLive | 10 | The IP multicast time to live. |
| MulticastLoopback | 11 | The IP Multicast loopback. |
| AddMembership | 12 | Add an IP group membership. |
| DropMembership | 13 | Drop an IP group membership. |
| DontFragment | 14 | Don't fragment the IP datagrams. |
| AddSourceMembership | 15 | Join the IP group/source. |
| DropSourceMembership | 16 | Drop the IP group/source. |
| BlockSource | 17 | Block the IP group/source. |
| UnblockSource | 18 | Unblock the IP group/source. |
| PacketInformation | 19 | Receive packet information for IPv4. |
| HopLimit | 21 | Delivers an integer containing the HOP count of the packet. |
| IPProtectionLevel | 23 | Enables restriction of an IPv6 socket to the specified scope. |
| IPv6Only | 27 | The socket is restricted to send and receive IPv6 packets only. |
| NoDelay | 1 | Disables the Nagle algorithm for coalescing the send packets. |
| BsdUrgent | 2 | Use the urgent data as defined in RFC-1222. |
| Expedited | 2 | Use the expedited data as defined in RFC-1222. |
| NoChecksum | 1 | Send the UDP datagrams with a checksum set to zero. |
| ChecksumCoverage | 20 | Set or get the UDP checksum coverage. |
| UpdateAcceptContext | 28683 | Updates a client socket with the same properties of a listening socket. |
| UpdateConnectContext | 28688 | Updates a client socket with the same properties of a listening socket. |

## See Also

* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
