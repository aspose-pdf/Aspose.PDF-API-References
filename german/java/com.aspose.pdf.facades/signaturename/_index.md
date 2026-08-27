---
title: "SignatureName"
linktitle: "SignatureName"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Klasse für einen Signaturnamen dar. Stellt einen präziseren Signaturnamen dar. Wird anstelle von Zeichenkettennamen verwendet. Ermöglicht es, Signaturen mit denselben Zeichenkettennamen darzustellen."
type: docs
weight: 690
url: /de/java/com.aspose.pdf.facades/signaturename/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.SignatureName

```
public final class SignatureName extends Object
```

Stellt eine Klasse für einen Signaturnamen dar. Stellt einen präziseren Signaturnamen dar. Wird anstelle von Zeichenkettennamen verwendet. Ermöglicht es, Signaturen mit denselben Zeichenkettennamen darzustellen.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [FullName](#FullName) | Liefert den vollständigen Namen der Signatur und stellt einen eindeutigen und präzisen Bezeichner für das Signaturfeld bereit. |
| [Name](#Name) | Liefert den Namen einer Signatur. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Bestimmt, ob diese Instanz und ein angegebenes Objekt gleich sind. |
| [getSignatureDictionary](#getSignatureDictionary--) | Liefert das Signaturwörterbuch. |
| [hashCode](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück, basierend auf der Eigenschaft FullName. |
| [hasSignature](#hasSignature--) | Gibt an, ob die Signatur vorhanden ist oder nicht. |
| [toString](#toString--) | Gibt eine String-Darstellung der {@link SignatureName}-Instanz zurück, wobei hauptsächlich ihr Name verwendet wird. |

### FullName {#FullName}
```
public final String FullName
```

Liefert den vollständigen Namen der Signatur und stellt einen eindeutigen und präzisen Bezeichner für das Signaturfeld bereit.

### Name {#Name}
```
public final String Name
```

Liefert den Namen einer Signatur.

### equals {#equals-java.lang.Object-}
Bestimmt, ob diese Instanz und ein angegebenes Objekt gleich sind.

### getSignatureDictionary {#getSignatureDictionary--}
```
public final com.aspose.pdf.engine.data.IPdfDictionary getSignatureDictionary()
```

Liefert das Signaturwörterbuch.

**Returns:**
Das Signaturwörterbuch oder null, wenn es nicht gefunden wird.

### hashCode {#hashCode--}
```
public int hashCode()
```

Gibt einen Hashcode für diese Instanz zurück, basierend auf der Eigenschaft FullName.

**Returns:**
Ein Integer, der den Hashcode der Eigenschaft FullName darstellt.

### hasSignature {#hasSignature--}
```
public final boolean hasSignature()
```

Gibt an, ob die Signatur vorhanden ist oder nicht.

**Returns:**
boolescher Wert

### toString {#toString--}
```
public String toString()
```

Gibt eine String-Darstellung der {@link SignatureName}-Instanz zurück, wobei hauptsächlich ihr Name verwendet wird.

**Returns:**
Ein String, der den Namen der Signatur darstellt.
