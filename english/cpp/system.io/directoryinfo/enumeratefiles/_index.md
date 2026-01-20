---
title: System::IO::DirectoryInfo::EnumerateFiles method
linktitle: EnumerateFiles
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::DirectoryInfo::EnumerateFiles method. Returns enumerable collection containing all files located in the directory represented by the current object in C++.'
type: docs
weight: 600
url: /cpp/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() method


Returns enumerable collection containing all files located in the directory represented by the current object.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::EnumerateFiles(const String\&) method


Searches for the files that satisfy the specified search criteria in the directory represented by the current object.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```


| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const String\& | The name pattern of the files to search for |

### ReturnValue

The enumerable collection of shared pointers to [FileInfo](../../fileinfo/) objects representing the found files whose names match **searchPattern**

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) method


Searches for the files that satisfy the specified search criteria either in the directory represented by the current object or in the whole directory tree rooted in the directory represented by the current object.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```


| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const String\& | The name pattern of the files to search for |
| searchOption | SearchOption | Specifies whether the search has to be performed in the directory represented by the current object only or in the whole directory tree rooted in the directory represented by the current object |

### ReturnValue

The enumerable collection of shared pointers to [FileInfo](../../fileinfo/) objects representing the found files whose names match **searchPattern**

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
