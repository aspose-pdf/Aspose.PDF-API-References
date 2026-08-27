---
title: "StructureTypeCategory"
linktitle: "StructureTypeCategory"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta le categorie dei tipi di struttura standard."
type: docs
weight: 120
url: /it/java/com.aspose.pdf.tagged.logicalstructure/structuretypecategory/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.StructureTypeCategory

```
public final class StructureTypeCategory extends Object
```

Rappresenta le categorie dei tipi di struttura standard.

## Campi

| Campo | Descrizione |
| --- | --- |
| [BLSEs](#BLSEs) | Gli elementi di struttura a livello di blocco (BLSE) descrivono la disposizione complessiva del contenuto sulla pagina, procedendo nella direzione di progressione del blocco. |
| [GroupingElements](#GroupingElements) | Gli elementi di raggruppamento raggruppano altri elementi in sequenze o gerarchie ma non contengono direttamente contenuti e non hanno effetto diretto sul layout. |
| [IllustrationElements](#IllustrationElements) | Gli elementi di illustrazione sono sequenze compatte di contenuto, nell'ordine del contenuto della pagina, considerati oggetti unitari rispetto al layout della pagina. Un'illustrazione può essere trattata sia come un BLSE sia come un ILSE. |
| [ILSEs](#ILSEs) | Gli elementi di struttura a livello inline (ILSE) descrivono la disposizione del contenuto all'interno di un BLSE, procedendo nella direzione di progressione inline. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [to_StructureTypeCategory](#to_StructureTypeCategory-java.lang.String-) | Esegue una conversione esplicita da {@link String} a {@link StructureTypeCategory}. |
| [toString](#toString--) | Restituisce una stringa che rappresenta l'oggetto corrente. |

### BLSEs {#BLSEs}
```
public static final StructureTypeCategory BLSEs
```

Gli elementi di struttura a livello di blocco (BLSE) descrivono la disposizione complessiva del contenuto sulla pagina, procedendo nella direzione di progressione del blocco.

### GroupingElements {#GroupingElements}
```
public static final StructureTypeCategory GroupingElements
```

Gli elementi di raggruppamento raggruppano altri elementi in sequenze o gerarchie ma non contengono direttamente contenuti e non hanno effetto diretto sul layout.

### IllustrationElements {#IllustrationElements}
```
public static final StructureTypeCategory IllustrationElements
```

Gli elementi di illustrazione sono sequenze compatte di contenuto, nell'ordine del contenuto della pagina, considerati oggetti unitari rispetto al layout della pagina. Un'illustrazione può essere trattata sia come un BLSE sia come un ILSE.

### ILSEs {#ILSEs}
```
public static final StructureTypeCategory ILSEs
```

Gli elementi di struttura a livello inline (ILSE) descrivono la disposizione del contenuto all'interno di un BLSE, procedendo nella direzione di progressione inline.

### to_StructureTypeCategory {#to_StructureTypeCategory-java.lang.String-}
Esegue una conversione esplicita da {@link String} a {@link StructureTypeCategory}.

### toString {#toString--}
```
public String toString()
```

Restituisce una stringa che rappresenta l'oggetto corrente.

**Returns:**
Stringa che rappresenta l'oggetto corrente.
