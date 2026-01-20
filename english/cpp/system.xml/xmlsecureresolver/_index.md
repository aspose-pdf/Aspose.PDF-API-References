---
title: System::Xml::XmlSecureResolver class
linktitle: XmlSecureResolver
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlSecureResolver class. Helps to secure another implementation of XmlResolver by wrapping the XmlResolver object and restricting the resources that the underlying XmlResolver has access to in C++.'
type: docs
weight: 3600
url: /cpp/system.xml/xmlsecureresolver/
---
## XmlSecureResolver class


Helps to secure another implementation of [XmlResolver](../xmlresolver/) by wrapping the [XmlResolver](../xmlresolver/) object and restricting the resources that the underlying [XmlResolver](../xmlresolver/) has access to.

```cpp
class XmlSecureResolver : public System::Xml::XmlResolver
```

## Methods

| Method | Description |
| --- | --- |
| [GetEntity](./getentity/)(SharedPtr\<Uri\>, String, const TypeInfo\&) override | Maps a URI to an object that contains the actual resource. |
| [ResolveUri](./resolveuri/)(SharedPtr\<Uri\>, String) override | Resolves the absolute URI from the base and relative URIs by calling **ResolveUri** on the underlying [XmlResolver](../xmlresolver/). |
| [set_Credentials](./set_credentials/)(SharedPtr\<Net::ICredentials\>) override | Sets credentials used to authenticate web requests. |
| [XmlSecureResolver](./xmlsecureresolver/)(const SharedPtr\<XmlResolver\>\&, const String\&) | Initializes a new instance of the [XmlSecureResolver](./) class with the [XmlResolver](../xmlresolver/) and URL provided. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlResolver](../xmlresolver/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
