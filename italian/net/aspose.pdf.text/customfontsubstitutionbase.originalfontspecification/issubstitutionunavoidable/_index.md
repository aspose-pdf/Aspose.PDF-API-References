---
title: "CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "OriginalFontSpecification proprietà. Restituisce un valore che indica che la sostituzione è inevitabile"
type: docs
weight: 20
url: /it/net/aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/issubstitutionunavoidable/
---
## CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable property

Restituisce un valore che indica che la sostituzione è inevitabile.

```csharp
public bool IsSubstitutionUnavoidable { get; }
```

## Osservazioni

Restituisce true se la sostituzione è stata richiesta a causa dell'assenza del font originale o nel caso in cui il font originale non possa essere utilizzato nel contesto di qualche attività. Nel caso l'utente ignori il flag e non sostituisca il font - viene eseguita la procedura di sostituzione del font predefinita. Tuttavia fornisce la possibilità all'utente di alternare la procedura standard di sostituzione del font e impostare un font migliore nel sistema. Restituisce false se il font originale è presente, valido, ma è consentito all'utente sostituirlo.

### Vedi anche

* class [OriginalFontSpecification](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


