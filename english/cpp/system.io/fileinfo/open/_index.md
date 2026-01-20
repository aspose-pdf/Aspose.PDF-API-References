---
title: System::IO::FileInfo::Open method
linktitle: Open
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::FileInfo::Open method. Opens the file represented by the current object in the specified mode for reading and writing and with no sharing in C++.'
type: docs
weight: 1600
url: /cpp/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) method


Opens the file represented by the current object in the specified mode for reading and writing and with no sharing.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```


| Parameter | Type | Description |
| --- | --- | --- |
| mode | FileMode | Specifies the mode in which to open the flie |

### ReturnValue

A [FileStream](../../filestream/) object associated with the file represented by the current object

## See Also

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Enum [FileMode](../../filemode/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileInfo::Open(FileMode, FileAccess) method


Opens the file represented by the current object in the specified mode, with the specified access type and with no sharing.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```


| Parameter | Type | Description |
| --- | --- | --- |
| mode | FileMode | Specifies the mode in which to open the flie |
| access | FileAccess | The requested access type |

### ReturnValue

A [FileStream](../../filestream/) object associated with the file represented by the current object

## See Also

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileInfo::Open(FileMode, FileAccess, FileShare) method


Opens the file represented by the current object in the specified mode, with the specified access type and sharing option.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```


| Parameter | Type | Description |
| --- | --- | --- |
| mode | FileMode | Specifies the mode in which to open the flie |
| access | FileAccess | The requested access type |
| share | FileShare | The type of access that other [FileStream](../../filestream/) objects have to the opened file |

### ReturnValue

A [FileStream](../../filestream/) object associated with the file represented by the current object

## See Also

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
