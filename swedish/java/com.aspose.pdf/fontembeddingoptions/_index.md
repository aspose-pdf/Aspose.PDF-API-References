---
title: "FontEmbeddingOptions"
linktitle: "FontEmbeddingOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "PDF/A-standarden kräver att alla teckensnitt måste bäddas in i dokumentet. Denna klass innehåller flaggor för fall då det inte är möjligt att bädda in vissa teckensnitt eftersom teckensnittet saknas."
type: docs
weight: 1680
url: /sv/java/com.aspose.pdf/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontEmbeddingOptions

```
public class FontEmbeddingOptions extends Object
```

PDF/A-standarden kräver att alla teckensnitt måste vara inbäddade i dokumentet. Denna klass innehåller flaggor för fall då det inte är möjligt att bädda in vissa teckensnitt eftersom de saknas på mål‑datorn.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [FontEmbeddingOptions](#FontEmbeddingOptions--) | Initierar en ny instans av klassen {@link FontEmbeddingOptions}. Denna konstruktor sätter standardvärdet för egenskapen {@code UseDefaultSubstitution}({@link #getUseDefaultSubstitution}/{@link #setUseDefaultSubstitution(boolean)}) till {@code }. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getUseDefaultSubstitution](#getUseDefaultSubstitution--) | Anger om ett icke-bäddat teckensnitt ska ersättas med standardstrategi för teckensnittsersättning. Standardvärdet är falskt; |
| [setUseDefaultSubstitution](#setUseDefaultSubstitution-boolean-) | Anger om ett icke-bäddat teckensnitt ska ersättas med standardstrategi för teckensnittsersättning. Standardvärdet är falskt; |

### FontEmbeddingOptions {#FontEmbeddingOptions--}
```
public FontEmbeddingOptions()
```

Initierar en ny instans av klassen {@link FontEmbeddingOptions}. Denna konstruktor sätter standardvärdet för egenskapen {@code UseDefaultSubstitution}({@link #getUseDefaultSubstitution}/{@link #setUseDefaultSubstitution(boolean)}) till {@code }.

### getUseDefaultSubstitution {#getUseDefaultSubstitution--}
```
public boolean getUseDefaultSubstitution()
```

Anger om ett icke-bäddat teckensnitt ska ersättas med standardstrategi för teckensnittsersättning. Standardvärdet är falskt;

**Returns:**
booleskt värde

### setUseDefaultSubstitution {#setUseDefaultSubstitution-boolean-}
```
public void setUseDefaultSubstitution(boolean value)
```

Anger om ett icke-bäddat teckensnitt ska ersättas med standardstrategi för teckensnittsersättning. Standardvärdet är falskt;

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
