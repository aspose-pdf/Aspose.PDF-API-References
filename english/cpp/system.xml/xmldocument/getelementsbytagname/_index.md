---
title: System::Xml::XmlDocument::GetElementsByTagName method
linktitle: GetElementsByTagName
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlDocument::GetElementsByTagName method. Returns an XmlNodeList containing a list of all descendant elements that match the specified XmlDocument::get_LocalName and XmlNode::get_NamespaceURI in C++.'
type: docs
weight: 3200
url: /cpp/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String, String) method


Returns an [XmlNodeList](../../xmlnodelist/) containing a list of all descendant elements that match the specified [XmlDocument::get_LocalName](../get_localname/) and [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | The LocalName to match. The special value **"*"** matches all tags. |
| namespaceURI | String | NamespaceURI to match. |

### ReturnValue

An [XmlNodeList](../../xmlnodelist/) containing a list of all matching nodes. If no nodes match the specified **localName** and **namespaceURI**, the returned collection will be empty.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlDocument::GetElementsByTagName(String) method


Returns an [XmlNodeList](../../xmlnodelist/) containing a list of all descendant elements that match the specified name.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The qualified name to match. It is matched against the **get_Name** value of the matching node. The special value **"*"** matches all tags. |

### ReturnValue

An [XmlNodeList](../../xmlnodelist/) containing a list of all matching nodes. If no nodes match **name**, the returned collection will be empty.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
