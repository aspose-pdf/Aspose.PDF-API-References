---
title: System::Net::Http::Headers::NameValueHeaderValue class
linktitle: NameValueHeaderValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::NameValueHeaderValue class. Represents a key/value pair to use in headers. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1400
url: /cpp/system.net.http.headers/namevalueheadervalue/
---
## NameValueHeaderValue class


Represents a key/value pair to use in headers. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class NameValueHeaderValue : public virtual System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static [Find](./find/)(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, String) | Finds the NameValueHeaderValue-class instance in a collection by the specified name. |
| [get_Name](./get_name/)() | Returns a name of the current instance. |
| [get_Value](./get_value/)() | Gets a value of the current instance. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| static [GetHashCode](./gethashcode/)(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) | Returns a hash code of all the collection items. |
| static [GetNameValueLength](./getnamevaluelength/)(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) | Converts a passed string from the specified index to an instance of the [NameValueHeaderValue](./) class. |
| static [GetNameValueLength](./getnamevaluelength/)(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) | Converts a passed string from the specified index to an instance of the [NameValueHeaderValue](./) class. |
| static [GetNameValueListLength](./getnamevaluelistlength/)(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) | Converts a passed string from the specified index to the collection of the NameValueHeaderValue-class instances and returns the length of a parsed substring. |
| static [GetValueLength](./getvaluelength/)(String, int32_t) | Returns the length of a value from the specified index. |
| [NameValueHeaderValue](./namevalueheadervalue/)() | Constructs a new instance. |
| [NameValueHeaderValue](./namevalueheadervalue/)(String) | Constructs a new instance. |
| [NameValueHeaderValue](./namevalueheadervalue/)(String, String) | Constructs a new instance. |
| static [Parse](./parse/)(String) | Converts a passed string to an instance of the [NameValueHeaderValue](./) class. |
| [set_Value](./set_value/)(String) | Sets a value of the current instance. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static [ToString](./tostring/)(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) | Returns a string representation of the collection of the NameValueHeaderValue-class instances. |
| static [ToString](./tostring/)(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) | Returns a string representation of the collection of the NameValueHeaderValue-class instances. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<NameValueHeaderValue\>\&) | Tries to convert a passed string to an instance of the [NameValueHeaderValue](./) class. |
## See Also

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
