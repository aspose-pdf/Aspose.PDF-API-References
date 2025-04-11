---
title: Enum PasswordType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PasswordType enum. Denna enum representerar kända typ av lösenord som används för lösenordsskyddade pdf-dokument
type: docs
weight: 8290
url: /sv/net/aspose.pdf/passwordtype/
---
## PasswordType-uppräkning

Denna enum representerar kända typ av lösenord som används för lösenordsskyddade pdf-dokument.

```csharp
public enum PasswordType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Ingen | `0` | Pdf-dokumentet är inte lösenordsskyddat. |
| Användare | `1` | Pdf-dokumentet öppnades med hjälp av dokumentöppningslösenord (begränsad åtkomst). |
| Ägare | `2` | Pdf-dokumentet öppnades med hjälp av lösenord för att ändra behörigheter (full åtkomst). |
| Otillgänglig | `3` | Pdf-dokumentet är lösenordsskyddat men både användar- och ägarlösenord är inte tomma och inget av lösenorden var definierat eller det angivna lösenordet var felaktigt. Så det är omöjligt att härleda typen av lösenordet. |

### Se Även

* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* samling [Aspose.PDF](../../)