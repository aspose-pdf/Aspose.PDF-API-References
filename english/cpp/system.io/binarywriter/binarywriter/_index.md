---
title: System::IO::BinaryWriter::BinaryWriter constructor
linktitle: BinaryWriter
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::BinaryWriter::BinaryWriter constructor. Constructs an instance of BinaryWriter class that writes data to the specified stream using the specified encoding in C++.'
type: docs
weight: 100
url: /cpp/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter constructor


Constructs an instance of [BinaryWriter](../) class that writes data to the specified stream using the specified encoding.

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```


| Parameter | Type | Description |
| --- | --- | --- |
| stream | const StreamPtr\& | The output stream |
| encoding | const EncodingPtr\& | The encoding to use |
| leaveopen | bool | Specifies whether the stream **stream** should be left open (true) after the current object has been disposed or not (false) |

## See Also

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [BinaryWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
