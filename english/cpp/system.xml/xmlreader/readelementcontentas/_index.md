---
title: System::Xml::XmlReader::ReadElementContentAs method
linktitle: ReadElementContentAs
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlReader::ReadElementContentAs method. Reads the element content as the requested type in C++.'
type: docs
weight: 5200
url: /cpp/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method


Reads the element content as the requested type.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| returnType | const TypeInfo\& | The type of the value to be returned. |
| namespaceResolver | SharedPtr\<IXmlNamespaceResolver\> | An [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) object that is used to resolve any namespace prefixes related to type conversion. |

### ReturnValue

The element content converted to the requested typed object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) method


Checks that the specified local name and namespace URI matches that of the current element, then reads the element content as the requested type.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| returnType | const TypeInfo\& | The type of the value to be returned. |
| namespaceResolver | SharedPtr\<IXmlNamespaceResolver\> | An [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) object that is used to resolve any namespace prefixes related to type conversion. |
| localName | String | The local name of the element. |
| namespaceURI | String | The namespace URI of the element. |

### ReturnValue

The element content converted to the requested typed object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
