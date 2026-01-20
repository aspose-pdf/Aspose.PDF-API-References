---
title: System::Xml::XmlElement::GetAttribute method
linktitle: GetAttribute
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlElement::GetAttribute method. Returns the value for the attribute with the specified local name and namespace URI in C++.'
type: docs
weight: 1300
url: /cpp/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String, String) method


Returns the value for the attribute with the specified local name and namespace URI.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | The local name of the attribute to retrieve. |
| namespaceURI | String | The namespace URI of the attribute to retrieve. |

### ReturnValue

The value of the specified attribute. An empty string is returned if a matching attribute is not found or if the attribute does not have a specified or default value.

## See Also

* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlElement::GetAttribute(String) method


Returns the value for the attribute with the specified name.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of the attribute to retrieve. This is a qualified name. It is matched against the **get_Name** value of the matching node. |

### ReturnValue

The value of the specified attribute. An empty string is returned if a matching attribute is not found or if the attribute does not have a specified or default value.

## See Also

* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
