---
title: System::Net::Sockets::Socket::GetSocketOption method
linktitle: GetSocketOption
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::Socket::GetSocketOption method. Returns the value that corresponds to the specified option name in C++.'
type: docs
weight: 3900
url: /cpp/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) method


Returns the value that corresponds to the specified option name.

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| optionLevel | SocketOptionLevel | The socket option level. |
| optionName | SocketOptionName | The option name. |

### ReturnValue

The value that corresponds to the specified option name.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) method


Returns the value that corresponds to the specified option name.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```


| Parameter | Type | Description |
| --- | --- | --- |
| optionLevel | SocketOptionLevel | The socket option level. |
| optionName | SocketOptionName | The option name. |
| optionLength | int32_t | The option length. |

### ReturnValue

The value that corresponds to the specified option name.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) method


Gets the value that corresponds to the specified option name.

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```


| Parameter | Type | Description |
| --- | --- | --- |
| optionLevel | SocketOptionLevel | The socket option level. |
| optionName | SocketOptionName | The option name. |
| optionValue | System::ArrayPtr\<uint8_t\> | The output parameter where the corresponding value will be assigned. |

## See Also

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
