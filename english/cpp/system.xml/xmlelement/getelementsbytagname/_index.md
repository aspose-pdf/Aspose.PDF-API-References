---
title: System::Xml::XmlElement::GetElementsByTagName method
linktitle: GetElementsByTagName
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlElement::GetElementsByTagName method. Returns an XmlNodeList containing a list of all descendant elements that match the specified XmlElement::get_LocalName and XmlElement::get_NamespaceURI values in C++.'
type: docs
weight: 1500
url: /cpp/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String, String) method


Returns an [XmlNodeList](../../xmlnodelist/) containing a list of all descendant elements that match the specified [XmlElement::get_LocalName](../get_localname/) and [XmlElement::get_NamespaceURI](../get_namespaceuri/) values.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | The local name to match. The asterisk (*) is a special value that matches all tags. |
| namespaceURI | String | The namespace URI to match. |

### ReturnValue

An [XmlNodeList](../../xmlnodelist/) containing a list of all matching nodes. The list is empty if there are no matching nodes.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlElement::GetElementsByTagName(String) method


Returns an [XmlNodeList](../../xmlnodelist/) containing a list of all descendant elements that match the specified [XmlElement::get_Name](../get_name/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name tag to match. This is a qualified name. It is matched against the **get_Name** value of the matching node. The asterisk (*) is a special value that matches all tags. |

### ReturnValue

An [XmlNodeList](../../xmlnodelist/) containing a list of all matching nodes. The list is empty if there are no matching nodes.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
