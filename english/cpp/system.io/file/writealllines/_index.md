---
title: System::IO::File::WriteAllLines method
linktitle: WriteAllLines
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::File::WriteAllLines method. Creates a new text file or overwrites the existing one and writes all strings from the specified array of strings to it, each string on a new line, using the specified encoding in C++.'
type: docs
weight: 3600
url: /cpp/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) method


Creates a new text file or overwrites the existing one and writes all strings from the specified array of strings to it, each string on a new line, using the specified encoding.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const String\& | The file to create or overwrite |
| contents | const ArrayPtr\<String\>\& | A string array |
| encoding | const EncodingPtr\& | The character encoding to use |

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) method


Creates a new text file or overwrites the existing one and writes all strings from the specified enumerable collection of strings to it, each string on a new line, using the specified encoding.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const String\& | The file to create or overwrite |
| contents | const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\& | An enumerable collection of strings |
| encoding | const EncodingPtr\& | The character encoding to use |

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
