---
title: System::Xml::XmlReader::ReadElementString method
linktitle: ReadElementString
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlReader::ReadElementString method. Reads a text-only element. However, it is recommended to use the XmlReader::ReadElementContentAsString method instead, because it provides a more straightforward way to handle this operation in C++.'
type: docs
weight: 6400
url: /cpp/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() method


Reads a text-only element. However, it is recommended to use the [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) method instead, because it provides a more straightforward way to handle this operation.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```


### ReturnValue

The text contained in the element that was read. An empty string if the element is empty.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadElementString(String, String) method


Checks that the [XmlReader::get_LocalName](../get_localname/) and [XmlReader::get_NamespaceURI](../get_namespaceuri/) values of the element found matches the given strings before reading a text-only element. However, it is recommended to use the [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) method instead, because it provides a more straightforward way to handle this operation.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localname | String | The local name to check. |
| ns | String | The namespace URI to check. |

### ReturnValue

The text contained in the element that was read. An empty string if the element is empty.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadElementString(String) method


Checks that the [XmlReader::get_Name](../get_name/) value of the element found matches the given string before reading a text-only element. However, it is recommended to use the [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) method instead, because it provides a more straightforward way to handle this operation.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name to check. |

### ReturnValue

The text contained in the element that was read. An empty string if the element is empty.

## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
