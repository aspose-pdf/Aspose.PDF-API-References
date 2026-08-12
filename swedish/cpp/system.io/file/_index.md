---
title: "System::IO::File-klass"
linktitle: "File"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::File-klass. Tillhandahåller metoder för att manipulera filer. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt i C++."
type: docs
weight: 1300
url: /sv/cpp/system.io/file/
---
## File class


Tillhandahåller metoder för att manipulera filer. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class File
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [AppendAllLines](./appendalllines/)(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) | Lägger till strängar från den angivna samlingen av strängar till den angivna filen med den angivna kodningen genom att skriva varje sträng på en ny rad. Om den angivna filen inte finns skapas den. Filen stängs efter att alla strängar har skrivits. |
| static [AppendAllText](./appendalltext/)(const String\&, const String\&, const EncodingPtr\&) | Lägger till den angivna strängen till den angivna filen med den angivna kodningen. |
| static [AppendText](./appendtext/)(const String\&) | Skapar ett [StreamWriter](../streamwriter/)-objekt som lägger till text till den angivna filen med UTF-8-kodning. Om den angivna filen inte finns skapas den. |
| static [Copy](./copy/)(const String\&, const String\&, bool) | Kopierar den angivna filen till den angivna platsen. Om målfilen redan finns anger en parameter om den ska skrivas över. |
| static [Create](./create/)(const String\&, int32_t, FileOptions) | Skapar en ny fil (eller skriver över befintlig) och öppnar den för läs- och skrivåtkomst med angiven buffertstorlek och alternativ. |
| static [CreateText](./createtext/)(const String\&) | Skapar en ny fil eller öppnar en befintlig fil för att skriva UTF-8‑kodad text. |
| static [Decrypt](./decrypt/)(const String\&) | INTE IMPLEMENTERAD. |
| static [Delete](./delete/)(const String\&) | Tar bort den angivna filen eller katalogen. |
| static [Encrypt](./encrypt/)(const String\&) | INTE IMPLEMENTERAD. |
| static [Exists](./exists/)(const String\&) | Avgör om den angivna sökvägen refererar till en befintlig fil. |
| static [GetAttributes](./getattributes/)(const String\&) | Returnerar attributen för den angivna enheten. |
| static [GetCreationTime](./getcreationtime/)(const String\&) | Returnerar skapandetiden för den angivna enheten som lokal tid. |
| static [GetCreationTimeUtc](./getcreationtimeutc/)(const String\&) | Returnerar skapandetiden för den angivna enheten som UTC‑tid. |
| static [GetLastAccessTime](./getlastaccesstime/)(const String\&) | Returnerar den senaste åtkomsttiden för den angivna enheten som lokal tid. |
| static [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const String\&) | Returnerar den senaste åtkomsttiden för den angivna enheten som UTC‑tid. |
| static [GetLastWriteTime](./getlastwritetime/)(const String\&) | Returnerar den senaste skrivtiden för den angivna enheten som lokal tid. |
| static [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const String\&) | Returnerar den senaste skrivtiden för den angivna enheten som UTC‑tid. |
| static [Move](./move/)(const String\&, const String\&) | Flyttar den angivna filen till den nya platsen. |
| static [Open](./open/)(const String\&, FileMode) | Öppnar den angivna filen i det angivna läget för läsning och skrivning utan delning. |
| static [Open](./open/)(const String\&, FileMode, FileAccess, FileShare) | Öppnar den angivna filen i det angivna läget, med den angivna åtkomsttypen och delningsalternativet. |
| static [OpenRead](./openread/)(const String\&) | Öppnar den angivna filen endast för läsning, i 'Open'-läge med delad åtkomst för läsning. |
| static [OpenText](./opentext/)(const String\&, const EncodingPtr\&) | Öppnar den angivna befintliga filen för att läsa text med UTF-8‑kodning utan delning. |
| static [OpenWrite](./openwrite/)(const String\&) | Öppnar den angivna filen endast för skrivning, i 'OpenOrCreate'-läge utan delning. |
| static [ReadAllBytes](./readallbytes/)(const String\&) | Läser innehållet i den angivna binära filen till en bytearray. |
| static [ReadAllLines](./readalllines/)(const String\&, const EncodingPtr\&) | Läser innehållet i den angivna textfilen rad för rad till en array av strängar med den angivna teckenkodningen. |
| static [ReadAllText](./readalltext/)(const String\&, const EncodingPtr\&) | Läser innehållet i den angivna textfilen till ett enda [String](../../system/string/)‑objekt med den angivna teckenkodningen. |
| static [ReadLines](./readlines/)(const String\&, const EncodingPtr\&) | Läser innehållet i den angivna textfilen rad för rad med den angivna teckenkodningen och returnerar en enumererbar samling av strängar där varje sträng representerar en enskild rad i filens innehåll. |
| static [Replace](./replace/)(const String\&, const String\&, const String\&, bool) | Ersätter innehållet i en fil med en annan och skapar en säkerhetskopia av den ersatta filen. |
| static [SetAttributes](./setattributes/)(const String\&, FileAttributes) | Ställer in de angivna attributen på den angivna filen. |
| static [SetCreationTime](./setcreationtime/)(const String\&, DateTime) | INTE IMPLEMENTERAD. |
| static [SetCreationTimeUtc](./setcreationtimeutc/)(const String\&, DateTime) | INTE IMPLEMENTERAD. |
| static [SetLastAccessTime](./setlastaccesstime/)(const String\&, DateTime) | INTE IMPLEMENTERAD. |
| static [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const String\&, DateTime) | INTE IMPLEMENTERAD. |
| static [SetLastWriteTime](./setlastwritetime/)(const String\&, DateTime) | Ställer in den senaste skrivtiden för den angivna enheten som lokal tid. |
| static [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const String\&, DateTime) | Ställer in den senaste skrivtiden för den angivna enheten som UTC‑tid. |
| static [WriteAllBytes](./writeallbytes/)(const String\&, const ArrayPtr\<uint8_t\>\&) | Skriver över den angivna binära filen och skriver de angivna byten till den. |
| static [WriteAllLines](./writealllines/)(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) | Skapar en ny textfil eller skriver över den befintliga och skriver alla strängar från den angivna enumererbara samlingen av strängar till den, varje sträng på en ny rad, med den angivna kodningen. |
| static [WriteAllLines](./writealllines/)(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) | Skapar en ny textfil eller skriver över den befintliga och skriver alla strängar från den angivna arrayen av strängar till den, varje sträng på en ny rad, med den angivna kodningen. |
| static [WriteAllText](./writealltext/)(const String\&, const String\&, const EncodingPtr\&) | Skapar en ny textfil eller skriver över den befintliga och skriver innehållet i den angivna strängen till den med den angivna kodningen. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | Standardvärde för antalet byte som buffras under läsning från och skrivning till en fil. |
## Se även

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
