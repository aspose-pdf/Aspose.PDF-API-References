---
title: System::IO::DirectoryInfo::GetFiles method
linktitle: GetFiles
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::DirectoryInfo::GetFiles method. Returns an array containing shared pointers to FileInfo objects representing all directories located in the directory represented by the current object in C++.'
type: docs
weight: 1300
url: /cpp/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() method


Returns an array containing shared pointers to [FileInfo](../../fileinfo/) objects representing all directories located in the directory represented by the current object.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::GetFiles(const String\&) method


Searches for the files that satisfy the specified search criteria in the directory represented by the current object.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```


| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const String\& | The name pattern of the files to search for |

### ReturnValue

An array of shared pointers to [FileInfo](../../fileinfo/) objects representing the found files whose names match **searchPattern**

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::GetFiles(const String\&, SearchOption) method


Searches for the files that satisfy the specified search criteria either in the directory represented by the current object or in the whole directory tree rooted in the directory represented by the current object.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```


| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const String\& | The name pattern of the files to search for |
| searchOption | SearchOption | Specifies whether the search has to be performed in the directory represented by the current object only or in the whole directory tree rooted in the directory represented by the current object |

### ReturnValue

An array of shared pointers to [FileInfo](../../fileinfo/) objects representing the found files whose names match **searchPattern**

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
