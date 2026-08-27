---
title: "IPdfFileEditor"
linktitle: "IPdfFileEditor"
second_title: "Aspose.PDF för Java API-referens"
description: "Implementerar operationer med PDF‑fil: sammanslagning, delning, extrahering av sidor, skapa häfte, etc."
type: docs
weight: 290
url: /sv/java/com.aspose.pdf.facades/ipdffileeditor/
---
```
public interface IPdfFileEditor
```

Implementerar operationer med PDF‑fil: sammanslagning, delning, extrahering av sidor, skapa häfte, etc.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Ändrar storlek på sidinnehåll och lägger till specificerade marginaler. |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Ändrar storlek på sidinnehåll och lägger till specificerade marginaler. |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Ändrar storlek på sidinnehåll och lägger till specificerade marginaler. |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Ändrar storlek på sidinnehåll och lägger till specificerade marginaler. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | Lägger till sidor som väljs från en array av dokument i portStreams. |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | Lägger till sidor som väljs från portStream inom intervallet från startPage till endPage, i portStream i slutet av firstInputStream. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | Lägger till sidor som väljs från portFiles-dokument. |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | Lägger till sidor som väljs från portFile inom intervallet från startPage till endPage, i portFile i slutet av firstInputFile. |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Kombinerar dokument. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | Konkatenar filer |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor i alternerande ordning och fyller de tomma platserna med tomma sidor. |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Konkatenar två filer. |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | Konkatenar filer till en fil. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | Konkatenar två filer. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor i alternerande ordning och fyller de tomma platserna med tomma sidor. |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | Tar bort sidor som specificeras av en nummerarray från inmatningsfilen, sparar som en ny Pdf-fil. |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | Tar bort sidor som specificeras av en nummerarray från inmatningsfilen, sparar som en ny Pdf-fil. |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | Extraherar sidor som specificeras av en nummerarray, sparar som en ny Pdf-fil. |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | Extraherar sidor från inmatningsfilen, sparar som en ny Pdf-fil. |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | Extraherar sidor som specificeras av en nummerarray, sparar som en ny PDF-fil. |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | Extraherar sidor från inmatningsfilen, sparar som en ny Pdf-fil. |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | är Tillåt Konkatenationsundantag |
| [getAttachmentName](#getAttachmentName--) | Hämtar namn på bilagan när resultatet av operationen lagras i HttpServletResponse-objekt som bilaga. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | Om den är satt till true stängs strömmar efter operationen. |
| [getContentDisposition](#getContentDisposition--) | Hämtar hur innehåll kommer att lagras när resultatet av operationen lagras i ett HttpServletResponse-objekt. |
| [getConversionLog](#getConversionLog--) | Hämtar logg för konverteringsprocessen. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | Denna egenskap definierar beteendet när en concatenating-process möter en korrupt fil. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | Om true görs inkrementella uppdateringar under sammanslagning. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | Om true så kommer fältnamn att göras unika när formulär concatenas. |
| [getLastException](#getLastException--) | Hämtar det senaste inträffade undantaget. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | Valfritt innehåll i sammanfogade dokument med samma namn kommer att slås samman till ett lager i det resulterande dokumentet om denna egenskap är sann. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | Om sant slås dubblettkonturer ihop. |
| [getOwnerPassword](#getOwnerPassword--) | Hämtar ägarens lösenord om den ursprungliga inmatnings-Pdf-filen är krypterad. |
| [getPreserveUserRights](#getPreserveUserRights--) | Om sant tillämpas användarrättigheterna från det första dokumentet på det sammanfogade dokumentet. |
| [getRemoveSignatures](#getRemoveSignatures--) | Om sant tas alla signaturer bort från fält (fälten kvarstår); annars kan du få ogiltiga signaturer. |
| [getSaveOptions](#getSaveOptions--) | Hämtar eller anger sparalternativ när resultatet lagras som HttpServletResponse. |
| [getUniqueSuffix](#getUniqueSuffix--) | Hämta formatet för suffixet som läggs till fältnamnet för att göra det unikt när formulär sammanfogas. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | Infogar sidor från en annan fil i den inkommande PDF-filen. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | Infogar sidor från en annan fil i den inkommande PDF-filen. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | Infogar sidor från en annan fil i den inkommande PDF-filen. |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | Infogar sidor från en annan fil i PDF-filen på en position. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | Skapar häfte från InputStream till outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | Skapar anpassat häfte från firstInputStream till outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | Skapar häfte från inmatningsströmmen och sparar resultatet i output stream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | Skapar häfte från firstInputStream till outputStream. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | Skapar häfte från indatafilen till utdatafilen. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | Skapar anpassat häfte från firstInputFile till outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | Skapar häfte från inputFile till outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | Skapar anpassat häfte från firstInputFile till outputFile. |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | Skapar N-Up-dokument från de flera inmatnings-PDF-strömmarna till outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Skapar N-Up-dokument från de två inmatnings-PDF-strömmarna till outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | Skapar N-Up-dokument från inmatningsströmmen och sparar resultatet i output stream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | Skapar N-Up-dokument från firstInputStream till output stream. |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | Skapar N-Up-dokument från de flera inmatnings-PDF-filerna till outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | Skapar N-Up-dokument från firstInputFile till outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | Skapar N-Up-dokument från inputFile till outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | Skapar N-Up-dokument från de två inmatnings-PDF-filerna till outputFile. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Ändrar storlek på innehållet i dokumentsidor. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | Ändrar storlek på innehållet i dokumentsidor. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Ändrar storlek på innehållet i dokumentsidor. |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | Ändrar storlek på innehållet i dokumentsidor. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | Om satt till true kastas undantag om ett fel inträffade. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Ställer in namn på bilagan när resultatet av operationen lagras i HttpServletResponse-objekt som bilaga. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | Om den är satt till true stängs strömmar efter operationen. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Ställer in hur innehåll ska lagras när resultatet av operationen lagras i HttpServletResponse-objektet. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Anger PDF-filformat. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | Denna egenskap definierar beteendet när en concatenating-process möter en korrupt fil. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | Om true görs inkrementella uppdateringar under sammanslagning. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | Om true så kommer fältnamn att göras unika när formulär concatenas. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | Valfritt innehåll i sammanfogade dokument med samma namn kommer att slås samman till ett lager i det resulterande dokumentet om denna egenskap är sann. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | Om sant slås dubblettkonturer ihop. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Ställer in ägarens lösenord om källfilens indata-PDF är krypterad. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | Om sant tillämpas användarrättigheterna från det första dokumentet på det sammanfogade dokumentet. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | Om sant tas alla signaturer bort från fält (fälten kvarstår); annars kan du få ogiltiga signaturer. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Ställer in sparalternativ när resultatet lagras som HttpServletResponse. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | Ange formatet för suffixet som läggs till fältnamnet för att göra det unikt när formulär sammanfogas. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | Delar från början till angiven plats och sparar den främre delen i output Stream. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | Delar Pdf-filen från första sidan till angiven plats och sparar den främre delen som en ny fil. |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Delar PDF-filen i flera dokument. Dokumenten kan vara enstaka sidor eller flersidiga. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Delar PDF-filen i flera dokument. Dokumenten kan vara enstaka sidor eller flersidiga. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | Delar från angiven plats och sparar den bakre delen som en ny filström. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | Delar från plats och sparar den bakre delen som en ny fil. |
| [splitToPages](#splitToPages-java.io.InputStream-) | Delar PDF-filen i enstaka sidodokument. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Dela PDF-filen i enstaka sidodokument och spara den på angiven sökväg. |
| [splitToPages](#splitToPages-java.lang.String-) | Delar PDF-filen i enstaka sidodokument. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Dela PDF-filen i enstaka sidodokument och spara den på angiven sökväg. |

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Ändrar storlek på sidinnehåll och lägger till specificerade marginaler.

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Ändrar storlek på sidinnehåll och lägger till specificerade marginaler.

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Ändrar storlek på sidinnehåll och lägger till specificerade marginaler.

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Ändrar storlek på sidinnehåll och lägger till specificerade marginaler.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
Lägger till sidor som väljs från en array av dokument i portStreams.

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
Lägger till sidor som väljs från portStream inom intervallet från startPage till endPage, i portStream i slutet av firstInputStream.

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
Lägger till sidor som väljs från portFiles-dokument.

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
Lägger till sidor som väljs från portFile inom intervallet från startPage till endPage, i portFile i slutet av firstInputFile.

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Kombinerar dokument.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
Konkatenar filer

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor i alternerande ordning och fyller de tomma platserna med tomma sidor.

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Konkatenar två filer.

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
Konkatenar filer till en fil.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
Konkatenar två filer.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor i alternerande ordning och fyller de tomma platserna med tomma sidor.

### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
Tar bort sidor som specificeras av en nummerarray från inmatningsfilen, sparar som en ny Pdf-fil.

### delete {#delete-java.lang.String-int:A-java.lang.String-}
Tar bort sidor som specificeras av en nummerarray från inmatningsfilen, sparar som en ny Pdf-fil.

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
Extraherar sidor som specificeras av en nummerarray, sparar som en ny Pdf-fil.

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
Extraherar sidor från inmatningsfilen, sparar som en ny Pdf-fil.

### extract {#extract-java.lang.String-int:A-java.lang.String-}
Extraherar sidor som specificeras av en nummerarray, sparar som en ny PDF-fil.

### extract {#extract-java.lang.String-int-int-java.lang.String-}
Extraherar sidor från inmatningsfilen, sparar som en ny Pdf-fil.

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
boolean getAllowConcatenateExceptions()
```

är Tillåt Konkatenationsundantag

**Returns:**
booleskt värde

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Hämtar namn på bilagan när resultatet av operationen lagras i HttpServletResponse-objekt som bilaga.

**Returns:**
strängvärde

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
boolean getCloseConcatenatedStreams()
```

Om den är satt till true stängs strömmar efter operationen.

**Returns:**
booleskt värde

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Hämtar hur innehåll kommer att lagras när resultatet av operationen lagras i ett HttpServletResponse-objekt.

**Returns:**
ContentDisposition-element

### getConversionLog {#getConversionLog--}
```
String getConversionLog()
```

Hämtar logg för konverteringsprocessen.

**Returns:**
strängvärde

### getCorruptedFileAction {#getCorruptedFileAction--}
```
int getCorruptedFileAction()
```

Denna egenskap definierar beteendet när en concatenating-process möter en korrupt fil.

**Returns:**
ConcatenateCorruptedFileAction‑element

### getIncrementalUpdates {#getIncrementalUpdates--}
```
boolean getIncrementalUpdates()
```

Om true görs inkrementella uppdateringar under sammanslagning.

**Returns:**
booleskt värde

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
boolean getKeepFieldsUnique()
```

Om true så kommer fältnamn att göras unika när formulär concatenas.

**Returns:**
booleskt värde

### getLastException {#getLastException--}
```
Exception getLastException()
```

Hämtar det senaste inträffade undantaget.

**Returns:**
java.lang.Exception-objekt

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
boolean getMergeDuplicateLayers()
```

Valfritt innehåll i sammanfogade dokument med samma namn kommer att slås samman till ett lager i det resulterande dokumentet om denna egenskap är sann.

**Returns:**
booleskt värde

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
boolean getMergeDuplicateOutlines()
```

Om sant slås dubblettkonturer ihop.

**Returns:**
booleskt värde

### getOwnerPassword {#getOwnerPassword--}
```
String getOwnerPassword()
```

Hämtar ägarens lösenord om den ursprungliga inmatnings-Pdf-filen är krypterad.

**Returns:**
strängvärde

### getPreserveUserRights {#getPreserveUserRights--}
```
boolean getPreserveUserRights()
```

Om sant tillämpas användarrättigheterna från det första dokumentet på det sammanfogade dokumentet.

**Returns:**
booleskt värde

### getRemoveSignatures {#getRemoveSignatures--}
```
boolean getRemoveSignatures()
```

Om sant tas alla signaturer bort från fält (fälten kvarstår); annars kan du få ogiltiga signaturer.

**Returns:**
booleskt värde

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Hämtar eller anger sparalternativ när resultatet lagras som HttpServletResponse.

**Returns:**
SaveOptions-objekt

### getUniqueSuffix {#getUniqueSuffix--}
```
String getUniqueSuffix()
```

Hämta formatet för suffixet som läggs till fältnamnet för att göra det unikt när formulär sammanfogas.

**Returns:**
strängvärde

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
Infogar sidor från en annan fil i den inkommande PDF-filen.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
Infogar sidor från en annan fil i den inkommande PDF-filen.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
Infogar sidor från en annan fil i den inkommande PDF-filen.

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
Infogar sidor från en annan fil i PDF-filen på en position.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
Skapar häfte från InputStream till outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
Skapar anpassat häfte från firstInputStream till outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
Skapar häfte från inmatningsströmmen och sparar resultatet i output stream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
Skapar häfte från firstInputStream till outputStream.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
Skapar häfte från indatafilen till utdatafilen.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
Skapar anpassat häfte från firstInputFile till outputFile.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
Skapar häfte från inputFile till outputFile.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
Skapar anpassat häfte från firstInputFile till outputFile.

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
Skapar N-Up-dokument från de flera inmatnings-PDF-strömmarna till outputStream.

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Skapar N-Up-dokument från de två inmatnings-PDF-strömmarna till outputStream.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
Skapar N-Up-dokument från inmatningsströmmen och sparar resultatet i output stream.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
Skapar N-Up-dokument från firstInputStream till output stream.

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
Skapar N-Up-dokument från de flera inmatnings-PDF-filerna till outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
Skapar N-Up-dokument från firstInputFile till outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
Skapar N-Up-dokument från inputFile till outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
Skapar N-Up-dokument från de två inmatnings-PDF-filerna till outputFile.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Ändrar storlek på innehållet i dokumentsidor.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
Ändrar storlek på innehållet i dokumentsidor.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Ändrar storlek på innehållet i dokumentsidor.

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
Ändrar storlek på innehållet i dokumentsidor.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
void setAllowConcatenateExceptions(boolean value)
```

Om satt till true kastas undantag om ett fel inträffade.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setAttachmentName {#setAttachmentName-java.lang.String-}
Ställer in namn på bilagan när resultatet av operationen lagras i HttpServletResponse-objekt som bilaga.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
void setCloseConcatenatedStreams(boolean value)
```

Om den är satt till true stängs strömmar efter operationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Ställer in hur innehåll ska lagras när resultatet av operationen lagras i HttpServletResponse-objektet.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Anger PDF-filformat.

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
void setCorruptedFileAction(int value)
```

Denna egenskap definierar beteendet när en concatenating-process möter en korrupt fil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | ConcatenateCorruptedFileAction‑element |

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
void setIncrementalUpdates(boolean value)
```

Om true görs inkrementella uppdateringar under sammanslagning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
void setKeepFieldsUnique(boolean value)
```

Om true så kommer fältnamn att göras unika när formulär concatenas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
void setMergeDuplicateLayers(boolean value)
```

Valfritt innehåll i sammanfogade dokument med samma namn kommer att slås samman till ett lager i det resulterande dokumentet om denna egenskap är sann.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
void setMergeDuplicateOutlines(boolean value)
```

Om sant slås dubblettkonturer ihop.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
Ställer in ägarens lösenord om källfilens indata-PDF är krypterad.

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
void setPreserveUserRights(boolean value)
```

Om sant tillämpas användarrättigheterna från det första dokumentet på det sammanfogade dokumentet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
void setRemoveSignatures(boolean value)
```

Om sant tas alla signaturer bort från fält (fälten kvarstår); annars kan du få ogiltiga signaturer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Ställer in sparalternativ när resultatet lagras som HttpServletResponse.

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
Ange formatet för suffixet som läggs till fältnamnet för att göra det unikt när formulär sammanfogas.

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
Delar från början till angiven plats och sparar den främre delen i output Stream.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
Delar Pdf-filen från första sidan till angiven plats och sparar den främre delen som en ny fil.

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Delar PDF-filen i flera dokument. Dokumenten kan vara enstaka sidor eller flersidiga.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Delar PDF-filen i flera dokument. Dokumenten kan vara enstaka sidor eller flersidiga.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
Delar från angiven plats och sparar den bakre delen som en ny filström.

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
Delar från plats och sparar den bakre delen som en ny fil.

### splitToPages {#splitToPages-java.io.InputStream-}
Delar PDF-filen i enstaka sidodokument.

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
Dela PDF-filen i enstaka sidodokument och spara den på angiven sökväg.

### splitToPages {#splitToPages-java.lang.String-}
Delar PDF-filen i enstaka sidodokument.

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
Dela PDF-filen i enstaka sidodokument och spara den på angiven sökväg.
