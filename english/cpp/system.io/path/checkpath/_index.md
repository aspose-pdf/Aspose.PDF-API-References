---
title: System::IO::Path::CheckPath method
linktitle: CheckPath
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::Path::CheckPath method. Determines if the specified path is valid by checking if it contains invalid characters. An exception is thrown if the path contains invalid characters in C++.'
type: docs
weight: 200
url: /cpp/system.io/path/checkpath/
---
## Path::CheckPath method


Determines if the specified path is valid by checking if it contains invalid characters. An exception is thrown if the path contains invalid characters.

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=true)
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const String\& | The path to check |
| msg | const String\& | The message to pass to the exception object's constructor |
| allow_empty | bool | Specifies whether an empty or null string should be considered a correct path (true) or not (false); if this parameter is false and **path** is empty an ArgumentException is thrown; if this parameter is false and **path** is null an ArgumentNullException is thrown |

## See Also

* Class [String](../../../system/string/)
* Class [Path](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
