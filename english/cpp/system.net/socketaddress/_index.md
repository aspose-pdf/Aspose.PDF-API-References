---
title: System::Net::SocketAddress class
linktitle: SocketAddress
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::SocketAddress class. Used to store serialized information about the EndPoint class instances. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3300
url: /cpp/system.net/socketaddress/
---
## SocketAddress class


Used to store serialized information about the [EndPoint](../endpoint/) class instances. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SocketAddress : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| [get_Family](./get_family/)() | RTTI information. |
| [get_Size](./get_size/)() | Returns the underlying buffer size. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| [idx_get](./idx_get/)(int32_t) | Gets a value of the underlying buffer at the specified index. |
| [idx_set](./idx_set/)(int32_t, uint8_t) | Sets a value of the underlying buffer at the specified index. |
| [SocketAddress](./socketaddress/)(Sockets::AddressFamily) | Constructs a new instance. |
| [SocketAddress](./socketaddress/)(Sockets::AddressFamily, int32_t) | Constructs a new instance. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
