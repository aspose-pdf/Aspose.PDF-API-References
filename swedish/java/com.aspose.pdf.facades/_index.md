---
title: "com.aspose.pdf.facades"
linktitle: "com.aspose.pdf.facades"
second_title: "Aspose.PDF för Java API-referens"
description: "com.aspose.pdf.facades‑paketet tillhandahåller klasser som ursprungligen kommer från Aspose.Pdf.Kit."
type: docs
weight: 180
url: /sv/java/com.aspose.pdf.facades/
---
com.aspose.pdf.facades‑paketet tillhandahåller klasser som ursprungligen kommer från Aspose.Pdf.Kit.

## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IFacade](./ifacade/) | Allmänt fasadgränssnitt som definierar gemensamma fasadmetoder. |
| [IForm](./iform/) | Klass som representerar Acro-formulärobjekt. |
| [IFormEditor](./iformeditor/) | Klass för att redigera formulär (lägga till/ta bort fält etc) |
| [IPdfFileEditor](./ipdffileeditor/) | Implementerar operationer med PDF‑fil: sammanslagning, delning, extrahering av sidor, skapa häfte, etc. |
| [IPdfFileStamp](./ipdffilestamp/) | gränssnitt för att lägga till stämplar (vattenstämpel eller bakgrund) till PDF‑filer. |
| [ISaveableFacade](./isaveablefacade/) | Fasadgränssnitt som definierar metoder gemensamma för alla sparbara fasader. |
## Klasser

