---
title: System::IO::DirectoryInfo::EnumerateDirectories method
linktitle: EnumerateDirectories
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::DirectoryInfo::EnumerateDirectories method. Returns enumerable collection containing all directories located in the directory represented by the current object in C++.'
type: docs
weight: 500
url: /cpp/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() method


Returns enumerable collection containing all directories located in the directory represented by the current object.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::EnumerateDirectories(const String\&) method


Searches for the directories that satisfy the specified search criteria in the directory represented by the current object.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```


| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const String\& | The name pattern of the directories to search for |

### ReturnValue

The enumerable collection of shared pointers to [DirectoryInfo](../) objects representing the found directories whose names match **searchPattern**

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) method


Searches for the directories that satisfy the specified search criteria either in the directory represented by the current object or in the whole directory tree rooted in the directory represented by the current object.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```


| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const String\& | The name pattern of the directories to search for |
| searchOption | SearchOption | Specifies whether the search has to be performed in the directory represented by the current object only or in the whole directory tree rooted in the directory represented by the current object |

### ReturnValue

The enumerable collection of shared pointers to [DirectoryInfo](../) objects representing the found directories whose names match **searchPattern**

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
