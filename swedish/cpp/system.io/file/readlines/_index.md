---
title: "System::IO::File::ReadLines metod"
linktitle: "ReadLines"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::File::ReadLines metod. Läser innehållet i den angivna textfilen rad för rad med den angivna teckenkodningen och returnerar en enumererbar samling av strängar där varje sträng representerar en enskild rad i filens innehåll i C++."
type: docs
weight: 2600
url: /sv/cpp/system.io/file/readlines/
---
## File::ReadLines method


Läser innehållet i den angivna textfilen rad för rad med den angivna teckenkodningen och returnerar en enumererbar samling av strängar där varje sträng representerar en enskild rad i filens innehåll.

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | const String\& | Sökvägen till filen som ska läsas |
| encoding | const EncodingPtr\& | Teckenkodningen att använda |

### ReturnValue

En enumererbar samling av strängar som representerar innehållet i den angivna filen

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
