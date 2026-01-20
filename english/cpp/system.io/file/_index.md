---
title: System::IO::File class
linktitle: File
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::File class. Provides methods for manipulating files. This is a static type with no instance services. You should never create instances of it by any means in C++.'
type: docs
weight: 1300
url: /cpp/system.io/file/
---
## File class


Provides methods for manipulating files. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class File
```

## Methods

| Method | Description |
| --- | --- |
| static [AppendAllLines](./appendalllines/)(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) | Appends strings from the specified collection of strings to the specified file using the specified encoding by writing each string in a new line. If the specified file does not exist, it is created. The file is closed after writing all strings. |
| static [AppendAllText](./appendalltext/)(const String\&, const String\&, const EncodingPtr\&) | Appends the specified string to the specified file using the specified encoding. |
| static [AppendText](./appendtext/)(const String\&) | Creates a [StreamWriter](../streamwriter/) object that appends text to the specified file using UTF-8 encoding. If the specified file does not exist, it is created. |
| static [Copy](./copy/)(const String\&, const String\&, bool) | Copies the specified file to the specified location. If the destination file already exists, a parameter specifies if it should be overwritten. |
| static [Create](./create/)(const String\&, int32_t, FileOptions) | Creates a new file (or overwrites existing) and opens it for reading and writing access using the specified buffer size and options. |
| static [CreateText](./createtext/)(const String\&) | Creates a new or opens existing file for writing UTF-8 encoded text. |
| static [Decrypt](./decrypt/)(const String\&) | NOT IMPLEMENTED. |
| static [Delete](./delete/)(const String\&) | Deletes the specified file or directory. |
| static [Encrypt](./encrypt/)(const String\&) | NOT IMPLEMENTED. |
| static [Exists](./exists/)(const String\&) | Determines if the specified path references an existing file. |
| static [GetAttributes](./getattributes/)(const String\&) | Returns the attributes of the specified entity. |
| static [GetCreationTime](./getcreationtime/)(const String\&) | Returns the creation time of the specified entity as local time. |
| static [GetCreationTimeUtc](./getcreationtimeutc/)(const String\&) | Returns the creation time of the specified entity as UTC time. |
| static [GetLastAccessTime](./getlastaccesstime/)(const String\&) | Returns the last access time of the specified entity as local time. |
| static [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const String\&) | Returns the last access time of the specified entity as UTC time. |
| static [GetLastWriteTime](./getlastwritetime/)(const String\&) | Returns the last write time of the specified entity as local time. |
| static [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const String\&) | Returns the last write time of the specified entity as UTC time. |
| static [Move](./move/)(const String\&, const String\&) | Moves the specified file to the new location. |
| static [Open](./open/)(const String\&, FileMode) | Opens the specified file in the specified mode for reading and writing and with no sharing. |
| static [Open](./open/)(const String\&, FileMode, FileAccess, FileShare) | Opens the specified file in the specified mode, with the specified access type and sharing option. |
| static [OpenRead](./openread/)(const String\&) | Opens the specified file for reading only, in 'Open' mode with shared access for reading. |
| static [OpenText](./opentext/)(const String\&, const EncodingPtr\&) | Opens the specified existing file for reading text using UTF-8 encoding with no sharing. |
| static [OpenWrite](./openwrite/)(const String\&) | Opens the specified file for writing only, in 'OpenOrCreate' mode with no sharing. |
| static [ReadAllBytes](./readallbytes/)(const String\&) | Reads the content of the specified binary file to a byte array. |
| static [ReadAllLines](./readalllines/)(const String\&, const EncodingPtr\&) | Reads the content of the specified text file line by line to an array of strings using the specified character encoding. |
| static [ReadAllText](./readalltext/)(const String\&, const EncodingPtr\&) | Reads the content of the specified text file to a single [String](../../system/string/) object using the specified character encoding. |
| static [ReadLines](./readlines/)(const String\&, const EncodingPtr\&) | Reads the content of the specified text file line by line using the specified character encoding and returns enumerable collection of strings each of which represents a single line of the file's content. |
| static [Replace](./replace/)(const String\&, const String\&, const String\&, bool) | Replaces the contents of a one file with another and creates a backup of the replaced file. |
| static [SetAttributes](./setattributes/)(const String\&, FileAttributes) | Sets the specified attributes on the specified file. |
| static [SetCreationTime](./setcreationtime/)(const String\&, DateTime) | NOT IMPLEMENTED. |
| static [SetCreationTimeUtc](./setcreationtimeutc/)(const String\&, DateTime) | NOT IMPLEMENTED. |
| static [SetLastAccessTime](./setlastaccesstime/)(const String\&, DateTime) | NOT IMPLEMENTED. |
| static [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const String\&, DateTime) | NOT IMPLEMENTED. |
| static [SetLastWriteTime](./setlastwritetime/)(const String\&, DateTime) | Sets the last write time of the specified entity as local time. |
| static [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const String\&, DateTime) | Sets the last write time of the specified entity as UTC time. |
| static [WriteAllBytes](./writeallbytes/)(const String\&, const ArrayPtr\<uint8_t\>\&) | Overwrites the specified binary file and writes the specified bytes to it. |
| static [WriteAllLines](./writealllines/)(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) | Creates a new text file or overwrites the existing one and writes all strings from the specified enumerable collection of strings to it, each string on a new line, using the specified encoding. |
| static [WriteAllLines](./writealllines/)(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) | Creates a new text file or overwrites the existing one and writes all strings from the specified array of strings to it, each string on a new line, using the specified encoding. |
| static [WriteAllText](./writealltext/)(const String\&, const String\&, const EncodingPtr\&) | Creates a new text file or overwrites the existing one and writes the content of the specified string to it using the specified encoding. |
## Fields

| Field | Description |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | Default value of the number of bytes buffered during reading from and writing to a file. |
## See Also

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
