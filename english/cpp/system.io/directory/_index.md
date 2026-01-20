---
title: System::IO::Directory class
linktitle: Directory
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::Directory class. Contains methods for manipulating directories. This is a static type with no instance services. You should never create instances of it by any means in C++.'
type: docs
weight: 1100
url: /cpp/system.io/directory/
---
## Directory class


Contains methods for manipulating directories. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Directory
```

## Methods

| Method | Description |
| --- | --- |
| static [CreateDirectory_](./createdirectory_/)(const String\&) | Creates all directories in the specified path if those don't exist. |
| static [Delete](./delete/)(const String\&, bool) | Removes the specified file or directory. Does not throw. |
| static [EnumerateDirectories](./enumeratedirectories/)(const String\&, const String\&, SearchOption) | Searches for the directories that satisfy the specified search criteria either in the specified directory or in the whole directory tree rooted in the specified directory. |
| static [EnumerateFiles](./enumeratefiles/)(const String\&, const String\&, SearchOption) | Searches for the files that satisfy the specified search criteria either in the specified directory or in the whole directory tree rooted in the specified directory. |
| static [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const String\&, const String\&, SearchOption) | Searches for the files and directories that satisfy the specified search criteria either in the specified directory or in the whole directory tree rooted in the specified directory. |
| static [Exists](./exists/)(const String\&) | Determines if the specified path refers to existing directory. |
| static [GetCreationTime](./getcreationtime/)(const String\&) | Returns the creation time of the specified entity as local time. |
| static [GetCreationTimeUtc](./getcreationtimeutc/)(const String\&) | Returns the creation time of the specified entity as UTC time. |
| static [GetCurrentDirectory](./getcurrentdirectory/)() | Returns the full name (including path) of the current directory. |
| static [GetDirectories](./getdirectories/)(const String\&, const String\&, SearchOption) | Searches for the directories that satisfy the specified search criteria either in the specified directory or in the whole directory tree rooted in the specified directory. |
| static [GetDirectoryRoot](./getdirectoryroot/)(const String\&) | Returns the root directory of the specified path. |
| static [GetFiles](./getfiles/)(const String\&, const String\&, SearchOption) | Searches for the files that satisfy the specified search criteria either in the specified directory or in the whole directory tree rooted in the specified directory. |
| static [GetFileSystemEntries](./getfilesystementries/)(const String\&, const String\&, SearchOption) | Searches for the files and directories that satisfy the specified search criteria either in the specified directory or in the whole directory tree rooted in the specified directory. |
| static [GetLastAccessTime](./getlastaccesstime/)(const String\&) | Returns the last access time of the specified entity as local time. |
| static [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const String\&) | Returns the last access time of the specified entity as UTC time. |
| static [GetLastWriteTime](./getlastwritetime/)(const String\&) | Returns the last write time of the specified entity as local time. |
| static [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const String\&) | Returns the last write time of the specified entity as UTC time. |
| static [GetLogicalDrives](./getlogicaldrives/)() | NOT IMPLEMENTED. |
| static [GetParent](./getparent/)(const String\&) | Returns a shared pointer to [DirectoryInfo](../directoryinfo/) object representing the parent directory of the specified entity. |
| static [Move](./move/)(const String\&, const String\&) | Moves the specified entity to the new location. If the entity to move is a directory, it is moved with all its content. |
| static [SetCreationTime](./setcreationtime/)(const String\&, DateTime) | Sets the creation time of the specified entity as local time. |
| static [SetCreationTimeUtc](./setcreationtimeutc/)(const String\&, DateTime) | Sets the creation time of the specified entity as UTC time. |
| static [SetCurrentDirectory](./setcurrentdirectory/)(const String\&) | Sets the current directory. |
| static [SetLastAccessTime](./setlastaccesstime/)(const String\&, DateTime) | Sets the last access time of the specified entity as local time. |
| static [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const String\&, DateTime) | Sets the last access time of the specified entity as UTC time. |
| static [SetLastWriteTime](./setlastwritetime/)(const String\&, DateTime) | Sets the last write time of the specified entity as local time. |
| static [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const String\&, DateTime) | Sets the last write time of the specified entity as UTC time. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | An alias for a shared pointer to IEnumerable object that enumerates over a set of [String](../../system/string/) objects. |
## Remarks



```cpp
#include "system/io/directory.h"
#include "system/io/path.h"
#include "system/string.h"
#include <iostream>

void PrintMessage(const System::String &path)
{
  std::cout << "Directory '" << path << (System::IO::Directory::Exists(path) ? "' exists." : "' doesn't exist.") << std::endl;
}

int main()
{
  // Create strings that contain paths to directories.
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // Check if directories exist.
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // Print the temp directory information.
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
This code example produces the following output:
Directory 'C:\' exists.
Directory 'C:\Some directory' doesn't exist.
Directory 'C:\Users\lanor\AppData\Local\Temp\' exists.
Creation Time: 27.08.2021 14:21:42
Last Access Time: 07.10.2021 12:16:41
Last Write Time: 07.10.2021 12:16:41
*/
```

## See Also

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
