---
title: "CollectionField"
linktitle: "CollectionField"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Klasse für ein Dokumentensammlungs‑Schema‑Feld dar."
type: docs
weight: 620
url: /de/java/com.aspose.pdf/collectionfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CollectionField

```
public class CollectionField extends Object
```

Stellt eine Klasse für ein Dokumentensammlungs‑Schema‑Feld dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getE](#getE--) | Ruft ein Flag ab, das angibt, ob der interaktive PDF‑Prozessor Unterstützung für die Bearbeitung des Feldwerts bereitstellen soll. Standardwert: false |
| [getFiledType](#getFiledType--) | Ruft den Typ eines Feldwerts in einer Schemasammlung ab. Dieses Feld beschreibt den Werttyp, der {@code Subtype}({@link #getSubtype}/{@link #setSubtype(int)}) entspricht. |
| [getN](#getN--) | Ruft den textuellen Feldnamen ab, der dem Benutzer vom interaktiven PDF‑Prozessor angezeigt werden soll. |
| [getO](#getO--) | Ruft die relative Reihenfolge des Feldnamens in der Benutzeroberfläche ab. Felder sollen vom interaktiven PDF‑Prozessor in aufsteigender Reihenfolge sortiert werden. |
| [getSubtype](#getSubtype--) | Ruft den Subtyp eines Feldwerts in einer Schemasammlung ab. Der Subtyp des Sammlungsfelds oder des dateibezogenen Felds, den dieses Wörterbuch beschreibt. Dieser Eintrag identifiziert den Datentyp, der im Feld gespeichert werden soll. |
| [getV](#getV--) | Ruft die anfängliche Sichtbarkeit des Feldes in der Benutzeroberfläche ab. Standardwert: true. |

### getE {#getE--}
```
public final boolean getE()
```

Ruft ein Flag ab, das angibt, ob der interaktive PDF‑Prozessor Unterstützung für die Bearbeitung des Feldwerts bereitstellen soll. Standardwert: false

**Returns:**
boolescher Wert

### getFiledType {#getFiledType--}
```
public final int getFiledType()
```

Ruft den Typ eines Feldwerts in einer Schemasammlung ab. Dieses Feld beschreibt den Werttyp, der {@code Subtype}({@link #getSubtype}/{@link #setSubtype(int)}) entspricht.

**Returns:**
FieldValueType-Element

### getN {#getN--}
```
public final String getN()
```

Ruft den textuellen Feldnamen ab, der dem Benutzer vom interaktiven PDF‑Prozessor angezeigt werden soll.

**Returns:**
String Wert

### getO {#getO--}
```
public final Integer [] getO()
```

Ruft die relative Reihenfolge des Feldnamens in der Benutzeroberfläche ab. Felder sollen vom interaktiven PDF‑Prozessor in aufsteigender Reihenfolge sortiert werden.

**Returns:**
Array von Integer

### getSubtype {#getSubtype--}
```
public final int getSubtype()
```

Ruft den Subtyp eines Feldwerts in einer Schemasammlung ab. Der Subtyp des Sammlungsfelds oder des dateibezogenen Felds, den dieses Wörterbuch beschreibt. Dieser Eintrag identifiziert den Datentyp, der im Feld gespeichert werden soll.

**Returns:**
CollectionFieldSubtype-Element

### getV {#getV--}
```
public final boolean getV()
```

Ruft die anfängliche Sichtbarkeit des Feldes in der Benutzeroberfläche ab. Standardwert: true.

**Returns:**
boolescher Wert
