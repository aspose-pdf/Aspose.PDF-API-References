---
title: "System::IO::Directory::GetFiles-metod"
linktitle: "GetFiles"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::Directory::GetFiles-metod. Söker efter filer som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet som har den angivna katalogen som rot i C++."
type: docs
weight: 1200
url: /sv/cpp/system.io/directory/getfiles/
---
## Directory::GetFiles method


Söker efter filerna som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet med rot i den angivna katalogen.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | const String\& | Fullständig eller relativ sökväg till katalogen att söka i |
| searchPattern | const String\& | Namnmönstret för de filer som ska sökas efter |
| searchOption | SearchOption | Anger om sökningen ska utföras endast i den angivna katalogen eller i hela katalogträdet med rot i den angivna katalogen |

### ReturnValue

En array av fullständiga sökvägar för de hittade filerna vars namn matchar **searchPattern**

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
