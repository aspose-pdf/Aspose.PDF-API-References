---
title: System::Xml::ReadState enum
linktitle: ReadState
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::ReadState enum. Specifies the state of the reader in C++.'
type: docs
weight: 5300
url: /cpp/system.xml/readstate/
---
## ReadState enum


Specifies the state of the reader.

```cpp
enum class ReadState
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Initial | 0 | The [XmlReader::Read](../xmlreader/read/) method has not been called. |
| Interactive | 1 | The [XmlReader::Read](../xmlreader/read/) method has been called. Additional methods may be called on the reader. |
| Error | 2 | An error occurred that prevents the read operation from continuing. |
| EndOfFile | 3 | The end of the file has been reached successfully. |
| Closed | 4 | The [XmlReader::Close](../xmlreader/close/) method has been called. |

## See Also

* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
