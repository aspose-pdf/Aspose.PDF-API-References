---
title: System::Xml::XmlValidatingReader::ReadElementContentAsBinHex method
linktitle: ReadElementContentAsBinHex
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlValidatingReader::ReadElementContentAsBinHex method. Reads the element and decodes the BinHex content in C++.'
type: docs
weight: 4400
url: /cpp/system.xml/xmlvalidatingreader/readelementcontentasbinhex/
---
## XmlValidatingReader::ReadElementContentAsBinHex method


Reads the element and decodes the BinHex content.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
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
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
