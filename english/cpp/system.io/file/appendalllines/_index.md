---
title: System::IO::File::AppendAllLines method
linktitle: AppendAllLines
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::File::AppendAllLines method. Appends strings from the specified collection of strings to the specified file using the specified encoding by writing each string in a new line. If the specified file does not exist, it is created. The file is closed after writing all strings in C++.'
type: docs
weight: 100
url: /cpp/system.io/file/appendalllines/
---
## File::AppendAllLines method


Appends strings from the specified collection of strings to the specified file using the specified encoding by writing each string in a new line. If the specified file does not exist, it is created. The file is closed after writing all strings.

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const String\& | The path of the file to append the strings to |
| contents | const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\& | The strings to write to the file |
| encoding | const EncodingPtr\& | The character encoding to use |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
