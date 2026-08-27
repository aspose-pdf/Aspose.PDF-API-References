---
title: "ParagraphAbsorber.SectionsSearchDepth"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà ParagraphAbsorber. Ottiene o imposta il valore che indica quante volte verranno eseguite ricerche sequenziali per elementi più dettagliati della struttura. La profondità di ricerca predefinita è 3. Significa tre ricerche per sezioni, intestazioni, paragrafi, ecc. divisi orizzontalmente e tre ricerche per quelli divisi verticalmente in colonne."
type: docs
weight: 50
url: /it/net/aspose.pdf.text/paragraphabsorber/sectionssearchdepth/
---
## ParagraphAbsorber.SectionsSearchDepth property

Ottiene o imposta il valore che indica quante volte verranno eseguite ricerche sequenziali per elementi più fini della struttura. La profondità di ricerca predefinita è 3. Significa tre ricerche per sezioni divise orizzontalmente (intestazioni, paragrafi ecc.) e tre ricerche per quelle divise verticalmente (colonne).

```csharp
public int SectionsSearchDepth { get; set; }
```

## Osservazioni

L'aumento di questo valore può comportare una leggera diminuzione delle prestazioni senza modifiche visibili nei risultati della ricerca. La diminuzione di questo valore può portare a una determinazione errata dei paragrafi nelle sezioni. Non consigliamo di impostare un valore inferiore a quello predefinito se non si desidera ottenere solo elementi 'grossolani' della struttura della pagina.

### Vedi anche

* class [ParagraphAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


