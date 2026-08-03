---
title: "Enum ValidationMode"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Security.ValidationMode enum. Anger valideringsläget för PDF-signaturvalideringsprocesser"
type: docs
weight: 10240
url: /sv/net/aspose.pdf.security/validationmode/
---
## ValidationMode enumeration

Specificerar valideringsläget för PDF-signaturvalideringsprocesser.

```csharp
public enum ValidationMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | `0` | Representerar ett läge där validering inte utförs. |
| OnlyCheck | `1` | Representerar läget där valideringen utförs, men dess resultat påverkar inte valideringen av den digitala signaturen. Du kan kontrollera valideringsresultatet själv. |
| Strict | `2` | Representerar läget där valideringen utförs och dess resultat påverkar valideringen av den digitala signaturen. Om certifikatet inte kunde verifieras kommer den digitala signaturen att betraktas som ogiltig. Du kan kontrollera valideringsresultatet själv. |

### Se även

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


