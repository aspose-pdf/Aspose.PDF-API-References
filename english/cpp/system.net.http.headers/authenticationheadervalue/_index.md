---
title: System::Net::Http::Headers::AuthenticationHeaderValue class
linktitle: AuthenticationHeaderValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::AuthenticationHeaderValue class. Represents values of the ''Authorization'', ''ProxyAuthorization'', ''WWW-Authenticate'', and ''Proxy-Authenticate'' headers. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.net.http.headers/authenticationheadervalue/
---
## AuthenticationHeaderValue class


Represents values of the 'Authorization', 'ProxyAuthorization', 'WWW-Authenticate', and 'Proxy-Authenticate' headers. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class AuthenticationHeaderValue : public System::ICloneable
```

## Methods

| Method | Description |
| --- | --- |
| [AuthenticationHeaderValue](./authenticationheadervalue/)(String) | Constructor. |
| [AuthenticationHeaderValue](./authenticationheadervalue/)(String, String) | Constructor. |
| [Clone](./clone/)() override | RTTI information. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| [get_Parameter](./get_parameter/)() | Gets the credentials containing the authentication information. |
| [get_Scheme](./get_scheme/)() | RTTI information. |
| static [GetAuthenticationLength](./getauthenticationlength/)(String, int32_t, System::SharedPtr\<Object\>\&) | Parses the specified string and returns the last index of the string representation. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| static [Parse](./parse/)(String) | Converts a passed string to an instance of the [AuthenticationHeaderValue](./) class. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<AuthenticationHeaderValue\>\&) | Trying to convert a passed string to an instance of the [AuthenticationHeaderValue](./) class. |
## See Also

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
