---
title: System::Net::Sockets::IPPacketInformation class
linktitle: IPPacketInformation
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Sockets::IPPacketInformation class. Represents information about the packet. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.net.sockets/ippacketinformation/
---
## IPPacketInformation class


Represents information about the packet. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class IPPacketInformation : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compares two objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| [get_Address](./get_address/)() | Returns the address from which the package is received. |
| [get_Interface](./get_interface/)() | Returns the network interface information. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| [IPPacketInformation](./ippacketinformation/)(System::SharedPtr\<IPAddress\>, int32_t) | Constructs a new instance. |
| [IPPacketInformation](./ippacketinformation/)() | Constructs a new instance. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
