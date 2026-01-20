---
title: System::Net::Sockets::SocketError enum
linktitle: SocketError
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::SocketError enum. Enumerates the socket error types in C++.'
type: docs
weight: 1300
url: /cpp/system.net.sockets/socketerror/
---
## SocketError enum


Enumerates the socket error types.

```cpp
enum class SocketError
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Success | 0 | A socket operation completed successfully. |
| SocketError | -1 | An unspecified socket error occurred. |
| Interrupted | 10004 | A blocking socket call is cancelled. |
| AccessDenied | 10013 | Access to a socket is denied. |
| Fault | 10014 | An invalid pointer address is detected. |
| InvalidArgument | 10022 | An invalid argument is provided. |
| TooManyOpenSockets | 10024 | There are too many open sockets in the underlying socket provider. |
| WouldBlock | 10035 | An operation cannot be immediately completed on a non-blocking socket. |
| InProgress | 10036 | A blocking operation is in progress. |
| AlreadyInProgress | 10037 | A non-blocking socket already has a running operation. |
| NotSocket | 10038 | An attempt to call a socket operation on non-socket. |
| DestinationAddressRequired | 10039 | A required address is omitted from a socket operation. |
| MessageSize | 10040 | A datagram is too long. |
| ProtocolType | 10041 | A protocol type is not supported by this socket. |
| ProtocolOption | 10042 | An unknown, invalid, or unsupported option or level is used. |
| ProtocolNotSupported | 10043 | A protocol is not implemented or not configured. |
| SocketNotSupported | 10044 | An address family doesn't support the specified socket. |
| OperationNotSupported | 10045 | A protocol family doesn't support an address family. |
| ProtocolFamilyNotSupported | 10046 | A protocol family is not implemented or not configured. |
| AddressFamilyNotSupported | 10047 | The specified address family is not supported. |
| AddressAlreadyInUse | 10048 | An address can be used only once. |
| AddressNotAvailable | 10049 | The selected IP address is not valid in this context. |
| NetworkDown | 10050 | The network is not available. |
| NetworkUnreachable | 10051 | No route to the remote host exists. |
| NetworkReset | 10052 | An application tried to set 'Keep-Alive' on a connection that has already timed out. |
| ConnectionAborted | 10053 | A connection is aborted. |
| ConnectionReset | 10054 | A connection is reset by a remote peer. |
| NoBufferSpaceAvailable | 10055 | No free buffer space is available for a socket operation. |
| IsConnected | 10056 | A socket is already connected. |
| NotConnected | 10057 | An application tried to send or receive data, and a socket is not connected. |
| Shutdown | 10058 | A request to send or receive data is forbidden because the socket has already been closed. |
| TimedOut | 10060 | A connection attempt timed out, or a connected host has failed to respond. |
| ConnectionRefused | 10061 | A remote host is actively refusing a connection. |
| HostDown | 10064 | An operation failed because a remote host is down. |
| HostUnreachable | 10065 | No network route to the specified host exists. |
| ProcessLimit | 10067 | Too many processes are using the underlying socket provider. |
| SystemNotReady | 10091 | A network subsystem is unavailable. |
| VersionNotSupported | 10092 | A version of the underlying socket provider is out of range. |
| NotInitialized | 10093 | The underlying socket provider is not initialized. |
| Disconnecting | 10101 | A graceful shutdown is in progress. |
| TypeNotFound | 10109 | The specified class is not found. |
| HostNotFound | 11001 | The specified host is unknown. |
| TryAgain | 11002 | A name of a host cannot be resolved. |
| NoRecovery | 11003 | An error is unrecoverable or a requested database cannot be located. |
| NoData | 11004 | A requested name or IP address is not found on the name server. |

## See Also

* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
