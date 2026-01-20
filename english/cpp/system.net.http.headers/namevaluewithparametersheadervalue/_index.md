---
title: System::Net::Http::Headers::NameValueWithParametersHeaderValue class
linktitle: NameValueWithParametersHeaderValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::NameValueWithParametersHeaderValue class. Represents a key/value pair with parameters to use in headers. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1500
url: /cpp/system.net.http.headers/namevaluewithparametersheadervalue/
---
## NameValueWithParametersHeaderValue class


Represents a key/value pair with parameters to use in headers. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class NameValueWithParametersHeaderValue : public System::Net::Http::Headers::NameValueHeaderValue
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| [get_Parameters](./get_parameters/)() | RTTI information. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| static [GetNameValueWithParametersLength](./getnamevaluewithparameterslength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Converts a passed string from the specified index to an instance of the [NameValueWithParametersHeaderValue](./) class. |
| [NameValueWithParametersHeaderValue](./namevaluewithparametersheadervalue/)(String) | Constructs a new instance. |
| [NameValueWithParametersHeaderValue](./namevaluewithparametersheadervalue/)(String, String) | Constructs a new instance. |
| [NameValueWithParametersHeaderValue](./namevaluewithparametersheadervalue/)() | Constructs a new instance. |
| static [Parse](./parse/)(String) | Converts a passed string to an instance of the [NameValueWithParametersHeaderValue](./) class. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<NameValueWithParametersHeaderValue\>\&) | Tries to convert a passed string to an instance of the [NameValueWithParametersHeaderValue](./) class. |
## See Also

* Class [NameValueHeaderValue](../namevalueheadervalue/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
