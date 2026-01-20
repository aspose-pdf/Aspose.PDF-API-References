---
title: System::Net::DnsEndPoint class
linktitle: DnsEndPoint
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::DnsEndPoint class. Contains information used by the application to connect to the service. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 800
url: /cpp/system.net/dnsendpoint/
---
## DnsEndPoint class


Contains information used by the application to connect to the service. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DnsEndPoint : public System::Net::EndPoint
```

## Methods

| Method | Description |
| --- | --- |
| [DnsEndPoint](./dnsendpoint/)(String, int32_t) | Constructs a new instance. |
| [DnsEndPoint](./dnsendpoint/)(String, int32_t, System::Net::Sockets::AddressFamily) | Constructs a new instance. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| [get_AddressFamily](./get_addressfamily/)() override | RTTI information. |
| [get_Host](./get_host/)() | RTTI information. |
| [get_Port](./get_port/)() | Returns the port number. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
## See Also

* Class [EndPoint](../endpoint/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
