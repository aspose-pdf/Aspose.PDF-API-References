---
title: System::Xml::XmlReader::ReadContentAs method
linktitle: ReadContentAs
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlReader::ReadContentAs method. Reads the content as an object of the type specified in C++.'
type: docs
weight: 3900
url: /cpp/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs method


Reads the content as an object of the type specified.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| returnType | const TypeInfo\& | The type of the value to be returned. |
| namespaceResolver | SharedPtr\<IXmlNamespaceResolver\> | An [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) object that is used to resolve any namespace prefixes related to type conversion. For example, this can be used when converting an [XmlQualifiedName](../../xmlqualifiedname/) object to an **xs:string**. This value can be **nullptr**. |

### ReturnValue

The concatenated text content or attribute value converted to the requested type.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
