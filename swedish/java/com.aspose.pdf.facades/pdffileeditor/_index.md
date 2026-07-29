---
title: "PdfFileEditor"
linktitle: "PdfFileEditor"
second_title: "Aspose.PDF för Java API-referens"
description: "Implementerar operationer med PDF‑fil: sammanslagning, delning, extrahering av sidor, skapa häfte, etc."
type: docs
weight: 410
url: /sv/java/com.aspose.pdf.facades/pdffileeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfFileEditor

**All Implemented Interfaces:**
IPdfFileEditor

```
public final class PdfFileEditor extends Object implements IPdfFileEditor
```

Implementerar operationer med PDF‑fil: sammanslagning, delning, extrahering av sidor, skapa häfte, etc.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PdfFileEditor](#PdfFileEditor--) | PdfFileEditor-konstruktor. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | <p> Ändrar storlek på sidinnehållet och lägger till angivna marginaler. Marginalerna anges i standardrymdsenheter. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMargins(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); dest.Close(); </pre> |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | <p> Ändrar storlek på sidinnehållet och lägger till angivna marginaler. Marginalerna anges i standardrymdsenheter. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMargins("input.pdf", "output.pdf", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); </pre> |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | <p> Ändrar storlek på sidinnehållet och lägger till angivna marginaler. Marginalerna anges i procent av den ursprungliga sidstorleken. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMarginsPct(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); dest.close(); </pre> |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | <p> Ändrar storlek på sidinnehållet och lägger till angivna marginaler. Marginalerna anges i procent av den ursprungliga sidstorleken. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMarginsPct("input.pdf", "output.pdf", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); </pre> |
| [addPageBreak](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Lägger till sidbrytningar i dokumentets sidor. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Lägger till sidbrytningar i dokumentets sidor. |
| [addPageBreak](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Lägger till sidbrytningar i dokumentets sidor. |
| [addPageBreak](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Lägger till sidbrytningar i dokumentets sidor. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | <p> Lägger till sidor som väljs från en array av dokument i portStreams. Resultatdokumentet inkluderar firstInputFile och alla portStreams-dokumentens sidor i intervallet startPage till endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream("input.pdf"); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OtputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream); </pre> |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | <p> Lägger till sidor som väljs från portStream inom intervallet från startPage till endPage, i portStream i slutet av firstInputStream. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream("input.pdf"); InputStream stream1 = new FileInputStream("file1.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.append(instream, stream1, 3, 5, outstream); </pre> |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | <p> Lägger till sidor som väljs från portFiles-dokument. Resultatdokumentet inkluderar firstInputFile och alla portFiles-dokumentens sidor i intervallet startPage till endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf"); </pre> |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | <p> Lägger till sidor som väljs från portFile inom intervallet från startPage till endPage, i portFile i slutet av firstInputFile. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append("input.pdf", "file1.pdf", 3, 5, "outfile.pdf"); </pre> |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Kombinerar dokument. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | <p> Kombinerar filer </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream); </pre> |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor i alternerande ordning och fyller de tomma platserna med tomma sidor. t.ex.: dokument1 har 5 sidor: p1, p2, p3, p4, p5. dokument2 har 3 sidor: p1', p2', p3'. Sammanfogning av de två Pdf-dokumenten kommer att producera resultatdokumentet med sidor:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); InputStream blank = new FileInputStream("blank.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream); </pre> |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> Kombinerar två filer. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(stream1, stream2, outstream); </pre> |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | <p> Kombinerar filer till en fil. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(new String[] { "src1.pdf", "src2.pdf" }, "dest.pdf"); </pre> |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | <p> Kombinerar två filer. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.concatenate("file1.pdf", "file2.pdf", "outfile.pdf"); </pre> |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | <p> Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor i alternerande ordning och fyller de tomma platserna med tomma sidor. t.ex.: dokument1 har 5 sidor: p1, p2, p3, p4, p5. dokument2 har 3 sidor: p1', p2', p3'. Sammanfogning av de två Pdf-dokumenten kommer att producera resultatdokumentet med sidor:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf"); </pre> |
| [createArrayWithExclusion](#createArrayWithExclusion-int-int-) |  |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | <p> Tar bort sidor som anges av en sifferarray från inmatningsfilen, sparar som en ny Pdf-fil. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream intputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream); </pre> |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | <p> Tar bort sidor som anges av en nummerarray från inmatningsfilen, sparar som en ny Pdf-fil. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.delete("input.pdf", new int[] { 2, 3 }, "out.pdf"); </pre> |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | <p> Extraherar sidor som anges av en nummerarray, sparar som en ny Pdf-fil. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream); </pre> |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | <p> Extraherar sidor från inmatningsfilen, sparar som en ny Pdf-fil. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.extract(sourceStream, 1, 3, 6, outStream); </pre> |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | <p> Extraherar sidor som anges av en nummerarray, sparar som en ny PDF-fil. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf"); </pre> |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | <p> Extraherar sidor från inmatningsfilen, sparar som en ny Pdf-fil. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.Extract("input.pdf", 3, 7, "output.pdf"); </pre> |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | <p> Om den är satt till true kastas undantag om ett fel inträffar. Annars kastas inte undantag och metoderna returnerar false vid misslyckande. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre> |
| [getAttachmentName](#getAttachmentName--) | Hämtar namn på bilagan när resultatet av operationen lagras i HttpServletResponse-objekt som bilaga. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | Om den är satt till true stängs strömmar efter operationen. |
| [getConcatenationPacketSize](#getConcatenationPacketSize--) | Antal dokument som sammanfogades innan en ny inkrementell uppdatering gjordes under sammanslagning när UseDiskBuffer är satt till true. |
| [getContentDisposition](#getContentDisposition--) | Hämtar hur innehållet kommer att lagras när resultatet av operationen lagras i HttpServletResponse-objektet. Möjligt värde: inline / attachment. Standard: inline. |
| [getConversionLog](#getConversionLog--) | Hämtar logg för konverteringsprocessen. |
| [getCopyLogicalStructure](#getCopyLogicalStructure--) | Om true kopieras den logiska strukturen i filen när sammanslagning utförs. |
| [getCopyOutlines](#getCopyOutlines--) | Om true kopieras konturerna. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | Denna egenskap definierar beteendet när sammanslagningsprocessen stöter på en korrupt fil. Möjliga värden är: StopWithError och ConcatenateIgnoringCorrupted. |
| [getCorruptedItems](#getCorruptedItems--) | <p> Array av uppkomna problem när sammanslagning utfördes. För varje korrupt dokument som skickas till Concatenate()-funktionen skapas en ny CorruptedItem-post. Denna egenskap kan endast användas när CorruptedFileAction är ConcatenateIgnoringCorrupted. </p> <hr> <pre> //concatenate documents and show information about corrupted documents PdfFileEditor pfe = new PdfFileEditor(); pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted); {@code if (pfe.getCorruptedItems().length >0)} { for(PdfFileEditor.CorruptedItem item : pfe.getCorruptedItems()) { System.out.println(item.getIndex()+ " reason: " + item.getException()); } } </pre> |
| [getCustomProgressConcatenationHandler](#getCustomProgressConcatenationHandler--) | Representation av intern processor för förloppshändelser som arbetar under sammanslagning och översätter sammanslagningshändelser från interna sammanslagningssteg till extern kundkod. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | Om true görs inkrementella uppdateringar under sammanslagning. |
| [getKeepActions](#getKeepActions--) | Om true kopieras åtgärder från källdokumenten. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | Om sant görs fältnamnen unika när formulär sammanfogas. Suffix läggs till fältnamnen, suffixmall kan specificeras i egenskapen UniqueSuffix. |
| [getLastException](#getLastException--) | Hämtar det senast inträffade undantaget. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | Valfritt innehåll i sammanfogade dokument med samma namn kommer att slås samman till ett lager i det resulterande dokumentet om denna egenskap är sann. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | Om sant slås dubblettkonturer ihop. |
| [getOptimizeSize](#getOptimizeSize--) | Hämtar eller anger optimeringsflagga. |
| [getOwnerPassword](#getOwnerPassword--) | Hämtar ägarens lösenord om käll‑Pdf‑filen är krypterad. Denna egenskap är ännu inte implementerad. |
| [getPreserveUserRights](#getPreserveUserRights--) | Om sant tillämpas användarrättigheterna från det första dokumentet på det sammanfogade dokumentet. |
| [getRemoveSignatures](#getRemoveSignatures--) | Om sant tas alla signaturer bort från fält (fälten kvarstår); annars kan du få ogiltiga signaturer. |
| [getSaveOptions](#getSaveOptions--) | Hämtar eller anger sparalternativ när resultatet lagras som HttpServletResponse. Standardvärde: PdfSaveOptions. |
| [getUniqueSuffix](#getUniqueSuffix--) | Hämta formatet för suffixet som läggs till fältnamnet för att göra det unikt när formulär sammanfogas. Denna sträng måste innehålla %NUM%-delsträngen som kommer att ersättas med siffror. Till exempel, om UniqueSuffix = "ABC%NUM%" så blir fältnamnen för "fieldName": fieldNameABC1, fieldNameABC2, fieldNameABC3 osv. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | <p> Infogar sidor från en annan fil i den inmatade Pdf-filen. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileoutputStream("out.pdf"); pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream); </pre> |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | <p> Infogar sidor från en annan fil i den inmatade Pdf-filen. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre> |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | <p> Infogar sidor från en annan fil i den inmatade Pdf-filen. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre> |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | <p> Infogar sidor från en annan fil i Pdf-filen på en position. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf"); </pre> |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | Ibland innehåller PDF-filer bakgrundsbilder (av sidor eller tabellceller) som är konstruerade av flera identiska mosaikbakgrundsbilder placerade intill varandra. |
| [isUseDiskBuffer](#isUseDiskBuffer--) | Om detta alternativ används sparas destinationsdokumentet på disk periodiskt och vidare sammanslagning tillämpas på det som inkrementella uppdateringar. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | <p> Skapar en häfte från InputStream till outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | <p> Skapar anpassat häfte från firstInputStream till outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | <p> Skapar häfte från inmatningsströmmen och sparar resultatet i utmatningsströmmen. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileInputStream(\"output.pdf\"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | <p> Skapar häfte från firstInputStream till outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | <p> Skapar häfte från indatafilen till utdatafilen. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\"); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | <p> Skapar anpassat häfte från firstInputFile till outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | <p> Skapar häfte från indatafilen till utdatafilen. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", PageSize.A4); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | <p> Skapar anpassat häfte från firstInputFile till outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | <p> Skapar N-Up-dokument från de flera inmatnings‑PDF‑strömmarna till outputStream. Varje sida i outputStream kommer att innehålla flera sidor, som är en kombination av sidor i inmatningsströmmarna med samma sidnummer. De flera sidorna staplas horisontellt om isSidewise är sant och staplas vertikalt om isSidewise är falskt. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"input1.pdf\"); InputStream stream2 = new FileInputStream(\"input2.pdf\"); InputStream stream3 = new FileInputStream(\"input3.pdf\"); OutputStream output = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> Skapar N-Up-dokument från de två inmatnings‑PDF‑strömmarna till outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream input1 = new FileInputStream(\"input1.pdf\"); InputStream input2 = new FileInputStream(\"input2.pdf\"); OutputStream output = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(input1, input2, output); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | <p> Skapar N-Up-dokument från inmatningsströmmen och sparar resultatet i utmatningsströmmen. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(inputStream, outputStream, 3, 3); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | <p> Skapar N-Up-dokument från den första inmatningsströmmen till utmatningsströmmen. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4); </pre> |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | <p> Skapar N-Up-dokument från flera inmatnings-PDF-filer till outputFile. Varje sida i outputFile kommer att innehålla flera sidor, som är en kombination av sidor i inmatningsfilerna med samma sidnummer. De flera sidorna staplas horisontellt om isSidewise är sant och staplas vertikalt om isSidewise är falskt. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(new String[] { \"input1.pdf\", \"input2.pdf\", \"input3.pdf\" }, \"output.pdf\", false); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | <p> Skapar N-Up-dokument från firstInputFile till outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input.pdf\", \"output.pdf\", 3, 3); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | <p> Skapar N-Up-dokument från indatafilen till outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input.pdf\", \"output.pdf\", 3, 3, PageSize.A4); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | <p> Skapar N-Up-dokument från de två inmatnings-PDF-filerna till outputFile. Varje sida i outputFile kommer att innehålla två sidor, en sida från den första indatafilen och en annan från den andra indatafilen. De två sidorna staplas horisontellt. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input1.pdf\", \"input2.pdf\", \"output.pdf\"); </pre> |
| [resizeContents](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ändrar storlek på dokumentets sidor. |
| [resizeContents](#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ändrar storlek på dokumentets sidor. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | <p> Ändrar storlek på innehållet i dokumentets sidor. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i standardenhetsmått. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileOutputStream(\"output.pdf\"); fileEditor.resizeContents(src, dest, //ändra storlek på alla sidor i dokumentet null, //nytt innehållsbredd = 200 200, //nytt innehållshöjd = 300 300); // återstående område på sidan blir tomt </pre> |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ändrar storlek på innehållet i dokumentets sidor. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | <p> Ändrar storlek på innehållet i dokumentets sidor. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i standardenhetsmått. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizeContents(\"input.pdf\", \"output.pdf\", //ändra storlek på alla sidor i dokumentet null, //nytt innehållsbredd = 200 200, //nytt innehållshöjd = 300 300); // återstående område på sidan blir tomt </pre> |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ändrar storlek på innehållet i sidor i dokumentet. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | <p> Ändrar storlek på innehållet i dokumentets sidor. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i procent. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileOutputStream(\"output.pdf\"); fileEditor.resizePct(src, dest, //ändra storlek på alla sidor i dokumentet null, //nytt innehållsbredd = 60% av ursprunglig storlek 60, //nytt innehållshöjd = 60% av ursprunglig storlek 60); // Återstående område på sidan blir tomt (sidomarginaler). Storleken på vänster och högermarginal är (100% - 60%) / 2 = 20% // Samma för övre och nedre marginaler. </pre> |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | <p> Ändrar storlek på innehållet i dokumentets sidor. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i procent. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizePct("input.pdf", "output.pdf", //ändra storlek på alla sidor i dokumentet null, //ny bredd på innehållet = 60% av ursprunglig storlek 60, //ny höjd på innehållet = 60% av ursprunglig storlek 60); // Restområdet på sidan blir tomt (sidomarginaler). // Storleken på vänster och högermarginaler är (100% - 60%) / 2 = 20% // Detsamma för övre och nedre marginaler. </pre> |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ändrar storlek på dokumentets sidor. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Ändrar storlek på dokumentets sidor. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | <p> Om den är satt till true kastas undantag om ett fel inträffar. Annars kastas inga undantag och metoderna returnerar false om de misslyckas. </p> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Ställer in namn på bilagan när resultatet av operationen lagras i HttpServletResponse-objekt som bilaga. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | <p> Om den är satt till true stängs strömmar efter operationen. </p> |
| [setConcatenationPacketSize](#setConcatenationPacketSize-int-) | Antal dokument som sammanfogades innan en ny inkrementell uppdatering gjordes under sammanslagning när UseDiskBuffer är satt till true. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Ställer in hur innehållet ska lagras när resultatet av operationen lagras i ett HttpServletResponse-objekt. Möjligt värde: inline / attachment. Standard: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Ställer in PDF-filformat. Resultatfilen sparas i angivet filformat. Om denna egenskap inte anges sparas filen i standard PDF-format utan konvertering. |
| [setCopyLogicalStructure](#setCopyLogicalStructure-boolean-) | Om true kopieras den logiska strukturen i filen när sammanslagning utförs. |
| [setCopyOutlines](#setCopyOutlines-boolean-) | Om true kopieras konturerna. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | Denna egenskap definierar beteendet när sammanslagningsprocessen stöter på en korrupt fil. Möjliga värden är: StopWithError och ConcatenateIgnoringCorrupted. |
| [setCustomProgressConcatenationHandler](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | Representation av intern processor för förloppshändelser som arbetar under sammanslagning och översätter sammanslagningshändelser från interna sammanslagningssteg till extern kundkod. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | Om true görs inkrementella uppdateringar under sammanslagning. |
| [setKeepActions](#setKeepActions-boolean-) | Om true kopieras åtgärder från källdokumenten. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | Om sant görs fältnamnen unika när formulär sammanfogas. Suffix läggs till fältnamnen, suffixmall kan specificeras i egenskapen UniqueSuffix. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | Valfritt innehåll i sammanfogade dokument med samma namn kommer att slås samman till ett lager i det resulterande dokumentet om denna egenskap är sann. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | Om sant slås dubblettkonturer ihop. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Hämtar eller anger optimeringsflagga. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Ställer in ägarens lösenord om den ursprungliga Pdf-filen är krypterad. Denna egenskap är ännu inte implementerad. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | Om sant tillämpas användarrättigheterna från det första dokumentet på det sammanfogade dokumentet. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | Om sant tas alla signaturer bort från fält (fälten kvarstår); annars kan du få ogiltiga signaturer. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Ställer in sparalternativ när resultatet lagras som HttpServletResponse. Standardvärde: PdfSaveOptions. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Ibland innehåller PDF-filer bakgrundsbilder (av sidor eller tabellceller) som är konstruerade av flera identiska mosaikbakgrundsbilder placerade intill varandra. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | <p> Ange formatet på suffixet som läggs till fältnamnet för att göra det unikt när formulär sammanfogas. Denna sträng måste innehålla %NUM%-delsträngen som kommer att ersättas med siffror. Till exempel om UniqueSuffix = "ABC%NUM%" så blir fältnamnen för "fieldName": fieldNameABC1, fieldNameABC2, fieldNameABC3 osv. </p> <hr> <pre> PdfFileEditor ed = new PdfFileEditor(); ed.setUniqueSuffix ( "_%NUM%"); </pre> |
| [setUseDiskBuffer](#setUseDiskBuffer-boolean-) | Om detta alternativ används sparas destinationsdokumentet på disk periodiskt och vidare sammanslagning tillämpas på det som inkrementella uppdateringar. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | <p> Delar från början till angiven plats och sparar den främre delen i utdataströmmen. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.splitFromFirst(sourceStream, 5, outStream); </pre> <hr> Strömmarna stängs INTE efter denna operation. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | <p> Delar PDF-filen från första sidan till angiven plats och sparar den främre delen som en ny fil. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitFromFirst("input.pdf", 5, "out.pdf"); </pre> |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Delar PDF-filen i flera dokument. Dokumenten kan vara enstaka sidor eller flersidiga. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Delar PDF-filen i flera dokument. Dokumenten kan vara enstaka sidor eller flersidiga. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | <p> Delar från angiven plats och sparar den bakre delen som en ny filström. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.splitToEnd(sourceStream, 5, outStream); </pre> <hr> Strömmarna stängs INTE efter denna operation om inte CloseConcatedStreams anges. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | <p> Delar från platsen och sparar den bakre delen som en ny fil. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitToEnd("input.pdf", 5, "out.pdf"); </pre> |
| [splitToPages](#splitToPages-java.io.InputStream-) | Delar PDF-filen i enstaka sidodokument. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Dela PDF-filen i enstaka sidodokument och spara den på angiven sökväg. |
| [splitToPages](#splitToPages-java.lang.String-) | Delar PDF-filen i enstaka sidodokument. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Dela PDF-filen i enstaka sidodokument och spara den på angiven sökväg. |

### PdfFileEditor {#PdfFileEditor--}
```
public PdfFileEditor()
```

PdfFileEditor-konstruktor.

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
<p> Ändrar storlek på sidinnehållet och lägger till angivna marginaler. Marginalerna anges i standardrymdsenheter. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMargins(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); dest.Close(); </pre>

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
<p> Ändrar storlek på sidinnehållet och lägger till angivna marginaler. Marginalerna anges i standardrymdsenheter. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMargins("input.pdf", "output.pdf", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); </pre>

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
<p> Ändrar storlek på sidinnehållet och lägger till angivna marginaler. Marginalerna anges i procent av den ursprungliga sidstorleken. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMarginsPct(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); dest.close(); </pre>

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
<p> Ändrar storlek på sidinnehållet och lägger till angivna marginaler. Marginalerna anges i procent av den ursprungliga sidstorleken. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMarginsPct("input.pdf", "output.pdf", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); </pre>

### addPageBreak {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Lägger till sidbrytningar i dokumentets sidor.

### addPageBreak {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Lägger till sidbrytningar i dokumentets sidor.

### addPageBreak {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Lägger till sidbrytningar i dokumentets sidor.

### addPageBreak {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Lägger till sidbrytningar i dokumentets sidor.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
<p> Lägger till sidor som väljs från en array av dokument i portStreams. Resultatdokumentet inkluderar firstInputFile och alla portStreams-dokumentens sidor i intervallet startPage till endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream("input.pdf"); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OtputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream); </pre>

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
<p> Lägger till sidor som väljs från portStream inom intervallet från startPage till endPage, i portStream i slutet av firstInputStream. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream("input.pdf"); InputStream stream1 = new FileInputStream("file1.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.append(instream, stream1, 3, 5, outstream); </pre>

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
<p> Lägger till sidor som väljs från portFiles-dokument. Resultatdokumentet inkluderar firstInputFile och alla portFiles-dokumentens sidor i intervallet startPage till endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf"); </pre>

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
<p> Lägger till sidor som väljs från portFile inom intervallet från startPage till endPage, i portFile i slutet av firstInputFile. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append("input.pdf", "file1.pdf", 3, 5, "outfile.pdf"); </pre>

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Kombinerar dokument.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
<p> Kombinerar filer </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream); </pre>

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor i alternerande ordning och fyller de tomma platserna med tomma sidor. t.ex.: dokument1 har 5 sidor: p1, p2, p3, p4, p5. dokument2 har 3 sidor: p1', p2', p3'. Sammanfogning av de två Pdf-dokumenten kommer att producera resultatdokumentet med sidor:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); InputStream blank = new FileInputStream("blank.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream); </pre>

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> Kombinerar två filer. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream("file1.pdf"); InputStream stream2 = new FileInputStream("file2.pdf"); OutputStream outstream = new FileOutputStream("outfile.pdf"); fileEditor.concatenate(stream1, stream2, outstream); </pre>

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
<p> Kombinerar filer till en fil. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(new String[] { "src1.pdf", "src2.pdf" }, "dest.pdf"); </pre>

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
<p> Kombinerar två filer. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.concatenate("file1.pdf", "file2.pdf", "outfile.pdf"); </pre>

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
<p> Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor i alternerande ordning och fyller de tomma platserna med tomma sidor. t.ex.: dokument1 har 5 sidor: p1, p2, p3, p4, p5. dokument2 har 3 sidor: p1', p2', p3'. Sammanfogning av de två Pdf-dokumenten kommer att producera resultatdokumentet med sidor:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf"); </pre>

### createArrayWithExclusion {#createArrayWithExclusion-int-int-}
```
public static Integer [] createArrayWithExclusion(int n, int y)
```



### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
<p> Tar bort sidor som anges av en sifferarray från inmatningsfilen, sparar som en ny Pdf-fil. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream intputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream); </pre>

### delete {#delete-java.lang.String-int:A-java.lang.String-}
<p> Tar bort sidor som anges av en nummerarray från inmatningsfilen, sparar som en ny Pdf-fil. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.delete("input.pdf", new int[] { 2, 3 }, "out.pdf"); </pre>

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
<p> Extraherar sidor som anges av en nummerarray, sparar som en ny Pdf-fil. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream); </pre>

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
<p> Extraherar sidor från inmatningsfilen, sparar som en ny Pdf-fil. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.extract(sourceStream, 1, 3, 6, outStream); </pre>

### extract {#extract-java.lang.String-int:A-java.lang.String-}
<p> Extraherar sidor som anges av en nummerarray, sparar som en ny PDF-fil. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf"); </pre>

### extract {#extract-java.lang.String-int-int-java.lang.String-}
<p> Extraherar sidor från inmatningsfilen, sparar som en ny Pdf-fil. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.Extract("input.pdf", 3, 7, "output.pdf"); </pre>

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
@Deprecated public boolean getAllowConcatenateExceptions()
```

<p> Om den är satt till true kastas undantag om ett fel inträffar. Annars kastas inte undantag och metoderna returnerar false vid misslyckande. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre>

**Returns:**
boolean value @deprecated Denna egenskap är föråldrad och kan inte användas för att tillåta att kasta undantag.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Hämtar namn på bilagan när resultatet av operationen lagras i HttpServletResponse-objekt som bilaga.

**Returns:**
String värde

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

Hämtar hur innehållet kommer att lagras när resultatet av operationen lagras i HttpServletResponse-objektet. Möjligt värde: inline / attachment. Standard: inline.

**Returns:**
ContentDisposition-element @see ContentDisposition

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

Denna egenskap definierar beteendet när sammanslagningsprocessen stöter på en korrupt fil. Möjliga värden är: StopWithError och ConcatenateIgnoringCorrupted.

**Returns:**
ConcatenateCorruptedFileAction-element @see ConcatenateCorruptedFileAction

### getCorruptedItems {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem [] getCorruptedItems()
```

<p> Array av uppkomna problem när sammanslagning utfördes. För varje korrupt dokument som skickas till Concatenate()-funktionen skapas en ny CorruptedItem-post. Denna egenskap kan endast användas när CorruptedFileAction är ConcatenateIgnoringCorrupted. </p> <hr> <pre> //concatenate documents and show information about corrupted documents PdfFileEditor pfe = new PdfFileEditor(); pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted); {@code if (pfe.getCorruptedItems().length >0)} { for(PdfFileEditor.CorruptedItem item : pfe.getCorruptedItems()) { System.out.println(item.getIndex()+ " reason: " + item.getException()); } } </pre>

**Returns:**
array av PdfFileEditor.CorruptedItem

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

Om sant görs fältnamnen unika när formulär sammanfogas. Suffix läggs till fältnamnen, suffixmall kan specificeras i egenskapen UniqueSuffix.

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

Hämtar ägarens lösenord om käll‑Pdf‑filen är krypterad. Denna egenskap är ännu inte implementerad.

**Returns:**
String värde

### getPreserveUserRights {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```

Om sant tillämpas användarrättigheterna från det första dokumentet på det sammanfogade dokumentet.

**Returns:**
booleskt värde

### getRemoveSignatures {#getRemoveSignatures--}
```
public final boolean getRemoveSignatures()
```

Om sant tas alla signaturer bort från fält (fälten kvarstår); annars kan du få ogiltiga signaturer.

**Returns:**
booleskt värde

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Hämtar eller anger sparalternativ när resultatet lagras som HttpServletResponse. Standardvärde: PdfSaveOptions.

**Returns:**
SaveOptions-objekt

### getUniqueSuffix {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```

Hämta formatet för suffixet som läggs till fältnamnet för att göra det unikt när formulär sammanfogas. Denna sträng måste innehålla %NUM%-delsträngen som kommer att ersättas med siffror. Till exempel, om UniqueSuffix = "ABC%NUM%" så blir fältnamnen för "fieldName": fieldNameABC1, fieldNameABC2, fieldNameABC3 osv.

**Returns:**
String värde

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
<p> Infogar sidor från en annan fil i den inmatade Pdf-filen. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileoutputStream("out.pdf"); pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream); </pre>

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
<p> Infogar sidor från en annan fil i den inmatade Pdf-filen. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre>

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
<p> Infogar sidor från en annan fil i den inmatade Pdf-filen. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre>

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
<p> Infogar sidor från en annan fil i Pdf-filen på en position. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf"); </pre>

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
<p> Skapar en häfte från InputStream till outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
<p> Skapar anpassat häfte från firstInputStream till outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
<p> Skapar häfte från inmatningsströmmen och sparar resultatet i utmatningsströmmen. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileInputStream(\"output.pdf\"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
<p> Skapar häfte från firstInputStream till outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
<p> Skapar häfte från indatafilen till utdatafilen. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\"); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
<p> Skapar anpassat häfte från firstInputFile till outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
<p> Skapar häfte från indatafilen till utdatafilen. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", PageSize.A4); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
<p> Skapar anpassat häfte från firstInputFile till outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
<p> Skapar N-Up-dokument från de flera inmatnings‑PDF‑strömmarna till outputStream. Varje sida i outputStream kommer att innehålla flera sidor, som är en kombination av sidor i inmatningsströmmarna med samma sidnummer. De flera sidorna staplas horisontellt om isSidewise är sant och staplas vertikalt om isSidewise är falskt. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"input1.pdf\"); InputStream stream2 = new FileInputStream(\"input2.pdf\"); InputStream stream3 = new FileInputStream(\"input3.pdf\"); OutputStream output = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> Skapar N-Up-dokument från de två inmatnings‑PDF‑strömmarna till outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream input1 = new FileInputStream(\"input1.pdf\"); InputStream input2 = new FileInputStream(\"input2.pdf\"); OutputStream output = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(input1, input2, output); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
<p> Skapar N-Up-dokument från inmatningsströmmen och sparar resultatet i utmatningsströmmen. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(inputStream, outputStream, 3, 3); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
<p> Skapar N-Up-dokument från den första inmatningsströmmen till utmatningsströmmen. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4); </pre>

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
<p> Skapar N-Up-dokument från flera inmatnings-PDF-filer till outputFile. Varje sida i outputFile kommer att innehålla flera sidor, som är en kombination av sidor i inmatningsfilerna med samma sidnummer. De flera sidorna staplas horisontellt om isSidewise är sant och staplas vertikalt om isSidewise är falskt. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(new String[] { \"input1.pdf\", \"input2.pdf\", \"input3.pdf\" }, \"output.pdf\", false); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
<p> Skapar N-Up-dokument från firstInputFile till outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input.pdf\", \"output.pdf\", 3, 3); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
<p> Skapar N-Up-dokument från indatafilen till outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input.pdf\", \"output.pdf\", 3, 3, PageSize.A4); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
<p> Skapar N-Up-dokument från de två inmatnings-PDF-filerna till outputFile. Varje sida i outputFile kommer att innehålla två sidor, en sida från den första indatafilen och en annan från den andra indatafilen. De två sidorna staplas horisontellt. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input1.pdf\", \"input2.pdf\", \"output.pdf\"); </pre>

### resizeContents {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ändrar storlek på dokumentets sidor.

### resizeContents {#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ändrar storlek på dokumentets sidor.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
<p> Ändrar storlek på innehållet i dokumentets sidor. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i standardenhetsmått. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileOutputStream(\"output.pdf\"); fileEditor.resizeContents(src, dest, //ändra storlek på alla sidor i dokumentet null, //nytt innehållsbredd = 200 200, //nytt innehållshöjd = 300 300); // återstående område på sidan blir tomt </pre>

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ändrar storlek på innehållet i dokumentets sidor.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
<p> Ändrar storlek på innehållet i dokumentets sidor. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i standardenhetsmått. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizeContents(\"input.pdf\", \"output.pdf\", //ändra storlek på alla sidor i dokumentet null, //nytt innehållsbredd = 200 200, //nytt innehållshöjd = 300 300); // återstående område på sidan blir tomt </pre>

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ändrar storlek på innehållet i sidor i dokumentet.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
<p> Ändrar storlek på innehållet i dokumentets sidor. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i procent. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileOutputStream(\"output.pdf\"); fileEditor.resizePct(src, dest, //ändra storlek på alla sidor i dokumentet null, //nytt innehållsbredd = 60% av ursprunglig storlek 60, //nytt innehållshöjd = 60% av ursprunglig storlek 60); // Återstående område på sidan blir tomt (sidomarginaler). Storleken på vänster och högermarginal är (100% - 60%) / 2 = 20% // Samma för övre och nedre marginaler. </pre>

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
<p> Ändrar storlek på innehållet i dokumentets sidor. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i procent. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizePct("input.pdf", "output.pdf", //ändra storlek på alla sidor i dokumentet null, //ny bredd på innehållet = 60% av ursprunglig storlek 60, //ny höjd på innehållet = 60% av ursprunglig storlek 60); // Restområdet på sidan blir tomt (sidomarginaler). // Storleken på vänster och högermarginaler är (100% - 60%) / 2 = 20% // Detsamma för övre och nedre marginaler. </pre>

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ändrar storlek på dokumentets sidor.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Ändrar storlek på dokumentets sidor.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
@Deprecated public void setAllowConcatenateExceptions(boolean value)
```

<p> Om den är satt till true kastas undantag om ett fel inträffar. Annars kastas inga undantag och metoderna returnerar false om de misslyckas. </p>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre> @deprecated Denna egenskap är föråldrad och kan inte användas för att tillåta att kasta undantag. |

### setAttachmentName {#setAttachmentName-java.lang.String-}
Ställer in namn på bilagan när resultatet av operationen lagras i HttpServletResponse-objekt som bilaga.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```

<p> Om den är satt till true stängs strömmar efter operationen. </p>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setCloseConcatenatedStreams (true); </pre> |

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
Ställer in hur innehållet ska lagras när resultatet av operationen lagras i ett HttpServletResponse-objekt. Möjligt värde: inline / attachment. Standard: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Ställer in PDF-filformat. Resultatfilen sparas i angivet filformat. Om denna egenskap inte anges sparas filen i standard PDF-format utan konvertering.

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

Denna egenskap definierar beteendet när sammanslagningsprocessen stöter på en korrupt fil. Möjliga värden är: StopWithError och ConcatenateIgnoringCorrupted.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int värde @see ConcatenateCorruptedFileAction |

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

Om sant görs fältnamnen unika när formulär sammanfogas. Suffix läggs till fältnamnen, suffixmall kan specificeras i egenskapen UniqueSuffix.

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
Ställer in ägarens lösenord om den ursprungliga Pdf-filen är krypterad. Denna egenskap är ännu inte implementerad.

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
public final void setRemoveSignatures(boolean value)
```

Om sant tas alla signaturer bort från fält (fälten kvarstår); annars kan du få ogiltiga signaturer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Ställer in sparalternativ när resultatet lagras som HttpServletResponse. Standardvärde: PdfSaveOptions.

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
<p> Ange formatet på suffixet som läggs till fältnamnet för att göra det unikt när formulär sammanfogas. Denna sträng måste innehålla %NUM%-delsträngen som kommer att ersättas med siffror. Till exempel om UniqueSuffix = "ABC%NUM%" så blir fältnamnen för "fieldName": fieldNameABC1, fieldNameABC2, fieldNameABC3 osv. </p> <hr> <pre> PdfFileEditor ed = new PdfFileEditor(); ed.setUniqueSuffix ( "_%NUM%"); </pre>

### setUseDiskBuffer {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```

Om detta alternativ används sparas destinationsdokumentet på disk periodiskt och vidare sammanslagning tillämpas på det som inkrementella uppdateringar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
<p> Delar från början till angiven plats och sparar den främre delen i utdataströmmen. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.splitFromFirst(sourceStream, 5, outStream); </pre> <hr> Strömmarna stängs INTE efter denna operation.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
<p> Delar PDF-filen från första sidan till angiven plats och sparar den främre delen som en ny fil. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitFromFirst("input.pdf", 5, "out.pdf"); </pre>

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Delar PDF-filen i flera dokument. Dokumenten kan vara enstaka sidor eller flersidiga.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Delar PDF-filen i flera dokument. Dokumenten kan vara enstaka sidor eller flersidiga.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
<p> Delar från angiven plats och sparar den bakre delen som en ny filström. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.splitToEnd(sourceStream, 5, outStream); </pre> <hr> Strömmarna stängs INTE efter denna operation om inte CloseConcatedStreams anges.

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
<p> Delar från platsen och sparar den bakre delen som en ny fil. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitToEnd("input.pdf", 5, "out.pdf"); </pre>

### splitToPages {#splitToPages-java.io.InputStream-}
Delar PDF-filen i enstaka sidodokument.

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
Dela PDF-filen i enstaka sidodokument och spara den på angiven sökväg.

### splitToPages {#splitToPages-java.lang.String-}
Delar PDF-filen i enstaka sidodokument.

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
Dela PDF-filen i enstaka sidodokument och spara den på angiven sökväg.
