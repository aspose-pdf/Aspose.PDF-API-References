---
title: System::IO::Directory::Delete method
linktitle: Delete
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::Directory::Delete method. Removes the specified file or directory. Does not throw in C++.'
type: docs
weight: 200
url: /cpp/system.io/directory/delete/
---
## Directory::Delete method


Removes the specified file or directory. Does not throw.

```cpp
static void System::IO::Directory::Delete(const String &path, bool recursive=false)
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const String\& | The path to the directory or file to be removed |
| recursive | bool | If **path** specifies a non-empty directory then **recursive** specifies if if all directory's content should be removed recursively; if the directory specified by **path** is not empty and **recursive** is 'false' then the operation fails |

## See Also

* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
