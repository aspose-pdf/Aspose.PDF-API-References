---
title: "System::IO::FileOptions enum"
linktitle: "FileOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::FileOptions enum. Representerar avancerade alternativ för att skapa FileStream‑objekt i C++."
type: docs
weight: 3200
url: /sv/cpp/system.io/fileoptions/
---
## FileOptions enum


Representerar avancerade alternativ för att skapa [FileStream](../filestream/) objekt.

```cpp
enum class FileOptions
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Ingen | 0 | Inga ytterligare alternativ. |
| Encrypted | 16384 | Filen är krypterad. INTE IMPLEMENTERAD. |
| DeleteOnClose | 67108864 | Filen bör automatiskt tas bort när den inte längre är i bruk. |
| SequentialScan | 134217728 | Filen bör nås sekventiellt. |
| RandomAccess | 268435456 | Filen nås slumpmässigt. |
| Asynchronous | 1073741824 | Filen kan användas för asynkrona I/O‑operationer. |
| WriteThrough | n/a | Alla skrivningar bör gå direkt till disken och kringgå eventuell mellanlagring. |

## Se även

* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
