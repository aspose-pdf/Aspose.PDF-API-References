---
title: "System::IO::Directory-klass"
linktitle: "Directory"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::Directory-klass. Innehåller metoder för att manipulera kataloger. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt i C++."
type: docs
weight: 1100
url: /sv/cpp/system.io/directory/
---
## Directory class


Innehåller metoder för att manipulera kataloger. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class Directory
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [CreateDirectory_](./createdirectory_/)(const String\&) | Skapar alla kataloger i den angivna sökvägen om de inte finns. |
| static [Delete](./delete/)(const String\&, bool) | Tar bort den angivna filen eller katalogen. Kastar inte undantag. |
| static [EnumerateDirectories](./enumeratedirectories/)(const String\&, const String\&, SearchOption) | Söker efter kataloger som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet som har den angivna katalogen som rot. |
| static [EnumerateFiles](./enumeratefiles/)(const String\&, const String\&, SearchOption) | Söker efter filerna som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet med rot i den angivna katalogen. |
| static [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const String\&, const String\&, SearchOption) | Söker efter filer och kataloger som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet med rot i den angivna katalogen. |
| static [Exists](./exists/)(const String\&) | Avgör om den angivna sökvägen refererar till en befintlig katalog. |
| static [GetCreationTime](./getcreationtime/)(const String\&) | Returnerar skapandetiden för den angivna enheten som lokal tid. |
| static [GetCreationTimeUtc](./getcreationtimeutc/)(const String\&) | Returnerar skapandetiden för den angivna enheten som UTC‑tid. |
| static [GetCurrentDirectory](./getcurrentdirectory/)() | Returnerar det fullständiga namnet (inklusive sökväg) för den aktuella katalogen. |
| static [GetDirectories](./getdirectories/)(const String\&, const String\&, SearchOption) | Söker efter kataloger som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet som har den angivna katalogen som rot. |
| static [GetDirectoryRoot](./getdirectoryroot/)(const String\&) | Returnerar rotkatalogen för den angivna sökvägen. |
| static [GetFiles](./getfiles/)(const String\&, const String\&, SearchOption) | Söker efter filerna som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet med rot i den angivna katalogen. |
| static [GetFileSystemEntries](./getfilesystementries/)(const String\&, const String\&, SearchOption) | Söker efter filer och kataloger som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet med rot i den angivna katalogen. |
| static [GetLastAccessTime](./getlastaccesstime/)(const String\&) | Returnerar den senaste åtkomsttiden för den angivna enheten som lokal tid. |
| static [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const String\&) | Returnerar den senaste åtkomsttiden för den angivna enheten som UTC‑tid. |
| static [GetLastWriteTime](./getlastwritetime/)(const String\&) | Returnerar den senaste skrivtiden för den angivna enheten som lokal tid. |
| static [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const String\&) | Returnerar den senaste skrivtiden för den angivna enheten som UTC‑tid. |
| static [GetLogicalDrives](./getlogicaldrives/)() | INTE IMPLEMENTERAD. |
| static [GetParent](./getparent/)(const String\&) | Returnerar en delad pekare till [DirectoryInfo](../directoryinfo/) objektet som representerar föräldrakatalogen för den angivna enheten. |
| static [Move](./move/)(const String\&, const String\&) | Flyttar den angivna enheten till den nya platsen. Om enheten som ska flyttas är en katalog, flyttas den med allt dess innehåll. |
| static [SetCreationTime](./setcreationtime/)(const String\&, DateTime) | Ställer in skapandetiden för den angivna enheten som lokal tid. |
| static [SetCreationTimeUtc](./setcreationtimeutc/)(const String\&, DateTime) | Ställer in skapandetiden för den angivna enheten som UTC-tid. |
| static [SetCurrentDirectory](./setcurrentdirectory/)(const String\&) | Ställer in den aktuella katalogen. |
| static [SetLastAccessTime](./setlastaccesstime/)(const String\&, DateTime) | Ställer in den senaste åtkomsttiden för den angivna enheten som lokal tid. |
| static [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const String\&, DateTime) | Ställer in den senaste åtkomsttiden för den angivna enheten som UTC-tid. |
| static [SetLastWriteTime](./setlastwritetime/)(const String\&, DateTime) | Ställer in den senaste skrivtiden för den angivna enheten som lokal tid. |
| static [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const String\&, DateTime) | Ställer in den senaste skrivtiden för den angivna enheten som UTC‑tid. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | Ett alias för en delad pekare till IEnumerable-objektet som enumererar en uppsättning [String](../../system/string/) objekt. |
## Anmärkningar



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
  // Skapa strängar som innehåller sökvägar till kataloger.
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // Kontrollera om kataloger finns.
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // Skriv ut information om temporärkatalogen.
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

## Se även

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
