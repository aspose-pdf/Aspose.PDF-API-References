---
title: "PdfFileEditorWeb"
linktitle: "PdfFileEditorWeb"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar PdfFileEditorWeb-klassen som implementerar operationer med PDF-filer: sammanslagning, delning, extrahering av sidor, skapa häfte osv."
type: docs
weight: 480
url: /sv/java/com.aspose.pdf.facades/pdffileeditorweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfFileEditorWeb

**All Implemented Interfaces:**
IPdfFileEditor

```
public final class PdfFileEditorWeb extends Object implements IPdfFileEditor
```

Representerar PdfFileEditorWeb-klassen som implementerar operationer med PDF-filer: sammanslagning, delning, extrahering av sidor, skapa häfte osv.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PdfFileEditorWeb](#PdfFileEditorWeb--) | PdfFileEditorWeb-konstruktor. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Ändrar storlek på sidinnehåll och lägger till specificerade marginaler. |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Ändrar storlek på sidinnehåll och lägger till specificerade marginaler. |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Ändrar storlek på sidinnehåll och lägger till specificerade marginaler. |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Ändrar storlek på sidinnehåll och lägger till specificerade marginaler. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Lägger till sidbrytningar i dokumentets sidor. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Lägger till sidbrytningar i dokumentets sidor. |
| [addPageBreak](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Lägger till sidbrytningar i dokumentets sidor. |
| [addPageBreak](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Lägger till sidbrytningar i dokumentets sidor. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-javax.servlet.http.HttpServletResponse-) | Lägger till dokument till källdokumentet och sparar resultatet i svarobjektet. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | Lägger till sidor som väljs från en array av dokument i portStreams. |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | Lägger till sidor som väljs från portStream inom intervallet från startPage till endPage, i portStream i slutet av firstInputStream. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-javax.servlet.http.HttpServletResponse-) | Lägger till dokument till källdokumentet och sparar resultatet i HttpServletResponse-objektet. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | Lägger till sidor som väljs från portFiles-dokument. |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | Lägger till sidor som väljs från portFile inom intervallet från startPage till endPage, i portFile i slutet av firstInputFile. |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Kombinerar dokument. |
| [concatenate](#concatenate-java.io.InputStream:A-javax.servlet.http.HttpServletResponse-) | Kedjar ihop filer och lagrar resultatet i HttpServletResponse-objektet. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | Konkatenar filer |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor i alternerande ordning och fyller de tomma platserna med tomma sidor. |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Konkatenar två filer. |
| [concatenate](#concatenate-java.lang.String:A-javax.servlet.http.HttpServletResponse-) | Kedjar ihop filer och sparar reslt i HttpResposnse-objektet. |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | Konkatenar filer till en fil. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | Konkatenar två filer. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor i alternerande ordning och fyller de tomma platserna med tomma sidor. |
| [createArrayWithExclusion](#createArrayWithExclusion-int-int-) |  |
| [delete](#delete-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Tar bort angivna sidor från dokumentet och sparar resultatet i HttpServletResponse-objektet. |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | Tar bort sidor som specificeras av en nummerarray från inmatningsfilen, sparar som en ny Pdf-fil. |
| [delete](#delete-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Tar bort angivna sidor från dokumentet och lagrar resultatet i HttpServletResponse-objektet. |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | Tar bort sidor som specificeras av en nummerarray från inmatningsfilen, sparar som en ny Pdf-fil. |
| [extract](#extract-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Extraherar angivna sidor från källfilen och lagrar resultatet i HttpServletResponse-objektet. |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | Extraherar sidor som specificeras av en nummerarray, sparar som en ny Pdf-fil. |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | Extraherar sidor från inmatningsfilen, sparar som en ny Pdf-fil. |
| [extract](#extract-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Extraherar angivna sidor från källfilen och lagrar resultatet i HttpServletResponse-objektet. |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | Extraherar sidor som specificeras av en nummerarray, sparar som en ny PDF-fil. |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | Extraherar sidor från inmatningsfilen, sparar som en ny Pdf-fil. |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | Föråldrad. Denna egenskap är föråldrad och kan inte användas för att tillåta att kasta undantag. |
| [getAttachmentName](#getAttachmentName--) | Hämtar namn på bilagan när resultatet av operationen lagras i HttpServletResponse-objekt som bilaga. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | Om den är satt till true stängs strömmar efter operationen. |
| [getConcatenationPacketSize](#getConcatenationPacketSize--) | Antal dokument som sammanfogades innan en ny inkrementell uppdatering gjordes under sammanslagning när UseDiskBuffer är satt till true. |
| [getContentDisposition](#getContentDisposition--) | Hämtar hur innehåll kommer att lagras när resultatet av operationen lagras i ett HttpServletResponse-objekt. |
| [getConversionLog](#getConversionLog--) | Hämtar logg för konverteringsprocessen. |
| [getCopyLogicalStructure](#getCopyLogicalStructure--) | Om true kopieras den logiska strukturen i filen när sammanslagning utförs. |
| [getCopyOutlines](#getCopyOutlines--) | Om true kopieras konturerna. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | Denna egenskap definierar beteendet när en concatenating-process möter en korrupt fil. |
| [getCorruptedItems](#getCorruptedItems--) | Array av uppkomna problem när sammanslagning utfördes. |
| [getCustomProgressConcatenationHandler](#getCustomProgressConcatenationHandler--) | Representation av intern processor för förloppshändelser som arbetar under sammanslagning och översätter sammanslagningshändelser från interna sammanslagningssteg till extern kundkod. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | Om true görs inkrementella uppdateringar under sammanslagning. |
| [getKeepActions](#getKeepActions--) | Om true kopieras åtgärder från källdokumenten. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | Om true så kommer fältnamn att göras unika när formulär concatenas. |
| [getLastException](#getLastException--) | Hämtar det senast inträffade undantaget. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | Valfritt innehåll i sammanfogade dokument med samma namn kommer att slås samman till ett lager i det resulterande dokumentet om denna egenskap är sann. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | Om sant slås dubblettkonturer ihop. |
| [getOptimizeSize](#getOptimizeSize--) | Hämtar eller anger optimeringsflagga. |
| [getOwnerPassword](#getOwnerPassword--) | Hämtar ägarens lösenord om den ursprungliga inmatnings-Pdf-filen är krypterad. |
| [getPreserveUserRights](#getPreserveUserRights--) | Om sant tillämpas användarrättigheterna från det första dokumentet på det sammanfogade dokumentet. |
| [getRemoveSignatures](#getRemoveSignatures--) | Om sant tas alla signaturer bort från fält (fälten kvarstår); annars kan du få ogiltiga signaturer. |
| [getSaveOptions](#getSaveOptions--) | Hämtar eller anger sparalternativ när resultatet lagras som HttpServletResponse. |
| [getUniqueSuffix](#getUniqueSuffix--) | Hämta formatet för suffixet som läggs till fältnamnet för att göra det unikt när formulär sammanfogas. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Infogar dokument i ett annat dokument och lagrar resultatet i svarobjektet. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | Infogar sidor från en annan fil i den inkommande PDF-filen. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | Infogar sidor från en annan fil i den inkommande PDF-filen. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Infogar innehållet i filen i källfilen och lagrar resultatet i HttpServletResponse-objektet. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | Infogar sidor från en annan fil i den inkommande PDF-filen. |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | Infogar sidor från en annan fil i PDF-filen på en position. |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | Ibland innehåller PDF-filer bakgrundsbilder (av sidor eller tabellceller) som är konstruerade av flera identiska mosaikbakgrundsbilder placerade intill varandra. |
| [isUseDiskBuffer](#isUseDiskBuffer--) | Om detta alternativ används sparas destinationsdokumentet på disk periodiskt och vidare sammanslagning tillämpas på det som inkrementella uppdateringar. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | Skapar häfte från InputStream till outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | Skapar anpassat häfte från firstInputStream till outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | Skapar häfte från inmatningsströmmen och sparar resultatet i output stream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | Skapar häfte från firstInputStream till outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Skapar häfte från källfilen och lagrar resultatet i HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-) | Skapa häfte från PDF-fil och lagra det i HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Skapar häfte från källfilen och lagrar resultatet i HttpServletResponse-objekt. |
| [makeBooklet](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-) | Skapar häfte från källfilen och lagrar resultatet i HttpServletResponse-objekt. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | Skapar häfte från indatafilen till utdatafilen. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | Skapar anpassat häfte från firstInputFile till outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | Skapar häfte från inputFile till outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | Skapar anpassat häfte från firstInputFile till outputFile. |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | Skapar N-Up-dokument från de flera inmatnings-PDF-strömmarna till outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Skapar N-Up-dokument från de två inmatnings-PDF-strömmarna till outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-) | Skapar N-up-dokument och lagrar resultatet i HttpServletResponse. |
| [makeNUp](#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Skapar N-up-dokument och lagrar resultatet i HttpServletResponse-objektet. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | Skapar N-Up-dokument från inmatningsströmmen och sparar resultatet i output stream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | Skapar N-Up-dokument från firstInputStream till output stream. |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | Skapar N-Up-dokument från de flera inmatnings-PDF-filerna till outputFile. |
| [makeNUp](#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-) | Skapar N-up-dokument och lagrar resultatet i HttpServletResponse. |
| [makeNUp](#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Skapar N-up-dokument och lagrar resultatet i HttpServletResponse-objektet. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | Skapar N-Up-dokument från firstInputFile till outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | Skapar N-Up-dokument från inputFile till outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | Skapar N-Up-dokument från de två inmatnings-PDF-filerna till outputFile. |
| [resizeContents](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ändrar storlek på dokumentets sidor. |
| [resizeContents](#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ändrar storlek på dokumentets sidor. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Ändrar storlek på innehållet i dokumentsidor. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ändrar storlek på innehållet i dokumentets sidor. |
| [resizeContents](#resizeContents-com.aspose.ms.System.IO.Stream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | Ändrar storlek på innehållet i sidor i dokumentet. |
| [resizeContents](#resizeContents-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | Ändrar storlek på innehållet i sidor i dokumentet. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | Ändrar storlek på innehållet i dokumentsidor. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ändrar storlek på innehållet i sidor i dokumentet. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Ändrar storlek på innehållet i dokumentsidor. |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | Ändrar storlek på innehållet i dokumentsidor. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ändrar storlek på dokumentets sidor. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ändrar storlek på dokumentets sidor. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | Föråldrad. Denna egenskap är föråldrad och kan inte användas för att tillåta att kasta undantag. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Ställer in namn på bilagan när resultatet av operationen lagras i HttpServletResponse-objekt som bilaga. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | Om den är satt till true stängs strömmar efter operationen. |
| [setConcatenationPacketSize](#setConcatenationPacketSize-int-) | Antal dokument som sammanfogades innan en ny inkrementell uppdatering gjordes under sammanslagning när UseDiskBuffer är satt till true. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Ställer in hur innehåll ska lagras när resultatet av operationen lagras i HttpServletResponse-objektet. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Anger PDF-filformat. |
| [setCopyLogicalStructure](#setCopyLogicalStructure-boolean-) | Om true kopieras den logiska strukturen i filen när sammanslagning utförs. |
| [setCopyOutlines](#setCopyOutlines-boolean-) | Om true kopieras konturerna. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | Denna egenskap definierar beteendet när en concatenating-process möter en korrupt fil. |
| [setCustomProgressConcatenationHandler](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | Representation av intern processor för förloppshändelser som arbetar under sammanslagning och översätter sammanslagningshändelser från interna sammanslagningssteg till extern kundkod. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | Om true görs inkrementella uppdateringar under sammanslagning. |
| [setKeepActions](#setKeepActions-boolean-) | Om true kopieras åtgärder från källdokumenten. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | Om true så kommer fältnamn att göras unika när formulär concatenas. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | Valfritt innehåll i sammanfogade dokument med samma namn kommer att slås samman till ett lager i det resulterande dokumentet om denna egenskap är sann. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | Om sant slås dubblettkonturer ihop. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Hämtar eller anger optimeringsflagga. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Ställer in ägarens lösenord om källfilens indata-PDF är krypterad. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | Om sant tillämpas användarrättigheterna från det första dokumentet på det sammanfogade dokumentet. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | Om sant tas alla signaturer bort från fält (fälten kvarstår); annars kan du få ogiltiga signaturer. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Ställer in sparalternativ när resultatet lagras som HttpServletResponse. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Ibland innehåller PDF-filer bakgrundsbilder (av sidor eller tabellceller) som är konstruerade av flera identiska mosaikbakgrundsbilder placerade intill varandra. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | Ange formatet för suffixet som läggs till fältnamnet för att göra det unikt när formulär sammanfogas. |
| [setUseDiskBuffer](#setUseDiskBuffer-boolean-) | Om detta alternativ används sparas destinationsdokumentet på disk periodiskt och vidare sammanslagning tillämpas på det som inkrementella uppdateringar. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | Delar dokumentet från början till angiven plats och lagrar resultatet i HttpServletResponse-objektet. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | Delar från början till angiven plats och sparar den främre delen i output Stream. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | Delar dokumentet från första sidan till platsen och sparar resultatet i HttpServletResponse-objekt. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | Delar Pdf-filen från första sidan till angiven plats och sparar den främre delen som en ny fil. |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Delar PDF-filen i flera dokument. Dokumenten kan vara enstaka sidor eller flersidiga. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Delar PDF-filen i flera dokument. Dokumenten kan vara enstaka sidor eller flersidiga. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | Delar från angiven plats och sparar den bakre delen i HttpServletResponse-objektet. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | Delar från angiven plats och sparar den bakre delen som en ny filström. |
| [splitToEnd](#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | Delar från angiven plats och sparar den bakre delen i HttpServletResponse-objektet. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | Delar från plats och sparar den bakre delen som en ny fil. |
| [splitToPages](#splitToPages-java.io.InputStream-) | Delar PDF-filen i enstaka sidodokument. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Dela PDF-filen i enstaka sidodokument och spara den på angiven sökväg. |
| [splitToPages](#splitToPages-java.lang.String-) | Delar PDF-filen i enstaka sidodokument. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Dela PDF-filen i enstaka sidodokument och spara den på angiven sökväg. |

### PdfFileEditorWeb {#PdfFileEditorWeb--}
```
public PdfFileEditorWeb()
```

PdfFileEditorWeb-konstruktor.

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Ändrar storlek på sidinnehåll och lägger till specificerade marginaler.

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Ändrar storlek på sidinnehåll och lägger till specificerade marginaler.

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Ändrar storlek på sidinnehåll och lägger till specificerade marginaler.

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Ändrar storlek på sidinnehåll och lägger till specificerade marginaler.

### addPageBreak {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Lägger till sidbrytningar i dokumentets sidor.

### addPageBreak {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Lägger till sidbrytningar i dokumentets sidor.

### addPageBreak {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Lägger till sidbrytningar i dokumentets sidor.

### addPageBreak {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Lägger till sidbrytningar i dokumentets sidor.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-javax.servlet.http.HttpServletResponse-}
Lägger till dokument till källdokumentet och sparar resultatet i svarobjektet.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
Lägger till sidor som väljs från en array av dokument i portStreams.

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
Lägger till sidor som väljs från portStream inom intervallet från startPage till endPage, i portStream i slutet av firstInputStream.

### append {#append-java.lang.String-java.lang.String:A-int-int-javax.servlet.http.HttpServletResponse-}
Lägger till dokument till källdokumentet och sparar resultatet i HttpServletResponse-objektet.

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
Lägger till sidor som väljs från portFiles-dokument.

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
Lägger till sidor som väljs från portFile inom intervallet från startPage till endPage, i portFile i slutet av firstInputFile.

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Kombinerar dokument.

### concatenate {#concatenate-java.io.InputStream:A-javax.servlet.http.HttpServletResponse-}
Kedjar ihop filer och lagrar resultatet i HttpServletResponse-objektet.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
Konkatenar filer

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor i alternerande ordning och fyller de tomma platserna med tomma sidor.

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Konkatenar två filer.

### concatenate {#concatenate-java.lang.String:A-javax.servlet.http.HttpServletResponse-}
Kedjar ihop filer och sparar reslt i HttpResposnse-objektet.

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
Konkatenar filer till en fil.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
Konkatenar två filer.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor i alternerande ordning och fyller de tomma platserna med tomma sidor.

### createArrayWithExclusion {#createArrayWithExclusion-int-int-}
```
public static Integer [] createArrayWithExclusion(int n, int y)
```



### delete {#delete-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Tar bort angivna sidor från dokumentet och sparar resultatet i HttpServletResponse-objektet.

### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
Tar bort sidor som specificeras av en nummerarray från inmatningsfilen, sparar som en ny Pdf-fil.

### delete {#delete-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Tar bort angivna sidor från dokumentet och lagrar resultatet i HttpServletResponse-objektet.

### delete {#delete-java.lang.String-int:A-java.lang.String-}
Tar bort sidor som specificeras av en nummerarray från inmatningsfilen, sparar som en ny Pdf-fil.

### extract {#extract-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Extraherar angivna sidor från källfilen och lagrar resultatet i HttpServletResponse-objektet.

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
Extraherar sidor som specificeras av en nummerarray, sparar som en ny Pdf-fil.

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
Extraherar sidor från inmatningsfilen, sparar som en ny Pdf-fil.

### extract {#extract-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Extraherar angivna sidor från källfilen och lagrar resultatet i HttpServletResponse-objektet.

### extract {#extract-java.lang.String-int:A-java.lang.String-}
Extraherar sidor som specificeras av en nummerarray, sparar som en ny PDF-fil.

### extract {#extract-java.lang.String-int-int-java.lang.String-}
Extraherar sidor från inmatningsfilen, sparar som en ny Pdf-fil.

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
@Deprecated public boolean getAllowConcatenateExceptions()
```

Föråldrad. Denna egenskap är föråldrad och kan inte användas för att tillåta att kasta undantag.

**Returns:**
Booleskt värde

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Hämtar namn på bilagan när resultatet av operationen lagras i HttpServletResponse-objekt som bilaga.

**Returns:**
strängvärde

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
public boolean getCloseConcatenatedStreams()
```

Om den är satt till true stängs strömmar efter operationen.

**Returns:**
booleskt värde

### getConcatenationPacketSize {#getConcatenationPacketSize--}
```
public final int getConcatenationPacketSize()
```

Antal dokument som sammanfogades innan en ny inkrementell uppdatering gjordes under sammanslagning när UseDiskBuffer är satt till true.

**Returns:**
int‑värde

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Hämtar hur innehåll kommer att lagras när resultatet av operationen lagras i ett HttpServletResponse-objekt.

**Returns:**
ContentDisposition-element

### getConversionLog {#getConversionLog--}
```
public String getConversionLog()
```

Hämtar logg för konverteringsprocessen.

**Returns:**
strängvärde

### getCopyLogicalStructure {#getCopyLogicalStructure--}
```
public boolean getCopyLogicalStructure()
```

Om true kopieras den logiska strukturen i filen när sammanslagning utförs.

**Returns:**
booleskt värde

### getCopyOutlines {#getCopyOutlines--}
```
public boolean getCopyOutlines()
```

Om true kopieras konturerna.

**Returns:**
booleskt värde

### getCorruptedFileAction {#getCorruptedFileAction--}
```
public int getCorruptedFileAction()
```

Denna egenskap definierar beteendet när en concatenating-process möter en korrupt fil.

**Returns:**
ConcatenateCorruptedFileAction‑element

### getCorruptedItems {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem [] getCorruptedItems()
```

Array av uppkomna problem när sammanslagning utfördes.

**Returns:**
PdfFileEditor.CorruptedItem-array

### getCustomProgressConcatenationHandler {#getCustomProgressConcatenationHandler--}
```
public PdfFileEditor.ConcatenationProgressHandler getCustomProgressConcatenationHandler()
```

Representation av intern processor för förloppshändelser som arbetar under sammanslagning och översätter sammanslagningshändelser från interna sammanslagningssteg till extern kundkod.

**Returns:**
ConcatenationProgressHandler-instans

### getIncrementalUpdates {#getIncrementalUpdates--}
```
public boolean getIncrementalUpdates()
```

Om true görs inkrementella uppdateringar under sammanslagning.

**Returns:**
booleskt värde

### getKeepActions {#getKeepActions--}
```
public final boolean getKeepActions()
```

Om true kopieras åtgärder från källdokumenten.

**Returns:**
booleskt värde

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
public boolean getKeepFieldsUnique()
```

Om true så kommer fältnamn att göras unika när formulär concatenas.

**Returns:**
booleskt värde

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

Hämtar det senast inträffade undantaget.

**Returns:**
java.lang.Exception-objekt

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
public boolean getMergeDuplicateLayers()
```

Valfritt innehåll i sammanfogade dokument med samma namn kommer att slås samman till ett lager i det resulterande dokumentet om denna egenskap är sann.

**Returns:**
booleskt värde

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
public boolean getMergeDuplicateOutlines()
```

Om sant slås dubblettkonturer ihop.

**Returns:**
booleskt värde

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Hämtar eller anger optimeringsflagga.

**Returns:**
booleskt värde

### getOwnerPassword {#getOwnerPassword--}
```
public String getOwnerPassword()
```

Hämtar ägarens lösenord om den ursprungliga inmatnings-Pdf-filen är krypterad.

**Returns:**
String-objekt

### getPreserveUserRights {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```

Om sant tillämpas användarrättigheterna från det första dokumentet på det sammanfogade dokumentet.

**Returns:**
booleskt värde

### getRemoveSignatures {#getRemoveSignatures--}
```
public boolean getRemoveSignatures()
```

Om sant tas alla signaturer bort från fält (fälten kvarstår); annars kan du få ogiltiga signaturer.

**Returns:**
booleskt värde

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Hämtar eller anger sparalternativ när resultatet lagras som HttpServletResponse.

**Returns:**
SaveOptions-objekt

### getUniqueSuffix {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```

Hämta formatet för suffixet som läggs till fältnamnet för att göra det unikt när formulär sammanfogas.

**Returns:**
String-objekt

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Infogar dokument i ett annat dokument och lagrar resultatet i svarobjektet.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
Infogar sidor från en annan fil i den inkommande PDF-filen.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
Infogar sidor från en annan fil i den inkommande PDF-filen.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Infogar innehållet i filen i källfilen och lagrar resultatet i HttpServletResponse-objektet.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
Infogar sidor från en annan fil i den inkommande PDF-filen.

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
Infogar sidor från en annan fil i PDF-filen på en position.

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

Ibland innehåller PDF-filer bakgrundsbilder (av sidor eller tabellceller) som är konstruerade av flera identiska mosaikbakgrundsbilder placerade intill varandra.

**Returns:**
booleskt värde

### isUseDiskBuffer {#isUseDiskBuffer--}
```
public final boolean isUseDiskBuffer()
```

Om detta alternativ används sparas destinationsdokumentet på disk periodiskt och vidare sammanslagning tillämpas på det som inkrementella uppdateringar.

**Returns:**
booleskt värde

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
Skapar häfte från InputStream till outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
Skapar anpassat häfte från firstInputStream till outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
Skapar häfte från inmatningsströmmen och sparar resultatet i output stream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
Skapar häfte från firstInputStream till outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Skapar häfte från källfilen och lagrar resultatet i HttpServletResponse.

### makeBooklet {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-}
Skapa häfte från PDF-fil och lagra det i HttpServletResponse.

### makeBooklet {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Skapar häfte från källfilen och lagrar resultatet i HttpServletResponse-objekt.

### makeBooklet {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-}
Skapar häfte från källfilen och lagrar resultatet i HttpServletResponse-objekt.

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

### makeNUp {#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-}
Skapar N-up-dokument och lagrar resultatet i HttpServletResponse.

### makeNUp {#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Skapar N-up-dokument och lagrar resultatet i HttpServletResponse-objektet.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
Skapar N-Up-dokument från inmatningsströmmen och sparar resultatet i output stream.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
Skapar N-Up-dokument från firstInputStream till output stream.

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
Skapar N-Up-dokument från de flera inmatnings-PDF-filerna till outputFile.

### makeNUp {#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-}
Skapar N-up-dokument och lagrar resultatet i HttpServletResponse.

### makeNUp {#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Skapar N-up-dokument och lagrar resultatet i HttpServletResponse-objektet.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
Skapar N-Up-dokument från firstInputFile till outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
Skapar N-Up-dokument från inputFile till outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
Skapar N-Up-dokument från de två inmatnings-PDF-filerna till outputFile.

### resizeContents {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ändrar storlek på dokumentets sidor.

### resizeContents {#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ändrar storlek på dokumentets sidor.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Ändrar storlek på innehållet i dokumentsidor.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ändrar storlek på innehållet i dokumentets sidor.

### resizeContents {#resizeContents-com.aspose.ms.System.IO.Stream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
Ändrar storlek på innehållet i sidor i dokumentet.

### resizeContents {#resizeContents-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
Ändrar storlek på innehållet i sidor i dokumentet.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
Ändrar storlek på innehållet i dokumentsidor.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ändrar storlek på innehållet i sidor i dokumentet.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Ändrar storlek på innehållet i dokumentsidor.

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
Ändrar storlek på innehållet i dokumentsidor.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ändrar storlek på dokumentets sidor.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ändrar storlek på dokumentets sidor.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
@Deprecated public void setAllowConcatenateExceptions(boolean value)
```

Föråldrad. Denna egenskap är föråldrad och kan inte användas för att tillåta att kasta undantag.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | Booleskt värde |

### setAttachmentName {#setAttachmentName-java.lang.String-}
Ställer in namn på bilagan när resultatet av operationen lagras i HttpServletResponse-objekt som bilaga.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```

Om den är satt till true stängs strömmar efter operationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setConcatenationPacketSize {#setConcatenationPacketSize-int-}
```
public final void setConcatenationPacketSize(int value)
```

Antal dokument som sammanfogades innan en ny inkrementell uppdatering gjordes under sammanslagning när UseDiskBuffer är satt till true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Ställer in hur innehåll ska lagras när resultatet av operationen lagras i HttpServletResponse-objektet.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Anger PDF-filformat.

### setCopyLogicalStructure {#setCopyLogicalStructure-boolean-}
```
public void setCopyLogicalStructure(boolean value)
```

Om true kopieras den logiska strukturen i filen när sammanslagning utförs.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setCopyOutlines {#setCopyOutlines-boolean-}
```
public void setCopyOutlines(boolean value)
```

Om true kopieras konturerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
public void setCorruptedFileAction(int value)
```

Denna egenskap definierar beteendet när en concatenating-process möter en korrupt fil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | ConcatenateCorruptedFileAction‑element |

### setCustomProgressConcatenationHandler {#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-}
Representation av intern processor för förloppshändelser som arbetar under sammanslagning och översätter sammanslagningshändelser från interna sammanslagningssteg till extern kundkod.

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
public void setIncrementalUpdates(boolean value)
```

Om true görs inkrementella uppdateringar under sammanslagning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setKeepActions {#setKeepActions-boolean-}
```
public final void setKeepActions(boolean value)
```

Om true kopieras åtgärder från källdokumenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
public void setKeepFieldsUnique(boolean value)
```

Om true så kommer fältnamn att göras unika när formulär concatenas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
public void setMergeDuplicateLayers(boolean value)
```

Valfritt innehåll i sammanfogade dokument med samma namn kommer att slås samman till ett lager i det resulterande dokumentet om denna egenskap är sann.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
public void setMergeDuplicateOutlines(boolean value)
```

Om sant slås dubblettkonturer ihop.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Hämtar eller anger optimeringsflagga.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
Ställer in ägarens lösenord om källfilens indata-PDF är krypterad.

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
public void setPreserveUserRights(boolean value)
```

Om sant tillämpas användarrättigheterna från det första dokumentet på det sammanfogade dokumentet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
public void setRemoveSignatures(boolean value)
```

Om sant tas alla signaturer bort från fält (fälten kvarstår); annars kan du få ogiltiga signaturer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Ställer in sparalternativ när resultatet lagras som HttpServletResponse.

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

Ibland innehåller PDF-filer bakgrundsbilder (av sidor eller tabellceller) som är konstruerade av flera identiska mosaikbakgrundsbilder placerade intill varandra.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | booleskt värde |

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
Ange formatet för suffixet som läggs till fältnamnet för att göra det unikt när formulär sammanfogas.

### setUseDiskBuffer {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```

Om detta alternativ används sparas destinationsdokumentet på disk periodiskt och vidare sammanslagning tillämpas på det som inkrementella uppdateringar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
Delar dokumentet från början till angiven plats och lagrar resultatet i HttpServletResponse-objektet.

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
Delar från början till angiven plats och sparar den främre delen i output Stream.

### splitFromFirst {#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
Delar dokumentet från första sidan till platsen och sparar resultatet i HttpServletResponse-objekt.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
Delar Pdf-filen från första sidan till angiven plats och sparar den främre delen som en ny fil.

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Delar PDF-filen i flera dokument. Dokumenten kan vara enstaka sidor eller flersidiga.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Delar PDF-filen i flera dokument. Dokumenten kan vara enstaka sidor eller flersidiga.

### splitToEnd {#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
Delar från angiven plats och sparar den bakre delen i HttpServletResponse-objektet.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
Delar från angiven plats och sparar den bakre delen som en ny filström.

### splitToEnd {#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
Delar från angiven plats och sparar den bakre delen i HttpServletResponse-objektet.

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
