---
title: "System::IO::FileSystemInfo klass"
linktitle: "FileSystemInfo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::FileSystemInfo klass. Basklassen för FileInfo och DirectoryInfo. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1600
url: /sv/cpp/system.io/filesysteminfo/
---
## FileSystemInfo class


Basklassen för [FileInfo](../fileinfo/) och [DirectoryInfo](../directoryinfo/). Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class FileSystemInfo : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Delete](./delete/)() | Tar bort enheten som representeras av det aktuella objektet. |
| virtual [Finalize](./finalize/)() | Gör ingenting. |
| [get_Attributes](./get_attributes/)() | Returnerar attributen för enheten som representeras av det aktuella objektet. |
| [get_CreationTime](./get_creationtime/)() | Returnerar skapandetiden för enheten som representeras av det aktuella objektet som lokal tid. |
| [get_CreationTimeUtc](./get_creationtimeutc/)() | Returnerar skapandetiden för enheten som representeras av det aktuella objektet som UTC-tid. |
| virtual [get_Exists](./get_exists/)() | Avgör om enheten som refereras av sökvägen som representeras av det aktuella objektet finns. |
| [get_Extension](./get_extension/)() | Returnerar filändelsen för filen som representeras av det aktuella objektet. |
| virtual [get_FullName](./get_fullname/)() | Returnerar det fullständiga namnet (inklusive sökväg) för enheten som representeras av det aktuella objektet. |
| [get_LastAccessTime](./get_lastaccesstime/)() | Returnerar den senaste åtkomsttiden för enheten som representeras av det aktuella objektet som lokal tid. |
| [get_LastAccessTimeUtc](./get_lastaccesstimeutc/)() | Returnerar den senaste åtkomsttiden för enheten som representeras av det aktuella objektet som UTC-tid. |
| [get_LastWriteTime](./get_lastwritetime/)() | Returnerar den senaste skrivtiden för enheten som representeras av det aktuella objektet som lokal tid. |
| [get_LastWriteTimeUtc](./get_lastwritetimeutc/)() | Returnerar den senaste skrivtiden för enheten som representeras av det aktuella objektet som UTC-tid. |
| virtual [get_Name](./get_name/)() | Returnerar ett namn på enheten som representeras av det aktuella objektet. |
| [Refresh](./refresh/)() | Uppdaterar tillståndet för det aktuella objektet. |
| [set_Attributes](./set_attributes/)(FileAttributes) | Ställer in de angivna attributen på enheten som representeras av det aktuella objektet. |
| [set_CreationTime](./set_creationtime/)(DateTime) | Ställer in skapandetiden för enheten som representeras av det aktuella objektet som lokal tid. |
| [set_CreationTimeUtc](./set_creationtimeutc/)(DateTime) | Ställer in skapandetiden för enheten som representeras av det aktuella objektet som UTC-tid. |
| [set_LastAccessTime](./set_lastaccesstime/)(DateTime) | Ställer in den senaste åtkomsttiden för enheten som representeras av det aktuella objektet som lokal tid. |
| [set_LastAccessTimeUtc](./set_lastaccesstimeutc/)(DateTime) | Ställer in den senaste åtkomsttiden för enheten som representeras av det aktuella objektet som UTC-tid. |
| [set_LastWriteTime](./set_lastwritetime/)(DateTime) | Ställer in den senaste skrivtiden för enheten som representeras av det aktuella objektet som lokal tid. |
| [set_LastWriteTimeUtc](./set_lastwritetimeutc/)(DateTime) | Ställer in den senaste skrivtiden för enheten som representeras av det aktuella objektet som UTC-tid. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
