---
title: System::Xml::XmlNodeReader::ReadElementContentAsBinHex method
linktitle: ReadElementContentAsBinHex
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNodeReader::ReadElementContentAsBinHex method. Reads the element and decodes the BinHex content in C++.'
type: docs
weight: 3500
url: /cpp/system.xml/xmlnodereader/readelementcontentasbinhex/
---
## XmlNodeReader::ReadElementContentAsBinHex method


Reads the element and decodes the BinHex content.

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
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
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
