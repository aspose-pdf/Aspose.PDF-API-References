---
title: System::Xml::XmlReader::IsStartElement method
linktitle: IsStartElement
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlReader::IsStartElement method. Calls XmlReader::MoveToContent and tests if the current content node is a start tag or empty element tag in C++.'
type: docs
weight: 3000
url: /cpp/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() method


Calls [XmlReader::MoveToContent](../movetocontent/) and tests if the current content node is a start tag or empty element tag.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```


### ReturnValue

**true** if [XmlReader::MoveToContent](../movetocontent/) finds a start tag or empty element tag; **false** if a node type other than [XmlNodeType::Element](../../xmlnodetype/) was found.

## See Also

* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::IsStartElement(String, String) method


Calls [XmlReader::MoveToContent](../movetocontent/) and tests if the current content node is a start tag or empty element tag and if the [XmlReader::get_LocalName](../get_localname/) and [XmlReader::get_NamespaceURI](../get_namespaceuri/) values of the element found match the given strings.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localname | String | The string to match against the **LocalName** value of the element found. |
| ns | String | The string to match against the **NamespaceURI** value of the element found. |

### ReturnValue

**true** if the resulting node is an element. **false** if a node type other than [XmlNodeType::Element](../../xmlnodetype/) was found or if the **LocalName** and **NamespaceURI** values of the element do not match the specified strings.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::IsStartElement(String) method


Calls [XmlReader::MoveToContent](../movetocontent/) and tests if the current content node is a start tag or empty element tag and if the [XmlReader::get_Name](../get_name/) value of the element found matches the given argument.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The string matched against the **Name** value of the element found. |

### ReturnValue

**true** if the resulting node is an element and the **Name** value matches the specified string. **false** if a node type other than [XmlNodeType::Element](../../xmlnodetype/) was found or if the element **Name** value does not match the specified string.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
