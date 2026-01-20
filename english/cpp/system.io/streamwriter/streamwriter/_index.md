---
title: System::IO::StreamWriter::StreamWriter constructor
linktitle: StreamWriter
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::StreamWriter::StreamWriter constructor. Constructs an instance of StreamWriter object that writes characters to the specified underlying stream using UTF-8 encoding and a buffer with default size of 1024 bytes in C++.'
type: docs
weight: 100
url: /cpp/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) constructor


Constructs an instance of [StreamWriter](../) object that writes characters to the specified underlying stream using UTF-8 encoding and a buffer with default size of 1024 bytes.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | const SharedPtr\<Stream\>\& | The underlying stream to write characters to |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) constructor


Constructs an instance of [StreamWriter](../) object that writes characters to the specified underlying stream using the specified encoding and a buffer with default size of 1024 bytes.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | const SharedPtr\<Stream\>\& | The underlying stream to write characters to |
| encoding | const EncodingPtr\& | The encoding to use |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) constructor


Constructs an instance of [StreamWriter](../) object that writes characters to the specified underlying stream using the specified encoding and a buffer of the specified size. A parameter specifies whether the underlying stream should be closed when the [StreamWriter](../) object is disposed.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | const SharedPtr\<Stream\>\& | The underlying stream to write characters to |
| encoding | const EncodingPtr\& | The encoding to use |
| buffer_size | int | The minimum size of the buffer in bytes |
| leave_open | bool | Specifies whether the underlying stream should be left open after the current [StreamWriter](../) object is disposed |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::StreamWriter(const String\&) constructor


Constructs an instance of [StreamWriter](../) object that writes characters to the specified file using UTF-8 encoding and a buffer with default size of 1024 bytes.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const String\& | The path of the file to write characters to |

## See Also

* Class [String](../../../system/string/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) constructor


Constructs an instance of [StreamWriter](../) object that writes characters to the specified file using the specified encoding and buffer size. A parameter specifies whether the data should be appened to the file or the file should be overwritten.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const String\& | The path of the file to write characters to |
| append | bool | Specifies whether the data should be appended to the specified file (true) or the file should be overwritten (false) |
| encoding | const EncodingPtr\& | The encoding to use |
| buffer_size | int | The size of buffer to use |

## See Also

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) constructor


Constructs an instance of [StreamWriter](../) object that writes characters to the specified file using the specified encoding and a buffer with default size of 1024 bytes. A parameter specifies whether the data should be appened to the file or the file should be overwritten.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const String\& | The path of the file to write characters to |
| append | bool | Specifies whether the data should be appended to the specified file (true) or the file should be overwritten (false) |
| encoding | const EncodingPtr\& | The encoding to use |

## See Also

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
