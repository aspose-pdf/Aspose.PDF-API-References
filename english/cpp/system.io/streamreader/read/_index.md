---
title: System::IO::StreamReader::Read method
linktitle: Read
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::StreamReader::Read method. Reads a single character from the stream in C++.'
type: docs
weight: 900
url: /cpp/system.io/streamreader/read/
---
## StreamReader::Read() method


Reads a single character from the stream.

```cpp
virtual int System::IO::StreamReader::Read() override
```


### ReturnValue

Read character encoded with UTF-16 encoding; if the read character is represented by two codepoints in UTF-16 encoding then only the high surragate is returned.

## See Also

* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::Read(ArrayPtr\<char_t\>, int, int) method


Reads the specified number of characters from the stream, converts them to UTF-16 encoding and writes the resulting UTF-16 characters to the specified character array starting at the specified position.

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
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
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
