---
title: System::Xml::XmlReader::ReadElementContentAsObject method
linktitle: ReadElementContentAsObject
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlReader::ReadElementContentAsObject method. Reads the current element and returns the contents as an Object in C++.'
type: docs
weight: 6200
url: /cpp/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() method


Reads the current element and returns the contents as an [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```


### ReturnValue

A boxed object of the most appropriate type. The [XmlReader::get_ValueType](../get_valuetype/) value determines the appropriate type. If the content is typed as a list type, this method returns an array of boxed objects of the appropriate type.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlReader::ReadElementContentAsObject(String, String) method


Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as an [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | The local name of the element. |
| namespaceURI | String | The namespace URI of the element. |

### ReturnValue

A boxed object of the most appropriate type. The [XmlReader::get_ValueType](../get_valuetype/) value determines the appropriate type. If the content is typed as a list type, this method returns an array of boxed objects of the appropriate type.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
