---
title: UnifiedSaveOptions.TryMergeAdjacentSameBackgroundImages
second_title: Aspose.PDF for .NET API Reference
description: Campo UnifiedSaveOptions. A volte i PDF contengono immagini di sfondo di pagine o celle di tabella costruite da diverse immagini di sfondo a mosaico identiche messe una vicino all'altra. In tal caso, i renderer dei formati di destinazione generano a volte confini visibili tra le parti delle immagini di sfondo, poiché le loro tecniche di levigatura dei bordi delle immagini sono diverse da quelle di Acrobat Reader. Se sembra che il documento esportato contenga tali confini visibili tra le parti delle stesse immagini di sfondo, si prega di provare a utilizzare questa impostazione per eliminare quell'effetto indesiderato. ATTENZIONE! Questa ottimizzazione della qualità rallenta solitamente in modo sostanziale la conversione, quindi si prega di utilizzare questa opzione solo quando è davvero necessario.
type: docs
weight: 40
url: /it/net/aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/
---
## UnifiedSaveOptions.TryMergeAdjacentSameBackgroundImages field

A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo a mosaico identiche messe una vicino all'altra. In tal caso, i renderer dei formati di destinazione (ad esempio MsWord per il formato DOCS) generano a volte confini visibili tra le parti delle immagini di sfondo, poiché le loro tecniche di levigatura dei bordi delle immagini (anti-aliasing) sono diverse da quelle di Acrobat Reader. Se sembra che il documento esportato contenga tali confini visibili tra le parti delle stesse immagini di sfondo, si prega di provare a utilizzare questa impostazione per eliminare quell'effetto indesiderato. ATTENZIONE! Questa ottimizzazione della qualità rallenta solitamente in modo sostanziale la conversione, quindi si prega di utilizzare questa opzione solo quando è davvero necessario.

```csharp
public bool TryMergeAdjacentSameBackgroundImages;
```

### See Also

* class [UnifiedSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)