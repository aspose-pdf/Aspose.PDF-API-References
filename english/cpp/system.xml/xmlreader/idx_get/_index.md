---
title: System::Xml::XmlReader::idx_get method
linktitle: idx_get
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlReader::idx_get method. When overridden in a derived class, gets the value of the attribute with the specified index in C++.'
type: docs
weight: 2900
url: /cpp/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) method


When overridden in a derived class, gets the value of the attribute with the specified index.

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```


| Parameter | Type | Description |
| --- | --- | --- |
| i | int32_t | The index of the attribute. |

### ReturnValue

The value of the specified attribute.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::idx_get(String) method


When overridden in a derived class, gets the value of the attribute with the specified [XmlReader::get_Name](../get_name/) value.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The qualified name of the attribute. |

### ReturnValue

The value of the specified attribute. If the attribute is not found, **nullptr** is returned.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::idx_get(String, String) method


When overridden in a derived class, gets the value of the attribute with the specified [XmlReader::get_LocalName](../get_localname/) and [XmlReader::get_NamespaceURI](../get_namespaceuri/) values.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The local name of the attribute. |
| namespaceURI | String | The namespace URI of the attribute. |

### ReturnValue

The value of the specified attribute. If the attribute is not found, **nullptr** is returned.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
