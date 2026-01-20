---
title: System::IO::File::OpenText method
linktitle: OpenText
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::File::OpenText method. Opens the specified existing file for reading text using UTF-8 encoding with no sharing in C++.'
type: docs
weight: 2100
url: /cpp/system.io/file/opentext/
---
## File::OpenText method


Opens the specified existing file for reading text using UTF-8 encoding with no sharing.

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const String\& | The path of the file to open |
| encoding | const EncodingPtr\& | The character encoding to use |

### ReturnValue

A shared pointer to a [StreamWriter](../../streamwriter/) object associated with the opened file

## See Also

* Typedef [StreamReaderPtr](../../../system/streamreaderptr/)
* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
