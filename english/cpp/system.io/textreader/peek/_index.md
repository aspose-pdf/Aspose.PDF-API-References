---
title: System::IO::TextReader::Peek method
linktitle: Peek
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::TextReader::Peek method. Reads a single character from the stream without changing the stream''s read cursor in C++.'
type: docs
weight: 300
url: /cpp/system.io/textreader/peek/
---
## TextReader::Peek method


Reads a single character from the stream without changing the stream's read cursor.

```cpp
virtual int System::IO::TextReader::Peek()
```


### ReturnValue

Read character encoded with UTF-16 encoding; if the read character is represented by two codepoints in UTF-16 encoding then only the high surragate is returned; if no character was read -1 is returned

## See Also

* Class [TextReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
