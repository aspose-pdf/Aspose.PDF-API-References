---
title: System::Xml::XmlTextReader::ReadBase64 method
linktitle: ReadBase64
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlTextReader::ReadBase64 method. Decodes Base64 and returns the decoded binary bytes in C++.'
type: docs
weight: 4400
url: /cpp/system.xml/xmltextreader/readbase64/
---
## XmlTextReader::ReadBase64 method


Decodes Base64 and returns the decoded binary bytes.

```cpp
int32_t System::Xml::XmlTextReader::ReadBase64(const ArrayPtr<uint8_t> &array, int32_t offset, int32_t len)
```


| Parameter | Type | Description |
| --- | --- | --- |
| array | const ArrayPtr\<uint8_t\>\& | The array of characters that serves as the buffer to which the text contents are written. |
| offset | int32_t | The zero-based index into the array specifying where the method can begin to write to the buffer. |
| len | int32_t | The number of bytes to write into the buffer. |

### ReturnValue

The number of bytes written to the buffer.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
