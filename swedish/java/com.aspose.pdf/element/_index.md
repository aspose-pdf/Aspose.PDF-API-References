---
title: "Element"
linktitle: "Element"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar baselementet i den logiska strukturen."
type: docs
weight: 1180
url: /sv/java/com.aspose.pdf/element/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Element

```
public abstract class Element extends Object
```

Klass som representerar baselementet i den logiska strukturen.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getActualText](#getActualText--) | (Valfritt; PDF 1.4) Text som är en exakt ersättning för strukturelementet och dess underordnade. Denna ersättningstext (som bör tillämpas på så liten mängd innehåll som möjligt) är användbar när man extraherar dokumentets innehåll för att stödja tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål. |
| [getAlt](#getAlt--) | (Valfritt) En alternativ beskrivning av strukturelementet och dess underordnade i mänskligt läsbar form, vilket är användbart när man extraherar dokumentets innehåll för att stödja tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål. |
| [getChildren](#getChildren--) | Hämtar samling av underordnade element. |
| [getE](#getE--) | (Valfritt; PDF 1.5) Den utökade formen av en förkortning. |
| [getLang](#getLang--) | (Valfritt; PDF 1.4) Ett språk som specificerar det naturliga språket för all text i strukturelementet, förutom där det åsidosätts av språkspecifikationer för nästlade strukturelement eller markerat innehåll. |
| [remove](#remove--) | Ta bort element. |
| [setActualText](#setActualText-java.lang.String-) | (Valfritt; PDF 1.4) Text som är en exakt ersättning för strukturelementet och dess underordnade. Denna ersättningstext (som bör tillämpas på så liten mängd innehåll som möjligt) är användbar när man extraherar dokumentets innehåll för att stödja tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål. |
| [setAlt](#setAlt-java.lang.String-) | (Valfritt) En alternativ beskrivning av strukturelementet och dess underordnade i mänskligt läsbar form, vilket är användbart när man extraherar dokumentets innehåll för att stödja tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål. |
| [setE](#setE-java.lang.String-) | (Valfritt; PDF 1.5) Den utökade formen av en förkortning. |
| [setLang](#setLang-java.lang.String-) | (Valfritt; PDF 1.4) Ett språk som specificerar det naturliga språket för all text i strukturelementet, förutom där det åsidosätts av språkspecifikationer för nästlade strukturelement eller markerat innehåll. |

### getActualText {#getActualText--}
```
public String getActualText()
```

(Valfritt; PDF 1.4) Text som är en exakt ersättning för strukturelementet och dess underordnade. Denna ersättningstext (som bör tillämpas på så liten mängd innehåll som möjligt) är användbar när man extraherar dokumentets innehåll för att stödja tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål.

**Returns:**
String-objekt

### getAlt {#getAlt--}
```
public String getAlt()
```

(Valfritt) En alternativ beskrivning av strukturelementet och dess underordnade i mänskligt läsbar form, vilket är användbart när man extraherar dokumentets innehåll för att stödja tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål.

**Returns:**
String-objekt

### getChildren {#getChildren--}
```
public final ElementCollection getChildren()
```

Hämtar samling av underordnade element.

**Returns:**
ElementCollection-instans

### getE {#getE--}
```
public String getE()
```

(Valfritt; PDF 1.5) Den utökade formen av en förkortning.

**Returns:**
String-objekt

### getLang {#getLang--}
```
public String getLang()
```

(Valfritt; PDF 1.4) Ett språk som specificerar det naturliga språket för all text i strukturelementet, förutom där det åsidosätts av språkspecifikationer för nästlade strukturelement eller markerat innehåll.

**Returns:**
String-objekt

### remove {#remove--}
```
public final void remove()
```

Ta bort element.

### setActualText {#setActualText-java.lang.String-}
(Valfritt; PDF 1.4) Text som är en exakt ersättning för strukturelementet och dess underordnade. Denna ersättningstext (som bör tillämpas på så liten mängd innehåll som möjligt) är användbar när man extraherar dokumentets innehåll för att stödja tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål.

### setAlt {#setAlt-java.lang.String-}
(Valfritt) En alternativ beskrivning av strukturelementet och dess underordnade i mänskligt läsbar form, vilket är användbart när man extraherar dokumentets innehåll för att stödja tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål.

### setE {#setE-java.lang.String-}
(Valfritt; PDF 1.5) Den utökade formen av en förkortning.

### setLang {#setLang-java.lang.String-}
(Valfritt; PDF 1.4) Ett språk som specificerar det naturliga språket för all text i strukturelementet, förutom där det åsidosätts av språkspecifikationer för nästlade strukturelement eller markerat innehåll.
