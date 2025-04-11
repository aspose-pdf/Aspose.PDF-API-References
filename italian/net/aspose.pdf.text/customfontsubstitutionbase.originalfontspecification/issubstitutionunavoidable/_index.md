---
title: CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable
second_title: Aspose.PDF for .NET API Reference
description: Proprietà OriginalFontSpecification. Ottiene un valore che indica che la sostituzione è inevitabile
type: docs
weight: 20
url: /it/net/aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/issubstitutionunavoidable/
---
## Proprietà CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable

Ottiene un valore che indica che la sostituzione è inevitabile.

```csharp
public bool IsSubstitutionUnavoidable { get; }
```

## Osservazioni

Restituisce true nel caso in cui la sostituzione sia stata richiesta a causa dell'assenza del font originale o nel caso in cui il font originale non possa essere utilizzato nel contesto di un determinato compito. Nel caso in cui l'utente ignori il flag e non sostituisca il font, viene eseguita la procedura di sostituzione del font predefinito. Ma offre all'utente l'opportunità di alternare la procedura di sostituzione del font standard e impostare un font migliore per il sistema. Restituisce false nel caso in cui il font originale sia presente, valido, ma è consentito all'utente sostituirlo.

### Vedi Anche

* classe [OriginalFontSpecification](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)