---
title: System::Xml::XmlUrlResolver class
linktitle: XmlUrlResolver
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlUrlResolver class. Resolves external XML resources named by a Uniform Resource Identifier (URI) in C++.'
type: docs
weight: 4100
url: /cpp/system.xml/xmlurlresolver/
---
## XmlUrlResolver class


Resolves external XML resources named by a Uniform Resource Identifier (URI).

```cpp
class XmlUrlResolver : public System::Xml::XmlResolver
```

## Methods

| Method | Description |
| --- | --- |
| [GetEntity](./getentity/)(SharedPtr\<Uri\>, String, const TypeInfo\&) override | Maps a URI to an object that contains the actual resource. |
| [ResolveUri](./resolveuri/)(SharedPtr\<Uri\>, String) override | Resolves the absolute URI from the base and relative URIs. |
| [set_CachePolicy](./set_cachepolicy/)(const SharedPtr\<Net::Cache::RequestCachePolicy\>\&) | Sets the cache policy for the underlying WebRequest object. |
| [set_Credentials](./set_credentials/)(SharedPtr\<Net::ICredentials\>) override | Sets credentials used to authenticate web requests. |
| [set_Proxy](./set_proxy/)(const SharedPtr\<Net::IWebProxy\>\&) | Sets the network proxy for the underlying WebRequest object. |
| [XmlUrlResolver](./xmlurlresolver/)() | Initializes a new instance of the [XmlUrlResolver](./) class. |
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
