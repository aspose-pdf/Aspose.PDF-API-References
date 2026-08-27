---
title: "ContentsAppender"
linktitle: "ContentsAppender"
second_title: "Aspose.PDF för Java API-referens"
description: "Utför innehållsmodifieringar endast i APPEND-läge. detta läge möjliggör att undvika onödig och tung innehållsparsning innan någon förändring görs i innehållet. Det lägger bara till nytt."
type: docs
weight: 800
url: /sv/java/com.aspose.pdf/contentsappender/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ContentsAppender

```
public class ContentsAppender extends Object
```

Utför innehållsmodifieringar enbart i APPEND-läge. Detta läge möjliggör att undvika onödig och tung parsning av innehållet innan någon förändring görs. Det lägger bara till nya operatorer i slutet eller i början av innehållet.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ContentsAppender](#ContentsAppender-com.aspose.pdf.Page-) | Initierar en ny instans av innehållsappendern med sidan bifogad |
| [ContentsAppender](#ContentsAppender-com.aspose.pdf.XForm-) | Initierar en ny instans av innehållsappendern med Form XObject. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [appendToBegin](#appendToBegin-com.aspose.ms.System.Collections.Generic.List-) | Lägger till operatorer i slutet av innehållet |
| [appendToBegin](#appendToBegin-com.aspose.pdf.Operator-) | Lägger till en operator i slutet av innehållet |
| [appendToBegin](#appendToBegin-com.aspose.pdf.Operator:A-) | Lägger till operatorer i slutet av innehållet |
| [appendToEnd](#appendToEnd-com.aspose.ms.System.Collections.Generic.List-) | Lägger till operatorer i början av innehållet |
| [appendToEnd](#appendToEnd-com.aspose.pdf.Operator-) | Lägger till en operator i början av innehållet |
| [appendToEnd](#appendToEnd-com.aspose.pdf.Operator:A-) | Lägger till operatorer i början av innehållet |
| [getBeginCode](#getBeginCode--) | Sträng som innehåller operatorer att infoga i början av sidan. |
| [getBeginOperators](#getBeginOperators--) | <p> returnerar startoperatorer </p> |
| [getEndCode](#getEndCode--) | Sträng som innehåller operatorer att lägga till i slutet av sidan. |
| [getEndOperators](#getEndOperators--) | <p> returnerar slutoperatorer </p> |
| [resumeUpdate](#resumeUpdate--) | återupptar dokumentuppdatering |
| [setBeginCode](#setBeginCode-java.lang.String-) | Sträng som innehåller operatorer att infoga i början av sidan. |
| [setEndCode](#setEndCode-java.lang.String-) | Sträng som innehåller operatorer att infoga i början av sidan. |
| [suppressUpdate](#suppressUpdate--) | Undertrycker uppdatering av innehållsdata. Innehållet uppdateras inte förrän ResumeUpdate anropas. |
| [updateData](#updateData--) | Detta är en ny version av UpdateData, som undviker avkodning av befintligt innehåll. |
| [updateDataOld](#updateDataOld--) | Måste anropas för att verkställa ändringarna |

### ContentsAppender {#ContentsAppender-com.aspose.pdf.Page-}
Initierar en ny instans av innehållsappendern med sidan bifogad

### ContentsAppender {#ContentsAppender-com.aspose.pdf.XForm-}
Initierar en ny instans av innehållsappendern med Form XObject.

### appendToBegin {#appendToBegin-com.aspose.ms.System.Collections.Generic.List-}
Lägger till operatorer i slutet av innehållet

### appendToBegin {#appendToBegin-com.aspose.pdf.Operator-}
Lägger till en operator i slutet av innehållet

### appendToBegin {#appendToBegin-com.aspose.pdf.Operator:A-}
Lägger till operatorer i slutet av innehållet

### appendToEnd {#appendToEnd-com.aspose.ms.System.Collections.Generic.List-}
Lägger till operatorer i början av innehållet

### appendToEnd {#appendToEnd-com.aspose.pdf.Operator-}
Lägger till en operator i början av innehållet

### appendToEnd {#appendToEnd-com.aspose.pdf.Operator:A-}
Lägger till operatorer i början av innehållet

### getBeginCode {#getBeginCode--}
```
public String getBeginCode()
```

Sträng som innehåller operatorer att infoga i början av sidan.

**Returns:**
String-objekt

### getBeginOperators {#getBeginOperators--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > getBeginOperators()
```

<p> returnerar startoperatorer </p>

**Returns:**
{@code List<Operator>} objekt

### getEndCode {#getEndCode--}
```
public String getEndCode()
```

Sträng som innehåller operatorer att lägga till i slutet av sidan.

**Returns:**
String-objekt

### getEndOperators {#getEndOperators--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > getEndOperators()
```

<p> returnerar slutoperatorer </p>

**Returns:**
{@code List<Operator>} objekt

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

återupptar dokumentuppdatering

### setBeginCode {#setBeginCode-java.lang.String-}
Sträng som innehåller operatorer att infoga i början av sidan.

### setEndCode {#setEndCode-java.lang.String-}
Sträng som innehåller operatorer att infoga i början av sidan.

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Undertrycker uppdatering av innehållsdata. Innehållet uppdateras inte förrän ResumeUpdate anropas.

### updateData {#updateData--}
```
public void updateData()
```

Detta är en ny version av UpdateData, som undviker avkodning av befintligt innehåll.

### updateDataOld {#updateDataOld--}
```
public void updateDataOld()
```

Måste anropas för att verkställa ändringarna
