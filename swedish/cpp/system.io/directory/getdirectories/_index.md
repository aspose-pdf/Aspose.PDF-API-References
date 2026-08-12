---
title: "System::IO::Directory::GetDirectories metod"
linktitle: "GetDirectories"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::Directory::GetDirectories metod. Söker efter kataloger som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet med rot i den angivna katalogen i C++."
type: docs
weight: 1000
url: /sv/cpp/system.io/directory/getdirectories/
---
## Directory::GetDirectories method


Söker efter kataloger som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet som har den angivna katalogen som rot.

```cpp
static ArrayPtr<String> System::IO::Directory::GetDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | const String\& | Fullständig eller relativ sökväg till katalogen att söka i |
| searchPattern | const String\& | Namnmönstret för de kataloger som ska sökas efter |
| searchOption | SearchOption | Anger om sökningen ska utföras endast i den angivna katalogen eller i hela katalogträdet med rot i den angivna katalogen |

### ReturnValue

En array av fullständiga sökvägar till de hittade katalogerna vars namn matchar **searchPattern**

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
