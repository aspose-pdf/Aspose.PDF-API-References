---
title: System::Xml::XmlDocument::CreateElement method
linktitle: CreateElement
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlDocument::CreateElement method. Creates an element with the specified name in C++.'
type: docs
weight: 800
url: /cpp/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) method


Creates an element with the specified name.

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | const String\& | The qualified name of the element. If the name contains a colon then the [XmlNode::get_Prefix](../../xmlnode/get_prefix/) value reflects the part of the name preceding the colon and the [XmlDocument::get_LocalName](../get_localname/) value reflects the part of the name after the colon. The qualified name cannot include a prefix of **xmlns**. |

### ReturnValue

The new [XmlElement](../../xmlelement/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlElement](../../xmlelement/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlDocument::CreateElement(const String\&, const String\&, const String\&) method


Creates an element with the specified [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/), and [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const String\& | The prefix of the new element (if any). [String::Empty](../../../system/string/empty/) and **nullptr** are equivalent. |
| localName | const String\& | The local name of the new element. |
| namespaceURI | const String\& | The namespace URI of the new element (if any). [String::Empty](../../../system/string/empty/) and **nullptr** are equivalent. |

### ReturnValue

The new [XmlElement](../../xmlelement/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlElement](../../xmlelement/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlDocument::CreateElement(const String\&, const String\&) method


Creates an [XmlElement](../../xmlelement/) with the qualified name and [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| qualifiedName | const String\& | The qualified name of the element. If the name contains a colon then the [XmlNode::get_Prefix](../../xmlnode/get_prefix/) value will reflect the part of the name preceding the colon and the [XmlDocument::get_LocalName](../get_localname/) value will reflect the part of the name after the colon. The qualified name cannot include a prefix of **xmlns**. |
| namespaceURI | const String\& | The namespace URI of the element. |

### ReturnValue

The new [XmlElement](../../xmlelement/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlElement](../../xmlelement/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
