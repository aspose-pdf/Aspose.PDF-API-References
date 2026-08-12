---
title: "System::IO::Path::CheckPath-metod"
linktitle: "CheckPath"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::Path::CheckPath-metod. Avgör om den angivna sökvägen är giltig genom att kontrollera om den innehåller ogiltiga tecken. Ett undantag kastas om sökvägen innehåller ogiltiga tecken i C++."
type: docs
weight: 200
url: /sv/cpp/system.io/path/checkpath/
---
## Path::CheckPath method


Avgör om den angivna sökvägen är giltig genom att kontrollera om den innehåller ogiltiga tecken. Ett undantag kastas om sökvägen innehåller ogiltiga tecken.

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=true)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | const String\& | Sökvägen att kontrollera |
| msg | const String\& | Meddelandet som ska skickas till undantagsobjektets konstruktor |
| allow_empty | bool | Anger om en tom eller null-sträng ska betraktas som en korrekt sökväg (true) eller inte (false); om detta parameter är false och **path** är tomt kastas ett ArgumentException; om detta parameter är false och **path** är null kastas ett ArgumentNullException. |

## Se även

* Class [String](../../../system/string/)
* Class [Path](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
