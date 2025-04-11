---
title: Enum SignaturesCoverage
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Signatures.SignaturesCoverage enum. Stellt das Enum für das Niveau der Abdeckung dar, das durch digitale Signaturen in einem Dokument bereitgestellt wird
type: docs
weight: 10110
url: /de/net/aspose.pdf.signatures/signaturescoverage/
---
## SignaturesCoverage Enumeration

Stellt das Enum für das Niveau der Abdeckung dar, das durch digitale Signaturen in einem Dokument bereitgestellt wird.

```csharp
public enum SignaturesCoverage
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Undefined | `0` | Gibt an, dass der Zustand der Abdeckung digitaler Signaturen im Dokument undefiniert ist. Dieser Wert wird typischerweise verwendet, wenn eine oder mehrere Signaturen im Dokument kompromittiert sind oder nicht verifiziert werden können, was eine definitive Bewertung der Signaturabdeckung des Dokuments verhindert. |
| EntirelySigned | `1` | Gibt an, dass das Dokument vollständig durch digitale Signaturen abgedeckt ist. Dieser Wert bedeutet, dass alle erforderlichen Teile des Dokuments signiert wurden und keine Signaturen kompromittiert sind. |
| PartiallySigned | `2` | Gibt an, dass das Dokument teilweise signiert ist, was bedeutet, dass einige, aber nicht alle, Inhalte durch digitale Signaturen abgedeckt sind. Dieser Wert wird verwendet, wenn bestimmte Teile des Dokuments nicht signiert sind oder von der Signaturabdeckung ausgeschlossen sind. |

### Siehe auch

* namespace [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* assembly [Aspose.PDF](../../)