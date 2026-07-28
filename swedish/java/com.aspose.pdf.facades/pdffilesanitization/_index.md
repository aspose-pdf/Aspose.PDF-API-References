---
title: "PdfFileSanitization"
linktitle: "PdfFileSanitization"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar sanerings- och återställnings-API. Använd det om du inte kan skapa/öppna dokument på annat sätt."
type: docs
weight: 510
url: /sv/java/com.aspose.pdf.facades/pdffilesanitization/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSanitization, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSanitization, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSanitization

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSanitization extends SaveableFacade implements com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery
```

Representerar sanerings- och återställnings-API. Använd det om du inte kan skapa/öppna dokument på annat sätt.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PdfFileSanitization](#PdfFileSanitization--) | Initierar en ny instans. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.Document-) | Initierar fasaden. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Kopplar en Pdf-ström för sanering. |
| [bindPdf](#bindPdf-java.lang.String-) | Kopplar en Pdf-fil för sanering. |
| [close](#close--) | Stänger fasaden. |
| [getLog](#getLog--) | Efter att filen har sparats kan du kontrollera vad som gjordes med filen. |
| [getUseRebuildXrefAndTrailer](#getUseRebuildXrefAndTrailer--) | Tillåter att generera ny xref och trailer för dokumentet. |
| [getUseTrimBottom](#getUseTrimBottom--) | Tillåter att ta bort data efter pdf-data |
| [getUseTrimTop](#getUseTrimTop--) | Tillåter att ta bort data före pdf-data. |
| [rebuildXrefAndTrailer](#rebuildXrefAndTrailer--) | Tar bort gammal xref med trailer och skapar en ny xref med trailer. |
| [recover](#recover--) | Återställer dokumentet. Använd egenskaper för att anpassa. |
| [save](#save-java.io.OutputStream-) | Sparar resultat-PDF till ström. |
| [save](#save-java.lang.String-) | Sparar resultat-PDF till fil. |
| [setUseRebuildXrefAndTrailer](#setUseRebuildXrefAndTrailer-boolean-) | Tillåter att generera ny xref och trailer för dokumentet. |
| [setUseTrimBottom](#setUseTrimBottom-boolean-) | Tillåter att ta bort data efter pdf-data |
| [setUseTrimTop](#setUseTrimTop-boolean-) | Tillåter att ta bort data före pdf-data. |
| [trimBottom](#trimBottom--) | Tar bort data efter sista %%EOF. |
| [trimTop](#trimTop--) | Tar bort data före %PDF. |

### PdfFileSanitization {#PdfFileSanitization--}
```
public PdfFileSanitization()
```

Initierar en ny instans.

### bindPdf {#bindPdf-com.aspose.pdf.Document-}
Initierar fasaden.

### bindPdf {#bindPdf-java.io.InputStream-}
Kopplar en Pdf-ström för sanering.

### bindPdf {#bindPdf-java.lang.String-}
Kopplar en Pdf-fil för sanering.

### close {#close--}
```
public void close()
```

Stänger fasaden.

### getLog {#getLog--}
```
public final List < String > getLog()
```

Efter att filen har sparats kan du kontrollera vad som gjordes med filen.

**Returns:**
lista med String-element

### getUseRebuildXrefAndTrailer {#getUseRebuildXrefAndTrailer--}
```
public final boolean getUseRebuildXrefAndTrailer()
```

Tillåter att generera ny xref och trailer för dokumentet.

**Returns:**
booleskt värde

### getUseTrimBottom {#getUseTrimBottom--}
```
public final boolean getUseTrimBottom()
```

Tillåter att ta bort data efter pdf-data

**Returns:**
booleskt värde

### getUseTrimTop {#getUseTrimTop--}
```
public final boolean getUseTrimTop()
```

Tillåter att ta bort data före pdf-data.

**Returns:**
booleskt värde

### rebuildXrefAndTrailer {#rebuildXrefAndTrailer--}
```
public final void rebuildXrefAndTrailer()
```

Tar bort gammal xref med trailer och skapar en ny xref med trailer.

### recover {#recover--}
```
public final void recover()
```

Återställer dokumentet. Använd egenskaper för att anpassa.

### save {#save-java.io.OutputStream-}
Sparar resultat-PDF till ström.

### save {#save-java.lang.String-}
Sparar resultat-PDF till fil.

### setUseRebuildXrefAndTrailer {#setUseRebuildXrefAndTrailer-boolean-}
```
public final void setUseRebuildXrefAndTrailer(boolean value)
```

Tillåter att generera ny xref och trailer för dokumentet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setUseTrimBottom {#setUseTrimBottom-boolean-}
```
public final void setUseTrimBottom(boolean value)
```

Tillåter att ta bort data efter pdf-data

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setUseTrimTop {#setUseTrimTop-boolean-}
```
public final void setUseTrimTop(boolean value)
```

Tillåter att ta bort data före pdf-data.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### trimBottom {#trimBottom--}
```
public final void trimBottom()
```

Tar bort data efter sista %%EOF.

### trimTop {#trimTop--}
```
public final void trimTop()
```

Tar bort data före %PDF.
