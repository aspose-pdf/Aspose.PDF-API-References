---
title: System::IO::FileInfo class
linktitle: FileInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::FileInfo class. Represents a path to a file and a file referred to by this path and provides methods for manipulating it. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1400
url: /cpp/system.io/fileinfo/
---
## FileInfo class


Represents a path to a file and a file referred to by this path and provides methods for manipulating it. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## Methods

| Method | Description |
| --- | --- |
| [AppendText](./appendtext/)() | Opens a file represented by the current object for writing text using UTF-8 encoding, in 'Append' mode with no sharing. |
| [CopyTo](./copyto/)(const String\&) | Copies the file represented by the current object to the specified location. If the destination file already exists, the copying fails. |
| [CopyTo](./copyto/)(const String\&, bool) | Copies the file represented by the current object to the specified location. A parameter specifies if existing destination file should be overwritten. |
| [Create](./create/)() | Creates a file at the location specified by the path represented by the current object and opens it for reading and writing, in truncate mode and with no sharing. |
| [CreateText](./createtext/)() | Creates a file at the location specified by the path represented by the current object and opens it for writing text using UTF-8 encoding with no sharing. |
| [Decrypt](./decrypt/)() | NOT IMPLEMENTED. |
| [Delete](./delete/)() override | Removes the file represented by the current object. |
| [Encrypt](./encrypt/)() | NOT IMPLEMENTED. |
| [FileInfo](./fileinfo/)(const String\&) | Constructs a new instance of [FileInfo](./) class that represents the specified file. |
| [get_Directory](./get_directory/)() | Returns a [DirectoryInfo](../directoryinfo/) object that represents a directory in which the file represented by the current object is located. |
| [get_DirectoryName](./get_directoryname/)() | Returns the full name of the directory in which the file represented by the current object is loctaed. |
| [get_Exists](./get_exists/)() override | Returns a value that indicates if the file exists. |
| [get_IsReadOnly](./get_isreadonly/)() | Returns a value that indicates if the ReadOnly attribute is set. |
| [get_Length](./get_length/)() | Returns the size of the file in bytes. |
| [get_Name](./get_name/)() override | Returns the name of the file. |
| [MoveTo](./moveto/)(const String\&) | Moves the file represented by the current object to the specified location. |
| [Open](./open/)(FileMode) | Opens the file represented by the current object in the specified mode for reading and writing and with no sharing. |
| [Open](./open/)(FileMode, FileAccess) | Opens the file represented by the current object in the specified mode, with the specified access type and with no sharing. |
| [Open](./open/)(FileMode, FileAccess, FileShare) | Opens the file represented by the current object in the specified mode, with the specified access type and sharing option. |
| [OpenRead](./openread/)() | Opens a file represented by the current object for reading only, in 'Open' mode with shared access for reading. |
| [OpenText](./opentext/)() | Opens the existing file at the location specified by the path represented by the current object for reading text using UTF-8 encoding with no sharing. |
| [OpenWrite](./openwrite/)() | Opens a file represented by the current object for writing only, in 'OpenOrCreate' mode with no sharing. |
| [Replace](./replace/)(const String\&, const String\&) | Replaces the contents of a specified destination file with the file represented by the current [FileInfo](./) object and creates a backup of the replaced file. |
| [Replace](./replace/)(const String\&, const String\&, bool) | Replaces the contents of a specified destination file with the file represented by the current [FileInfo](./) object and creates a backup of the replaced file. |
| [set_IsReadOnly](./set_isreadonly/)(bool) | Sets or unsets the ReadOnly attribute on the file. |
| [ToString](./tostring/)() const override | Returns a path represented by the current object. |
## See Also

* Class [FileSystemInfo](../filesysteminfo/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
