---
title: SignaturesCompromiseDetector.Check
second_title: Aspose.PDF for .NET API Reference
description: Metodo SignaturesCompromiseDetector. Controlla le firme digitali del documento per compromissione
type: docs
weight: 20
url: /it/net/aspose.pdf/signaturescompromisedetector/check/
---
## Metodo SignaturesCompromiseDetector.Check

Controlla le firme digitali del documento per compromissione.

```csharp
public bool Check(out CompromiseCheckResult compromiseCheckResult)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| compromiseCheckResult | CompromiseCheckResult& | Il risultato della verifica del documento. |

### Valore di ritorno

True, se non viene rilevata la compromissione delle firme.

## Osservazioni

L'uso di questo metodo per un documento in cui non ci sono firme digitali restituirà `True`.

### Vedi anche

* classe [CompromiseCheckResult](../../../aspose.pdf.signatures/compromisecheckresult/)
* classe [SignaturesCompromiseDetector](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)