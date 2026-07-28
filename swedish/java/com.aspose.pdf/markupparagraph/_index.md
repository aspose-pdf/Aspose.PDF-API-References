---
title: "MarkupParagraph"
linktitle: "MarkupParagraph"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar ett stycke."
type: docs
weight: 2880
url: /sv/java/com.aspose.pdf/markupparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MarkupParagraph

```
public final class MarkupParagraph extends Object
```

Representerar ett stycke.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getContinuationPageNumbers](#getContinuationPageNumbers--) | Lista över sidnummer där stycket fortsätter. Den kommer att matcha med sidan där stycket började om det fortsätter i nästa kolumn på samma sida. |
| [getFragments](#getFragments--) | <p> Samling av icke tomma {@code TextFragment}-objekt i stycket. </p><hr> {@code TextFragment}-objektet ger åtkomst till den hittade texten, textegenskaper och möjliggör redigering av text samt ändring av textens tillstånd (teckensnitt, teckenstorlek, färg osv). |
| [getFragmentsInternal](#getFragmentsInternal--) |  |
| [getLines](#getLines--) | <p> Rader i stycket. Varje rad representeras av en lista med textfragment. </p><hr> {@code TextFragment}-objektet ger åtkomst till den hittade texten, textegenskaper och möjliggör redigering av text samt ändring av textens tillstånd (teckensnitt, teckenstorlek, färg osv). |
| [getLinesInternal](#getLinesInternal--) |  |
| [getPoints](#getPoints--) | Punkter i polygonen som beskriver stycket. Startpunkten är styckets nedre vänstra hörn. Och följande punkter är i moturs sekvens. |
| [getSecondaryPoints](#getSecondaryPoints--) | Punkter i sekundär polygon som beskriver styckets fortsättning. Den kommer inte att vara null om stycket fortsätter i nästa kolumn eller på nästa sida. Startpunkten är styckets nedre vänstra hörn. Och följande punkter är i moturs sekvens. |
| [getText](#getText--) | Hämtar {@code string}-textobjektet som {@code MarkupParagraph}-objektet representerar. |
| [setText](#setText-java.lang.String-) | Hämtar eller anger styckets text. |

### getContinuationPageNumbers {#getContinuationPageNumbers--}
```
public final List < Integer > getContinuationPageNumbers()
```

Lista över sidnummer där stycket fortsätter. Den kommer att matcha med sidan där stycket började om det fortsätter i nästa kolumn på samma sida.

**Returns:**
lista över Integer

### getFragments {#getFragments--}
```
public List < TextFragment > getFragments()
```

<p> Samling av icke tomma {@code TextFragment}-objekt i stycket. </p><hr> {@code TextFragment}-objektet ger åtkomst till den hittade texten, textegenskaper och möjliggör redigering av text samt ändring av textens tillstånd (teckensnitt, teckenstorlek, färg osv).

**Returns:**
lista med TextFragment-instansier

### getFragmentsInternal {#getFragmentsInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< TextFragment > getFragmentsInternal()
```



### getLines {#getLines--}
```
public List <com.aspose.ms.System.Collections.Generic.List< TextFragment >> getLines()
```

<p> Rader i stycket. Varje rad representeras av en lista med textfragment. </p><hr> {@code TextFragment}-objektet ger åtkomst till den hittade texten, textegenskaper och möjliggör redigering av text samt ändring av textens tillstånd (teckensnitt, teckenstorlek, färg osv).

**Returns:**
lista med TextFragment-instansier

### getLinesInternal {#getLinesInternal--}
```
public com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Collections.Generic.List< TextFragment >> getLinesInternal()
```



### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Punkter i polygonen som beskriver stycket. Startpunkten är styckets nedre vänstra hörn. Och följande punkter är i moturs sekvens.

**Returns:**
array av Point-instans

### getSecondaryPoints {#getSecondaryPoints--}
```
public final List < Point []> getSecondaryPoints()
```

Punkter i sekundär polygon som beskriver styckets fortsättning. Den kommer inte att vara null om stycket fortsätter i nästa kolumn eller på nästa sida. Startpunkten är styckets nedre vänstra hörn. Och följande punkter är i moturs sekvens.

**Returns:**
lista över Point[]

### getText {#getText--}
```
public String getText()
```

Hämtar {@code string}-textobjektet som {@code MarkupParagraph}-objektet representerar.

**Returns:**
String värde

### setText {#setText-java.lang.String-}
Hämtar eller anger styckets text.
