---
title: "Aspose.PDF för Go via C++"
description: "Aspose.PDF för Go via C++"
keywords:  "Go, Golang, PDF, PDF toolkit, pdf, convert, processing"
tags: ['pdf-to-jpg', 'pdf-to-png', 'pdf-convert', 'pdf-tools']
weight: 40
url: /sv/go-cpp/
type: docs
is_root: true
---

> Aspose.PDF for Go via C++ allows developers manipulate them PDF files directly in the Go.

# Types

## Document
Dokumentet representerar ett PDF-dokument.

```go
type Document struct {
}
```

# Functions

## Convert from PDF functions

| Funktion | Beskrivning |
| -------- | ----------- |
| [SaveDocX](./convert/savedocx/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som DocX-dokument. |
| [SaveDoc](./convert/savedoc/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som Doc-dokument. |
| [SaveXlsX](./convert/savexlsx/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som XlsX-dokument. |
| [SaveTxt](./convert/savetxt/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som Txt-dokument. |
| [SavePptX](./convert/savepptx/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som PptX-dokument. |
| [SaveXps](./convert/savexps/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som Xps-dokument. |
| [SaveTeX](./convert/savetex/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som TeX-dokument. |
| [SaveEpub](./convert/saveepub/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som Epub-dokument. |
| [SaveBooklet](./convert/savebooklet/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som häfte PDF-dokument. |
| [SaveNUp](./convert/savenup/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som N-Up PDF-dokument. |
| [SaveMarkdown](./convert/savemarkdown/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som Markdown-dokument. |
| [SaveTiff](./convert/savetiff/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som Tiff-dokument. |
| [SaveDocXEnhanced](./convert/savedocxenhanced/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som DocX-dokument med Förbättrat igenkänningsläge (fullt redigerbara tabeller och stycken). |
| [SaveSvgZip](./convert/savesvgzip/) | Konvertera och spara det tidigare öppnade PDF-dokumentet som SVG-arkiv. |
| [ExportFdf](./convert/exportfdf/) | Exportera från det tidigare öppnade PDF-dokumentet med AcroForm till FDF-dokument. |
| [ExportXfdf](./convert/exportxfdf/) | Exportera från det tidigare öppnade PDF-dokumentet med AcroForm till XFDF-dokument. |
| [ExportXml](./convert/exportxml/) | Exportera från det tidigare öppnade PDF-dokumentet med AcroForm till XML-dokument. |
| [PageToJpg](./convert/pagetojpg/) | Konvertera och spara den angivna sidan som Jpg-bild. |
| [PageToPng](./convert/pagetopng/) | Konvertera och spara den angivna sidan som Png-bild. |
| [PageToBmp](./convert/pagetobmp/) | Konvertera och spara den angivna sidan som Bmp-bild. |
| [PageToTiff](./convert/pagetotiff/) | Konvertera och spara den angivna sidan som Tiff-bild. |
| [PageToSvg](./convert/pagetosvg/) | Konvertera och spara den angivna sidan som Svg-bild. |
| [PageToPdf](./convert/pagetopdf/) | Konvertera och spara den angivna sidan som Pdf. |
| [PageToDICOM](./convert/pagetodicom/) | Konvertera och spara den angivna sidan som DICOM-bild. |


## Organize PDF functions

| Funktion | Beskrivning |
| -------- | ----------- |
| [Optimize](./organize/optimize/) | Optimera PDF-dokumentets innehåll. |
| [OptimizeResource](./organize/optimizeresource/) | Optimera resurserna i PDF-dokumentet. |
| [Grayscale](./organize/grayscale/) | Konvertera PDF-dokument till svartvitt. |
| [Rotate](./organize/rotate/) | Rotera PDF-dokument. |
| [SetBackground](./organize/setbackground/) | Ställ in bakgrundsfärgen för PDF-dokument. |
| [Repair](./organize/repair/) | Reparera PDF-dokument. |
| [ReplaceText](./organize/replacetext/) | Ersätt text i PDF-dokument. |
| [AddPageNum](./organize/addpagenum/) | Lägg till sidnummer i ett PDF-dokument. |
| [AddTextHeader](./organize/addtextheader/) | Lägg till text i rubriken på ett PDF-dokument. |
| [AddTextFooter](./organize/addtextfooter/) | Lägg till text i sidfoten på ett PDF-dokument. |
| [Flatten](./organize/flatten/) | Platta till PDF-dokument. |
| [RemoveAnnotations](./organize/removeannotations/) | Ta bort annotationer från PDF-dokument. |
| [RemoveAttachments](./organize/removeattachments/) | Ta bort bilagor från PDF-dokument. |
| [RemoveBlankPages](./organize/removeblankpages/) | Ta bort tomma sidor från PDF-dokument. |
| [RemoveBookmarks](./organize/removebookmarks/) | Ta bort bokmärken från PDF-dokument. |
| [RemoveHiddenText](./organize/removehiddentext/) | Ta bort dold text från PDF-dokument. |
| [RemoveImages](./organize/removeimages/) | Ta bort bilder från PDF-dokument. |
| [RemoveJavaScripts](./organize/removejavascripts/) | Ta bort Java-skript från PDF-dokument. |
| [RemoveTables](./organize/removetables/) | Ta bort tabeller från PDF-dokument. |
| [RemoveWatermarks](./organize/removewatermarks/) | Ta bort vattenstämplar från PDF-dokument. |
| [AddWatermark](./organize/addwatermark/) | Lägg till vattenstämpel i PDF-dokument. |
| [EmbedFonts](./organize/embedfonts/) | Bädda in typsnitt i ett PDF-dokument. |
| [UnembedFonts](./organize/unembedfonts/) | Ta bort inbäddade teckensnitt i ett PDF-dokument. |
| [OptimizeFileSize](./organize/optimizefilesize/) | Optimera storleken på PDF-dokumentet med bildkomprimeringskvalitet. |
| [RemoveTextHeaders](./organize/removetextheaders/) | Ta bort textrubriker från PDF-dokumentet. |
| [RemoveTextFooters](./organize/removetextfooters/) | Ta bort textsidfötter från PDF-dokumentet. |
| [Crop](./organize/crop/) | Beskär sidor i ett PDF-dokument. |
| [ReplaceFont](./organize/replacefont/) | Byt teckensnitt i ett PDF-dokument. |
| [Convert](./organize/convert/) | Konvertera ett PDF-dokument till ett PDF-dokument med det angivna PDF-formatet. |
| [Validate](./organize/validate/) | Validera ett PDF-dokument för efterlevnad av PDF-formatet. |
| [RemovePdfaCompliance](./organize/removepdfacompliance/) | Ta bort PDF/A-efterlevnad från ett PDF-dokument. |
| [RemovePdfUaCompliance](./organize/removepdfuacompliance/) | Ta bort PDF/UA-efterlevnad från ett PDF-dokument. |
| [IsPdfaCompliant](./organize/ispdfacompliant/) | Kontrollera om ett PDF-dokument är PDF/A-kompatibelt. |
| [IsPdfUaCompliant](./organize/ispdfuacompliant/) | Kontrollera om ett PDF-dokument är PDF/UA-kompatibelt. |
| [PageRotate](./organize/pagerotate/) | Rotera sida. |
| [PageSetSize](./organize/pagesetsize/) | Ställ in sidans storlek. |
| [PageGrayscale](./organize/pagegrayscale/) | Konvertera sida till svartvitt. |
| [PageAddText](./organize/pageaddtext/) | Lägg till text på sidan. |
| [PageReplaceText](./organize/pagereplacetext/) | Byt ut text på sidan. |
| [PageAddPageNum](./organize/pageaddpagenum/) | Lägg till sidnummer på sidan. |
| [PageAddTextHeader](./organize/pageaddtextheader/) | Lägg till text i sidhuvud. |
| [PageAddTextFooter](./organize/pageaddtextfooter/) | Lägg till text i sidfot. |
| [PageRemoveAnnotations](./organize/pageremoveannotations/) | Ta bort annotationer på sidan. |
| [PageRemoveHiddenText](./organize/pageremovehiddentext/) | Ta bort dold text på sidan. |
| [PageRemoveImages](./organize/pageremoveimages/) | Ta bort bilder på sidan. |
| [PageRemoveTables](./organize/pageremovetables/) | Ta bort tabeller på sidan. |
| [PageRemoveWatermarks](./organize/pageremovewatermarks/) | Ta bort vattenstämplar på sidan. |
| [PageAddWatermark](./organize/pageaddwatermark/) | Lägg till vattenstämpel på sidan. |
| [PageRemoveTextHeaders](./organize/pageremovetextheaders/) | Ta bort textrubriker på sidan. |
| [PageRemoveTextFooters](./organize/pageremovetextfooters/) | Ta bort textfotnoter på sidan. |
| [PageCrop](./organize/pagecrop/) | Beskär sidan. |
| [PageReplaceFont](./organize/pagereplacefont/) | Byt teckensnitt på sidan. |
| [PageMergeLayers](./organize/pagemergelayers/) | Slå samman alla lager på sidan till ett enda lager med det angivna nya lagernamnet. |
| [PageLayers](./organize/pagelayers/) | Hämtar lagernamnen på sidan. |


## Core PDF functions

| Funktion | Beskrivning |
| -------- | ----------- |
| [New](./core/new/) | Skapa ett nytt PDF-dokument. |
| [Open](./core/open/) | Öppna ett PDF-dokument med filnamnet. |
| [Save](./core/save/) | Spara det tidigare öppnade PDF-dokumentet. |
| [SaveAs](./core/saveas/) | Spara det tidigare öppnade PDF-dokumentet med ett nytt filnamn. |
| [Close](./core/close/) | Frigör allokerade resurser för PDF-dokumentet. |
| [SetLicense](./core/setlicense/) | Ställ in licens med filnamn. |
| [ExtractText](./core/extracttext/) | Returnera PDF-dokumentets innehåll som vanlig text. |
| [WordCount](./core/wordcount/) | Returnera antalet ord i PDF-dokumentet. |
| [CharacterCount](./core/charactercount/) | Returnera antalet tecken i PDF-dokumentet. |
| [Append](./core/append/) | Lägg till sidor från ett annat PDF-dokument. |
| [AppendPages](./core/appendpages/) | Lägg till valda sidor från ett annat PDF-dokument. |
| [MergeDocuments](./core/mergedocuments/) | Skapa ett nytt PDF-dokument genom att slå samman de angivna PDF-dokumenten. |
| [SplitDocument](./core/splitdocument/) | Skapa flera nya PDF-dokument genom att extrahera sidor från käll-PDF-dokumentet. |
| [Split](./core/split/) | Skapa flera nya PDF-dokument genom att extrahera sidor från det aktuella PDF-dokumentet. |
| [SplitAtPage](./core/splitatpage/) | Dela PDF-dokumentet i två nya PDF-dokument. |
| [SplitAt](./core/splitat/) | Dela det aktuella PDF-dokumentet i två nya PDF-dokument. |
| [Bytes](./core/bytes/) | Returnera innehållet i PDF-dokumentet som en byte-slice. |
| [GetMetaInfo](./core/getmetainfo/) | Hämta metainformationsvärde för PDF-dokumentet.. |
| [SetMetaInfo](./core/setmetainfo/) | Ställ in metainformationsvärde för PDF-dokument.. |
| [ClearMetaInfo](./core/clearmetainfo/) | Rensa alla metainformationsvärden för PDF-dokument.. |
| [IsLinearized](./core/islinearized/) | Hämta ett värde som indikerar om dokumentet är lineariserat. |
| [PageAdd](./core/pageadd/) | Lägg till ny sida i PDF-dokument. |
| [PageInsert](./core/pageinsert/) | Infoga ny sida på den angivna positionen i PDF-dokument. |
| [PageDelete](./core/pagedelete/) | Ta bort angiven sida i PDF-dokument. |
| [PageCount](./core/pagecount/) | Returnera sidantal i PDF-dokument. |
| [PageWordCount](./core/pagewordcount/) | Returnera ordantal på angiven sida i PDF-dokument. |
| [PageCharacterCount](./core/pagecharactercount/) | Returnera teckenantal på angiven sida i PDF-dokument. |
| [PageIsBlank](./core/pageisblank/) | Returnera om sidan är tom i PDF-dokument. |


## Security

| Funktion | Beskrivning |
| -------- | ----------- |
| [OpenWithPassword](./security/openwithpassword/) | Öppna ett lösenordsskyddat PDF-dokument. |
| [Encrypt](./security/encrypt/) | Kryptera PDF-dokument. |
| [Decrypt](./security/decrypt/) | Dekryptera PDF-dokument. |
| [SetPermissions](./security/setpermissions/) | Ställ in behörigheter för PDF-dokument. |
| [GetPermissions](./security/getpermissions/) | Hämta aktuella behörigheter för PDF-dokument. |
| [IsEncrypted](./security/isencrypted/) | Hämta krypteringsstatus för PDF-dokument. |
| [SignPKCS7](./security/signpkcs7/) | Signera ett PDF-dokument med PKCS#7 digitala signaturer. |
| [SignPKCS7Detached](./security/signpkcs7detached/) | Signera ett PDF-dokument med PKCS#7 fristående digitala signaturer. |
| [IsSigned](./security/issigned/) | Hämta signeringsstatus för PDF-dokument. |
| [RemoveSigns](./security/removesigns/) | Ta bort signaturer från PDF-dokument. |


## Miscellaneous

| Funktion | Beskrivning |
| -------- | ----------- |
| [About](./miscellaneous/about/) | Returnera metadatainformation om Aspose.PDF för Go via C++. |


# Types secondary

## ProductInfo contains metadata about the Aspose.PDF for Go via C++.
```go
type ProductInfo struct {
	Product     string `json:"product"`     // Name
	Family      string `json:"family"`      // Family (e.g., "Aspose.PDF")
	Version     string `json:"version"`     // Version
	ReleaseDate string `json:"releasedate"` // Release date in ISO format (YYYY-MM-DD)
	Producer    string `json:"producer"`    // Producer
	IsLicensed  bool   `json:"islicensed"`  // License status (true if licensed)
}
```


# Constants

## Enumeration of possible rotation values.
```go
const (
    RotationNone  int32 = 0 // Non-rotated.
    RotationOn90  int32 = 1 // Rotated on 90 degrees clockwise.
    RotationOn180 int32 = 2 // Rotated on 180 degrees.
    RotationOn270 int32 = 3 // Rotated on 270 degrees clockwise.
    RotationOn360 int32 = 4 // Rotated on 360 degrees clockwise.
)
```

## Enumeration of possible page size values.
```go
const (
    PageSizeA0         int32 = 0  // A0 size.
    PageSizeA1         int32 = 1  // A1 size.
    PageSizeA2         int32 = 2  // A2 size.
    PageSizeA3         int32 = 3  // A3 size.
    PageSizeA4         int32 = 4  // A4 size.
    PageSizeA5         int32 = 5  // A5 size.
    PageSizeA6         int32 = 6  // A6 size.
    PageSizeB5         int32 = 7  // B5 size.
    PageSizePageLetter int32 = 8  // PageLetter size.
    PageSizePageLegal  int32 = 9  // PageLegal size.
    PageSizePageLedger int32 = 10 // PageLedger size.
    PageSizeP11x17     int32 = 11 // P11x17 size.
)
```

## Enumeration of possible crypto algorithms.
```go
type CryptoAlgorithm int32
const (
	RC4x40  CryptoAlgorithm = 0 // RC4 with key length 40.
	RC4x128 CryptoAlgorithm = 1 // RC4 with key length 128.
	AESx128 CryptoAlgorithm = 2 // AES with key length 128.
	AESx256 CryptoAlgorithm = 3 // AES with key length 256.
)
```

## Enumeration of possible PDF formats.
```go
type PdfFormat int32
const (
	PDF_A_1A      PdfFormat = iota // Pdf/A-1a format.
	PDF_A_1B                       // Pdf/A-1b format.
	PDF_A_2A                       // Pdf/A-2a format.
	PDF_A_3A                       // Pdf/A-3a format.
	PDF_A_2B                       // Pdf/A-2b format.
	PDF_A_2U                       // Pdf/A-2u format.
	PDF_A_3B                       // Pdf/A-3b format.
	PDF_A_3U                       // Pdf/A-3u format.
	V_1_0                          // Adobe version 1.0.
	V_1_1                          // Adobe version 1.1.
	V_1_2                          // Adobe version 1.2.
	V_1_3                          // Adobe version 1.3.
	V_1_4                          // Adobe version 1.4.
	V_1_5                          // Adobe version 1.5.
	V_1_6                          // Adobe version 1.6.
	V_1_7                          // Adobe version 1.7.
	V_2_0                          // ISO Standard PDF 2.0.
	PDF_UA_1                       // PDF/UA-1 format.
	PDF_X_1A_2001                  // PDF/X-1a-2001 format.
	PDF_X_1A                       // PDF/X-1a format.
	PDF_X_3                        // PDF/X-3 format.
	ZUGFeRD                        // ZUGFeRD format.
	PDF_A_4                        // PDF/A-4 format.
	PDF_A_4E                       // PDF/A-4e format.
	PDF_A_4F                       // PDF/A-4f format.
	PDF_X_4                        // PDF/X-4 format.
	PDF_E_1                        // PDF/E-1 (PDF 1.6) format.
)
```

## Enumeration of possible conversion errors action.
```go
type ConvertErrorAction int32
const (
	Delete ConvertErrorAction = iota // Delete convert errors.
	None                             // Do nothing with convert errors.
)
```

## Bitflag set representing PDF permission capabilities.
```go
type Permissions int32
const (
    PrintDocument                  Permissions = 1 << 2  // 4
    ModifyContent                  Permissions = 1 << 3  // 8
    ExtractContent                 Permissions = 1 << 4  // 16
    ModifyTextAnnotations          Permissions = 1 << 5  // 32
    FillForm                       Permissions = 1 << 8  // 256
    ExtractContentWithDisabilities Permissions = 1 << 9  // 512
    AssembleDocument               Permissions = 1 << 10 // 1024
    PrintingQuality                Permissions = 1 << 11 // 2048
)
```
