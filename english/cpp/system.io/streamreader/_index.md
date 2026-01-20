---
title: System::IO::StreamReader class
linktitle: StreamReader
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::StreamReader class. Represents a reader that reads characters from a byte stream. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2200
url: /cpp/system.io/streamreader/
---
## StreamReader class


Represents a reader that reads characters from a byte stream. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StreamReader : public System::IO::TextReader
```

## Methods

| Method | Description |
| --- | --- |
| [Close](./close/)() override | Closes the current and underlying streams. |
| [Dispose](./dispose/)() override | Releases all resources used by the current object and closes the undelying stream. |
| [get_BaseStream](./get_basestream/)() const | Returns a shared pointer to an object that represents the underlying stream. |
| [get_CurrentEncoding](./get_currentencoding/)() | Returns the currently used encoding. |
| [get_EndOfStream](./get_endofstream/)() | Returns a value that indicates if the end of of stream has been reached. |
| [Peek](./peek/)() override | Reads a single character from the stream without changing the stream's read cursor. |
| [Read](./read/)() override | Reads a single character from the stream. |
| [Read](./read/)(ArrayPtr\<char_t\>, int, int) override | Reads the specified number of characters from the stream, converts them to UTF-16 encoding and writes the resulting UTF-16 characters to the specified character array starting at the specified position. |
| [ReadLine](./readline/)() override | Reads characters from the stream until the end of the current line. |
| [ReadToEnd](./readtoend/)() override | Reads characters from the stream until the end of the stream. |
| [StreamReader](./streamreader/)(const SharedPtr\<Stream\>\&) | Constructs an instance of [StreamReader](./) object that reads characters from the specified underlying stream using UTF-8 encoding and a buffer with default size of 1024 bytes. |
| [StreamReader](./streamreader/)(const SharedPtr\<Stream\>\&, bool) | Constructs an instance of [StreamReader](./) object that reads characters from the specified underlying stream using UTF-8 encoding and a buffer with default size of 1024 bytes. A parameter specifies if byte order mark detection should be enabled. |
| [StreamReader](./streamreader/)(const SharedPtr\<Stream\>\&, const EncodingPtr\&) | Constructs an instance of [StreamReader](./) object that reads characters from the specified underlying stream using the specified encoding and a buffer with default size of 1024 bytes. |
| [StreamReader](./streamreader/)(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) | Constructs an instance of [StreamReader](./) object that reads characters from the specified underlying stream using the specified encoding and a buffer with default size of 1024 bytes. A parameter specifies if byte order mark detection should be enabled. |
| [StreamReader](./streamreader/)(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) | Constructs an instance of [StreamReader](./) object that reads characters from the specified underlying stream using the specified encoding and a buffer of the specified size. A parameter specifies if byte order mark detection should be enabled. |
| [StreamReader](./streamreader/)(const System::String\&) | Constructs an instance of [StreamReader](./) object that reads characters from the specified file using UTF-8 encoding and a buffer with default size of 4096 bytes. |
| [StreamReader](./streamreader/)(const System::String\&, bool) | Constructs an instance of [StreamReader](./) object that reads characters from the specified file using UTF-8 encoding and a buffer with default size of 4096 bytes. A parameter specifies if byte order mark detection should be enabled. |
| [StreamReader](./streamreader/)(const System::String\&, const EncodingPtr\&) | Constructs an instance of [StreamReader](./) object that reads characters from the specified file using the specified encoding and a buffer with default size of 4096 bytes. |
| [StreamReader](./streamreader/)(const System::String\&, const EncodingPtr\&, bool) | Constructs an instance of [StreamReader](./) object that reads characters from the specified underlying stream using the specified encoding and a buffer with default size of 4096 bytes. A parameter specifies if byte order mark detection should be enabled. |
| [StreamReader](./streamreader/)(const System::String\&, const EncodingPtr\&, bool, int) | Constructs an instance of [StreamReader](./) object that reads characters from the specified file using the specified encoding and a buffer of the specified size. A parameter specifies if byte order mark detection should be enabled. |
| [~StreamReader](./~streamreader/)() | Destructor. |
## See Also

* Class [TextReader](../textreader/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
