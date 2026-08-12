---
title: "Aspose::Pdf::Security::ValidationMode enum"
linktitle: "ValidationMode"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Security::ValidationMode enum. Anger valideringsläget för PDF‑signaturvalideringsprocesser i C++."
type: docs
weight: 1800
url: /sv/cpp/aspose.pdf.security/validationmode/
---
## ValidationMode enum


Specificerar valideringsläget för PDF-signaturvalideringsprocesser.

```cpp
enum class ValidationMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Ingen | 0 | Representerar ett läge där validering inte utförs. |
| OnlyCheck | 1 | Representerar läget där valideringen utförs, men dess resultat påverkar inte valideringen av den digitala signaturen. Du kan själv kontrollera valideringsresultatet. |
| Strict | 2 | Representerar läget där valideringen utförs och dess resultat påverkar valideringen av den digitala signaturen. Om certifikatet inte kunde verifieras kommer den digitala signaturen att betraktas som ogiltig. Du kan själv kontrollera valideringsresultatet. |

## Se även

* Namespace [Aspose::Pdf::Security](../)
* Library [Aspose.PDF for C++](../../)
