---
title: "System::IO::FileInfo‑klass"
linktitle: "FileInfo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::FileInfo‑klass. Representerar en sökväg till en fil och den fil som refereras av denna sökväg samt tillhandahåller metoder för att manipulera den. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1400
url: /sv/cpp/system.io/fileinfo/
---
## FileInfo class


Representerar en sökväg till en fil och den fil som refereras av denna sökväg samt tillhandahåller metoder för att manipulera den. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AppendText](./appendtext/)() | Öppnar en fil som representeras av det aktuella objektet för att skriva text med UTF‑8‑kodning, i 'Append'-läge utan delning. |
| [CopyTo](./copyto/)(const String\&) | Kopierar filen som representeras av det aktuella objektet till den angivna platsen. Om målfilen redan finns, misslyckas kopieringen. |
| [CopyTo](./copyto/)(const String\&, bool) | Kopierar filen som representeras av det aktuella objektet till den angivna platsen. En parameter anger om befintlig målfil ska skrivas över. |
| [Create](./create/)() | Skapar en fil på den plats som anges av sökvägen som representeras av det aktuella objektet och öppnar den för läsning och skrivning, i trunkeringsläge utan delning. |
| [CreateText](./createtext/)() | Skapar en fil på den plats som anges av sökvägen som representeras av det aktuella objektet och öppnar den för att skriva text med UTF‑8‑kodning utan delning. |
| [Decrypt](./decrypt/)() | INTE IMPLEMENTERAD. |
| [Delete](./delete/)() override | Tar bort filen som representeras av det aktuella objektet. |
| [Encrypt](./encrypt/)() | INTE IMPLEMENTERAD. |
| [FileInfo](./fileinfo/)(const String\&) | Skapar en ny instans av klassen [FileInfo](./) som representerar den angivna filen. |
| [get_Directory](./get_directory/)() | Returnerar ett [DirectoryInfo](../directoryinfo/)‑objekt som representerar en katalog där filen som representeras av det aktuella objektet finns. |
| [get_DirectoryName](./get_directoryname/)() | Returnerar det fullständiga namnet på katalogen där filen som representeras av det aktuella objektet är placerad. |
| [get_Exists](./get_exists/)() override | Returnerar ett värde som indikerar om filen finns. |
| [get_IsReadOnly](./get_isreadonly/)() | Returnerar ett värde som indikerar om attributet ReadOnly är satt. |
| [get_Length](./get_length/)() | Returnerar filens storlek i byte. |
| [get_Name](./get_name/)() override | Returnerar filens namn. |
| [MoveTo](./moveto/)(const String\&) | Flyttar filen som representeras av det aktuella objektet till den angivna platsen. |
| [Open](./open/)(FileMode) | Öppnar filen som representeras av det aktuella objektet i det angivna läget för läsning och skrivning utan delning. |
| [Open](./open/)(FileMode, FileAccess) | Öppnar filen som representeras av det aktuella objektet i det angivna läget, med den angivna åtkomsttypen och utan delning. |
| [Open](./open/)(FileMode, FileAccess, FileShare) | Öppnar filen som representeras av det aktuella objektet i det angivna läget, med den angivna åtkomsttypen och delningsalternativet. |
| [OpenRead](./openread/)() | Öppnar en fil som representeras av det aktuella objektet enbart för läsning, i läget 'Open' med delad åtkomst för läsning. |
| [OpenText](./opentext/)() | Öppnar den befintliga filen på den plats som anges av sökvägen som representeras av det aktuella objektet för att läsa text med UTF-8‑kodning utan delning. |
| [OpenWrite](./openwrite/)() | Öppnar en fil som representeras av det aktuella objektet enbart för skrivning, i läget 'OpenOrCreate' utan delning. |
| [Replace](./replace/)(const String\&, const String\&) | Ersätter innehållet i en angiven destinationsfil med filen som representeras av det aktuella [FileInfo](./)-objektet och skapar en säkerhetskopia av den ersatta filen. |
| [Replace](./replace/)(const String\&, const String\&, bool) | Ersätter innehållet i en angiven destinationsfil med filen som representeras av det aktuella [FileInfo](./)-objektet och skapar en säkerhetskopia av den ersatta filen. |
| [set_IsReadOnly](./set_isreadonly/)(bool) | Sätter eller tar bort attributet ReadOnly på filen. |
| [ToString](./tostring/)() const override | Returnerar en sökväg som representeras av det aktuella objektet. |
## Se även

* Class [FileSystemInfo](../filesysteminfo/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
