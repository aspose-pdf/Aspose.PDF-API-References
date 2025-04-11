---
title: Enum ValidationMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.ValidationMode enum. Anger valideringsläget för PDF-signaturvalideringsprocesser
type: docs
weight: 10060
url: /sv/net/aspose.pdf.security/validationmode/
---
## ValidationMode-uppräkning

Anger valideringsläget för PDF-signaturvalideringsprocesser.

```csharp
public enum ValidationMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | `0` | Representerar ett läge där validering inte utförs. |
| OnlyCheck | `1` | Representerar läget där validering görs, men dess resultat påverkar inte valideringen av den digitala signaturen. Du kan kontrollera resultatet av valideringen själv. |
| Strict | `2` | Representerar läget där validering görs och dess resultat påverkar valideringen av den digitala signaturen. Om certifikatet inte kunde verifieras, kommer den digitala signaturen att anses vara ogiltig. Du kan kontrollera resultatet av valideringen själv. |

### Se Även

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)