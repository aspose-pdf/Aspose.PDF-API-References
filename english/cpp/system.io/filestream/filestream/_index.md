---
title: System::IO::FileStream::FileStream constructor
linktitle: FileStream
second_title: Aspose.PDF for C++ API Reference
description: 'How to use FileStream constructor of System::IO::FileStream class in C++.'
type: docs
weight: 100
url: /cpp/system.io/filestream/filestream/
---
## FileStream::FileStream(const FileStream\&) constructor




```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## See Also

* Class [FileStream](../)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileStream::FileStream(const String\&, FileMode) constructor


Constructs a new instance of [FileStream](../) class and initializes it with the specified parameters.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const String\& | The path of the file to open. |
| mode | FileMode | Specifies the mode in which to open the file. |

## See Also

* Class [String](../../../system/string/)
* Enum [FileMode](../../filemode/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) constructor


Constructs a new instance of [FileStream](../) class and initializes it with the specified parameters.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const String\& | The path of the file to open. |
| mode | FileMode | Specifies the mode in which to open the file. |
| access | FileAccess | The requested access type. |
| share | FileShare | The type of access that other [FileStream](../) objects have to the opened file. |
| buffer_size | int32_t | The number of bytes bufferred during read and write operations. |
| useAsync | bool | Specifies whether to use asynchronous I/O or synchronous I/O. |
## Remarks



The underlying operating system might not support asynchronous I/O. 

## See Also

* Class [String](../../../system/string/)
* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) constructor


Constructs a new instance of [FileStream](../) class and initializes it with the specified parameters.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | const String\& | The path of the file to open. |
| mode | FileMode | Specifies the mode in which to open the file. |
| access | FileAccess | The requested access type. |
| share | FileShare | The type of access that other [FileStream](../) objects have to the opened file. |
| buffer_size | int32_t | The number of bytes bufferred during read and write operations. |
| options | FileOptions | Additional options. |

## See Also

* Class [String](../../../system/string/)
* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
