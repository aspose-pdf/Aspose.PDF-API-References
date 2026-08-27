---
title: "Delegato HtmlSaveOptions.CssSavingStrategy"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "È possibile assegnare a questa proprietà una strategia personalizzata che implementa l'elaborazione e/o il salvataggio di una parte CSSs creata durante la conversione da PDF a HTML. In tal caso, l'elaborazione, come il salvataggio su stream o su disco, deve essere eseguita in quel codice personalizzato."
type: docs
weight: 5720
url: /it/net/aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
## HtmlSaveOptions.CssSavingStrategy delegate

È possibile assegnare a questa proprietà una strategia personalizzata che implementa l'elaborazione e/o il salvataggio di una parte CSS creata durante la conversione da PDF a HTML. In tal caso, l'elaborazione (come il salvataggio su stream o su disco) deve essere eseguita in quel codice personalizzato.

```csharp
public delegate void CssSavingStrategy(CssSavingInfo partSavingInfo);
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| partSavingInfo | CssSavingInfo | rappresenta un insieme di dati che può essere utilizzato per il salvataggio della parte CSS fornita. |

### Vedi anche

* class [CssSavingInfo](../htmlsaveoptions.csssavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


