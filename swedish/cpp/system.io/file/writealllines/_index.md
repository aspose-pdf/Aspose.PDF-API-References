---
title: "System::IO::File::WriteAllLines metod"
linktitle: "WriteAllLines"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::File::WriteAllLines metod. Skapar en ny textfil eller skriver över den befintliga och skriver alla strängar från den angivna arrayen av strängar till den, varje sträng på en ny rad, med den angivna kodningen i C++."
type: docs
weight: 3600
url: /sv/cpp/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) method


Skapar en ny textfil eller skriver över den befintliga och skriver alla strängar från den angivna arrayen av strängar till den, varje sträng på en ny rad, med den angivna kodningen.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | const String\& | Filen att skapa eller skriva över |
| innehåll | const ArrayPtr\<String\>\& | En strängarray |
| encoding | const EncodingPtr\& | Teckenkodningen att använda |

## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) method


Skapar en ny textfil eller skriver över den befintliga och skriver alla strängar från den angivna enumererbara samlingen av strängar till den, varje sträng på en ny rad, med den angivna kodningen.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | const String\& | Filen att skapa eller skriva över |
| innehåll | const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\& | En enumererbar samling av strängar |
| encoding | const EncodingPtr\& | Teckenkodningen att använda |

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
