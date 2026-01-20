---
title: System::IO::File::Copy method
linktitle: Copy
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::File::Copy method. Copies the specified file to the specified location. If the destination file already exists, a parameter specifies if it should be overwritten in C++.'
type: docs
weight: 400
url: /cpp/system.io/file/copy/
---
## File::Copy method


Copies the specified file to the specified location. If the destination file already exists, a parameter specifies if it should be overwritten.

```cpp
static void System::IO::File::Copy(const String &sourceFileName, const String &destFileName, bool overwrite=false)
```


| Parameter | Type | Description |
| --- | --- | --- |
| sourceFileName | const String\& | A path of the file to copy |
| destFileName | const String\& | A path of the new location of the file to copy |
| overwrite | bool | True if the existing destination file should be overwritten, false if copying should fail if the destination file already exists |

## See Also

* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
