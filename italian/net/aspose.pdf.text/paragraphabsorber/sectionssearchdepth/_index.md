---
title: ParagraphAbsorber.SectionsSearchDepth
second_title: Aspose.PDF for .NET API Reference
description: Proprietà di ParagraphAbsorber. Ottiene o imposta un valore che istruisce quante volte verranno eseguite ricerche sequenziali per elementi più fini della struttura. La profondità di ricerca predefinita è 3. Significa tre ricerche per sezioni divise orizzontalmente e tre ricerche per quelle divise verticalmente .
type: docs
weight: 50
url: /it/net/aspose.pdf.text/paragraphabsorber/sectionssearchdepth/
---
## Proprietà ParagraphAbsorber.SectionsSearchDepth

Ottiene o imposta un valore che istruisce quante volte verranno eseguite ricerche sequenziali per elementi più fini della struttura. La profondità di ricerca predefinita è 3. Significa tre ricerche per sezioni divise orizzontalmente (intestazioni, paragrafi, ecc.) e tre ricerche per quelle divise verticalmente (colonne).

```csharp
public int SectionsSearchDepth { get; set; }
```

## Osservazioni

L'aumento di questo valore può portare a una leggera diminuzione delle prestazioni senza cambiamenti visibili nei risultati della ricerca. La diminuzione di questo valore può portare a una determinazione errata dei paragrafi nelle sezioni. Non si consiglia di impostare un valore inferiore a quello predefinito se non si desidera ottenere solo elementi "grezzi" della struttura della pagina.

### Vedi anche

* classe [ParagraphAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)