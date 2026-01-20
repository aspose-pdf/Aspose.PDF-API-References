---
title: System::IO::DirectoryInfo::EnumerateFileSystemInfos method
linktitle: EnumerateFileSystemInfos
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::DirectoryInfo::EnumerateFileSystemInfos method. Returns enumerable collection containing all files and directories located in the directory represented by the current object in C++.'
type: docs
weight: 700
url: /cpp/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() method


Returns enumerable collection containing all files and directories located in the directory represented by the current object.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::EnumerateFileSystemInfos(const String\&) method


Searches for the files and directories that satisfy the specified search criteria in the directory represented by the current object.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```


| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const String\& | The name pattern of the files and directories to search for |

### ReturnValue

The enumerable collection of shared pointers to [FileSystemInfo](../../filesysteminfo/) objects representing the found files and directories whose names match **searchPattern**

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) method


Searches for the files and directories that satisfy the specified search criteria either in the directory represented by the current object or in the whole directory tree rooted in the directory represented by the current object.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const String\& | The name pattern of the files and directories to search for |
| searchOption | SearchOption | Specifies whether the search has to be performed in the directory represented by the current object only or in the whole directory tree rooted in the directory represented by the current object |

### ReturnValue

The enumerable collection of shared pointers to [FileSystemInfo](../../filesysteminfo/) objects representing the found files and directories whose names match **searchPattern**

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
