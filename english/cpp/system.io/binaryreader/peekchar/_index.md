---
title: System::IO::BinaryReader::PeekChar method
linktitle: PeekChar
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::BinaryReader::PeekChar method. Reads a single character from the input stream without changing the stream''s read cursor in C++.'
type: docs
weight: 600
url: /cpp/system.io/binaryreader/peekchar/
---
## BinaryReader::PeekChar method


Reads a single character from the input stream without changing the stream's read cursor.

```cpp
virtual int System::IO::BinaryReader::PeekChar()
```


### ReturnValue

Read character encoded with UTF-16 encoding; if the read character is represented by two codepoints in UTF-16 encoding then only the high surragate is returned; if no character was read -1 is returned

## See Also

* Class [BinaryReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
