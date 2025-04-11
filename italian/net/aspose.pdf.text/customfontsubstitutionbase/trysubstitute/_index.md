---
title: CustomFontSubstitutionBase.TrySubstitute
second_title: Aspose.PDF for .NET API Reference
description: Metodo CustomFontSubstitutionBase. Sostituisce il font originale con un altro font
type: docs
weight: 20
url: /it/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## Metodo CustomFontSubstitutionBase.TrySubstitute

Sostituisce il font originale con un altro font.

```csharp
public virtual bool TrySubstitute(OriginalFontSpecification originalFontSpecification, 
    out Font substitutionFont)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| originalFontSpecification | OriginalFontSpecification | Specifica del font originale. |
| substitutionFont | Font& | Font di sostituzione. |

### Valore di Ritorno

True nel caso in cui la sostituzione sia avvenuta con successo.

## Osservazioni

La classe CustomFontSubstitutionBase dovrebbe essere ereditata per implementare la logica di sostituzione del font personalizzato. Il metodo TrySubstitute dovrebbe essere sovrascritto correttamente: deve restituire true nel caso in cui sia necessaria la sostituzione. substitutionFont deve essere impostato su un oggetto Font valido. Deve restituire false nel caso in cui non sia necessaria alcuna sostituzione. substitutionFont può essere impostato su null.

### Vedi Anche

* classe [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification/)
* classe [Font](../../font/)
* classe [CustomFontSubstitutionBase](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)