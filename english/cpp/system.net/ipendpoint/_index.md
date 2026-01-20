---
title: System::Net::IPEndPoint class
linktitle: IPEndPoint
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::IPEndPoint class. Represents a network endpoint that contains an IP address and a port. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2500
url: /cpp/system.net/ipendpoint/
---
## IPEndPoint class


Represents a network endpoint that contains an IP address and a port. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class IPEndPoint : public System::Net::EndPoint
```

## Methods

| Method | Description |
| --- | --- |
| [Create](./create/)(System::SharedPtr\<SocketAddress\>) override | Create a new instance of the [EndPoint](../endpoint/) class using the specified socket address. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| [get_Address](./get_address/)() | Gets the endpoint address. |
| [get_AddressFamily](./get_addressfamily/)() override | RTTI information. |
| [get_Port](./get_port/)() | Gets the port number. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| [GetImpl](./getimpl/)() const override | Returns a pointer to implementation. |
| [IPEndPoint](./ipendpoint/)(int64_t, int32_t) | Constructs a new instance. |
| [IPEndPoint](./ipendpoint/)(System::SharedPtr\<IPAddress\>, int32_t) | Constructs a new instance. |
| [set_Address](./set_address/)(System::SharedPtr\<IPAddress\>) | Sets the endpoint address. |
| [set_Port](./set_port/)(int32_t) | Sets the port number. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
## Fields

| Field | Description |
| --- | --- |
| static [Any](./any/) | The endpoint for any IPv4 address and any port. |
| static [AnyPort](./anyport/) | A value that indicates if any port can be used. |
| static [IPv6Any](./ipv6any/) | The endpoint for any IPv6 address and any port. |
| static [MaxPort](./maxport/) | The maximum port number. |
| static [MinPort](./minport/) | RTTI information. |
## See Also

* Class [EndPoint](../endpoint/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
