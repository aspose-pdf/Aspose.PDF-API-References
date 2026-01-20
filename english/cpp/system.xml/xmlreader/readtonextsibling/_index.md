---
title: System::Xml::XmlReader::ReadToNextSibling method
linktitle: ReadToNextSibling
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlReader::ReadToNextSibling method. Advances the XmlReader to the next sibling element with the specified local name and namespace URI in C++.'
type: docs
weight: 7300
url: /cpp/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String, String) method


Advances the [XmlReader](../) to the next sibling element with the specified local name and namespace URI.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | The local name of the sibling element you wish to move to. |
| namespaceURI | String | The namespace URI of the sibling element you wish to move to. |

### ReturnValue

**true** if a matching sibling element is found; otherwise, **false**. If a matching sibling element is not found, the [XmlReader](../) is positioned on the end tag ([XmlReader::get_NodeType](../get_nodetype/) value is [XmlNodeType::EndElement](../../xmlnodetype/)) of the parent element.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadToNextSibling(String) method


Advances the [XmlReader](../) to the next sibling element with the specified qualified name.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The qualified name of the sibling element you wish to move to. |

### ReturnValue

**true** if a matching sibling element is found; otherwise **false**. If a matching sibling element is not found, the [XmlReader](../) is positioned on the end tag ([XmlReader::get_NodeType](../get_nodetype/) value is [XmlNodeType::EndElement](../../xmlnodetype/)) of the parent element.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
