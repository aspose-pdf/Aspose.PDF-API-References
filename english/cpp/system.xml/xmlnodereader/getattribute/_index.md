---
title: System::Xml::XmlNodeReader::GetAttribute method
linktitle: GetAttribute
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNodeReader::GetAttribute method. Returns the value of the attribute with the specified index in C++.'
type: docs
weight: 2400
url: /cpp/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(int32_t) method


Returns the value of the attribute with the specified index.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| attributeIndex | int32_t | The index of the attribute. The index is zero-based. (The first attribute has index 0.) |

### ReturnValue

The value of the specified attribute.

## See Also

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNodeReader::GetAttribute(String) method


Returns the value of the attribute with the specified name.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The qualified name of the attribute. |

### ReturnValue

The value of the specified attribute. If the attribute is not found, **nullptr** is returned.

## See Also

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNodeReader::GetAttribute(String, String) method


Returns the value of the attribute with the specified local name and namespace URI.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The local name of the attribute. |
| namespaceURI | String | The namespace URI of the attribute. |

### ReturnValue

The value of the specified attribute. If the attribute is not found, **nullptr** is returned.

## See Also

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
