---
title: System::Xml::XmlReader::ReadToFollowing method
linktitle: ReadToFollowing
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlReader::ReadToFollowing method. Reads until an element with the specified local name and namespace URI is found in C++.'
type: docs
weight: 7200
url: /cpp/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String, String) method


Reads until an element with the specified local name and namespace URI is found.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | The local name of the element. |
| namespaceURI | String | The namespace URI of the element. |

### ReturnValue

**true** if a matching element is found; otherwise **false** and the [XmlReader](../) is in an end of file state.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadToFollowing(String) method


Reads until an element with the specified qualified name is found.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The qualified name of the element. |

### ReturnValue

**true** if a matching element is found; otherwise **false** and the [XmlReader](../) is in an end of file state.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
