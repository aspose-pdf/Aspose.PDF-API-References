---
title: System::Xml::XmlReader::ReadToDescendant method
linktitle: ReadToDescendant
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlReader::ReadToDescendant method. Advances the XmlReader to the next descendant element with the specified local name and namespace URI in C++.'
type: docs
weight: 7100
url: /cpp/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String, String) method


Advances the [XmlReader](../) to the next descendant element with the specified local name and namespace URI.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | The local name of the element you wish to move to. |
| namespaceURI | String | The namespace URI of the element you wish to move to. |

### ReturnValue

**true** if a matching descendant element is found; otherwise **false**. If a matching child element is not found, the [XmlReader](../) is positioned on the end tag ([XmlReader::get_NodeType](../get_nodetype/) value is [XmlNodeType::EndElement](../../xmlnodetype/)) of the element. If the [XmlReader](../) is not positioned on an element when [XmlReader::ReadToDescendant(String,String)](./) was called, this method returns **false** and the position of the [XmlReader](../) is not changed.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadToDescendant(String) method


Advances the [XmlReader](../) to the next descendant element with the specified qualified name.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The qualified name of the element you wish to move to. |

### ReturnValue

**true** if a matching descendant element is found; otherwise **false**. If a matching child element is not found, the [XmlReader](../) is positioned on the end tag ([XmlReader::get_NodeType](../get_nodetype/) value is [XmlNodeType::EndElement](../../xmlnodetype/)) of the element. If the [XmlReader](../) is not positioned on an element when [XmlReader::ReadToDescendant(String)](./) was called, this method returns **false** and the position of the [XmlReader](../) is not changed.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
