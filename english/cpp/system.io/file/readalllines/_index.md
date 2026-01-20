---
title: System::IO::File::ReadAllLines method
linktitle: ReadAllLines
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::File::ReadAllLines method. Reads the content of the specified text file line by line to an array of strings using the specified character encoding in C++.'
type: docs
weight: 2400
url: /cpp/system.io/file/readalllines/
---
## File::ReadAllLines method


Reads the content of the specified text file line by line to an array of strings using the specified character encoding.

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const String\& | The path of the file to read |
| encoding | const EncodingPtr\& | The character encoding to use |

### ReturnValue

A string array each element of which represents a single line from the specified file

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
