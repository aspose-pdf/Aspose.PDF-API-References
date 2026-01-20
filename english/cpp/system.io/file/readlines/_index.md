---
title: System::IO::File::ReadLines method
linktitle: ReadLines
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::File::ReadLines method. Reads the content of the specified text file line by line using the specified character encoding and returns enumerable collection of strings each of which represents a single line of the file''s content in C++.'
type: docs
weight: 2600
url: /cpp/system.io/file/readlines/
---
## File::ReadLines method


Reads the content of the specified text file line by line using the specified character encoding and returns enumerable collection of strings each of which represents a single line of the file's content.

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const String\& | The path of the file to read |
| encoding | const EncodingPtr\& | The character encoding to use |

### ReturnValue

An enumerable collection of strings representing the content of the specified file

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
