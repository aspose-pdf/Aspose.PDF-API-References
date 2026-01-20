---
title: System::Xml::XmlTextReader::ReadBinHex method
linktitle: ReadBinHex
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlTextReader::ReadBinHex method. Decodes BinHex and returns the decoded binary bytes in C++.'
type: docs
weight: 4500
url: /cpp/system.xml/xmltextreader/readbinhex/
---
## XmlTextReader::ReadBinHex method


Decodes **BinHex** and returns the decoded binary bytes.

```cpp
int32_t System::Xml::XmlTextReader::ReadBinHex(const ArrayPtr<uint8_t> &array, int32_t offset, int32_t len)
```


| Parameter | Type | Description |
| --- | --- | --- |
| array | const ArrayPtr\<uint8_t\>\& | The byte array that serves as the buffer to which the decoded binary bytes are written. |
| offset | int32_t | The zero-based index into the array specifying where the method can begin to write to the buffer. |
| len | int32_t | The number of bytes to write into the buffer. |

### ReturnValue

The number of bytes written to your buffer.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
