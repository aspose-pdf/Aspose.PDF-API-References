---
title: Enum PasswordType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PasswordType-Enum. Dieses Enum repräsentiert bekannte Passworttypen, die für passwortgeschützte PDF-Dokumente verwendet werden.
type: docs
weight: 8290
url: /de/net/aspose.pdf/passwordtype/
---
## PasswordType-Enumeration

Dieses Enum repräsentiert bekannte Passworttypen, die für passwortgeschützte PDF-Dokumente verwendet werden.

```csharp
public enum PasswordType
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | `0` | PDF-Dokument ist nicht passwortgeschützt. |
| User | `1` | PDF-Dokument wurde mit dem Dokumentenöffnungs-Passwort (eingeschränkter Zugriff) geöffnet. |
| Owner | `2` | PDF-Dokument wurde mit dem Passwort für Berechtigungsänderungen (voller Zugriff) geöffnet. |
| Inaccessible | `3` | PDF-Dokument ist passwortgeschützt, aber sowohl Benutzer- als auch Eigentümerpasswörter sind nicht leer und keines der Passwörter wurde definiert oder das angegebene Passwort war falsch. Daher ist es unmöglich, den Typ des Passworts abzuleiten. |

### Siehe auch

* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)