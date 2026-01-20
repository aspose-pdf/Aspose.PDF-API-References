---
title: System::IO::File::Replace method
linktitle: Replace
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::File::Replace method. Replaces the contents of a one file with another and creates a backup of the replaced file in C++.'
type: docs
weight: 2700
url: /cpp/system.io/file/replace/
---
## File::Replace method


Replaces the contents of a one file with another and creates a backup of the replaced file.

```cpp
static void System::IO::File::Replace(const String &sourceFileName, const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors=true)
```


| Parameter | Type | Description |
| --- | --- | --- |
| sourceFileName | const String\& | A name of the file to replace with |
| destinationFileName | const String\& | A name of the file to replace |
| destinationBackupFileName | const String\& | A name of the backup file |
| ignoreMetadataErrors | bool | Specifies if the merge errors from the replaced file to the replacement file should be ignored (true) or not (false) |

## See Also

* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
