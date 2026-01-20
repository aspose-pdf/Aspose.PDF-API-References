---
title: System::IO::DirectoryInfo class
linktitle: DirectoryInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::DirectoryInfo class. Represents a file system path, a directory referred to by this path and provides instance methods for manipulating directories. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1200
url: /cpp/system.io/directoryinfo/
---
## DirectoryInfo class


Represents a file system path, a directory referred to by this path and provides instance methods for manipulating directories. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DirectoryInfo : public System::IO::FileSystemInfo
```

## Methods

| Method | Description |
| --- | --- |
| [Create](./create/)() | Creates a directory at the path represented by the current object. |
| [CreateSubdirectory](./createsubdirectory/)(const String\&) | Creates subdirectories on the specified path. |
| [Delete](./delete/)() override | Removes the directory referred to by the path represented by the current object if the directory is empty. |
| [Delete](./delete/)(bool) | Removes the directory referred to by the path represented by the current object. A parameter specifies if the content of the directory should be recursively removed if the directory is not empty. |
| [DirectoryInfo](./directoryinfo/)(const String\&) | Constructs an instnace of [DirectoryInfo](./) class on the specified path. |
| [EnumerateDirectories](./enumeratedirectories/)() | Returns enumerable collection containing all directories located in the directory represented by the current object. |
| [EnumerateDirectories](./enumeratedirectories/)(const String\&) | Searches for the directories that satisfy the specified search criteria in the directory represented by the current object. |
| [EnumerateDirectories](./enumeratedirectories/)(const String\&, SearchOption) | Searches for the directories that satisfy the specified search criteria either in the directory represented by the current object or in the whole directory tree rooted in the directory represented by the current object. |
| [EnumerateFiles](./enumeratefiles/)() | Returns enumerable collection containing all files located in the directory represented by the current object. |
| [EnumerateFiles](./enumeratefiles/)(const String\&) | Searches for the files that satisfy the specified search criteria in the directory represented by the current object. |
| [EnumerateFiles](./enumeratefiles/)(const String\&, SearchOption) | Searches for the files that satisfy the specified search criteria either in the directory represented by the current object or in the whole directory tree rooted in the directory represented by the current object. |
| [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)() | Returns enumerable collection containing all files and directories located in the directory represented by the current object. |
| [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const String\&) | Searches for the files and directories that satisfy the specified search criteria in the directory represented by the current object. |
| [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const String\&, SearchOption) | Searches for the files and directories that satisfy the specified search criteria either in the directory represented by the current object or in the whole directory tree rooted in the directory represented by the current object. |
| [get_Exists](./get_exists/)() override | Determines if the path represented by the current object refers to existing directory. |
| [get_Name](./get_name/)() override | Returns the name of the entity referred to by the path represented by the current object. |
| [get_Parent](./get_parent/)() | Returns a shared pointer to [DirectoryInfo](./) object that represents a path referring the parent directory of the directory represented by the current object. |
| [get_Root](./get_root/)() | Returns a shared pointer to [DirectoryInfo](./) object that represents a path referring the root directory of the directory represented by the current object. |
| [GetDirectories](./getdirectories/)() | Returns an array containing shared pointers to [DirectoryInfo](./) objects representing all directories located in the directory represented by the current object. |
| [GetDirectories](./getdirectories/)(const String\&) | Searches for the directories that satisfy the specified search criteria in the directory represented by the current object. |
| [GetDirectories](./getdirectories/)(const String\&, SearchOption) | Searches for the directories that satisfy the specified search criteria either in the directory represented by the current object or in the whole directory tree rooted in the directory represented by the current object. |
| [GetFiles](./getfiles/)() | Returns an array containing shared pointers to [FileInfo](../fileinfo/) objects representing all directories located in the directory represented by the current object. |
| [GetFiles](./getfiles/)(const String\&) | Searches for the files that satisfy the specified search criteria in the directory represented by the current object. |
| [GetFiles](./getfiles/)(const String\&, SearchOption) | Searches for the files that satisfy the specified search criteria either in the directory represented by the current object or in the whole directory tree rooted in the directory represented by the current object. |
| [GetFileSystemInfos](./getfilesysteminfos/)() | Returns an array containing shared pointers to [FileSystemInfo](../filesysteminfo/) objects representing all files and directories located in the directory represented by the current object. |
| [GetFileSystemInfos](./getfilesysteminfos/)(const String\&) | Searches for the files and directories that satisfy the specified search criteria in the directory represented by the current object. |
| [GetFileSystemInfos](./getfilesysteminfos/)(const String\&, SearchOption) | Searches for the files and directories that satisfy the specified search criteria either in the directory represented by the current object or in the whole directory tree rooted in the directory represented by the current object. |
| [MoveTo](./moveto/)(const String\&) | Moves the directory represented by the current object and all its contentto the specified location. |
| [ToString](./tostring/)() const override | Returns a string containing the path represented by the current object. |
## See Also

* Class [FileSystemInfo](../filesysteminfo/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
