---
title: System::Xml::Resolvers::XmlPreloadedResolver class
linktitle: XmlPreloadedResolver
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Resolvers::XmlPreloadedResolver class. Represents a class that is used to prepopulate the cache with DTDs or XML streams in C++.'
type: docs
weight: 100
url: /cpp/system.xml.resolvers/xmlpreloadedresolver/
---
## XmlPreloadedResolver class


Represents a class that is used to prepopulate the cache with DTDs or XML streams.

```cpp
class XmlPreloadedResolver : public System::Xml::XmlResolver
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) | Adds a byte array to the [XmlPreloadedResolver](./) store and maps it to a URI. If the store already contains a mapping for the same URI, the existing mapping is overridden. |
| [Add](./add/)(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) | Adds a byte array to the [XmlPreloadedResolver](./) store and maps it to a URI. If the store already contains a mapping for the same URI, the existing mapping is overridden. |
| [Add](./add/)(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) | Adds a Stream to the [XmlPreloadedResolver](./) store and maps it to a URI. If the store already contains a mapping for the same URI, the existing mapping is overridden. |
| [Add](./add/)(const SharedPtr\<Uri\>\&, const String\&) | Adds a string with preloaded data to the [XmlPreloadedResolver](./) store and maps it to a URI. If the store already contains a mapping for the same URI, the existing mapping is overridden. |
| [get_PreloadedUris](./get_preloadeduris/)() | Returns a collection of preloaded URIs. |
| [GetEntity](./getentity/)(SharedPtr\<Uri\>, String, const TypeInfo\&) override | Maps a URI to an object that contains the actual resource. |
| [Remove](./remove/)(const SharedPtr\<Uri\>\&) | Removes the data that corresponds to the URI from the [XmlPreloadedResolver](./). |
| [ResolveUri](./resolveuri/)(SharedPtr\<Uri\>, String) override | Resolves the absolute URI from the base and relative URIs. |
| [set_Credentials](./set_credentials/)(SharedPtr\<Net::ICredentials\>) override | Sets the credentials that are used to authenticate the underlying [Net::WebRequest](../../system.net/webrequest/). |
| [SupportsType](./supportstype/)(SharedPtr\<Uri\>, const TypeInfo\&) override | Determines whether the resolver supports other Types than just Stream. |
| [XmlPreloadedResolver](./xmlpreloadedresolver/)() | Initializes a new instance of the [XmlPreloadedResolver](./) class. |
| [XmlPreloadedResolver](./xmlpreloadedresolver/)(XmlKnownDtds) | Initializes a new instance of the [XmlPreloadedResolver](./) class with the specified preloaded well-known DTDs. |
| [XmlPreloadedResolver](./xmlpreloadedresolver/)(const SharedPtr\<XmlResolver\>\&) | Initializes a new instance of the [XmlPreloadedResolver](./) class with the specified fallback resolver. |
| [XmlPreloadedResolver](./xmlpreloadedresolver/)(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) | Initializes a new instance of the [XmlPreloadedResolver](./) class with the specified fallback resolver and preloaded well-known DTDs. |
| [XmlPreloadedResolver](./xmlpreloadedresolver/)(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) | Initializes a new instance of the [XmlPreloadedResolver](./) class with the specified fallback resolver, preloaded well-known DTDs, and URI equality comparer. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlResolver](../../system.xml/xmlresolver/)
* Namespace [System::Xml::Resolvers](../)
* Library [Aspose.PDF for C++](../../)
