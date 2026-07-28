---
title: "IPdfFileStamp"
linktitle: "IPdfFileStamp"
second_title: "Aspose.PDF för Java API-referens"
description: "gränssnitt för att lägga till stämplar (vattenstämpel eller bakgrund) till PDF‑filer."
type: docs
weight: 320
url: /sv/java/com.aspose.pdf.facades/ipdffilestamp/
---
```
public interface IPdfFileStamp
```

gränssnitt för att lägga till stämplar (vattenstämpel eller bakgrund) till PDF‑filer.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [POS_BOTTOM_LEFT](#POS_BOTTOM_LEFT) | Nedre vänstra positionen. |
| [POS_BOTTOM_MIDDLE](#POS_BOTTOM_MIDDLE) | Nedre mellersta positionen. |
| [POS_BOTTOM_RIGHT](#POS_BOTTOM_RIGHT) | Nedre högra positionen. |
| [POS_SIDES_LEFT](#POS_SIDES_LEFT) | Vänster position. |
| [POS_SIDES_RIGHT](#POS_SIDES_RIGHT) | Höger position. |
| [POS_UPPER_LEFT](#POS_UPPER_LEFT) | Övre vänstra positionen. |
| [POS_UPPER_MIDDLE](#POS_UPPER_MIDDLE) | Övre mellersta positionen. |
| [POS_UPPER_RIGHT](#POS_UPPER_RIGHT) | Övre högra positionen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | Lägger till sidfot på dokumentets sidor. |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | Lägger till sidfot på dokumentets sidor. |
| [addFooter](#addFooter-java.io.InputStream-float-) | Lägger till bild som sidfot på sidan. |
| [addFooter](#addFooter-java.io.InputStream-float-float-float-) | Lägger till bild som sidfot på sidan. |
| [addFooter](#addFooter-java.lang.String-float-) | Lägger till bild som sidfot på dokumentets sidor. |
| [addFooter](#addFooter-java.lang.String-float-float-float-) | Lägger till bild som sidfot på sidorna. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | Lägger till sidhuvud på sidan. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | Lägger till sidhuvud på filens sidor. |
| [addHeader](#addHeader-java.io.InputStream-float-) | Lägger till bild som sidhuvud på sidorna. |
| [addHeader](#addHeader-java.io.InputStream-float-float-float-) | Lägger till bild högst upp på sidan. |
| [addHeader](#addHeader-java.lang.String-float-) | Lägger till bild som sidhuvud på filens sidor. |
| [addHeader](#addHeader-java.lang.String-float-float-float-) | Lägger till bild som sidhuvud på sidorna. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | Lägger till sidnummer på sidan. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | Lägger till sidnummer på den angivna positionen på sidan. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | Lägger till sidnummer på sidorna. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | Lägger till sidnummer på dokumentets sidor. |
| [addPageNumber](#addPageNumber-java.lang.String-) | Lägg till sidnummer i filen. |
| [addPageNumber](#addPageNumber-java.lang.String-float-float-) | Lägger till sidnummer på den angivna positionen på sidan. |
| [addPageNumber](#addPageNumber-java.lang.String-int-) | Lägger till sidnummer på sidorna. |
| [addPageNumber](#addPageNumber-java.lang.String-int-float-float-float-float-) | Lägger till sidnummer på dokumentets sidor. |
| [addStamp](#addStamp-com.aspose.pdf.facades.Stamp-) | Lägger till stämpel i filen. |
| [close](#close--) | Stänger öppnade filer och sparar ändringar. |
| [dispose](#dispose--) | Föråldrad. |
| [getAttachmentName](#getAttachmentName--) | Hämtar namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga. |
| [getContentDisposition](#getContentDisposition--) | Hämtar hur innehållet kommer att lagras när resultatet av operationen lagras i HttpResponse-objektet. |
| [getDocument](#getDocument--) | Hämtar dokumentet som PdfFileStamp arbetar med. |
| [getInputFile](#getInputFile--) | Hämtar namn och sökväg för indatafilen. |
| [getInputStream](#getInputStream--) | Hämtar inmatningsström. |
| [getKeepSecurity](#getKeepSecurity--) | Behåller säkerhet om sant. |
| [getOutputFile](#getOutputFile--) | Hämtar namn och sökväg för utdatafilen. |
| [getOutputStream](#getOutputStream--) | Hämtar utmatningsström. |
| [getPageHeight](#getPageHeight--) | Hämtar höjden på den första sidan i källfilen. |
| [getPageNumberRotation](#getPageNumberRotation--) | Hämtar rotationen för sidnummer. |
| [getPageWidth](#getPageWidth--) | Hämtar bredden på den första sidan i indatafilen. |
| [getSaveOptions](#getSaveOptions--) | Hämtar sparalternativ när resultatet lagras som HttpResponse. |
| [getStartingNumber](#getStartingNumber--) | Hämtar eller anger startnummer för den första sidan i indatafilen. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Ställer in namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Anger hur innehållet kommer att lagras när resultatet av operationen lagras i HttpResponse-objektet. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Anger PDF-filformat. |
| [setInputFile](#setInputFile-java.lang.String-) | Anger namn och sökväg för indatafilen. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Ställer in inmatningsström. |
| [setKeepSecurity](#setKeepSecurity-boolean-) | Ställ in behåll säkerhet |
| [setOutputFile](#setOutputFile-java.lang.String-) | Ställer in namn och sökväg för utdatafil. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Ställer in eller återställer utmatningsström. |
| [setPageNumberRotation](#setPageNumberRotation-float-) | Ställer in rotation för sidnummer. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Ställer in sparalternativ när resultatet lagras som HttpResponse. |
| [setStartingNumber](#setStartingNumber-int-) | Ställer in startnummer för första sidan i inmatningsfilen. |

### POS_BOTTOM_LEFT {#POS_BOTTOM_LEFT}
```
static final int POS_BOTTOM_LEFT
```

Nedre vänstra positionen.

### POS_BOTTOM_MIDDLE {#POS_BOTTOM_MIDDLE}
```
static final int POS_BOTTOM_MIDDLE
```

Nedre mellersta positionen.

### POS_BOTTOM_RIGHT {#POS_BOTTOM_RIGHT}
```
static final int POS_BOTTOM_RIGHT
```

Nedre högra positionen.

### POS_SIDES_LEFT {#POS_SIDES_LEFT}
```
static final int POS_SIDES_LEFT
```

Vänster position.

### POS_SIDES_RIGHT {#POS_SIDES_RIGHT}
```
static final int POS_SIDES_RIGHT
```

Höger position.

### POS_UPPER_LEFT {#POS_UPPER_LEFT}
```
static final int POS_UPPER_LEFT
```

Övre vänstra positionen.

### POS_UPPER_MIDDLE {#POS_UPPER_MIDDLE}
```
static final int POS_UPPER_MIDDLE
```

Övre mellersta positionen.

### POS_UPPER_RIGHT {#POS_UPPER_RIGHT}
```
static final int POS_UPPER_RIGHT
```

Övre högra positionen.

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
Lägger till sidfot på dokumentets sidor.

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
Lägger till sidfot på dokumentets sidor.

### addFooter {#addFooter-java.io.InputStream-float-}
Lägger till bild som sidfot på sidan.

### addFooter {#addFooter-java.io.InputStream-float-float-float-}
Lägger till bild som sidfot på sidan.

### addFooter {#addFooter-java.lang.String-float-}
Lägger till bild som sidfot på dokumentets sidor.

### addFooter {#addFooter-java.lang.String-float-float-float-}
Lägger till bild som sidfot på sidorna.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
Lägger till sidhuvud på sidan.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
Lägger till sidhuvud på filens sidor.

### addHeader {#addHeader-java.io.InputStream-float-}
Lägger till bild som sidhuvud på sidorna.

### addHeader {#addHeader-java.io.InputStream-float-float-float-}
Lägger till bild högst upp på sidan.

### addHeader {#addHeader-java.lang.String-float-}
Lägger till bild som sidhuvud på filens sidor.

### addHeader {#addHeader-java.lang.String-float-float-float-}
Lägger till bild som sidhuvud på sidorna.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
Lägger till sidnummer på sidan.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
Lägger till sidnummer på den angivna positionen på sidan.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
Lägger till sidnummer på sidorna.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
Lägger till sidnummer på dokumentets sidor.

### addPageNumber {#addPageNumber-java.lang.String-}
Lägg till sidnummer i filen.

### addPageNumber {#addPageNumber-java.lang.String-float-float-}
Lägger till sidnummer på den angivna positionen på sidan.

### addPageNumber {#addPageNumber-java.lang.String-int-}
Lägger till sidnummer på sidorna.

### addPageNumber {#addPageNumber-java.lang.String-int-float-float-float-float-}
Lägger till sidnummer på dokumentets sidor.

### addStamp {#addStamp-com.aspose.pdf.facades.Stamp-}
Lägger till stämpel i filen.

### close {#close--}
```
void close()
```

Stänger öppnade filer och sparar ändringar.

### dispose {#dispose--}
```
@Deprecated void dispose()
```

Föråldrad.

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Hämtar namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga.

**Returns:**
String värde

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Hämtar hur innehållet kommer att lagras när resultatet av operationen lagras i HttpResponse-objektet.

**Returns:**
ContentDisposition-element

### getDocument {#getDocument--}
```
IDocument getDocument()
```

Hämtar dokumentet som PdfFileStamp arbetar med.

**Returns:**
IDocument-objekt

### getInputFile {#getInputFile--}
```
String getInputFile()
```

Hämtar namn och sökväg för indatafilen.

**Returns:**
String-objekt

### getInputStream {#getInputStream--}
```
InputStream getInputStream()
```

Hämtar inmatningsström.

**Returns:**
InputStream-objekt

### getKeepSecurity {#getKeepSecurity--}
```
boolean getKeepSecurity()
```

Behåller säkerhet om sant.

**Returns:**
booleskt värde

### getOutputFile {#getOutputFile--}
```
String getOutputFile()
```

Hämtar namn och sökväg för utdatafilen.

**Returns:**
String-objekt

### getOutputStream {#getOutputStream--}
```
OutputStream getOutputStream()
```

Hämtar utmatningsström.

**Returns:**
OutputStream objekt

### getPageHeight {#getPageHeight--}
```
float getPageHeight()
```

Hämtar höjden på den första sidan i källfilen.

**Returns:**
flyttalsvärde

### getPageNumberRotation {#getPageNumberRotation--}
```
float getPageNumberRotation()
```

Hämtar rotationen för sidnummer.

**Returns:**
flyttalsvärde

### getPageWidth {#getPageWidth--}
```
float getPageWidth()
```

Hämtar bredden på den första sidan i indatafilen.

**Returns:**
flyttalsvärde

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Hämtar sparalternativ när resultatet lagras som HttpResponse.

**Returns:**
SaveOptions-objekt

### getStartingNumber {#getStartingNumber--}
```
int getStartingNumber()
```

Hämtar eller anger startnummer för den första sidan i indatafilen.

**Returns:**
int‑värde

### setAttachmentName {#setAttachmentName-java.lang.String-}
Ställer in namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Anger hur innehållet kommer att lagras när resultatet av operationen lagras i HttpResponse-objektet.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Anger PDF-filformat.

### setInputFile {#setInputFile-java.lang.String-}
Anger namn och sökväg för indatafilen.

### setInputStream {#setInputStream-java.io.InputStream-}
Ställer in inmatningsström.

### setKeepSecurity {#setKeepSecurity-boolean-}
```
void setKeepSecurity(boolean value)
```

Ställ in behåll säkerhet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setOutputFile {#setOutputFile-java.lang.String-}
Ställer in namn och sökväg för utdatafil.

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Ställer in eller återställer utmatningsström.

### setPageNumberRotation {#setPageNumberRotation-float-}
```
void setPageNumberRotation(float value)
```

Ställer in rotation för sidnummer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Ställer in sparalternativ när resultatet lagras som HttpResponse.

### setStartingNumber {#setStartingNumber-int-}
```
void setStartingNumber(int value)
```

Ställer in startnummer för första sidan i inmatningsfilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |
