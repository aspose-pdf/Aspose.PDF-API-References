---
title: System::IO::Directory::GetFileSystemEntries method
linktitle: GetFileSystemEntries
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::Directory::GetFileSystemEntries method. Searches for the files and directories that satisfy the specified search criteria either in the specified directory or in the whole directory tree rooted in the specified directory in C++.'
type: docs
weight: 1300
url: /cpp/system.io/directory/getfilesystementries/
---
## Directory::GetFileSystemEntries method


Searches for the files and directories that satisfy the specified search criteria either in the specified directory or in the whole directory tree rooted in the specified directory.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const String\& | Full or relative path to the directory to search in |
| searchPattern | const String\& | The name pattern of the files and directories to search for |
| searchOption | SearchOption | Specifies whether the search has to be performed in the specified directory only or in the whole directory tree rooted in the specified directory |

### ReturnValue

An array of full paths of the found files and directories whose names match **searchPattern**

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
