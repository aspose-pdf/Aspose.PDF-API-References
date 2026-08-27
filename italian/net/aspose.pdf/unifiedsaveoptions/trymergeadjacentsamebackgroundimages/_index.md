---
title: "UnifiedSaveOptions.TryMergeAdjacentSameBackgroundImages"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Campo UnifiedSaveOptions. A volte i PDF contengono immagini di sfondo di pagine o celle di tabella costruite da diverse immagini di sfondo a tassello identiche posizionate una accanto all'altra. In tal caso i renderer dei formati di destinazione, ad es. MsWord per il formato DOCS, a volte generano bordi visibili tra le parti delle immagini di sfondo perché le loro tecniche di smussatura dei bordi delle immagini e antialiasing differiscono da quelle di Acrobat Reader. Se sembra che il documento esportato contenga tali bordi visibili tra le parti delle stesse immagini di sfondo, prova a utilizzare questa impostazione per eliminare quell'effetto indesiderato. ATTENTION Questa ottimizzazione della qualità di solito rallenta notevolmente la conversione, quindi utilizza questa opzione solo quando è davvero necessaria."
type: docs
weight: 40
url: /it/net/aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/
---
## UnifiedSaveOptions.TryMergeAdjacentSameBackgroundImages field

A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo a tasselli identiche posizionate una accanto all'altra. In tal caso i renderer dei formati di destinazione (ad es. MsWord per il formato DOCS) a volte generano bordi visibili tra le parti delle immagini di sfondo, poiché le loro tecniche di smussatura dei bordi delle immagini (anti-aliasing) differiscono da quelle di Acrobat Reader. Se sembra che il documento esportato contenga tali bordi visibili tra le parti delle stesse immagini di sfondo, provare a utilizzare questa impostazione per eliminare l'effetto indesiderato. ATTENZIONE! Questa ottimizzazione della qualità solitamente rallenta notevolmente la conversione, quindi, per favore, usala solo quando è davvero necessaria.

```csharp
public bool TryMergeAdjacentSameBackgroundImages;
```

### Vedi anche

* class [UnifiedSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


