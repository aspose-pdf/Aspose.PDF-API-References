---
title: System::IO::FileInfo::CopyTo method
linktitle: CopyTo
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::FileInfo::CopyTo method. Copies the file represented by the current object to the specified location. If the destination file already exists, the copying fails in C++.'
type: docs
weight: 300
url: /cpp/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) method


Copies the file represented by the current object to the specified location. If the destination file already exists, the copying fails.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| destFileName | const String\& | The destination file name |

### ReturnValue

A [FileInfo](../) object that represents the copy

## See Also

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileInfo::CopyTo(const String\&, bool) method


Copies the file represented by the current object to the specified location. A parameter specifies if existing destination file should be overwritten.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```


| Parameter | Type | Description |
| --- | --- | --- |
| destFileName | const String\& | The destination file name |
| overwrite | bool | True if the existing destination file should be overwritten, false if copying should fail if the destination file already exists |

### ReturnValue

A [FileInfo](../) object that represents the copy

## See Also

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
