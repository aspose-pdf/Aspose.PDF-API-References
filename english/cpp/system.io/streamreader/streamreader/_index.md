---
title: System::IO::StreamReader::StreamReader constructor
linktitle: StreamReader
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::StreamReader::StreamReader constructor. Constructs an instance of StreamReader object that reads characters from the specified underlying stream using UTF-8 encoding and a buffer with default size of 1024 bytes in C++.'
type: docs
weight: 100
url: /cpp/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified underlying stream using UTF-8 encoding and a buffer with default size of 1024 bytes.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | const SharedPtr\<Stream\>\& | The underlying stream to read characters from |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified underlying stream using UTF-8 encoding and a buffer with default size of 1024 bytes. A parameter specifies if byte order mark detection should be enabled.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | const SharedPtr\<Stream\>\& | The underlying stream to read characters from |
| detectEncodingFromByteOrderMarks | bool | True to look for byte order marks at the beginning of the stream, otherwise - false |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified underlying stream using the specified encoding and a buffer with default size of 1024 bytes.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | const SharedPtr\<Stream\>\& | The underlying stream to read characters from |
| encoding | const EncodingPtr\& | The encoding to use |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified underlying stream using the specified encoding and a buffer with default size of 1024 bytes. A parameter specifies if byte order mark detection should be enabled.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | const SharedPtr\<Stream\>\& | The underlying stream to read characters from |
| encoding | const EncodingPtr\& | The encoding to use |
| detectEncodingFromByteOrderMarks | bool | True to look for byte order marks at the beginning of the stream, otherwise - false |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified underlying stream using the specified encoding and a buffer of the specified size. A parameter specifies if byte order mark detection should be enabled.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | const SharedPtr\<Stream\>\& | The underlying stream to read characters from |
| encoding | const EncodingPtr\& | The encoding to use |
| detectEncodingFromByteOrderMarks | bool | True to look for byte order marks at the beginning of the stream, otherwise - false |
| bufferSize | int | The minimum size of the buffer in bytes |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const System::String\&) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified file using UTF-8 encoding and a buffer with default size of 4096 bytes.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const System::String\& | The path of the file to read characters from |

## See Also

* Class [String](../../../system/string/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const System::String\&, bool) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified file using UTF-8 encoding and a buffer with default size of 4096 bytes. A parameter specifies if byte order mark detection should be enabled.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const System::String\& | The path of the file to read characters from |
| detectEncodingFromByteOrderMarks | bool | True to look for byte order marks at the beginning of the file, otherwise - false |

## See Also

* Class [String](../../../system/string/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified file using the specified encoding and a buffer with default size of 4096 bytes.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const System::String\& | The path of the file to read characters from |
| encoding | const EncodingPtr\& | The encoding to use |

## See Also

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified underlying stream using the specified encoding and a buffer with default size of 4096 bytes. A parameter specifies if byte order mark detection should be enabled.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const System::String\& | The path of the file to read characters from |
| encoding | const EncodingPtr\& | The encoding to use |
| detectEncodingFromByteOrderMarks | bool | True to look for byte order marks at the beginning of the file, otherwise - false |

## See Also

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified file using the specified encoding and a buffer of the specified size. A parameter specifies if byte order mark detection should be enabled.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const System::String\& | The path of the file to read characters from |
| encoding | const EncodingPtr\& | The encoding to use |
| detectEncodingFromByteOrderMarks | bool | True to look for byte order marks at the beginning of the file, otherwise - false |
| bufferSize | int | The minimum size of the buffer in bytes |

## See Also

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
