---
title: System::IO::StringReader::Read method
linktitle: Read
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::StringReader::Read method. Reads a single character from the stream in C++.'
type: docs
weight: 500
url: /cpp/system.io/stringreader/read/
---
## StringReader::Read() method


Reads a single character from the stream.

```cpp
virtual int System::IO::StringReader::Read() override
```


### ReturnValue

A read character or -1 if no character has been read

## See Also

* Class [StringReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StringReader::Read(ArrayPtr\<char_t\>, int, int) method


Reads the specified number of characters from the stream to the specified character array starting at the specified position.

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| buffer | ArrayPtr\<char_t\> | The character array to write the characters read from the stream to |
| index | int | A 0-based index in **buffer** at which to start writing |
| count | int | The number of characters to read from the stream |

### ReturnValue

The number of characters read from the stream

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
