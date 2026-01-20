---
title: System::Net::Sockets::IOControlCode enum
linktitle: IOControlCode
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::IOControlCode enum. Enumerates the IO control codes in C++.'
type: docs
weight: 900
url: /cpp/system.net.sockets/iocontrolcode/
---
## IOControlCode enum


Enumerates the [IO](../../system.io/) control codes.

```cpp
enum class IOControlCode : int64_t
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| AsyncIO | -2147195267 | Enable or disable the asynchronous I/O mode of the socket. |
| NonBlockingIO | -2147195266 | Mark the socket as nonblocking. |
| DataToRead | 1074030207 | Return the number of bytes available for reading. |
| OobDataRead | 1074033415 | Return information about out-of-band data waiting to be received. |
| AssociateHandle | -2013265919 | Associate this socket with the specified handle of a companion interface. |
| EnableCircularQueuing | 671088642 | Replace the oldest queued datagram with an incoming one when the incoming message queues are full. |
| Flush | 671088644 | Discards current contents of the sending queue associated with this socket. |
| GetBroadcastAddress | 1207959557 | Return a SOCKADDR structure that contains the broadcast address for the address family of the current socket. |
| GetExtensionFunctionPointer | -939524090 | Retrieve a pointer to the specified extension function supported by the associated service provider. |
| GetQos | -939524089 | Retrieve the QOS structure associated with the socket. |
| GetGroupQos | -939524088 | Return the QOS attributes for the socket group. |
| MultipointLoopback | -2013265911 | Control whether data sent by an application on the local computer (not necessarily by the same socket) in a multicast session will be received by a socket joined to the multicast destination group on the loopback interface. |
| MulticastScope | -2013265910 | Control the number of times a multicast packet can be forwarded by a router, also known as TTL, or hop count. |
| SetQos | -2013265909 | Set the QOS attributes for the socket. |
| SetGroupQos | -2013265908 | Set the QOS attributes for the socket group. |
| TranslateHandle | -939524083 | Return a handle for the socket that is valid in the context of a companion interface. |
| RoutingInterfaceQuery | -939524076 | Return the interface addresses that can be used to connect to the specified remote address. |
| RoutingInterfaceChange | -2013265899 | Enable receiving a notification when the local interface used to access a remote endpoint changes. |
| AddressListQuery | 1207959574 | Return the list of the local interfaces that the socket can bind to. |
| AddressListChange | 671088663 | Enable receiving a notification when the list of the local interfaces for the socket's protocol family changes. |
| QueryTargetPnpHandle | 1207959576 | Retrieve the underlying provider's SOCKET handle. |
| NamespaceChange | -2013265895 | Control whether the socket receives notification when a namespace query becomes invalid. |
| AddressListSort | -939524071 | Sort a list of IPv6 and IPv4 destination addresses to determine the best available address for making a connection. |
| ReceiveAll | -1744830463 | Enable receiving all IPv4 packets on the network. |
| ReceiveAllMulticast | -1744830462 | Enable receiving all multicast IPv4 packets on the network. |
| ReceiveAllIgmpMulticast | -1744830461 | Enable receiving all IGMP packets on the network. |
| KeepAliveValues | -1744830460 | Control sending TCP keep-alive packets and the interval at which they are sent. |
| AbsorbRouterAlert | -1744830459 | This value is equal to the Winsock 2 'SIO_ABSORB_RTRALERT' constant. |
| UnicastInterface | -1744830458 | Set the interface used for the outgoing unicast packets. |
| LimitBroadcasts | -1744830457 | This value is equal to the Winsock 2 'SIO_LIMIT_BROADCASTS' constant. |
| BindToInterface | -1744830456 | Bind the socket to a specified interface index. |
| MulticastInterface | -1744830455 | Set the interface used for the outgoing multicast packets. |
| AddMulticastGroupOnInterface | -1744830454 | Join a multicast group using an interface identified by its index. |
| DeleteMulticastGroupFromInterface | -1744830453 | Remove the socket from a multicast group. |

## See Also

* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
