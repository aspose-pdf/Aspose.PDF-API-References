---
title: System::IO::FileSystemInfo class
linktitle: FileSystemInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::FileSystemInfo class. The base class for FileInfo and DirectoryInfo. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1600
url: /cpp/system.io/filesysteminfo/
---
## FileSystemInfo class


The base class for [FileInfo](../fileinfo/) and [DirectoryInfo](../directoryinfo/). Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class FileSystemInfo : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Delete](./delete/)() | Deletes the entity represented by the current object. |
| virtual [Finalize](./finalize/)() | Does nothing. |
| [get_Attributes](./get_attributes/)() | Returns the attributes of the entity represented by the current object. |
| [get_CreationTime](./get_creationtime/)() | Returns the creation time of the entity represented by the current object as local time. |
| [get_CreationTimeUtc](./get_creationtimeutc/)() | Returns the creation time of the entity represented by the current object as UTC time. |
| virtual [get_Exists](./get_exists/)() | Determines if the entity referenced by the path represented by the current object exists. |
| [get_Extension](./get_extension/)() | Returns the extension of the file represented by the current object. |
| virtual [get_FullName](./get_fullname/)() | Returns the full name (including path) of the entity represented by the current object. |
| [get_LastAccessTime](./get_lastaccesstime/)() | Returns the last access time of the entity represented by the current object as local time. |
| [get_LastAccessTimeUtc](./get_lastaccesstimeutc/)() | Returns the last access time of the entity represented by the current object as UTC time. |
| [get_LastWriteTime](./get_lastwritetime/)() | Returns the last write time of the entity represented by the current object as local time. |
| [get_LastWriteTimeUtc](./get_lastwritetimeutc/)() | Returns the last write time of the entity represented by the current object as UTC time. |
| virtual [get_Name](./get_name/)() | Returns a name of the entity represented by the current object. |
| [Refresh](./refresh/)() | Refreshes the state of the current object. |
| [set_Attributes](./set_attributes/)(FileAttributes) | Sets the specified attributes on the entity represeted by the current object. |
| [set_CreationTime](./set_creationtime/)(DateTime) | Sets the creation time of the entity represented by the current object as local time. |
| [set_CreationTimeUtc](./set_creationtimeutc/)(DateTime) | Sets the creation time of the entity represented by the current object as UTC time. |
| [set_LastAccessTime](./set_lastaccesstime/)(DateTime) | Sets the last access time of the entity represented by the current object as local time. |
| [set_LastAccessTimeUtc](./set_lastaccesstimeutc/)(DateTime) | Sets the last access time of the entity represented by the current object as UTC time. |
| [set_LastWriteTime](./set_lastwritetime/)(DateTime) | Sets the last write time of the entity represented by the current object as local time. |
| [set_LastWriteTimeUtc](./set_lastwritetimeutc/)(DateTime) | Sets the last write time of the entity represented by the current object as UTC time. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
