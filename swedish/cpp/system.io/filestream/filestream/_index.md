---
title: "System::IO::FileStream::FileStream konstruktor"
linktitle: "FileStream"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder FileStream-konstruktorn i klassen System::IO::FileStream i C++."
type: docs
weight: 100
url: /sv/cpp/system.io/filestream/filestream/
---
## FileStream::FileStream(const FileStream\&) constructor




```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## Se även

* Class [FileStream](../)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileStream::FileStream(const String\&, FileMode) constructor


Skapar en ny instans av klassen [FileStream](../) och initierar den med de angivna parametrarna.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | const String\& | Sökvägen till filen som ska öppnas. |
| läge | FileMode | Anger läget i vilket filen ska öppnas. |

## Se även

* Class [String](../../../system/string/)
* Enum [FileMode](../../filemode/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) constructor


Skapar en ny instans av klassen [FileStream](../) och initierar den med de angivna parametrarna.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | const String\& | Sökvägen till filen som ska öppnas. |
| läge | FileMode | Anger läget i vilket filen ska öppnas. |
| åtkomst | FileAccess | Den begärda åtkomsttypen. |
| share | FileShare | Typen av åtkomst som andra [FileStream](../)-objekt har till den öppnade filen. |
| buffer_size | int32_t | Antalet byte som buffras under läs- och skrivoperationer. |
| useAsync | bool | Anger om asynkron I/O eller synkron I/O ska användas. |
## Anmärkningar



Det underliggande operativsystemet kanske inte stöder asynkron I/O.

## Se även

* Class [String](../../../system/string/)
* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) constructor


Skapar en ny instans av klassen [FileStream](../) och initierar den med de angivna parametrarna.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | const String\& | Sökvägen till filen som ska öppnas. |
| läge | FileMode | Anger läget i vilket filen ska öppnas. |
| åtkomst | FileAccess | Den begärda åtkomsttypen. |
| share | FileShare | Typen av åtkomst som andra [FileStream](../)-objekt har till den öppnade filen. |
| buffer_size | int32_t | Antalet byte som buffras under läs- och skrivoperationer. |
| options | FileOptions | Ytterligare alternativ. |

## Se även

* Class [String](../../../system/string/)
* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
