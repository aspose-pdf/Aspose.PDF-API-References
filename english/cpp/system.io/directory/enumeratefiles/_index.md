---
title: System::IO::Directory::EnumerateFiles method
linktitle: EnumerateFiles
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::Directory::EnumerateFiles method. Searches for the files that satisfy the specified search criteria either in the specified directory or in the whole directory tree rooted in the specified directory in C++.'
type: docs
weight: 400
url: /cpp/system.io/directory/enumeratefiles/
---
## Directory::EnumerateFiles method


Searches for the files that satisfy the specified search criteria either in the specified directory or in the whole directory tree rooted in the specified directory.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const String\& | Full or relative path to the directory to search in |
| searchPattern | const String\& | The name pattern of the files to search for |
| searchOption | SearchOption | Specifies whether the search has to be performed in the specified directory only or in the whole directory tree rooted in the specified directory |

### ReturnValue

The enumerable collection of full paths of the found files whose names match **searchPattern**

## See Also

* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
