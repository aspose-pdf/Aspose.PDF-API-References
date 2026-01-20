---
title: System::Xml::XmlValidatingReader::MoveToAttribute method
linktitle: MoveToAttribute
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlValidatingReader::MoveToAttribute method. Moves to the attribute with the specified index in C++.'
type: docs
weight: 3500
url: /cpp/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(int32_t) method


Moves to the attribute with the specified index.

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| i | int32_t | The index of the attribute. |

## See Also

* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlValidatingReader::MoveToAttribute(String, String) method


Moves to the attribute with the specified local name and namespace Uniform Resource Identifier (URI).

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | The local name of the attribute. |
| namespaceURI | String | The namespace URI of the attribute. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the position of the reader does not change.

## See Also

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlValidatingReader::MoveToAttribute(String) method


Moves to the attribute with the specified name.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The qualified name of the attribute. |

### ReturnValue

**true** if the attribute is found; otherwise, **false**. If **false**, the position of the reader does not change.

## See Also

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
