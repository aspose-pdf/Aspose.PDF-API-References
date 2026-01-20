---
title: System::Xml::Serialization::XmlSerializerNamespaces class
linktitle: XmlSerializerNamespaces
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Serialization::XmlSerializerNamespaces class. Contains the XML namespaces and prefixes that the Serialization::XmlSerializer uses to generate qualified names in an XML-document instance in C++.'
type: docs
weight: 800
url: /cpp/system.xml.serialization/xmlserializernamespaces/
---
## XmlSerializerNamespaces class


Contains the XML namespaces and prefixes that the [Serialization::XmlSerializer](../xmlserializer/) uses to generate qualified names in an XML-document instance.

```cpp
class XmlSerializerNamespaces : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const String\&, const String\&) | Adds a prefix and namespace pair to an [Serialization::XmlSerializerNamespaces](./) object. |
| [get_Count](./get_count/)() | Returns the number of prefix and namespace pairs in the collection. |
| [get_NamespaceList](./get_namespacelist/)() |  |
| [get_Namespaces](./get_namespaces/)() |  |
| [set_Namespaces](./set_namespaces/)(const SharedPtr\<Collections::Generic::Dictionary\<String, String\>\>\&) |  |
| [ToArray](./toarray/)() | Returns the array of prefix and namespace pairs in an [Serialization::XmlSerializerNamespaces](./) object. |
| [XmlSerializerNamespaces](./xmlserializernamespaces/)() | Initializes a new instance of the [Serialization::XmlSerializerNamespaces](./) class. |
| [XmlSerializerNamespaces](./xmlserializernamespaces/)(const SharedPtr\<XmlSerializerNamespaces\>\&) | Initializes a new instance of the [Serialization::XmlSerializerNamespaces](./) class, using the specified instance of **[XmlSerializerNamespaces](./)** containing the collection of prefix and namespace pairs. |
| [XmlSerializerNamespaces](./xmlserializernamespaces/)(const ArrayPtr\<SharedPtr\<XmlQualifiedName\>\>\&) | Initializes a new instance of the [Serialization::XmlSerializerNamespaces](./) class. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml::Serialization](../)
* Library [Aspose.PDF for C++](../../)
