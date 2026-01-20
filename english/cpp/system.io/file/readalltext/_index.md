---
title: System::IO::File::ReadAllText method
linktitle: ReadAllText
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::File::ReadAllText method. Reads the content of the specified text file to a single String object using the specified character encoding in C++.'
type: docs
weight: 2500
url: /cpp/system.io/file/readalltext/
---
## File::ReadAllText method


Reads the content of the specified text file to a single [String](../../../system/string/) object using the specified character encoding.

```cpp
static String System::IO::File::ReadAllText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const String\& | The path of the file to read |
| encoding | const EncodingPtr\& | The character encoding to use |

### ReturnValue

A string containing the content of the specified file

## See Also

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
