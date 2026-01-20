---
title: System::IO::TextReader::Read method
linktitle: Read
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::TextReader::Read method. Reads a single character from the stream in C++.'
type: docs
weight: 400
url: /cpp/system.io/textreader/read/
---
## TextReader::Read() method


Reads a single character from the stream.

```cpp
virtual int System::IO::TextReader::Read()
```


### ReturnValue

Read character encoded with UTF-16 encoding; if the read character is represented by two codepoints in UTF-16 encoding then only the high surragate is returned.

## See Also

* Class [TextReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## TextReader::Read(ArrayPtr\<char_t\>, int, int) method


Reads the specified number of characters from the stream and writes them to the specified character array starting at the specified position.

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | ArrayPtr\<char_t\> | The UTF-16 character array to write the characters read from the stream to |
| index | int | A 0-based index in **buffer** at which to start writing |
| count | int | The number of characters to read from the stream |

### ReturnValue

The number of characters read from the stream

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TextReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
