---
title: System::Xml::XmlReader::ReadElementContentAsBase64 method
linktitle: ReadElementContentAsBase64
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlReader::ReadElementContentAsBase64 method. Reads the element and decodes the Base64 content in C++.'
type: docs
weight: 5300
url: /cpp/system.xml/xmlreader/readelementcontentasbase64/
---
## XmlReader::ReadElementContentAsBase64 method


Reads the element and decodes the **Base64** content.

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | ArrayPtr\<uint8_t\> | The buffer into which to copy the resulting text. This value cannot be **nullptr**. |
| index | int32_t | The offset into the buffer where to start copying the result. |
| count | int32_t | The maximum number of bytes to copy into the buffer. The actual number of bytes copied is returned from this method. |

### ReturnValue

The number of bytes written to the buffer.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
