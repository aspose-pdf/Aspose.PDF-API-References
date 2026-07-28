---
title: "GraphicsAbsorber"
linktitle: "GraphicsAbsorber"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar ett absorberingsobjekt för grafikelement. Utför grafiksökning och ger åtkomst till sökresultaten via {@code GraphicsAbsorber.Elements}({@link."
type: docs
weight: 30
url: /sv/java/com.aspose.pdf.vector/graphicsabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicsAbsorber

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class GraphicsAbsorber extends Object implements com.aspose.ms.System.IDisposable
```

Representerar ett absorberingsobjekt för grafikelement. Utför grafiksökning och ger åtkomst till sökresultat via {@code GraphicsAbsorber.Elements}({@link GraphicsAbsorber#getElements})-samlingen.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [GraphicsAbsorber](#GraphicsAbsorber--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [dispose](#dispose--) | Frigör alla resurser som används av klassen {@link GraphicsAbsorber}. |
| [getElements](#getElements--) | Hämtar samlingen av sökförekomster som presenteras med {@link GraphicElement}-objekt. |
| [resumeUpdate](#resumeUpdate--) | Återuppta uppdatering för Page#getContents och alla @link XForm#getContents. Gjordes för att öka prestanda, se även. |
| [suppressUpdate](#suppressUpdate--) | Undertrycker uppdatering för Page#getContents och alla @link XForm#getContents. Gjordes för att öka prestanda, se även. |
| [visit](#visit-com.aspose.pdf.Page-) | Utför sökning på den angivna sidan. |

### GraphicsAbsorber {#GraphicsAbsorber--}
```
public GraphicsAbsorber()
```



### dispose {#dispose--}
```
public final void dispose()
```

Frigör alla resurser som används av klassen {@link GraphicsAbsorber}.

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

Hämtar samlingen av sökförekomster som presenteras med {@link GraphicElement}-objekt.

**Returns:**
GraphicElementCollection-instans

### resumeUpdate {#resumeUpdate--}
```
public final void resumeUpdate()
```

Återuppta uppdatering för Page#getContents och alla @link XForm#getContents. Gjordes för att öka prestanda, se även.

### suppressUpdate {#suppressUpdate--}
```
public final void suppressUpdate()
```

Undertrycker uppdatering för Page#getContents och alla @link XForm#getContents. Gjordes för att öka prestanda, se även.

### visit {#visit-com.aspose.pdf.Page-}
Utför sökning på den angivna sidan.
