---
title: "Behörigheter"
linktitle: "Behörigheter"
second_title: "Aspose.PDF för Java API-referens"
description: "Binär flagga Detta enum representerar användarens behörigheter för en PDF."
type: docs
weight: 3830
url: /sv/java/com.aspose.pdf/permissions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.Permissions, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.Permissions, com.aspose.ms.System.Enum, com.aspose.pdf.Permissions

```
public final class Permissions extends com.aspose.ms.System.Enum
```

Binär flagga Detta enum representerar användarens behörigheter för en PDF.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [AssembleDocument](#AssembleDocument) | (Security handlers of revision 3 or greater) Sammanställ dokumentet (infoga, rotera eller ta bort sidor och skapa bokmärken eller miniatyrbilder), även om {@code ModifyContent} är avmarkerad. |
| [ExtractContent](#ExtractContent) | (Security handlers of revision 2) Kopiera eller på annat sätt extrahera text och grafik från dokumentet, inklusive extrahering av text och grafik (i stöd för tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål). (Security handlers of revision 3 or greater) Kopiera eller på annat sätt extrahera text och grafik från dokumentet genom operationer som inte styrs av {@code ExtractContentWithDisabilities}. |
| [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | (Security handlers of revision 3 or greater) Extrahera text och grafik (i stöd för tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål). |
| [FillForm](#FillForm) | (Security handlers of revision 3 or greater) Fyll i befintliga interaktiva formulärfält (inklusive signaturfält), även om {@code ModifyTextAnnotations} är avmarkerad. |
| [ModifyContent](#ModifyContent) | Modifiera dokumentets innehåll genom operationer som inte styrs av {@code ModifyTextAnnotations}, {@code FillForm} och 11. |
| [ModifyTextAnnotations](#ModifyTextAnnotations) | Lägg till eller ändra textanteckningar, fyll i interaktiva formulärfält, och, om {@code ModifyContent} också är aktiverat, skapa eller ändra interaktiva formulärfält (inklusive signaturfält). |
| [PrintDocument](#PrintDocument) | (Security handlers of revision 2) Skriv ut dokumentet. (Security handlers of revision 3 or greater) Skriv ut dokumentet (möjligen inte på högsta kvalitet, beroende på om {@code PrintingQuality} också är aktiverat). |
| [PrintingQuality](#PrintingQuality) | (Security handlers of revision 3 or greater) Skriv ut dokumentet till en representation från vilken en trogen digital kopia av PDF-innehållet kan genereras. När denna bit är avmarkerad (och bit 3 är satt) begränsas utskriften till en låg nivå-representation av utseendet, möjligen med försämrad kvalitet. |

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

(Security handlers of revision 3 or greater) Sammanställ dokumentet (infoga, rotera eller ta bort sidor och skapa bokmärken eller miniatyrbilder), även om {@code ModifyContent} är avmarkerad.

### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```

(Security handlers of revision 2) Kopiera eller på annat sätt extrahera text och grafik från dokumentet, inklusive extrahering av text och grafik (i stöd för tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål). (Security handlers of revision 3 or greater) Kopiera eller på annat sätt extrahera text och grafik från dokumentet genom operationer som inte styrs av {@code ExtractContentWithDisabilities}.

### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```

(Security handlers of revision 3 or greater) Extrahera text och grafik (i stöd för tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål).

### FillForm {#FillForm}
```
public static final int FillForm
```

(Security handlers of revision 3 or greater) Fyll i befintliga interaktiva formulärfält (inklusive signaturfält), även om {@code ModifyTextAnnotations} är avmarkerad.

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Modifiera dokumentets innehåll genom operationer som inte styrs av {@code ModifyTextAnnotations}, {@code FillForm} och 11.

### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```

Lägg till eller ändra textanteckningar, fyll i interaktiva formulärfält, och, om {@code ModifyContent} också är aktiverat, skapa eller ändra interaktiva formulärfält (inklusive signaturfält).

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

(Security handlers of revision 2) Skriv ut dokumentet. (Security handlers of revision 3 or greater) Skriv ut dokumentet (möjligen inte på högsta kvalitet, beroende på om {@code PrintingQuality} också är aktiverat).

### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```

(Security handlers of revision 3 or greater) Skriv ut dokumentet till en representation från vilken en trogen digital kopia av PDF-innehållet kan genereras. När denna bit är avmarkerad (och bit 3 är satt) begränsas utskriften till en låg nivå-representation av utseendet, möjligen med försämrad kvalitet.
