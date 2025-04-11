---
title: SignaturesCompromiseDetector.Check
second_title: Aspose.PDF for .NET API Reference
description: SignaturesCompromiseDetector-Methode. Überprüfen Sie die digitalen Signaturen des Dokuments auf Kompromittierung
type: docs
weight: 20
url: /de/net/aspose.pdf/signaturescompromisedetector/check/
---
## SignaturesCompromiseDetector.Check-Methode

Überprüfen Sie die digitalen Signaturen des Dokuments auf Kompromittierung.

```csharp
public bool Check(out CompromiseCheckResult compromiseCheckResult)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| compromiseCheckResult | CompromiseCheckResult& | Das Ergebnis der Überprüfung des Dokuments. |

### Rückgabewert

Wahr, wenn die Kompromittierung der Signaturen nicht festgestellt wird.

## Anmerkungen

Die Verwendung dieser Methode für ein Dokument, in dem keine digitalen Signaturen vorhanden sind, gibt `True` zurück.

### Siehe auch

* Klasse [CompromiseCheckResult](../../../aspose.pdf.signatures/compromisecheckresult/)
* Klasse [SignaturesCompromiseDetector](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)