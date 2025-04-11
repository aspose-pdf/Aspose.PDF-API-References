---
title: Class PdfFileInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileInfo klass. Representerar en klass för att få åtkomst till meta-information om PDF-dokument
type: docs
weight: 4520
url: /sv/net/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo klass

Representerar en klass för att få åtkomst till meta-information om PDF-dokument.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfFileInfo](pdffileinfo/#constructor)() | Initierar en ny instans av Aspose.Pdf.Facades.PdfFileInfo-klassen med standardvärden. |
| [PdfFileInfo](pdffileinfo/#constructor_1)(Document) | Initierar ett nytt `PdfFileInfo`-objekt baserat på *dokumentet*. |
| [PdfFileInfo](pdffileinfo/#constructor_2)(Stream) | Initierar en ny instans av Aspose.Pdf.Facades.PdfFileInfo-klassen. |
| [PdfFileInfo](pdffileinfo/#constructor_4)(string) | Initierar en ny instans av Aspose.Pdf.Facades.PdfFileInfo-klassen. |
| [PdfFileInfo](pdffileinfo/#constructor_3)(Stream, string) | Initierar en ny instans av Aspose.Pdf.Facades.PdfFileInfo-klassen. |
| [PdfFileInfo](pdffileinfo/#constructor_5)(string, string) | Initierar en ny instans av Aspose.Pdf.Facades.PdfFileInfo-klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author/) { get; set; } | Hämtar eller sätter författarinformationen för PDF-dokumentet. |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate/) { get; set; } | Hämtar eller sätter skapelsedatuminformationen för PDF-dokumentet. |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator/) { get; set; } | Hämtar eller sätter skaparinformationen för PDF-dokumentet. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar det dokument som fasaden arbetar med. |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection/) { get; } | Returnerar sant om den aktuella inmatningsfilen är en 'Portfolio'-fil som innehåller en samling av PDF-filer. |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword/) { get; } | Returnerar sant om ett lösenord behövs för att ändra behörigheter eller dokumentets säkerhetsegenskap. Observera att denna egenskap endast kan läsas om ett giltigt lösenord angavs i `PdfFileInfo`-konstruktorn. Om PasswordType är Inaccessible (betyder att ett ogiltigt lösenord angavs) kommer läsning av denna egenskap att misslyckas med [`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception/). |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword/) { get; } | Returnerar sant om ett lösenord behövs för att öppna ett lösenordsskyddat PDF-dokument. |
| [Header](../../aspose.pdf.facades/pdffileinfo/header/) { get; set; } | Hämtar eller sätter den anpassade informationen för PDF-dokumentet. |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted/) { get; } | Kontrollerar om PDF-dokumentet är krypterat. |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile/) { get; } | Kontrollerar om den källinmatning är en giltig PDF-fil. |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords/) { get; set; } | Hämtar eller sätter nyckelordsinformationen för PDF-dokumentet. |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate/) { get; set; } | Hämtar eller sätter ModDate-datuminformationen för PDF-dokumentet. |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages/) { get; } | Hämtar antalet sidor i dokumentet. |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype/) { get; } | Returnerar typen av lösenord som angavs för att skapa PdfFileInfo-instansen. Se möjliga värden i [`PasswordType`](./passwordtype/). Observera att PDF-dokumentet kan öppnas med både användar- (eller öppet) lösenord och ägar- (eller behörigheter, redigera) lösenord. |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer/) { get; } | Hämtar producentinformationen för PDF-dokumentet. |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject/) { get; set; } | Hämtar eller sätter ämnesinformationen för PDF-dokumentet. |
| [Title](../../aspose.pdf.facades/pdffileinfo/title/) { get; set; } | Hämtar eller sätter titelinformationen för PDF-dokumentet. |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation/) { get; set; } | Använder strikta valideringsregler genom att använda [`IsPdfFile`](./ispdffile/) egenskapen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf/#bindpdf)(Document) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initierar fasaden. |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo/)() | Rensar all meta-information om PDF-dokumentet. |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close/)() | Avinitialiserar instansen. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avsätter fasaden. |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege/)() | Hämtar inställningarna för PDF-dokumentets privilegier. |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo/)(string) | Hämtar anpassad information om PDF-dokumentet med egenskapsnamnet. Om det inte finns någon egenskap som matchar namnet returneras en tom sträng. |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight/)(int) | Hämtar höjden på den angivna sidan. |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation/)(int) | Hämtar rotationen av den angivna sidan. |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth/)(int) | Hämtar bredden på den angivna sidan. |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset/)(int) | Hämtar den horisontella förskjutningen av det angivna sidvisningsområdet. |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset/)(int) | Hämtar den vertikala förskjutningen av det angivna sidvisningsområdet. |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion/)() | Hämtar versionsinformationen för PDF-dokumentet. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save)(Stream) | Sparar PDF-dokumentet till den angivna filen. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save_1)(string) | Sparar PDF-dokumentet till den angivna filen. |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo/#savenewinfo_1)(string) | Sparar det uppdaterade PDF-dokumentet i den angivna filen. |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp/)(string) | Ändrar de egenskaper som anges uttryckligen genom att ställa in filinformationen, andra egenskaper förblir oförändrade. |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo/)(string, string) | Sätter anpassad information om PDF-dokumentet. |

### Se Även

* klass [SaveableFacade](../saveablefacade/)
* namnrymd [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)