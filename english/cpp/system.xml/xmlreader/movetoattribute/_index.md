---
title: System::Xml::XmlReader::MoveToAttribute method
linktitle: MoveToAttribute
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlReader::MoveToAttribute method. When overridden in a derived class, moves to the attribute with the specified index in C++.'
type: docs
weight: 3200
url: /cpp/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(int32_t) method


When overridden in a derived class, moves to the attribute with the specified index.

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```


| Parameter | Type | Description |
| --- | --- | --- |
| i | int32_t | The index of the attribute. |

## See Also

* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::MoveToAttribute(String) method


When overridden in a derived class, moves to the attribute with the specified [XmlReader::get_Name](../get_name/) value.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The qualified name of the attribute. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::MoveToAttribute(String, String) method


When overridden in a derived class, moves to the attribute with the specified [XmlReader::get_LocalName](../get_localname/) and [XmlReader::get_NamespaceURI](../get_namespaceuri/) values.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The local name of the attribute. |
| ns | String | The namespace URI of the attribute. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
