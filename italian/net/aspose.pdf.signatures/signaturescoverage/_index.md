---
title: Enum SignaturesCoverage
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Signatures.SignaturesCoverage enum. Represents enum for the level of coverage provided by digital signatures in a document
type: docs
weight: 10110
url: /it/net/aspose.pdf.signatures/signaturescoverage/
---
## Enumerazione SignaturesCoverage

Rappresenta l'enum per il livello di copertura fornito dalle firme digitali in un documento.

```csharp
public enum SignaturesCoverage
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Undefined | `0` | Indica che lo stato della copertura delle firme digitali nel documento è indefinito. Questo valore è tipicamente utilizzato quando una o più firme nel documento sono compromesse o non possono essere verificate, impedendo una valutazione definitiva della copertura delle firme del documento. |
| EntirelySigned | `1` | Indica che il documento è completamente coperto da firme digitali. Questo valore significa che tutte le parti richieste del documento sono state firmate e nessuna firma è compromessa. |
| PartiallySigned | `2` | Indica che il documento è parzialmente firmato, il che significa che alcune, ma non tutte, delle sue parti sono coperte da firme digitali. Questo valore è utilizzato quando alcune parti del documento rimangono non firmate o sono escluse dalla copertura delle firme. |

### Vedi Anche

* namespace [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* assembly [Aspose.PDF](../../)