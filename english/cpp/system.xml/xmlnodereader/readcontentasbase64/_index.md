---
title: System::Xml::XmlNodeReader::ReadContentAsBase64 method
linktitle: ReadContentAsBase64
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNodeReader::ReadContentAsBase64 method. Reads the content and returns the Base64 decoded binary bytes in C++.'
type: docs
weight: 3200
url: /cpp/system.xml/xmlnodereader/readcontentasbase64/
---
## XmlNodeReader::ReadContentAsBase64 method


Reads the content and returns the Base64 decoded binary bytes.

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
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
