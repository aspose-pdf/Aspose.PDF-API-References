---
title: System::IO::FileOptions enum
linktitle: FileOptions
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::FileOptions enum. Represents advanced options for creating FileStream object in C++.'
type: docs
weight: 3200
url: /cpp/system.io/fileoptions/
---
## FileOptions enum


Represents advanced options for creating [FileStream](../filestream/) object.

```cpp
enum class FileOptions
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | No additional options. |
| Encrypted | 16384 | The file is encrypted. NOT IMPLEMENTED. |
| DeleteOnClose | 67108864 | The file should be automatically deleted when it is not in use anymore. |
| SequentialScan | 134217728 | The file shoud be accesses sequentially. |
| RandomAccess | 268435456 | The file is accessed randomly. |
| Asynchronous | 1073741824 | The file can be used for asynchronous I/O operations. |
| WriteThrough | n/a | All writes should go directly to the disk bypassing any intermediate cache. |

## See Also

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
