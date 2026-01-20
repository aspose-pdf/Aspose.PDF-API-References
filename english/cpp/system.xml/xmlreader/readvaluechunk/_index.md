---
title: System::Xml::XmlReader::ReadValueChunk method
linktitle: ReadValueChunk
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlReader::ReadValueChunk method. Reads large streams of text embedded in an XML document in C++.'
type: docs
weight: 7400
url: /cpp/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk method


Reads large streams of text embedded in an XML document.

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | ArrayPtr\<char16_t\> | The array of characters that serves as the buffer to which the text contents are written. This value cannot be **nullptr**. |
| index | int32_t | The offset within the buffer where the [XmlReader](../) can start to copy the results. |
| count | int32_t | The maximum number of characters to copy into the buffer. The actual number of characters copied is returned from this method. |

### ReturnValue

The number of characters read into the buffer. The value zero is returned when there is no more text content.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
