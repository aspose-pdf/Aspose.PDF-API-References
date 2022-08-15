---
title: PdfFileInfo
second_title: Aspose.PDF för .NET API Referens
description: Representerar en klass för åtkomst av metainformation för PDF-dokument.
type: docs
weight: 2530
url: /sv/net/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo class

Representerar en klass för åtkomst av metainformation för PDF-dokument.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PdfFileInfo](pdffileinfo#constructor)() | Initierar en ny instans av klassen Aspose.Pdf.Facades.PdfFileInfo med standardvärden. |
| [PdfFileInfo](pdffileinfo#constructor_1)(Document) | Initierar ny[`PdfFileInfo`](../pdffileinfo) objekt på basen av*document* . |
| [PdfFileInfo](pdffileinfo#constructor_2)(Stream) | Initierar en ny instans av klassen Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo#constructor_4)(string) | Initierar en ny instans av klassen Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo#constructor_3)(Stream, string) | Initierar en ny instans av klassen Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo#constructor_5)(string, string) | Initierar en ny instans av klassen Aspose.Pdf.Facades.PdfFileInfo. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author) { get; set; } | Hämtar eller ställer in författarinformation för PDF-dokument. |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate) { get; set; } | Hämtar eller ställer in CreationDate-informationen för PDF-dokument. |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator) { get; set; } | Hämtar eller ställer in skaparinformationen för PDF-dokument. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Får dokumentfasaden arbetar på. |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection) { get; } | Returnerar sant om den aktuella indatafilen är en "Portfolio"-fil som innehåller en samling PDF-filer. |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword) { get; } | Returnerar sant om lösenord behövs för att ändra behörigheter eller dokumentsäkerhetsegenskap. Var uppmärksam på att den här egenskapen endast kan läsas om ett giltigt lösenord angavs i[`PdfFileInfo`](../pdffileinfo) constructor. Om PasswordType är otillgänglig (betyder att ogiltigt lösenord angavs) kommer läsning av denna egenskap att misslyckas med[`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception) . |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword) { get; } | Returnerar sant om lösenord behövs för att öppna ett lösenordsskyddat pdf-dokument. |
| [Header](../../aspose.pdf.facades/pdffileinfo/header) { get; set; } | Hämtar eller ställer in den anpassade informationen för PDF-dokument. |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted) { get; } | Kontrollerar om PDF-dokumentet är krypterat. |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile) { get; } | Kontrollerar om källingången är en giltig PDF-fil. |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords) { get; set; } | Hämtar eller ställer in nyckelordsinformation för PDF-dokument. |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate) { get; set; } | Hämtar eller ställer in ModDate-datuminformation för PDF-dokument. |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages) { get; } | Hämtar antalet dokumentsidor. |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype) { get; } | Returnerar den typ av lösenord som skickades för att skapa PdfFileInfo-instanser. Se möjliga värden i[`PasswordType`](./passwordtype) . Var uppmärksam på att pdf-dokument kan öppnas med både användarlösenord (eller öppet) och ägarens (eller behörigheter, redigera) lösenord. |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer) { get; } | Hämtar producentinformation för PDF-dokument. |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject) { get; set; } | Hämtar eller ställer in ämnesinformationen för PDF-dokumentet. |
| [Title](../../aspose.pdf.facades/pdffileinfo/title) { get; set; } | Hämtar eller ställer in titelinformation för PDF-dokument. |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation) { get; set; } | Använder strikta valideringsregler genom att använda[`IsPdfFile`](./ispdffile) egenskap. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf#bindpdf)(Document) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Initierar fasaden. |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo)() | Rensar all metainformation i PDF-dokument. |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close)() | Avinitialiserar instansen. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Disponerar fasaden. |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege)() | Hämtar behörighetsinställningarna för PDF-dokument. |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo)(string) | Får anpassad information om PDF-dokument med egenskapsnamn. Om det inte finns någon egenskap som matchar namnet kommer den att returnera en tom sträng. |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight)(int) | Hämtar höjden på den angivna sidan. |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation)(int) | Hämtar rotationen av den angivna sidan. |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth)(int) | Hämtar bredden på den angivna sidan. |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset)(int) | Får den horisontella förskjutningen av det angivna sidvisningsområdet. |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset)(int) | Hämtar den vertikala förskjutningen av det angivna sidvisningsområdet. |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion)() | Hämtar versionsinformation för PDF-dokument. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save#save)(Stream) | Sparar PDF-dokumentet till den angivna filen. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save#save_1)(string) | Sparar PDF-dokumentet till den angivna filen. |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo#savenewinfo_1)(string) | Spara uppdaterat PDF-dokument i angiven fil. |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp)(string) | Ändrar de egenskaper som anges explicit genom att ställa in filinformation, andra egenskaper kvarstår. |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo)(string, string) | Ställer in anpassad information för PDF-dokument. |

### Se även

* class [SaveableFacade](../saveablefacade)
* namnutrymme [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
