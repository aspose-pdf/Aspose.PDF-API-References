---
title: System::IO::Path class
linktitle: Path
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::Path class. Provides methods for manipulating paths. This is a static type with no instance services. You should never create instances of it by any means in C++.'
type: docs
weight: 1900
url: /cpp/system.io/path/
---
## Path class


Provides methods for manipulating paths. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Path
```

## Methods

| Method | Description |
| --- | --- |
| static [ChangeExtension](./changeextension/)(const String\&, const String\&) | Changes the extension in the specified file path. |
| static [CheckPath](./checkpath/)(const String\&, const String\&, bool) | Determines if the specified path is valid by checking if it contains invalid characters. An exception is thrown if the path contains invalid characters. |
| static [Combine](./combine/)(const ArrayPtr\<String\>\&) | Combines the specified path segments into a single path inserting directory separator characters between the segments if necessary. |
| static [Combine](./combine/)(const String\&, const String\&) | Combines two specified path segments into a single path inserting directory separator character between the segments if necessary. |
| static [Combine](./combine/)(const String\&, const String\&, const String\&) | Combines three specified path segments into a single path inserting directory separator characters between the segments if necessary. |
| static [Combine](./combine/)(const String\&, const String\&, const String\&, const String\&) | Combines four specified path segments into a single path inserting directory separator characters between the segments if necessary. |
| static [GetDirectoryName](./getdirectoryname/)(const String\&) | Returns the name of the directory referenced by the specified path. |
| static [GetExtension](./getextension/)(const String\&) | Returns the extension of the file referenced by the specified path. |
| static [GetFileName](./getfilename/)(const String\&) | Returns the name of the file referenced by the specified path. |
| static [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const String\&) | Returns the name without extension of the file referenced by the specified path. |
| static [GetFullPath](./getfullpath/)(const String\&) | Converts the specified path into absolute path. |
| static [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | Returns an array containing characters that are not allowed in the names of files. |
| static [GetInvalidPathChars](./getinvalidpathchars/)() | Returns an array containing characters that are not allowed in path names. |
| static [GetPathRoot](./getpathroot/)(const String\&) | Returns the root directory of the specified path. |
| static [GetRandomFileName](./getrandomfilename/)() | Returns a randomly generated file name. |
| static [GetTempFileName_](./gettempfilename_/)() | Creates a new file with a unique name and returns a full path to it. |
| static [GetTempFileNameSafe](./gettempfilenamesafe/)() | Creates a new file with a unique name and returns a full path to it. Is a synonym of [GetTempFileName_()](./gettempfilename_/) method. |
| static [GetTempPath](./gettemppath/)() | Returns the path of the current user's temporary directory. |
| static [HasExtension](./hasextension/)(const String\&) | Determines if the specified path references a file with extension. |
| static [IsPathRooted](./ispathrooted/)(const String\&) | Determines if the specified path contains a root. |
| static [NormalizePath](./normalizepath/)(const String\&) | Normalizes the specified path. |
| static [ToBoost](./toboost/)(const String\&) | Returns an instance of boost::filesystem::path class that represents the specified path. |
| static [ToString](./tostring/)(const boost::filesystem::path\&) | Returns a string representation of the specified Boost's path object. |
## Fields

| Field | Description |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | An alternate character used to separate directory levels in a path. |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | A character used to separate directory levels in a path. |
| static [PathSeparator](./pathseparator/) | A separator character used to separate path strings in environment variables. |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | A volume separator character. |
## Remarks



```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // Generate a random filename.
  auto filename = Path::GetRandomFileName();

  // Print information about file name.
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
This code example produces the following output:
Filename: qhuzkyqv.y6p
Filename w/o an extension: qhuzkyqv
Extension: .y6p
*/
```

## See Also

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
