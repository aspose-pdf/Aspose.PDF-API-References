---
title: System::Net::Cookie class
linktitle: Cookie
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Cookie class. Represents an HTTP cookie. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.net/cookie/
---
## Cookie class


Represents an HTTP cookie. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Cookie : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() | Creates a copy of the current instance. |
| [Cookie](./cookie/)() | Constructs a new instance. |
| [Cookie](./cookie/)(String, String) | Constructs a new instance. |
| [Cookie](./cookie/)(String, String, String) | Constructs a new instance. |
| [Cookie](./cookie/)(String, String, String, String) | Constructs a new instance. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| [get_Comment](./get_comment/)() const | Gets the 'Comment' attribute's value. |
| [get_CommentUri](./get_commenturi/)() const | Gets the 'CommentURL' attribute's value. |
| [get_Discard](./get_discard/)() const | Gets the 'Discard' attribute's value. |
| [get_Domain](./get_domain/)() const | Gets the 'Domain' attribute's value. |
| [get_DomainImplicit](./get_domainimplicit/)() | Gets a value that indicates if the domain is implicit. |
| [get_DomainKey](./get_domainkey/)() const | Returns the domain key. |
| [get_Expired](./get_expired/)() | Gets a value that indicates if the cookie expired. |
| [get_Expires](./get_expires/)() | Gets the 'Expires' attribute's value. |
| [get_HttpOnly](./get_httponly/)() const | Gets the 'HttpOnly' attribute's value. |
| [get_Name](./get_name/)() const | Gets the cookie's name. |
| [get_Path](./get_path/)() const | Gets the 'Path' attribute's value. |
| [get_Plain](./get_plain/)() const | Returns a value that indicates if the cookie specification is 'Plain'. |
| [get_Port](./get_port/)() const | Gets the 'Port' attribute's value. |
| [get_PortList](./get_portlist/)() const | Returns the collection of the 'Port' attribute's values. |
| [get_Secure](./get_secure/)() const | Gets the 'Secure' attribute's value. |
| [get_TimeStamp](./get_timestamp/)() const | Returns the time when the cookie was created. |
| [get_Value](./get_value/)() const | Gets the cookie's'value. |
| [get_Variant](./get_variant/)() const | Gets the cookie's specification. |
| [get_Version](./get_version/)() const | Gets the '[Version](../../system/version/)' attribute's value. |
| [GetHashCode](./gethashcode/)() const override | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| [InternalSetName](./internalsetname/)(String) | This method is called by other methods to set a method name. |
| [set_Comment](./set_comment/)(String) | Sets the 'Comment' attribute's value. |
| [set_CommentUri](./set_commenturi/)(System::SharedPtr\<Uri\>) | Sets the 'CommentURL' attribute's value. |
| [set_Discard](./set_discard/)(bool) | Sets the 'Discard' attribute's value. |
| [set_Domain](./set_domain/)(String) | Sets the 'Domain' attribute's value. |
| [set_DomainImplicit](./set_domainimplicit/)(bool) | Sets a value that indicates if the domain is implicit. |
| [set_Expired](./set_expired/)(bool) | Sets a value that indicates if the cookie expired. |
| [set_Expires](./set_expires/)(DateTime) | Sets the 'Expires' attribute's value. |
| [set_HttpOnly](./set_httponly/)(bool) | Sets the 'HttpOnly' attribute's value. |
| [set_Name](./set_name/)(String) | Sets the cookie's name. |
| [set_Path](./set_path/)(String) | Sets the 'Path' attribute's value. |
| [set_Port](./set_port/)(String) | Sets the 'Port' attribute's value. |
| [set_Secure](./set_secure/)(bool) | Sets the 'Secure' attribute's value. |
| [set_Value](./set_value/)(String) | Sets the cookie's value. |
| [set_Variant](./set_variant/)(CookieVariant) | Sets the cookie's specification. |
| [set_Version](./set_version/)(int32_t) | Sets the '[Version](../../system/version/)' attribute's value. |
| [ToServerString](./toserverstring/)() | Serializes the current instance to the string representation. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| [VerifySetDefaults](./verifysetdefaults/)(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) | Verifies and sets the default attribute's values. |
## Fields

| Field | Description |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | The 'Comment' attribute's name. |
| static [CommentUrlAttributeName](./commenturlattributename/) | The 'CommentURL' attribute's name. |
| static [DiscardAttributeName](./discardattributename/) | The 'Discard' attribute's name. |
| static [DomainAttributeName](./domainattributename/) | The 'Domain' attribute's name. |
| static [EqualsLiteral](./equalsliteral/) | The separator that is used to separates the name and value of an attribute. |
| static [ExpiresAttributeName](./expiresattributename/) | The 'Expires' attribute's name. |
| static [HttpOnlyAttributeName](./httponlyattributename/) | The 'HttpOnly' attribute's name. |
| static [MaxAgeAttributeName](./maxageattributename/) | The 'Max-Age' attribute's name. |
| static [MaxSupportedVersion](./maxsupportedversion/) | RTTI information. |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | The string representation of the maximum supported version. |
| static [PathAttributeName](./pathattributename/) | The 'Path' attribute's name. |
| static [PortAttributeName](./portattributename/) | The 'Port' attribute's name. |
| static [PortSplitDelimiters](./portsplitdelimiters/) | The array that contains delimiters for the 'Port' attribute's values. |
| static [QuotesLiteral](./quotesliteral/) | The symbol used to wrap the attribute's parts. |
| static [ReservedToName](./reservedtoname/) | A value that is reserved for the cookie name. |
| static [ReservedToValue](./reservedtovalue/) | A value that is reserved for the cookie value. |
| static [SecureAttributeName](./secureattributename/) | The 'Secure' attribute's name. |
| static [SeparatorLiteral](./separatorliteral/) | The attribute separator. |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | The prefix of the special attributes' names. |
| static [VersionAttributeName](./versionattributename/) | The '[Version](../../system/version/)' attribute's name. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
