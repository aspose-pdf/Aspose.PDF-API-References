---
title: System::Xml::XmlAttributeCollection::idx_get method
linktitle: idx_get
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlAttributeCollection::idx_get method. Returns the attribute with the specified local name and namespace Uniform Resource Identifier (URI) in C++.'
type: docs
weight: 300
url: /cpp/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(const String\&, const String\&) method


Returns the attribute with the specified local name and namespace Uniform Resource Identifier (URI).

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | const String\& | The local name of the attribute. |
| namespaceURI | const String\& | The namespace URI of the attribute. |

### ReturnValue

The attribute with the specified local name and namespace URI. If the attribute does not exist, this method returns **nullptr**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlAttributeCollection::idx_get(const String\&) method


Returns the attribute with the specified name.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | const String\& | The qualified name of the attribute. |

### ReturnValue

The attribute with the specified name. If the attribute does not exist, this method returns **nullptr**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlAttributeCollection::idx_get(int32_t) method


Returns the attribute with the specified index.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```


| Parameter | Type | Description |
| --- | --- | --- |
| i | int32_t | The index of the attribute. |

### ReturnValue

The attribute at the specified index.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
