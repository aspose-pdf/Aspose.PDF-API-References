---
title: System::IO::FileMode enum
linktitle: FileMode
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::FileMode enum. Specifies how a file should be opened in C++.'
type: docs
weight: 3100
url: /cpp/system.io/filemode/
---
## FileMode enum


Specifies how a file should be opened.

```cpp
enum class FileMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| CreateNew | 1 | Create a new file. If the file already exists, an exception is thrown. |
| Create | 2 | Create a new file. If the file already exists, it is overwritten. |
| Open | 3 | Open an existing file. If the file does not exist, an exception is thrown. |
| OpenOrCreate | 4 | Open an existing file or create a new one if it does not exist. |
| Truncate | 5 | Open an existing file and truncate it so that it is empty. If the file does not exist, an exception is thrown. |
| Append | 6 | Open an existing file and seek to the end of it or create a new one if it does not exist. |

## See Also

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
