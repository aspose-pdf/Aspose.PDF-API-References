---
title: System::Net::IPAddress class
linktitle: IPAddress
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::IPAddress class. Represents the IP address. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2400
url: /cpp/system.net/ipaddress/
---
## IPAddress class


Represents the IP address. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class IPAddress : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| [get_AddressFamily](./get_addressfamily/)() | Returns the address family. |
| [get_IsIPv4MappedToIPv6](./get_isipv4mappedtoipv6/)() | Returns a value that indicates if the address is an IPv4 address and is mapped to an IPv6 address. |
| [get_IsIPv6LinkLocal](./get_isipv6linklocal/)() | Returns a value that indicates if the address is an IPv6 link-local address. |
| [get_IsIPv6Multicast](./get_isipv6multicast/)() | Returns a value that indicates if the address is an global IPv6 multicast address. |
| [get_IsIPv6SiteLocal](./get_isipv6sitelocal/)() | Returns a value that indicates if the address is an IPv6 site-local address. |
| [get_IsIPv6Teredo](./get_isipv6teredo/)() | Returns a value that indicates if the address is an IPv6 Teredo address. |
| [get_ScopeId](./get_scopeid/)() | Gets the scope identifier of the IPv6 address. |
| [GetAddressBytes](./getaddressbytes/)() | Returns a byte array of the IP address. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| [GetImpl](./getimpl/)() const | Returns a pointer to implementation. |
| static [HostToNetworkOrder](./hosttonetworkorder/)(int64_t) | Converts the specified host byte order to the corresponding network byte order. |
| static [HostToNetworkOrder](./hosttonetworkorder/)(int32_t) | Converts the specified host byte order to the corresponding network byte order. |
| static [HostToNetworkOrder](./hosttonetworkorder/)(int16_t) | Converts the specified host byte order to the corresponding network byte order. |
| [IPAddress](./ipaddress/)(int64_t) | Constructs a new instance. |
| [IPAddress](./ipaddress/)(System::ArrayPtr\<uint8_t\>, int64_t) | Constructs a new instance. |
| [IPAddress](./ipaddress/)(System::ArrayPtr\<uint8_t\>) | Constructs a new instance. |
| [IPAddress](./ipaddress/)() | Constructs a new instance. |
| static [IsLoopback](./isloopback/)(System::SharedPtr\<IPAddress\>) | Returns a value that indicates if the specified address is a loopback address. |
| [MapToIPv4](./maptoipv4/)() | Maps the address to the IPv4 address. |
| [MapToIPv6](./maptoipv6/)() | Maps the address to the IPv6 address. |
| static [NetworkToHostOrder](./networktohostorder/)(int64_t) | Converts the specified network byte order to the corresponding host byte order. |
| static [NetworkToHostOrder](./networktohostorder/)(int32_t) | Converts the specified network byte order to the corresponding host byte order. |
| static [NetworkToHostOrder](./networktohostorder/)(int16_t) | Converts the specified network byte order to the corresponding host byte order. |
| static [Parse](./parse/)(String) | Converts a passed string to an instance of the [IPAddress](./) class. |
| [set_ScopeId](./set_scopeid/)(int64_t) | Sets the scope identifier of the IPv6 address. |
| [SetImpl](./setimpl/)(ImplPtr) | Sets a pointer to implementation. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<IPAddress\>\&) | Tries to convert a passed string to an instance of the [IPAddress](./) class. |
## Fields

| Field | Description |
| --- | --- |
| static [Any](./any/) | RTTI information. |
| static [Broadcast](./broadcast/) | The IPv4 broadcast address. |
| static [IPv6Any](./ipv6any/) | The IPv6 address that indicates if the server must listen all network interfaces. |
| static [IPv6Loopback](./ipv6loopback/) | The IPv6 loopback address. |
| static [IPv6None](./ipv6none/) | The IPv6 address that indicates if the server mustn't listen any network interface. |
| static [Loopback](./loopback/) | The IPv4 loopback address. |
| static [None](./none/) | The IPv4 address that indicates if the server mustn't listen any network interface. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ImplPtr](./implptr/) | A pointer to the implementation type. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
