---
title: System::Xml::XmlTextReader::ReadChars method
linktitle: ReadChars
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlTextReader::ReadChars method. Reads the text contents of an element into a character buffer. This method is designed to read large streams of embedded text by calling it successively in C++.'
type: docs
weight: 4600
url: /cpp/system.xml/xmltextreader/readchars/
---
## XmlTextReader::ReadChars method


Reads the text contents of an element into a character buffer. This method is designed to read large streams of embedded text by calling it successively.

```cpp
int32_t System::Xml::XmlTextReader::ReadChars(const ArrayPtr<char16_t> &buffer, int32_t index, int32_t count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const ArrayPtr\<char16_t\>\& | The array of characters that serves as the buffer to which the text contents are written. |
| index | int32_t | The position within **buffer** where the method can begin writing text contents. |
| count | int32_t | The number of characters to write into **buffer**. |

### ReturnValue

The number of characters read. This can be 0 if the reader is not positioned on an element or if there is no more text content to return in the current context.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
