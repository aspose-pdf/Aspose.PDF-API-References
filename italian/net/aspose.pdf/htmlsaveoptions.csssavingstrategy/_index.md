---
title: Delegate HtmlSaveOptions.CssSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: È possibile assegnare a questa proprietà una strategia personalizzata che implementa l'elaborazione e/o il salvataggio di una parte di CSS che è stata creata durante la conversione da PDF a HTML. In tal caso, l'elaborazione (come il salvataggio su stream o disco) deve essere eseguita in quel codice personalizzato
type: docs
weight: 5590
url: /it/net/aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
## Delegato HtmlSaveOptions.CssSavingStrategy

È possibile assegnare a questa proprietà una strategia personalizzata che implementa l'elaborazione e/o il salvataggio di una parte di CSS che è stata creata durante la conversione da PDF a HTML. In tal caso, l'elaborazione (come il salvataggio su stream o disco) deve essere eseguita in quel codice personalizzato

```csharp
public delegate void CssSavingStrategy(CssSavingInfo partSavingInfo);
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| partSavingInfo | CssSavingInfo | rappresenta un insieme di dati che possono essere utilizzati per il salvataggio della parte di CSS fornita |

### Vedi Anche

* classe [CssSavingInfo](../htmlsaveoptions.csssavinginfo/)
* classe [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)