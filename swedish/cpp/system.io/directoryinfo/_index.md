---
title: "System::IO::DirectoryInfo‑klass"
linktitle: "DirectoryInfo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::DirectoryInfo‑klass. Representerar en filsökväg, en katalog som refereras till av denna sökväg och tillhandahåller instansmetoder för att manipulera kataloger. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1200
url: /sv/cpp/system.io/directoryinfo/
---
## DirectoryInfo class


Representerar en filsökväg, en katalog som refereras till av denna sökväg och tillhandahåller instansmetoder för att manipulera kataloger. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i pekaren [System::SmartPtr](../../system/smartptr/) och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class DirectoryInfo : public System::IO::FileSystemInfo
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Create](./create/)() | Skapar en katalog på den sökväg som representeras av det aktuella objektet. |
| [CreateSubdirectory](./createsubdirectory/)(const String\&) | Skapar underkataloger på den angivna sökvägen. |
| [Delete](./delete/)() override | Tar bort katalogen som refereras till av den sökväg som representeras av det aktuella objektet om katalogen är tom. |
| [Delete](./delete/)(bool) | Tar bort katalogen som refereras till av den sökväg som representeras av det aktuella objektet. En parameter anger om katalogens innehåll ska tas bort rekursivt om katalogen inte är tom. |
| [DirectoryInfo](./directoryinfo/)(const String\&) | Skapar en instans av [DirectoryInfo](./)-klassen på den angivna sökvägen. |
| [EnumerateDirectories](./enumeratedirectories/)() | Returnerar en enumererbar samling som innehåller alla kataloger som finns i katalogen som representeras av det aktuella objektet. |
| [EnumerateDirectories](./enumeratedirectories/)(const String\&) | Söker efter katalogerna som uppfyller de angivna sökkriterierna i katalogen som representeras av det aktuella objektet. |
| [EnumerateDirectories](./enumeratedirectories/)(const String\&, SearchOption) | Söker efter katalogerna som uppfyller de angivna sökkriterierna antingen i katalogen som representeras av det aktuella objektet eller i hela katalogträdet som har sin rot i katalogen som representeras av det aktuella objektet. |
| [EnumerateFiles](./enumeratefiles/)() | Returnerar en enumererbar samling som innehåller alla filer som finns i katalogen som representeras av det aktuella objektet. |
| [EnumerateFiles](./enumeratefiles/)(const String\&) | Söker efter filerna som uppfyller de angivna sökkriterierna i katalogen som representeras av det aktuella objektet. |
| [EnumerateFiles](./enumeratefiles/)(const String\&, SearchOption) | Söker efter filerna som uppfyller de angivna sökkriterierna antingen i katalogen som representeras av det aktuella objektet eller i hela katalogträdet som har sin rot i katalogen som representeras av det aktuella objektet. |
| [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)() | Returnerar en enumererbar samling som innehåller alla filer och kataloger som finns i katalogen som representeras av det aktuella objektet. |
| [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const String\&) | Söker efter filer och kataloger som uppfyller de angivna sökkriterierna i katalogen som representeras av det aktuella objektet. |
| [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const String\&, SearchOption) | Söker efter filer och kataloger som uppfyller de angivna sökkriterierna antingen i katalogen som representeras av det aktuella objektet eller i hela katalogträdet som har sin rot i katalogen som representeras av det aktuella objektet. |
| [get_Exists](./get_exists/)() override | Avgör om sökvägen som representeras av det aktuella objektet hänvisar till en befintlig katalog. |
| [get_Name](./get_name/)() override | Returnerar namnet på den entitet som sökvägen som representeras av det aktuella objektet hänvisar till. |
| [get_Parent](./get_parent/)() | Returnerar en delad pekare till [DirectoryInfo](./)-objektet som representerar en sökväg som pekar på föräldrakatalogen till katalogen som representeras av det aktuella objektet. |
| [get_Root](./get_root/)() | Returnerar en delad pekare till [DirectoryInfo](./)-objektet som representerar en sökväg som pekar på rotkatalogen för katalogen som representeras av det aktuella objektet. |
| [GetDirectories](./getdirectories/)() | Returnerar en array som innehåller delade pekare till [DirectoryInfo](./)-objekt som representerar alla kataloger som finns i katalogen som representeras av det aktuella objektet. |
| [GetDirectories](./getdirectories/)(const String\&) | Söker efter katalogerna som uppfyller de angivna sökkriterierna i katalogen som representeras av det aktuella objektet. |
| [GetDirectories](./getdirectories/)(const String\&, SearchOption) | Söker efter katalogerna som uppfyller de angivna sökkriterierna antingen i katalogen som representeras av det aktuella objektet eller i hela katalogträdet som har sin rot i katalogen som representeras av det aktuella objektet. |
| [GetFiles](./getfiles/)() | Returnerar en array som innehåller delade pekare till [FileInfo](../fileinfo/)-objekt som representerar alla kataloger som finns i katalogen som representeras av det aktuella objektet. |
| [GetFiles](./getfiles/)(const String\&) | Söker efter filerna som uppfyller de angivna sökkriterierna i katalogen som representeras av det aktuella objektet. |
| [GetFiles](./getfiles/)(const String\&, SearchOption) | Söker efter filerna som uppfyller de angivna sökkriterierna antingen i katalogen som representeras av det aktuella objektet eller i hela katalogträdet som har sin rot i katalogen som representeras av det aktuella objektet. |
| [GetFileSystemInfos](./getfilesysteminfos/)() | Returnerar en array som innehåller delade pekare till [FileSystemInfo](../filesysteminfo/)-objekt som representerar alla filer och kataloger som finns i katalogen som representeras av det aktuella objektet. |
| [GetFileSystemInfos](./getfilesysteminfos/)(const String\&) | Söker efter filer och kataloger som uppfyller de angivna sökkriterierna i katalogen som representeras av det aktuella objektet. |
| [GetFileSystemInfos](./getfilesysteminfos/)(const String\&, SearchOption) | Söker efter filer och kataloger som uppfyller de angivna sökkriterierna antingen i katalogen som representeras av det aktuella objektet eller i hela katalogträdet som har sin rot i katalogen som representeras av det aktuella objektet. |
| [MoveTo](./moveto/)(const String\&) | Flyttar katalogen som representeras av det aktuella objektet och allt dess innehåll till den angivna platsen. |
| [ToString](./tostring/)() const override | Returnerar en sträng som innehåller sökvägen som representeras av det aktuella objektet. |
## Se även

* Class [FileSystemInfo](../filesysteminfo/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
