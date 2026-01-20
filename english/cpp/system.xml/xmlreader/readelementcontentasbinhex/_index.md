---
title: System::Xml::XmlReader::ReadElementContentAsBinHex method
linktitle: ReadElementContentAsBinHex
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlReader::ReadElementContentAsBinHex method. Reads the element and decodes the BinHex content in C++.'
type: docs
weight: 5400
url: /cpp/system.xml/xmlreader/readelementcontentasbinhex/
---
## XmlReader::ReadElementContentAsBinHex method


Reads the element and decodes the **BinHex** content.

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
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
