---
title: "System::IO::Directory::EnumerateFileSystemEntries metod"
linktitle: "EnumerateFileSystemEntries"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::Directory::EnumerateFileSystemEntries metod. Söker efter filer och kataloger som uppfyller det angivna sökkriteriet antingen i den angivna katalogen eller i hela katalogträdet med den angivna katalogen som rot i C++."
type: docs
weight: 500
url: /sv/cpp/system.io/directory/enumeratefilesystementries/
---
## Directory::EnumerateFileSystemEntries method


Söker efter filer och kataloger som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet med rot i den angivna katalogen.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | const String\& | Fullständig eller relativ sökväg till katalogen att söka i |
| searchPattern | const String\& | Namnmönstret för filerna och katalogerna att söka efter |
| searchOption | SearchOption | Anger om sökningen ska utföras endast i den angivna katalogen eller i hela katalogträdet med rot i den angivna katalogen |

### ReturnValue

Den enumererbara samlingen av fullständiga sökvägar för de hittade filerna och katalogerna vars namn matchar **searchPattern**

## Se även

* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Enum [SearchOption](../../searchoption/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
