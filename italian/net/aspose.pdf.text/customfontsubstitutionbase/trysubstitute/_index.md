---
title: TrySubstitute
second_title: Aspose.PDF per .NET API Reference
description: Sostituisce il font originale con un altro font.
type: docs
weight: 20
url: /it/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## CustomFontSubstitutionBase.TrySubstitute method

Sostituisce il font originale con un altro font.

```csharp
public virtual bool TrySubstitute(OriginalFontSpecification originalFontSpecification, 
    out Font substitutionFont)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| originalFontSpecification | OriginalFontSpecification | Specifica del carattere originale. |
| substitutionFont | Font& | Carattere di sostituzione. |

### Valore di ritorno

Vero nel caso in cui la sostituzione abbia avuto successo.

### Osservazioni

La classe CustomFontSubstitutionBase deve essere ereditata per implementare la logica di sostituzione dei caratteri personalizzati. Il metodo TrySubstitute deve essere sovrascritto correttamente: Deve restituire true nel caso sia richiesta la sostituzione. substitutionFont deve essere impostato su Font oggetto valido. Deve restituire false nel caso in cui non sia richiesta alcuna sostituzione. sostituzioneFont può essere impostato su null.

### Guarda anche

* class [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification)
* class [Font](../../font)
* class [CustomFontSubstitutionBase](../../customfontsubstitutionbase)
* spazio dei nomi [Aspose.Pdf.Text](../../customfontsubstitutionbase)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->