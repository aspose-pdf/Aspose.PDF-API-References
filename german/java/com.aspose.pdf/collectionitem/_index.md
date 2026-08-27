---
title: "CollectionItem"
linktitle: "CollectionItem"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Klasse für ein Sammlungs‑Element dar. Das Sammlungs‑Element enthält die im Sammlungs‑Schema beschriebenen Daten."
type: docs
weight: 640
url: /de/java/com.aspose.pdf/collectionitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CollectionItem

```
public class CollectionItem extends Object
```

Stellt eine Klasse für ein Sammlungs‑Element dar. Das Sammlungs‑Element enthält die im Sammlungs‑Schema beschriebenen Daten.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAllNames](#getAllNames--) | Liefert eine Sammlung aller Namen der Werte des CollectionItem. |
| [hasName](#hasName-java.lang.String-) | Prüft, ob der angegebene Name im CollectionItem vorhanden ist. |
| [isEmpty](#isEmpty--) | Liefert einen Wert, der angibt, ob das CollectionItem leer ist. |
| [tryGetDateTimeValue](#tryGetDateTimeValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Versucht, den Wert vom Typ DateTime aus dem CollectionItem anhand des angegebenen Namens zu erhalten. |
| [tryGetDoubleValue](#tryGetDoubleValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Versucht, den Double-Wert für den angegebenen Namen aus dem CollectionItem zu erhalten. |
| [tryGetIntValue](#tryGetIntValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Versucht, den Integer-Wert für einen angegebenen Namen aus dem CollectionItem zu erhalten. |
| [tryGetTextValue](#tryGetTextValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Versucht, den Textwert mit dem angegebenen Namen aus dem CollectionItem zu erhalten. |

### getAllNames {#getAllNames--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllNames()
```

Liefert eine Sammlung aller Namen der Werte des CollectionItem.

**Returns:**
Liste von String

### hasName {#hasName-java.lang.String-}
Prüft, ob der angegebene Name im CollectionItem vorhanden ist.

### isEmpty {#isEmpty--}
```
public final boolean isEmpty()
```

Liefert einen Wert, der angibt, ob das CollectionItem leer ist.

**Returns:**
true, wenn das CollectionItem leer ist; andernfalls false. Diese Eigenschaft gibt true zurück, wenn das CollectionItem keine Werte enthält, einschließlich String-Werten, Double-Werten, Integer-Werten und Datumswerten. Wenn einer dieser Wertetypen im CollectionItem vorhanden ist, gibt diese Eigenschaft false zurück.

### tryGetDateTimeValue {#tryGetDateTimeValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Versucht, den Wert vom Typ DateTime aus dem CollectionItem anhand des angegebenen Namens zu erhalten.

### tryGetDoubleValue {#tryGetDoubleValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Versucht, den Double-Wert für den angegebenen Namen aus dem CollectionItem zu erhalten.

### tryGetIntValue {#tryGetIntValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Versucht, den Integer-Wert für einen angegebenen Namen aus dem CollectionItem zu erhalten.

### tryGetTextValue {#tryGetTextValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Versucht, den Textwert mit dem angegebenen Namen aus dem CollectionItem zu erhalten.
