---
title: "UnsignedContentAbsorber"
linktitle: "UnsignedContentAbsorber"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Klasse zum Extrahieren unsignierten Inhalts aus einer PDF-Datei bereit, die von digitalen Signaturen verwaltet wird."
type: docs
weight: 30
url: /de/java/com.aspose.pdf.security/unsignedcontentabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber

```
public final class UnsignedContentAbsorber extends Object
```

Stellt eine Klasse zum Extrahieren unsignierten Inhalts aus einer PDF-Datei bereit, die von digitalen Signaturen verwaltet wird.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [UnsignedContentAbsorber](#UnsignedContentAbsorber-com.aspose.pdf.facades.PdfFileSignature-) | Stellt eine Klasse dar, die zur Verarbeitung von nicht signiertem Inhalt verwendet wird. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [tryGetContent](#tryGetContent--) | Versucht, den nicht signierten Inhalt aus dem zugehörigen Dokument abzurufen. |

### UnsignedContentAbsorber {#UnsignedContentAbsorber-com.aspose.pdf.facades.PdfFileSignature-}
Stellt eine Klasse dar, die zur Verarbeitung von nicht signiertem Inhalt verwendet wird.

### tryGetContent {#tryGetContent--}
```
public final UnsignedContentAbsorber.Result tryGetContent()
```

Versucht, den nicht signierten Inhalt aus dem zugehörigen Dokument abzurufen.

**Returns:**
Ein {@link UnsignedContentAbsorber.Result} Objekt, das Details über den nicht signierten Inhalt, die Abdeckung digitaler Signaturen, den Erfolgsstatus der Operation und eine Informationsnachricht enthält.
