---
title: System::Xml::XmlNodeReader::MoveToAttribute method
linktitle: MoveToAttribute
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNodeReader::MoveToAttribute method. Moves to the attribute with the specified index in C++.'
type: docs
weight: 2600
url: /cpp/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(int32_t) method


Moves to the attribute with the specified index.

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| attributeIndex | int32_t | The index of the attribute. |

## See Also

* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNodeReader::MoveToAttribute(String) method


Moves to the attribute with the specified name.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The qualified name of the attribute. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## See Also

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNodeReader::MoveToAttribute(String, String) method


Moves to the attribute with the specified local name and namespace URI.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The local name of the attribute. |
| namespaceURI | String | The namespace URI of the attribute. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## See Also

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
