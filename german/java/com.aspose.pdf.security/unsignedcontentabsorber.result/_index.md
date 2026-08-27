---
title: "UnsignedContentAbsorber.Result"
linktitle: "UnsignedContentAbsorber.Result"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Kapselt das Ergebnis einer Operation, die versucht, unsignierten Inhalt aus einem PDF-Dokument zu extrahieren. Diese Klasse liefert Informationen über den Erfolg der Operation, Details dazu."
type: docs
weight: 40
url: /de/java/com.aspose.pdf.security/unsignedcontentabsorber.result/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.Result

```
public static final class UnsignedContentAbsorber.Result extends Object
```

Kapselt das Ergebnis einer Operation, die versucht, unsignierten Inhalt aus einem PDF-Dokument zu extrahieren. Diese Klasse liefert Informationen über den Erfolg der Operation, Details des unsignierten Inhalts, eine Nachricht, die das Ergebnis beschreibt, sowie den Deckungsstatus der Signaturen des Dokuments.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCoverage](#getCoverage--) | Liefert einen Wert, der angibt, in welchem Umfang das Dokument von gültigen digitalen Signaturen abgedeckt ist. |
| [getMessage](#getMessage--) | Liefert eine Nachricht, die das Ergebnis der Operation beschreibt. |
| [getSuccess](#getSuccess--) | Liefert einen Wert, der angibt, ob die Operation zum Abrufen unsignierten Inhalts aus dem Dokument erfolgreich war. |
| [getUnsignedContent](#getUnsignedContent--) | Liefert einen unsignierten Inhalt. |

### getCoverage {#getCoverage--}
```
public final int getCoverage()
```

Liefert einen Wert, der angibt, in welchem Umfang das Dokument von gültigen digitalen Signaturen abgedeckt ist.

**Returns:**
ein Wert, der angibt, in welchem Umfang das Dokument von gültigen digitalen Signaturen abgedeckt ist.

### getMessage {#getMessage--}
```
public final String getMessage()
```

Liefert eine Nachricht, die das Ergebnis der Operation beschreibt.

**Returns:**
eine Nachricht, die das Ergebnis der Operation beschreibt.

### getSuccess {#getSuccess--}
```
public final boolean getSuccess()
```

Liefert einen Wert, der angibt, ob die Operation zum Abrufen unsignierten Inhalts aus dem Dokument erfolgreich war.

**Returns:**
ein Wert, der angibt, ob die Operation zum Abrufen unsignierten Inhalts aus dem Dokument erfolgreich war.

### getUnsignedContent {#getUnsignedContent--}
```
public final UnsignedContentAbsorber.UnsignedContent getUnsignedContent()
```

Liefert einen unsignierten Inhalt.

**Returns:**
ein unsignierter Inhalt.
