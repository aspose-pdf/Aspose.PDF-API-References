---
title: System::Net::Http::Headers::ViaHeaderValue class
linktitle: ViaHeaderValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::ViaHeaderValue class. Represents a value of the ''Via'' header. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2600
url: /cpp/system.net.http.headers/viaheadervalue/
---
## ViaHeaderValue class


Represents a value of the 'Via' header. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ViaHeaderValue : public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| [get_Comment](./get_comment/)() | Returns the comment from the 'Via' header value. |
| [get_ProtocolName](./get_protocolname/)() | RTTI information. |
| [get_ProtocolVersion](./get_protocolversion/)() | Returns the protocol version from the 'Via' header value. |
| [get_ReceivedBy](./get_receivedby/)() | Returns the host and port that the request or response was received by. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| static [GetViaLength](./getvialength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Converts a passed string from the specified index to an instance of the [ViaHeaderValue](./) class. |
| static [Parse](./parse/)(String) | Converts a passed string to an instance of the [ViaHeaderValue](./) class. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<ViaHeaderValue\>\&) | Tries to convert a passed string to an instance of the [ViaHeaderValue](./) class. |
| [ViaHeaderValue](./viaheadervalue/)(String, String) | Constructs a new instance. |
| [ViaHeaderValue](./viaheadervalue/)(String, String, String) | Constructs a new instance. |
| [ViaHeaderValue](./viaheadervalue/)(String, String, String, String) | Constructs a new instance. |
## See Also

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
