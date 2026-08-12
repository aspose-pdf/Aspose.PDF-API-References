---
title: "Aspose::Pdf::PasswordType enum"
linktitle: "PasswordType"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::PasswordType enum. Denna enum representerar kända lösenordstyper som används för lösenordsskyddade PDF-dokument i C++."
type: docs
weight: 25700
url: /sv/cpp/aspose.pdf/passwordtype/
---
## PasswordType enum


Denna enum representerar kända lösenordstyper som används för lösenordsskyddade pdf-dokument.

```cpp
enum class PasswordType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | 0 | [Pdf](../) dokument är inte lösenordsskyddat. |
| User | 1 | [Pdf](../) dokument öppnades med dokumentets öppningslösenord (begränsad åtkomst). |
| Owner | 2 | [Pdf](../) dokument öppnades med lösenord för att ändra behörigheter (full åtkomst). |
| Inaccessible | 3 | [Pdf](../) dokument är lösenordsskyddat men både användar- och ägarlösenorden är inte tomma och ingen av lösenorden var definierad eller angivet lösenord var felaktigt. Så det är omöjligt att avgöra vilken typ av lösenord som används. |

## Se även

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
