---
title: System::Net::Http::Headers::TransferCodingHeaderValue class
linktitle: TransferCodingHeaderValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::TransferCodingHeaderValue class. Represents a value of the ''Accept-Encoding'' header. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2400
url: /cpp/system.net.http.headers/transfercodingheadervalue/
---
## TransferCodingHeaderValue class


Represents a value of the 'Accept-Encoding' header. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class TransferCodingHeaderValue : public virtual System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| [get_Parameters](./get_parameters/)() | Returns the parameters. |
| [get_Value](./get_value/)() | RTTI information. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| static [GetTransferCodingLength](./gettransfercodinglength/)(String, int32_t, const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\&, System::SharedPtr\<TransferCodingHeaderValue\>\&) | Converts a passed string from the specified index to an instance of the [TransferCodingHeaderValue](./) class. |
| static [Parse](./parse/)(String) | Converts a passed string to an instance of the [TransferCodingHeaderValue](./) class. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| [TransferCodingHeaderValue](./transfercodingheadervalue/)() | Constructs a new instance. |
| [TransferCodingHeaderValue](./transfercodingheadervalue/)(String) | Constructs a new instance. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<TransferCodingHeaderValue\>\&) | Tries to convert a passed string to an instance of the [TransferCodingHeaderValue](./) class. |
## See Also

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
