---
title: "System::IO::File::ReadAllLines metod"
linktitle: "ReadAllLines"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::File::ReadAllLines metod. Läser innehållet i den angivna textfilen rad för rad till en array av strängar med den angivna teckenkodningen i C++."
type: docs
weight: 2400
url: /sv/cpp/system.io/file/readalllines/
---
## File::ReadAllLines method


Läser innehållet i den angivna textfilen rad för rad till en array av strängar med den angivna teckenkodningen.

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | const String\& | Sökvägen till filen som ska läsas |
| encoding | const EncodingPtr\& | Teckenkodningen att använda |

### ReturnValue

En strängarray där varje element representerar en enskild rad från den angivna filen

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
