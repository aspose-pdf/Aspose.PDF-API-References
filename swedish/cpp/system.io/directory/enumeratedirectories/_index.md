---
title: "System::IO::Directory::EnumerateDirectories-metod"
linktitle: "EnumerateDirectories"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::Directory::EnumerateDirectories-metod. Söker efter kataloger som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet som har den angivna katalogen som rot i C++."
type: docs
weight: 300
url: /sv/cpp/system.io/directory/enumeratedirectories/
---
## Directory::EnumerateDirectories method


Söker efter kataloger som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet som har den angivna katalogen som rot.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | const String\& | Fullständig eller relativ sökväg till katalogen att söka i |
| searchPattern | const String\& | Namnmönstret för de kataloger som ska sökas efter |
| searchOption | SearchOption | Anger om sökningen ska utföras endast i den angivna katalogen eller i hela katalogträdet med rot i den angivna katalogen |

### ReturnValue

Den enumererbara samlingen av fullständiga sökvägar för de hittade katalogerna vars namn matchar **searchPattern**

## Se även

* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
