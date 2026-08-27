---
title: "PaginationArtifact"
linktitle: "PaginationArtifact"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en abstrakt basklass för pagineringsartefakter i ett dokument."
type: docs
weight: 3460
url: /sv/java/com.aspose.pdf/paginationartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public abstract class PaginationArtifact extends Artifact
```

Representerar en abstrakt basklass för pagineringsartefakter i ett dokument.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEndPage](#getEndPage--) | Hämtar eller anger det avslutande sidnumret för artefakten. Värdet måste vara större än eller lika med 0. Om ett värde mindre än 0 anges, justeras det till 0. Standardvärdet 0 betyder att det inte finns några slutsidgränser. |
| [getStartPage](#getStartPage--) | Hämtar eller anger det startande sidnumret för artefakten. Värdet måste vara större än eller lika med 1. Om ett värde mindre än 1 anges, justeras det till 1. |
| [getSubset](#getSubset--) | Hämtar eller anger den delmängd av sidor som artefakten gäller för (t.ex. alla sidor, jämna sidor, udda sidor). |
| [setEndPage](#setEndPage-int-) | Hämtar eller anger det avslutande sidnumret för artefakten. Värdet måste vara större än eller lika med 0. Om ett värde mindre än 0 anges, justeras det till 0. Standardvärdet 0 betyder att det inte finns några slutsidgränser. |
| [setStartPage](#setStartPage-int-) | Hämtar eller anger det startande sidnumret för artefakten. Värdet måste vara större än eller lika med 1. Om ett värde mindre än 1 anges, justeras det till 1. |
| [setSubset](#setSubset-int-) | Hämtar eller anger den delmängd av sidor som artefakten gäller för (t.ex. alla sidor, jämna sidor, udda sidor). |

### getEndPage {#getEndPage--}
```
public final int getEndPage()
```

Hämtar eller anger det avslutande sidnumret för artefakten. Värdet måste vara större än eller lika med 0. Om ett värde mindre än 0 anges, justeras det till 0. Standardvärdet 0 betyder att det inte finns några slutsidgränser.

**Returns:**
int‑värde

### getStartPage {#getStartPage--}
```
public final int getStartPage()
```

Hämtar eller anger det startande sidnumret för artefakten. Värdet måste vara större än eller lika med 1. Om ett värde mindre än 1 anges, justeras det till 1.

**Returns:**
int‑värde

### getSubset {#getSubset--}
```
public final int getSubset()
```

Hämtar eller anger den delmängd av sidor som artefakten gäller för (t.ex. alla sidor, jämna sidor, udda sidor).

**Returns:**
int‑värde

### setEndPage {#setEndPage-int-}
```
public final void setEndPage(int value)
```

Hämtar eller anger det avslutande sidnumret för artefakten. Värdet måste vara större än eller lika med 0. Om ett värde mindre än 0 anges, justeras det till 0. Standardvärdet 0 betyder att det inte finns några slutsidgränser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setStartPage {#setStartPage-int-}
```
public final void setStartPage(int value)
```

Hämtar eller anger det startande sidnumret för artefakten. Värdet måste vara större än eller lika med 1. Om ett värde mindre än 1 anges, justeras det till 1.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setSubset {#setSubset-int-}
```
public final void setSubset(int value)
```

Hämtar eller anger den delmängd av sidor som artefakten gäller för (t.ex. alla sidor, jämna sidor, udda sidor).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |
