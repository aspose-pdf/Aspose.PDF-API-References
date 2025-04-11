---
title: SignaturesCompromiseDetector.Check
second_title: Aspose.PDF for .NET API Reference
description: SignaturesCompromiseDetector metod. Kontrollera de digitala signaturerna av dokumentet för kompromiss
type: docs
weight: 20
url: /sv/net/aspose.pdf/signaturescompromisedetector/check/
---
## SignaturesCompromiseDetector.Check metod

Kontrollera de digitala signaturerna av dokumentet för kompromiss.

```csharp
public bool Check(out CompromiseCheckResult compromiseCheckResult)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| compromiseCheckResult | CompromiseCheckResult& | Resultatet av verifieringen av dokumentet. |

### Returvärde

Sant, om kompromissen av signaturerna inte upptäcktes.

## Kommentarer

Användningen av denna metod för ett dokument där det inte finns några digitala signaturer kommer att returnera `True`.

### Se Även

* klass [CompromiseCheckResult](../../../aspose.pdf.signatures/compromisecheckresult/)
* klass [SignaturesCompromiseDetector](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)