| Klass | Beskrivning |
| --- | --- |
| [AlignmentType](./alignmenttype/) | Klassen innehåller eventuella justeringstyper. Använd HorizontalAlignment istället. |
| [AutoRotateMode](./autorotatemode/) | Riktning för rotation när dokumentet skrivs ut. |
| [BDCProperties](./bdcproperties/) | BDC‑operatorns egenskaper. |
| [Bookmark](./bookmark/) | Representerar ett bokmärke. |
| [Bookmarks](./bookmarks/) | Representerar en samling av {@code Bookmark}-objekt. |
| [CgmPdfProducer](./cgmpdfproducer/) | Representerar en klass för att producera PDF från Computer Graphics Metafile (CGM)-format. |
| [DataType](./datatype/) | Enumererar definitioner av fälttyper. |
| [DefaultMetadataProperties](./defaultmetadataproperties/) | Enumeration av standard‑XMP‑egenskaper. |
| [DocumentPrivilege](./documentprivilege/) | Representerar behörigheterna för åtkomst till Pdf fil. Referera till{@code PdfFileSecurity}. Det finns 4 sätt att använda denna klass: 1. Använda fördefinierad behörighet direkt. 2. Baserat på en fördefinierad behörighet och ändra vissa specifika rättigheter. 3. Baserat på en fördefinierad behörighet och ändra en specifik kombination av Adobe Professional‑rättigheter. 4. Kombinerar sätt 2 och sätt 3. //Way1: Använda fördefinierad behörighet direkt. DocumentPrivilege privilege = DocumentPrivilege.getPrint(); //Way2: Baserat på en fördefinierad behörighet och ändra vissa specifika rättigheter. DocumentPrivilege privilege = DocumentPrivilege.getAllowAll(); privilege.setAllowPrint(false); privilege.setAllowModifyContents(false); //Way3: Baserat på en fördefinierad behörighet och ändra en specifik kombination av Adobe Professional‑rättigheter. DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setPrintAllowLevel(2); //Way4: Kombinerar sätt 2 och sätt 3 DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setAllowPrint(true); |
| [EncodingType](./encodingtype/) | Enumererar kodningstyper som används för texten. |
| [Facade](./facade/) | Basfasadklass. |
| [FontColor](./fontcolor/) | Klass som representerar färgen på texten. |
| [Form](./form/) | Klass som representerar Acro-formulärobjekt. |
| [Form.ImportStatus](./form.importstatus/) | Status för importerat fält |
| [FormattedText](./formattedtext/) | Klass som representerar formaterad text. Innehåller information om texten samt dess färg, storlek och stil. |
| [FormEditor](./formeditor/) | Klass för att redigera formulär (lägga till/ta bort fält etc) |
| [FormEditorWeb](./formeditorweb/) | Klass för att redigera formulär (ading/ta bort fält etc) |
| [FormFieldFacade](./formfieldfacade/) | Klass för att representera fältegenskaper. |
| [FormWeb](./formweb/) | Representerar Acro‑formulärgränssnitt. |
| [InternalHelper](./internalhelper/) | Hjälpklass |
| [IPdfFileEditor.ContentsResizeParameters](./ipdffileeditor.contentsresizeparameters/) | Klass för att specificera sidändringsparametrar. Tillåter att ställa in följande parametrar: Storlek på resultatsidan (bredd, höjd) i standardenhetsmått eller i procent av den ursprungliga sidans storlek; Vänster-, topp-, botten- och högermarginaler i standardenhetsmått eller i procent av den ursprungliga sidans storlek; Vissa värden kan lämnas null för automatisk beräkning. Dessa värden beräknas från återstående sidstorlek efter beräkning av explicit angivna värden. Till exempel: om sidbredd = 100 och ny sidbredd anges till 60 enheter så beräknas vänster- och högermarginaler automatiskt: (100 - 60) / 2 = 15. Denna klass används i metoden ResizeContents. |
| [IPdfFileEditor.ContentsResizeValue](./ipdffileeditor.contentsresizevalue/) | Värde för marginal eller innehållsstorlek angivet i procent av standardenhetsmått. Denna klass används i ContentsResizeParameters. |
| [LineInfo](./lineinfo/) | Representerar informationen för en rad. |
| [PdfAnnotationEditor](./pdfannotationeditor/) | Representerar en klass för arbete med PDF-dokumentanteckningar (kommentarer). |
| [PdfBookmarkEditor](./pdfbookmarkeditor/) | Representerar en klass för att arbeta med PDF-fils bokmärken inklusive skapa, ändra, exportera, importera och ta bort. |
| [PdfContentEditor](./pdfcontenteditor/) | Representerar en klass för att redigera PDF-fils innehåll. |
| [PdfConverter](./pdfconverter/) | Representerar en klass för att konvertera varje sida i en pdf-fil till bilder, med stöd för BMP, JPEG, PNG och TIFF nu. Stödd innehåll i pdf-filer: bilder, formulär, kommentarer. |
| [PdfExtractor](./pdfextractor/) | Klass för att extrahera bilder och text från PDF-dokument. |
| [PdfFileEditor](./pdffileeditor/) | Implementerar operationer med PDF‑fil: sammanslagning, delning, extrahering av sidor, skapa häfte, etc. |
| [PdfFileEditor.ConcatenateCorruptedFileAction](./pdffileeditor.concatenatecorruptedfileaction/) | Åtgärd som utförs när en korrupt fil påträffas i sammanslagningsprocessen. |
| [PdfFileEditor.ConcatenationProgressHandler](./pdffileeditor.concatenationprogresshandler/) | Representerar en klass med en abstrakt metod som vanligtvis tillhandahålls av anroparens sida och hanterar förloppshändelser som kommer från sammanslagning. Sådan levererad kundhanterare kan vanligtvis användas för att visa total sammanslagningsförlopp i konsolen eller i ett förloppsfält. Representerar information om inträffad förloppshändelse. |
| [PdfFileEditor.CorruptedItem](./pdffileeditor.corrupteditem/) | Klass som tillhandahåller information om korrupta filer under sammanslagning. |
| [PdfFileEditor.PageBreak](./pdffileeditor.pagebreak/) | Data för sidbrytningsposition. |
| [PdfFileEditor.ProgressEventHandlerInfo](./pdffileeditor.progresseventhandlerinfo/) | Denna klass representerar information om sammanslagningsförlopp som kan användas i ett externt program. |
| [PdfFileEditor.ProgressEventType](./pdffileeditor.progresseventtype/) | Denna enum beskriver möjliga typer av förloppshändelser som kan inträffa under sammanslagning |
| [PdfFileEditorWeb](./pdffileeditorweb/) | Representerar PdfFileEditorWeb-klassen som implementerar operationer med PDF-filer: sammanslagning, delning, extrahering av sidor, skapa häfte osv. |
| [PdfFileInfo](./pdffileinfo/) | Representerar en klass för åtkomst till metadata i PDF-dokument. |
| [PdfFileMend](./pdffilemend/) | Representerar en klass för att lägga till texter och bilder på sidorna i ett befintligt PDF-dokument. |
| [PdfFileSanitization](./pdffilesanitization/) | Representerar sanerings- och återställnings-API. Använd det om du inte kan skapa/öppna dokument på annat sätt. |
| [PdfFileSecurity](./pdffilesecurity/) | Representerar kryptering eller dekryptering av en Pdf-fil med ägar- eller användarlösenord, ändring av säkerhetsinställningar och lösenord. |
| [PdfFileSignature](./pdffilesignature/) | Representerar en klass för att signera en pdf-fil med ett certifikat. |
| [PdfFileStamp](./pdffilestamp/) | Klass för att lägga till stämplar (vattenstämpel eller bakgrund) i PDF-filer. |
| [PdfFileStampWeb](./pdffilestampweb/) | Klass för att lägga till stämplar (vattenstämpel eller bakgrund) i PDF-filer. Möjliggör arbete med HttpServletResponse. |
| [PdfJavaScriptStripper](./pdfjavascriptstripper/) | Klass för att ta bort all JavaScript-kod. |
| [PdfPageEditor](./pdfpageeditor/) | Representerar en klass för att redigera PDF-filens sida, inklusive rotera sidan, zooma sidan, flytta position och ändra sidstorlek. |
| [PdfPrintPageInfo](./pdfprintpageinfo/) | Representerar ett objekt som innehåller aktuell utskriftsinfosida. |
| [PdfProducer](./pdfproducer/) | <p> Representerar en klass för att skapa PDF från andra format. </p> <hr> <pre>Detta exempel visar hur man producerar en Pdf-fil från en CGM-fil. String inputFile = \"myImage.cgm\"; String outputFile = \"myPdf.pdf\"; try { PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); // Lyckad skapad pdf-fil. } catch (Exception e) { // Gör något... } </pre> |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler/) | Representerar metoden som hanterar QueryPageSettings‑händelsen för ett PrintDocument. |
| [PdfViewer](./pdfviewer/) | Representerar en klass för att visa eller skriva ut en pdf. |
| [PdfXmpMetadata](./pdfxmpmetadata/) | Klass för manipulation med XMP‑metadata. |
| [PositioningMode](./positioningmode/) | Definierar placeringsläge. Möjliga värden inkluderar Legacy (bakåtkompatibilitet) och Current (uppdaterad beräkningsmetod för textposition). |
| [PropertyFlag](./propertyflag/) | Enumeration av möjliga fältflaggor. |
| [ReplaceTextStrategy](./replacetextstrategy/) | Denna klass innehåller parametrar som definierar PdfContentEditor‑beteende när ReplaceText‑operationen utförs. |
| [SaveableFacade](./saveablefacade/) | <p> Basisklass för alla sparbara fasader. |
| [SignatureName](./signaturename/) | Representerar en klass för ett signaturnamn. Representerar ett mer exakt signaturnamn. Används istället för strängnamn. Gör det möjligt att presentera signaturer med samma strängnamn. |
| [Stamp](./stamp/) | Klass som representerar stämpel. |
| [StampInfo](./stampinfo/) | Klass som representerar stämpelinformation. |
| [TextProperties](./textproperties/) | Representerar textegenskaper såsom: textstorlek, färg, stil osv. |
| [VerticalAlignmentType](./verticalalignmenttype/) | Klass som representerar möjliga vertikala justeringsvärden. Använd VerticalAlignment istället. |
| [ViewerPreference](./viewerpreference/) | Beskriver visningsinställningar (sidläge, icke‑fullskärmsläge, sidlayout). |
| [WordWrapMode](./wordwrapmode/) | Definierar strategier för ordbrytning |
## Enums

| Enum | Beskrivning |
| --- | --- |
| [Algorithm](./algorithm/) | Representerar algoritmer som kan användas för att kryptera pdf‑dokument. |
| [BlendingColorSpace](./blendingcolorspace/) | Klass representerar blandningsfärgrymd. |
| [FieldType](./fieldtype/) | Enumeration av möjliga fälttyper. |
| [FontStyle](./fontstyle/) | Enumererar 14 typsnitt. |
| [ImageMergeMode](./imagemergemode/) | Representerar lägen för sammanslagning av bilder. |
| [KeySize](./keysize/) | Definierar olika nyckelstorlekar som kan användas för att kryptera pdf‑dokument. |
| [ReplaceTextStrategy.NoCharacterAction](./replacetextstrategy.nocharacteraction/) | Åtgärd att utföra om teckensnittet inte innehåller det erforderliga tecknet |
| [ReplaceTextStrategy.Scope](./replacetextstrategy.scope/) | Omfång där replace‑text‑operationen tillämpas, REPLACE_FIRST som standard. |
| [StampType](./stamptype/) | Beskriver stämpeltyper. |
| [SubmitFormFlag](./submitformflag/) | Enumeration av möjliga submit‑formulärflaggor. |
