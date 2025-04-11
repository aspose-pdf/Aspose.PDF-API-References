---
title: Aspose.Pdf.Facades
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades-namnområdet tillhandahåller klasser som ursprungligen kom från Aspose.Pdf.Kit. Dessa klasser används för att manipulera dokument och utföra operationer som sammanfogning, stämpling, signering, annotering etc. men på en hög nivå utan tillgång till ett dokuments inre struktur.
type: docs
weight: 100
url: /sv/net/aspose.pdf.facades/
---
Det **Aspose.Pdf.Facades** namnområdet tillhandahåller klasser som ursprungligen kom från Aspose.Pdf.Kit. Dessa klasser används för att manipulera dokument och utföra operationer som sammanfogning, stämpling, signering, annotering etc. men på en hög nivå utan tillgång till ett dokuments inre struktur.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [AutoFiller](./autofiller/) | Representerar en klass för att ta emot data från databas eller annan datakälla, fyller dem i de designade fälten i den mallade pdf:en och genererar slutligen en ny pdf-fil eller ström. Den har två inmatningslägen för mallfil: inmatning som en ström eller en pdf-fil. Den har fyra typer av utmatningslägen: en sammanfogad ström, en sammanfogad fil, många små strömmar, många små filer. Den kan ta emot bokstavlig data som finns i en System.Data.DataTable. |
| [BDCProperties](./bdcproperties/) | BDC-operatörsegenskaper. |
| [Bookmark](./bookmark/) | Representerar ett bokmärke. |
| [Bookmarks](./bookmarks/) | Representerar en samling av [`Bookmark`](../aspose.pdf.facades/bookmark/) objekt. |
| [DocumentPrivilege](./documentprivilege/) | Representerar privilegier för att få åtkomst till Pdf-fil. Se [`PdfFileSecurity`](../aspose.pdf.facades/pdffilesecurity/). Det finns 4 sätt att använda denna klass: 1. Använda fördefinierat privilegium direkt. 2. Baserat på ett fördefinierat privilegium och ändra vissa specifika behörigheter. 3. Baserat på ett fördefinierat privilegium och ändra vissa specifika kombinationer av Adobe Professional-behörigheter. 4. Blandar sätt 2 och sätt 3. |
| [Facade](./facade/) | Basfacadklass. |
| [FontColor](./fontcolor/) | Klass som representerar färgen på texten. |
| [Form](./form/) | Klass som representerar Acro-formobjekt. |
| [FormattedText](./formattedtext/) | Klass som representerar formaterad text. Innehåller information om text och dess färg, storlek, stil. |
| [FormDataConverter](./formdataconverter/) | Representerar en klass för att konvertera data från ett format till ett annat format. Den kan konvertera data i fdf/xml/pdf/xfdf till OLEDB/OdbcDB. Den kan också konvertera data i OLEDB/OdbcDB till data i fdf/xml/xfdf. Den kan konvertera fdf till xml med "hård-namngiven" tagg. |
| [FormEditor](./formeditor/) | Klass för att redigera formulär (lägga till/ta bort fält etc.) |
| [FormFieldFacade](./formfieldfacade/) | Klass för att representera fältets egenskaper. |
| [LineInfo](./lineinfo/) | Representerar information om linjen. |
| [PdfAnnotationEditor](./pdfannotationeditor/) | Representerar en klass för att arbeta med PDF-dokumentannoteringar (kommentarer). |
| [PdfBookmarkEditor](./pdfbookmarkeditor/) | Representerar en klass för att arbeta med PDF-filens bokmärken inklusive skapa, ändra, exportera, importera och ta bort. |
| [PdfContentEditor](./pdfcontenteditor/) | Representerar en klass för att redigera PDF-filens innehåll. |
| [PdfConverter](./pdfconverter/) | Representerar en klass för att konvertera varje sida av en pdf-fil till bilder, som nu stöder BMP, JPEG, PNG och TIFF. Stödda innehåll i pdf:er: bilder, formulär, kommentarer. |
| [PdfExtractor](./pdfextractor/) | Klass för att extrahera bilder och text från PDF-dokument. |
| [PdfFileEditor](./pdffileeditor/) | Implementerar operationer med PDF-fil: sammanfogning, uppdelning, extrahera sidor, göra häfte, etc. |
| [PdfFileInfo](./pdffileinfo/) | Representerar en klass för att få åtkomst till meta-information om PDF-dokument. |
| [PdfFileMend](./pdffilemend/) | Representerar en klass för att lägga till texter och bilder på sidorna av ett befintligt PDF-dokument. |
| [PdfFileSanitization](./pdffilesanitization/) | Representerar sanering och återställning API. Använd det om du inte kan skapa/öppna dokument på något annat sätt. |
| [PdfFileSecurity](./pdffilesecurity/) | Representerar kryptering eller dekryptering av en Pdf-fil med ägar- eller användarlösenord, ändra säkerhetsinställningar och lösenord. |
| [PdfFileSignature](./pdffilesignature/) | Representerar en klass för att signera en pdf-fil med ett certifikat. |
| [PdfFileStamp](./pdffilestamp/) | Klass för att lägga till stämplar (vattenstämpel eller bakgrund) till PDF-filer. |
| [PdfJavaScriptStripper](./pdfjavascriptstripper/) | Klass för att ta bort all JavaScript-kod. |
| [PdfPageEditor](./pdfpageeditor/) | Representerar en klass för att redigera PDF-filens sida, inklusive rotera sida, zooma sida, flytta position och ändra sidstorlek. |
| [PdfPrintPageInfo](./pdfprintpageinfo/) | Representerar ett objekt som innehåller aktuell utskrifts sidinformation. |
| [PdfProducer](./pdfproducer/) | Representerar en klass för att producera PDF från andra format. Detta exempel visar hur man producerar en Pdf-fil från CGM-fil. |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler/) | Representerar metoden som hanterar [`PdfQueryPageSettings`](../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) händelsen av en [`PdfViewer`](../aspose.pdf.facades/pdfviewer/). |
| [PdfViewer](./pdfviewer/) | Representerar en klass för att visa eller skriva ut en pdf. |
| [PdfXmpMetadata](./pdfxmpmetadata/) | Klass för manipulation med XMP-metadata. |
| [ReplaceTextStrategy](./replacetextstrategy/) | Denna klass innehåller parametrar som definierar PdfContentEditors beteende när ReplaceText-operationen utförs. |
| [SaveableFacade](./saveablefacade/) | Bas klass för alla sparbara fasader. |
| [SignatureName](./signaturename/) | Representerar en klass för ett signaturnamn. |
| [Stamp](./stamp/) | Klass som representerar stämpel. |
| [StampInfo](./stampinfo/) | Klass som representerar stämpelinformation. |
| [TextProperties](./textproperties/) | Representerar textegenskaper som: textstorlek, färg, stil etc. |
| [ViewerPreference](./viewerpreference/) | Beskriver visningspreferenser (sidemod, icke-fullskärm sidemod, sidlayout). |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IFacade](./ifacade/) | Allmänt fasadgränssnitt som definierar gemensamma fasadmetoder. |
| [ISaveableFacade](./isaveablefacade/) | Fasadgränssnitt som definierar metoder som är gemensamma för alla sparbara fasader. |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [Algorithm](./algorithm/) | Representerar algoritmer som kan användas för att kryptera pdf-dokument. |
| [AutoRotateMode](./autorotatemode/) | Riktning av rotation när dokumentet skrivs ut. |
| [BlendingColorSpace](./blendingcolorspace/) | Klass som representerar blandningsfärgrymd. |
| [DataType](./datatype/) | Uppräkning av fälttyperdefinitioner. |
| [DefaultMetadataProperties](./defaultmetadataproperties/) | Uppräkning av standard XMP-egenskaper. |
| [EncodingType](./encodingtype/) | Uppräkning av kodningstyper för textanvändning. |
| [FieldType](./fieldtype/) | Uppräkning av möjliga fälttyper. |
| [FontStyle](./fontstyle/) | Uppräkning av 14 typer av typsnitt. |
| [ImageMergeMode](./imagemergemode/) | Representerar lägen för att sammanfoga bilder. |
| [KeySize](./keysize/) | Definierar olika nyckelstorlekar som kan användas för att kryptera pdf-dokument. |
| [PositioningMode](./positioningmode/) | Definierar placeringsläge. Möjliga värden inkluderar Legacy (bakåtkompatibilitet) och Current (uppdaterad metod för beräkning av textposition) |
| [PropertyFlag](./propertyflag/) | Uppräkning av möjliga fältflaggor. |
| [StampType](./stamptype/) | Beskriver stämplar. |
| [SubmitFormFlag](./submitformflag/) | Uppräkning av möjliga flaggor för att skicka formulär. |
| [WordWrapMode](./wordwrapmode/) | Definierar strategier för radbrytning |