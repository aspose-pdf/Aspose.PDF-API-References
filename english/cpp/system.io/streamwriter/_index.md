---
title: System::IO::StreamWriter class
linktitle: StreamWriter
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::StreamWriter class. Represents a writer that writes characters to a byte stream. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2300
url: /cpp/system.io/streamwriter/
---
## StreamWriter class


Represents a writer that writes characters to a byte stream. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StreamWriter : public System::IO::TextWriter
```

## Methods

| Method | Description |
| --- | --- |
| [Close](./close/)() override | Closes the stream and releases aquired resources. |
| [Dispose](./dispose/)() override | Releases all resources used by the current object and closes the undelying stream. |
| [Flush](./flush/)() override | Flushes the content of the buffer to the underlying stream and then flushes the underlying stream. |
| [get_AutoFlush](./get_autoflush/)() const | Returns a value that indicates whether the [StreamWriter](./) will flush the data to the underlying stream every time method [StreamWriter::Write](./write/) is called. |
| [get_BaseStream](./get_basestream/)() const | Returns a shared pointer to an object that represents the underlying stream. |
| [get_Encoding](./get_encoding/)() override | Returns the currently used encoding. |
| [set_AutoFlush](./set_autoflush/)(bool) | Returns a value that specifies whether the [StreamWriter](./) should flush the data to the underlying stream every time method [StreamWriter::Write](./write/) is called. |
| [StreamWriter](./streamwriter/)(const SharedPtr\<Stream\>\&) | Constructs an instance of [StreamWriter](./) object that writes characters to the specified underlying stream using UTF-8 encoding and a buffer with default size of 1024 bytes. |
| [StreamWriter](./streamwriter/)(const SharedPtr\<Stream\>\&, const EncodingPtr\&) | Constructs an instance of [StreamWriter](./) object that writes characters to the specified underlying stream using the specified encoding and a buffer with default size of 1024 bytes. |
| [StreamWriter](./streamwriter/)(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) | Constructs an instance of [StreamWriter](./) object that writes characters to the specified underlying stream using the specified encoding and a buffer of the specified size. A parameter specifies whether the underlying stream should be closed when the [StreamWriter](./) object is disposed. |
| [StreamWriter](./streamwriter/)(const String\&) | Constructs an instance of [StreamWriter](./) object that writes characters to the specified file using UTF-8 encoding and a buffer with default size of 1024 bytes. |
| [StreamWriter](./streamwriter/)(const String\&, bool, const EncodingPtr\&) | Constructs an instance of [StreamWriter](./) object that writes characters to the specified file using the specified encoding and a buffer with default size of 1024 bytes. A parameter specifies whether the data should be appened to the file or the file should be overwritten. |
| [StreamWriter](./streamwriter/)(const String\&, bool, const EncodingPtr\&, int) | Constructs an instance of [StreamWriter](./) object that writes characters to the specified file using the specified encoding and buffer size. A parameter specifies whether the data should be appened to the file or the file should be overwritten. |
| [Write](./write/)(char_t) override | Writes the specified character to the stream. |
| [Write](./write/)(const String\&) override | Writes the specified string to the stream. |
| [Write](./write/)(const SharedPtr\<Object\>\&) override | Writes the string representation of the specified object to the stream. |
| [Write](./write/)(const ArrayPtr\<char_t\>\&) override | Writes all characetrs from the specified array to the stream. |
| [Write](./write/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) override | Writes the specified subrange of UTF-16 characters from the specified character array to the stream. |
| [Write](./write/)(const char_t *) override | Writes the specified c-string to the stream. |
| [Write](./write/)(const System::SharedPtr\<T\>\&) | Writes the string representation of the specified object to the stream. |
| [WriteLine](./writeline/)() override | Writes line terminator characters to the stream. |
| [WriteLine](./writeline/)(const String\&) override | Writes the specified string followed by the line-terminating characters to the stream. |
| [WriteLine](./writeline/)(const SharedPtr\<Object\>\&) override | Writes the string representation of the specified object followed by the line-terminating characters to the stream. |
| [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&) override | Writes all characetrs from the specified array followed by the line-terminating characters to the stream. |
| [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) override | Writes the specified subrange of UTF-16 characters from the specified character array followed by the line-terminating characters to the stream. |
| [WriteLine](./writeline/)(const char_t *) override | Writes the specified c-string followed by the line-terminating characters to the stream. |
| [WriteLine](./writeline/)(const System::SharedPtr\<T\>\&) | Writes the string representation of the specified object followed by the line-terminating characters to the stream. |
| [~StreamWriter](./~streamwriter/)() | Destructor. |
## See Also

* Class [TextWriter](../textwriter/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
