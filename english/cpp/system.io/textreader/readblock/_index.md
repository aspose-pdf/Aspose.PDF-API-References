---
title: System::IO::TextReader::ReadBlock method
linktitle: ReadBlock
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::TextReader::ReadBlock method. Reads the specified maximum number of characters from the current text reader and writes the data to a buffer, starting at the specified index in C++.'
type: docs
weight: 500
url: /cpp/system.io/textreader/readblock/
---
## TextReader::ReadBlock method


Reads the specified maximum number of characters from the current text reader and writes the data to a buffer, starting at the specified index.

```cpp
virtual int System::IO::TextReader::ReadBlock(ArrayPtr<char_t> buffer, int index, int count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | ArrayPtr\<char_t\> | A character buffer to write the read data to |
| index | int | A 0-based index in **buffer** to start writing at |
| count | int | The maximum number of characters to read |

### ReturnValue

The actual number of characters read

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TextReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
