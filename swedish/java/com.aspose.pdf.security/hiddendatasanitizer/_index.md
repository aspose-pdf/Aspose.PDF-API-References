---
title: "HiddenDataSanitizer"
linktitle: "HiddenDataSanitizer"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en klass för sanering av dolda data."
type: docs
weight: 20
url: /sv/java/com.aspose.pdf.security/hiddendatasanitizer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.HiddenDataSanitizer

```
public final class HiddenDataSanitizer extends Object
```

Representerar en klass för sanering av dolda data.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [HiddenDataSanitizer](#HiddenDataSanitizer-com.aspose.pdf.security.HiddenDataSanitizationOptions-) | Tillhandahåller funktionalitet för att sanera dold data från ett PDF‑dokument, vilket säkerställer att känslig eller onödig information såsom metadata, annotationer, JavaScripts eller privat innehåll tas bort eller omvandlas. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [sanitize](#sanitize-com.aspose.pdf.Document-) | Sanerar ett givet PDF‑dokument genom att ta bort eller omvandla dold data. |
| [sanitizeAllToImages](#sanitizeAllToImages-com.aspose.pdf.Document-) | Ersätter sidinnehåll med bilder och tar bort annan dold data. Gör det möjligt att ta bort dold text med en bakgrundsfärg, samt text dold under bilder. Dessutom tas alla interaktiva element bort helt. Dokumentet konverteras till bilder som det är, och rensas sedan på eventuell återstående dold data. Om du först behöver rensa och sedan konvertera, använd huvudklassens metod. |
| [sanitizeAllToImages](#sanitizeAllToImages-com.aspose.pdf.Document-int-) | Ersätter sidinnehåll med bilder och tar bort annan dold data. Gör att du kan ta bort dold text med en bakgrundsfärg, samt text dold under bilder. Tar också helt bort alla interaktiva element. Dokumentet konverteras till bilder som det är, och rensas sedan på eventuell återstående dold data. Om du behöver rensa först och sedan konvertera, använd huvudklassens metod. |

### HiddenDataSanitizer {#HiddenDataSanitizer-com.aspose.pdf.security.HiddenDataSanitizationOptions-}
Tillhandahåller funktionalitet för att sanera dold data från ett PDF‑dokument, vilket säkerställer att känslig eller onödig information såsom metadata, annotationer, JavaScripts eller privat innehåll tas bort eller omvandlas.

### sanitize {#sanitize-com.aspose.pdf.Document-}
Sanerar ett givet PDF‑dokument genom att ta bort eller omvandla dold data.

### sanitizeAllToImages {#sanitizeAllToImages-com.aspose.pdf.Document-}
Ersätter sidinnehåll med bilder och tar bort annan dold data. Gör det möjligt att ta bort dold text med en bakgrundsfärg, samt text dold under bilder. Dessutom tas alla interaktiva element bort helt. Dokumentet konverteras till bilder som det är, och rensas sedan på eventuell återstående dold data. Om du först behöver rensa och sedan konvertera, använd huvudklassens metod.

### sanitizeAllToImages {#sanitizeAllToImages-com.aspose.pdf.Document-int-}
Ersätter sidinnehåll med bilder och tar bort annan dold data. Gör att du kan ta bort dold text med en bakgrundsfärg, samt text dold under bilder. Tar också helt bort alla interaktiva element. Dokumentet konverteras till bilder som det är, och rensas sedan på eventuell återstående dold data. Om du behöver rensa först och sedan konvertera, använd huvudklassens metod.
