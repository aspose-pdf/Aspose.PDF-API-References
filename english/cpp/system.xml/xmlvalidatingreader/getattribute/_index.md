---
title: System::Xml::XmlValidatingReader::GetAttribute method
linktitle: GetAttribute
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlValidatingReader::GetAttribute method. Returns the value of the attribute with the specified index in C++.'
type: docs
weight: 3200
url: /cpp/system.xml/xmlvalidatingreader/getattribute/
---
## XmlValidatingReader::GetAttribute(int32_t) method


Returns the value of the attribute with the specified index.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(int32_t i) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| i | int32_t | The index of the attribute. The index is zero-based. (The first attribute has index 0.) |

### ReturnValue

The value of the specified attribute.

## See Also

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlValidatingReader::GetAttribute(String, String) method


Returns the value of the attribute with the specified local name and namespace Uniform Resource Identifier (URI).

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String localName, String namespaceURI) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | The local name of the attribute. |
| namespaceURI | String | The namespace URI of the attribute. |

### ReturnValue

The value of the specified attribute. If the attribute is not found, **nullptr** is returned. This method does not move the reader.

## See Also

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlValidatingReader::GetAttribute(String) method


Returns the value of the attribute with the specified name.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String name) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The qualified name of the attribute. |

### ReturnValue

The value of the specified attribute. If the attribute is not found, **nullptr** is returned.

## See Also

* Class [String](../../../system/string/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
