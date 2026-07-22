---
title: "System::IO::Path-klass"
linktitle: "Path"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::Path-klass. Tillhandahåller metoder för att manipulera sökvägar. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt i C++."
type: docs
weight: 1900
url: /sv/cpp/system.io/path/
---
## Path class


Tillhandahåller metoder för att manipulera sökvägar. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class Path
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [ChangeExtension](./changeextension/)(const String\&, const String\&) | Ändrar filändelsen i den angivna filsökvägen. |
| static [CheckPath](./checkpath/)(const String\&, const String\&, bool) | Avgör om den angivna sökvägen är giltig genom att kontrollera om den innehåller ogiltiga tecken. Ett undantag kastas om sökvägen innehåller ogiltiga tecken. |
| static [Combine](./combine/)(const ArrayPtr\<String\>\&) | Kombinerar de angivna sökvägssegmenten till en enda sökväg och infogar katalogseparator-tecken mellan segmenten om det behövs. |
| static [Combine](./combine/)(const String\&, const String\&) | Kombinerar två angivna sökvägssegment till en enda sökväg och infogar katalogseparator-tecken mellan segmenten om det behövs. |
| static [Combine](./combine/)(const String\&, const String\&, const String\&) | Kombinerar tre angivna sökvägssegment till en enda sökväg och infogar katalogseparator-tecken mellan segmenten om det behövs. |
| static [Combine](./combine/)(const String\&, const String\&, const String\&, const String\&) | Kombinerar fyra angivna sökvägssegment till en enda sökväg och infogar katalogseparator-tecken mellan segmenten om det behövs. |
| static [GetDirectoryName](./getdirectoryname/)(const String\&) | Returnerar namnet på katalogen som refereras av den angivna sökvägen. |
| static [GetExtension](./getextension/)(const String\&) | Returnerar filens filändelse som refereras av den angivna sökvägen. |
| static [GetFileName](./getfilename/)(const String\&) | Returnerar filens namn som refereras av den angivna sökvägen. |
| static [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const String\&) | Returnerar filens namn utan filändelse som refereras av den angivna sökvägen. |
| static [GetFullPath](./getfullpath/)(const String\&) | Konverterar den angivna sökvägen till en absolut sökväg. |
| static [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | Returnerar en array som innehåller tecken som inte är tillåtna i filnamn. |
| static [GetInvalidPathChars](./getinvalidpathchars/)() | Returnerar en array som innehåller tecken som inte är tillåtna i sökvägsnamn. |
| static [GetPathRoot](./getpathroot/)(const String\&) | Returnerar rotkatalogen för den angivna sökvägen. |
| static [GetRandomFileName](./getrandomfilename/)() | Returnerar ett slumpmässigt genererat filnamn. |
| static [GetTempFileName_](./gettempfilename_/)() | Skapar en ny fil med ett unikt namn och returnerar en fullständig sökväg till den. |
| static [GetTempFileNameSafe](./gettempfilenamesafe/)() | Skapar en ny fil med ett unikt namn och returnerar en fullständig sökväg till den. Är ett synonym till [GetTempFileName_()](./gettempfilename_/) metoden. |
| static [GetTempPath](./gettemppath/)() | Returnerar sökvägen till den aktuella användarens temporära katalog. |
| static [HasExtension](./hasextension/)(const String\&) | Avgör om den angivna sökvägen refererar till en fil med filändelse. |
| static [IsPathRooted](./ispathrooted/)(const String\&) | Avgör om den angivna sökvägen innehåller en rot. |
| static [NormalizePath](./normalizepath/)(const String\&) | Normaliserar den angivna sökvägen. |
| static [ToBoost](./toboost/)(const String\&) | Returnerar en instans av klassen boost::filesystem::path som representerar den angivna sökvägen. |
| static [ToString](./tostring/)(const boost::filesystem::path\&) | Returnerar en strängrepresentation av det angivna Boost's path-objektet. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | Ett alternativt tecken som används för att separera katalognivåer i en sökväg. |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | Ett tecken som används för att separera katalognivåer i en sökväg. |
| static [PathSeparator](./pathseparator/) | Ett avgränsartecken som används för att separera sökvägssträngar i miljövariabler. |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | Ett volymavgränsartecken. |
## Anmärkningar



```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // Generera ett slumpmässigt filnamn.
  auto filename = Path::GetRandomFileName();

  // Skriv ut information om filnamnet.
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

## Se även

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
