---
title: System::Xml::XmlTextReader::MoveToAttribute method
linktitle: MoveToAttribute
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlTextReader::MoveToAttribute method. Moves to the attribute with the specified index in C++.'
type: docs
weight: 3800
url: /cpp/system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(int32_t) method


Moves to the attribute with the specified index.

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| i | int32_t | The index of the attribute. |

## See Also

* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::MoveToAttribute(String, String) method


Moves to the attribute with the specified local name and namespace URI.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | The local name of the attribute. |
| namespaceURI | String | The namespace URI of the attribute. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## See Also

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlTextReader::MoveToAttribute(String) method


Moves to the attribute with the specified name.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The qualified name of the attribute. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## See Also

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
