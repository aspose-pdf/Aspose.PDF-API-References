---
title: System::Xml::XmlResolver class
linktitle: XmlResolver
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlResolver class. Resolves external XML resources named by a Uniform Resource Identifier (URI) in C++.'
type: docs
weight: 3500
url: /cpp/system.xml/xmlresolver/
---
## XmlResolver class


Resolves external XML resources named by a Uniform Resource Identifier (URI).

```cpp
class XmlResolver : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [GetEntity](./getentity/)(SharedPtr\<Uri\>, String, const TypeInfo\&) | When overridden in a derived class, maps a URI to an object that contains the actual resource. |
| virtual [ResolveUri](./resolveuri/)(SharedPtr\<Uri\>, String) | When overridden in a derived class, resolves the absolute URI from the base and relative URIs. |
| virtual [set_Credentials](./set_credentials/)(SharedPtr\<Net::ICredentials\>) | When overridden in a derived class, sets the credentials used to authenticate web requests. |
| virtual [SupportsType](./supportstype/)(SharedPtr\<Uri\>, const TypeInfo\&) | Enables the resolver to return types other than Stream. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
