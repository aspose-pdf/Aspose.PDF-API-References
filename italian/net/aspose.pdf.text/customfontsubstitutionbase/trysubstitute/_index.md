---
title: "CustomFontSubstitutionBase.TrySubstitute"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo CustomFontSubstitutionBase. Sostituisce il font originale con un altro font"
type: docs
weight: 20
url: /it/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## CustomFontSubstitutionBase.TrySubstitute method

Sostituisce il carattere originale con un altro carattere.

```csharp
public virtual bool TrySubstitute(OriginalFontSpecification originalFontSpecification, 
    out Font substitutionFont)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| originalFontSpecification | OriginalFontSpecification | Specificazione del font originale. |
| substitutionFont | Font& | Font di sostituzione. |

### Valore di ritorno

True se la sostituzione è avvenuta con successo.

## Osservazioni

La classe CustomFontSubstitutionBase dovrebbe essere ereditata per implementare la logica di sostituzione dei font personalizzata. Il metodo TrySubstitute dovrebbe essere sovrascritto correttamente: Deve restituire true nel caso in cui sia necessaria la sostituzione. substitutionFont deve essere impostato su un oggetto Font valido. Deve restituire false nel caso in cui non sia necessaria alcuna sostituzione. substitutionFont può essere impostato a null.

### Vedi anche

* class [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification/)
* class [Font](../../font/)
* class [CustomFontSubstitutionBase](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


