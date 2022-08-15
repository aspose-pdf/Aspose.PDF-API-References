---
title: Aspose.Pdf.Facades
second_title: Aspose.PDF för .NET API Referens
description: Den Aspose.Pdf.Facadesnamnområdet tillhandahåller klasser som ursprungligen kom från Aspose.Pdf.Kit. Dessa klasser används för att manipulera documents för att utföra operationer som sammanlänkning stämpling signering anteckning etc. men på hög nivå utan tillgång till dokumentets inre struktur.
type: docs
weight: 80
url: /sv/net/aspose.pdf.facades/
---
Den **Aspose.Pdf.Facades**namnområdet tillhandahåller klasser som ursprungligen kom från Aspose.Pdf.Kit. Dessa klasser används för att manipulera documents för att utföra operationer som sammanlänkning, stämpling, signering, anteckning etc. men på hög nivå utan tillgång till dokumentets inre struktur.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [AutoFiller](./autofiller) | Representerar en klass för att ta emot data från databas eller annan datakälla, fyller dem i de designade fälten i mallen pdf och genererar till sist en ny pdf-fil eller ström. Den har två inmatningslägen för mallfil: inmatning som en ström eller en pdf-fil . Den har fyra typer av utdatalägen: en sammanslagen ström, en sammanslagen fil, många små strömmar, många små filer. Den kan ta emot bokstavlig data som finns i en System.Data.DataTable. |
| [Bookmark](./bookmark) | Representerar ett bokmärke. |
| [Bookmarks](./bookmarks) | Representerar en samling av[`Bookmark`](../aspose.pdf.facades/bookmark) objekt. |
| [DocumentPrivilege](./documentprivilege) | Representerar privilegierna för åtkomst till Pdf-fil. Hänvisa till[`PdfFileSecurity`](../aspose.pdf.facades/pdffilesecurity) . Det finns fyra sätt att använda den här klassen: 1.Användning av fördefinierad behörighet direkt. 2.Baserat på en fördefinierad behörighet och ändra vissa specifika behörigheter. 3.Baserat på en fördefinierad behörighet och ändra någon specifik Adobe-kombination0 behörighet._x00d 4.Blandar way2 och way3. |
| [Facade](./facade) | Basfasadklass. |
| [FontColor](./fontcolor) | Klass som representerar färgen på texten. |
| [Form](./form) | Klass som representerar Acro-formulärobjekt. |
| [FormattedText](./formattedtext) | Klass som representerar formaterad text. Innehåller information om text och dess färg, storlek, stil. |
| [FormDataConverter](./formdataconverter) | Representerar en klass för att konvertera data från ett format till ett annat format. Den kan konvertera data i fdf/xml/pdf/xfdf till OLEDB/OdbcDB. Den kan också konvertera data i OLEDB/OdbcDB till data i fdf/xml/xfdf. Det kan konvertera fdf till xml med "hard-named" tag. |
| [FormEditor](./formeditor) | Klass för redigering av formulär (lägga till/ta bort fält etc) |
| [FormFieldFacade](./formfieldfacade) | Klass för att representera fältegenskaper. |
| [LineInfo](./lineinfo) | Representerar informationen för linjen. |
| [PdfAnnotationEditor](./pdfannotationeditor) | Representerar en klass för arbete med PDF-dokumentkommentarer (kommentarer). |
| [PdfBookmarkEditor](./pdfbookmarkeditor) | Representerar en klass för att arbeta med PDF-filens bokmärken inklusive skapa, ändra, exportera, importera och ta bort. |
| [PdfContentEditor](./pdfcontenteditor) | Representerar en klass för att redigera PDF-filens innehåll. |
| [PdfConverter](./pdfconverter) | Representerar en klass för att konvertera en pdf-fils varje sida till bilder, stöder BMP, JPEG, PNG och TIFF nu. Innehåll som stöds i pdf:er: bilder, formulär, kommentar. |
| [PdfExtractor](./pdfextractor) | Klass för att extrahera bilder och text från PDF-dokument. |
| [PdfFileEditor](./pdffileeditor) | Implementerar operationer med PDF-fil: sammanlänkning, dela, extrahera sidor, göra häften, etc. |
| [PdfFileInfo](./pdffileinfo) | Representerar en klass för åtkomst av metainformation för PDF-dokument. |
| [PdfFileMend](./pdffilemend) | Representerar en klass för att lägga till texter och bilder på sidorna i befintliga PDF-dokument. |
| [PdfFileSanitization](./pdffilesanitization) | Representerar sanerings- och återställnings-API. Använd det om du inte kan skapa/öppna dokument på något annat sätt. |
| [PdfFileSecurity](./pdffilesecurity) | Representerar kryptering eller dekryptering av en PDF-fil med ägar- eller användarlösenord, ändring av säkerhetsinställning och lösenord. |
| [PdfFileSignature](./pdffilesignature) | Representerar en klass för att signera en pdf-fil med ett certifikat. |
| [PdfFileStamp](./pdffilestamp) | Klass för att lägga till stämplar (vattenstämpel eller bakgrund) till PDF-filer. |
| [PdfJavaScriptStripper](./pdfjavascriptstripper) | Klass för att ta bort all Java Script-kod. |
| [PdfPageEditor](./pdfpageeditor) | Representerar en klass för att redigera PDF-filens sida, inklusive roterande sida, zoomande sida, flytta position och ändra sidstorlek. |
| [PdfPrintPageInfo](./pdfprintpageinfo) | Representerar ett objekt som innehåller information om aktuell utskriftssida. |
| [PdfProducer](./pdfproducer) | Representerar en klass för att producera PDF från andra format.  Detta exempel visar hur man skapar en pdf-fil från CGM-fil. |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler) | Representerar metoden som hanterar QueryPageSettings-händelsen i ett PrintDocument. |
| [PdfViewer](./pdfviewer) | Representerar en klass för att visa eller skriva ut en pdf. |
| [PdfXmpMetadata](./pdfxmpmetadata) | Klass för manipulation med XMP-metadata. |
| [ReplaceTextStrategy](./replacetextstrategy) | Den här klassen innehåller parametrar som definierar PdfContentEditor-beteendet när ReplaceText-operationen utförs. |
| [SaveableFacade](./saveablefacade) | Basklass för alla räddningsbara fasader. |
| [Stamp](./stamp) | Klassrepreset stämpel. |
| [StampInfo](./stampinfo) | Klass som representerar stämpelinformation. |
| [TextProperties](./textproperties) | Representerar textegenskaper som: textstorlek, färg, stil etc. |
| [ViewerPreference](./viewerpreference) | Beskriver visningsinställningar (sidläge, sidläge utan helskärm, sidlayout). |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IFacade](./ifacade) | Allmänt fasadgränssnitt som definierar vanliga fasadmetoder. |
| [ISaveableFacade](./isaveablefacade) | Fasadgränssnitt som definierar metoder som är gemensamma för alla räddningsbara fasader. |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [Algorithm](./algorithm) | Representerar algoritmer som kan användas för att kryptera pdf-dokument. |
| [AutoRotateMode](./autorotatemode) | Rotationsriktningen när dokumentet skrivs ut. |
| [BlendingColorSpace](./blendingcolorspace) | Klass representerar blandad färgrymd. |
| [DataType](./datatype) | Räknar upp fälttypers definitioner. |
| [DefaultMetadataProperties](./defaultmetadataproperties) | Uppräkning av standard XMP-egenskaper. |
| [EncodingType](./encodingtype) | Räknar upp kodningstyper för texten med hjälp av. |
| [FieldType](./fieldtype) | Uppräkning av möjliga fälttyper. |
| [FontStyle](./fontstyle) | Räknar upp 14 typer av teckensnitt. |
| [ImageMergeMode](./imagemergemode) | Representerar lägen för sammanfogning av bilder. |
| [KeySize](./keysize) | Definierar olika nyckelstorlekar som kan användas för att kryptera pdf-dokument. |
| [PositioningMode](./positioningmode) | Definierar positioneringsläge. Möjliga värden inkluderar Legacy (bakåtkompatibilitet) och Current (uppdaterad textpositionsberäkningsmetod) |
| [PropertyFlag](./propertyflag) | Uppräkning av möjliga fältflaggor. |
| [StampType](./stamptype) | Beskriver stämpeltyper. |
| [SubmitFormFlag](./submitformflag) | Uppräkning av möjliga flaggor för inlämning av formulär. |
| [WordWrapMode](./wordwrapmode) | Definierar ordinpackningsstrategier |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
