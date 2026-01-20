---
title: System::IO::FileInfo::Replace method
linktitle: Replace
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::FileInfo::Replace method. Replaces the contents of a specified destination file with the file represented by the current FileInfo object and creates a backup of the replaced file in C++.'
type: docs
weight: 2000
url: /cpp/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) method


Replaces the contents of a specified destination file with the file represented by the current [FileInfo](../) object and creates a backup of the replaced file.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| destinationFileName | const String\& | A name of the file to replace |
| destinationBackupFileName | const String\& | A name of the backup file |

### ReturnValue

A FileInfor object that represents the file pointed to by **destinationFileName**

## See Also

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileInfo::Replace(const String\&, const String\&, bool) method


Replaces the contents of a specified destination file with the file represented by the current [FileInfo](../) object and creates a backup of the replaced file.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```


| Parameter | Type | Description |
| --- | --- | --- |
| destinationFileName | const String\& | A name of the file to replace |
| destinationBackupFileName | const String\& | A name of the backup file |
| ignoreMetadataErrors | bool | Specifies if the merge errors from the replaced file to the replacement file should be ignored (true) or not (false) |

### ReturnValue

A FileInfor object that represents the file pointed to by **destinationFileName**

## See Also

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
