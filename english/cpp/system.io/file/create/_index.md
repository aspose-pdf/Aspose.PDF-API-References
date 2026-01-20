---
title: System::IO::File::Create method
linktitle: Create
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::File::Create method. Creates a new file (or overwrites existing) and opens it for reading and writing access using the specified buffer size and options in C++.'
type: docs
weight: 500
url: /cpp/system.io/file/create/
---
## File::Create method


Creates a new file (or overwrites existing) and opens it for reading and writing access using the specified buffer size and options.

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const String\& | The path of the file to create or overwrite |
| bufferSize | int32_t | The number of bytes buffered when reading from and writing to the file |
| options | FileOptions | Specifies how to create or overwrite the file |

### ReturnValue

A shared pointer to the [FileStream](../../filestream/) object associated with the specified file

## See Also

* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Enum [FileOptions](../../fileoptions/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
