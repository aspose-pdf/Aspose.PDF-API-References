---
title: System::IO::File::Open method
linktitle: Open
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::File::Open method. Opens the specified file in the specified mode for reading and writing and with no sharing in C++.'
type: docs
weight: 1900
url: /cpp/system.io/file/open/
---
## File::Open(const String\&, FileMode) method


Opens the specified file in the specified mode for reading and writing and with no sharing.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const String\& | The path of the file to open |
| mode | FileMode | Specifies the mode in which to open the file |

### ReturnValue

A [FileStream](../../filestream/) object associated with the opened file

## See Also

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Enum [FileMode](../../filemode/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## File::Open(const String\&, FileMode, FileAccess, FileShare) method


Opens the specified file in the specified mode, with the specified access type and sharing option.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const String\& | The path of the file to open |
| mode | FileMode | Specifies the mode in which to open the file |
| access | FileAccess | The requested access type |
| share | FileShare | The type of access that other [FileStream](../../filestream/) objects have to the opened file |

### ReturnValue

A [FileStream](../../filestream/) object associated with the opened file

## See Also

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
