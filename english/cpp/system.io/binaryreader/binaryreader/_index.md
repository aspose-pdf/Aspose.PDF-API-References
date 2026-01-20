---
title: System::IO::BinaryReader::BinaryReader constructor
linktitle: BinaryReader
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::BinaryReader::BinaryReader constructor. Constructs an instance of BinaryReader class that reads data from the specified stream using UTF-8 encoding in C++.'
type: docs
weight: 100
url: /cpp/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) constructor


Constructs an instance of [BinaryReader](../) class that reads data from the specified stream using UTF-8 encoding.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<Stream\>\& | The input stream |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [BinaryReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) constructor


Constructs an instance of [BinaryReader](../) class that reads data from the specified stream using the specified encoding.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<Stream\>\& | The input stream |
| encoding | const SharedPtr\<Text::Encoding\>\& | The encoding to use |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [Encoding](../../../system.text/encoding/)
* Class [BinaryReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) constructor


Constructs an instance of [BinaryReader](../) class that reads data from the specified stream using the specified encoding.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | const SharedPtr\<Stream\>\& | The input stream |
| encoding | const SharedPtr\<Text::Encoding\>\& | The encoding to use |
| leaveOpen | bool | Specifies whether the stream **input** should be left open (true) after the current object has been disposed or not (false) |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [Encoding](../../../system.text/encoding/)
* Class [BinaryReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
