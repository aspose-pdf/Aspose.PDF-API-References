---
title: System::IO::DirectoryInfo::GetDirectories method
linktitle: GetDirectories
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::DirectoryInfo::GetDirectories method. Returns an array containing shared pointers to DirectoryInfo objects representing all directories located in the directory represented by the current object in C++.'
type: docs
weight: 1200
url: /cpp/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() method


Returns an array containing shared pointers to [DirectoryInfo](../) objects representing all directories located in the directory represented by the current object.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::GetDirectories(const String\&) method


Searches for the directories that satisfy the specified search criteria in the directory represented by the current object.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```


| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const String\& | The name pattern of the directories to search for |

### ReturnValue

An array of shared pointers to [DirectoryInfo](../) objects representing the found directories whose names match **searchPattern**

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [String](../../../system/string/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## DirectoryInfo::GetDirectories(const String\&, SearchOption) method


Searches for the directories that satisfy the specified search criteria either in the directory represented by the current object or in the whole directory tree rooted in the directory represented by the current object.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```


| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const String\& | The name pattern of the directories to search for |
| searchOption | SearchOption | Specifies whether the search has to be performed in the directory represented by the current object only or in the whole directory tree rooted in the directory represented by the current object |

### ReturnValue

An array of shared pointers to [DirectoryInfo](../) objects representing the found directories whose names match **searchPattern**

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [DirectoryInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
