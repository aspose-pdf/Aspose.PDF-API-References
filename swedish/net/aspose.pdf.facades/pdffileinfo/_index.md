---
title: "Klass PdfFileInfo"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.PdfFileInfo-klass. Representerar en klass för att komma åt metadata för PDF-dokument."
type: docs
weight: 4640
url: /sv/net/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo class

Representerar en klass för åtkomst till meta‑information i PDF document.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfFileInfo](pdffileinfo/#constructor)() | Initierar en ny instans av klassen Aspose.Pdf.Facades.PdfFileInfo med standardvärden. |
| [PdfFileInfo](pdffileinfo/#constructor_1)(Document) | Initierar ett nytt `PdfFileInfo`-objekt baserat på *dokumentet*. |
| [PdfFileInfo](pdffileinfo/#constructor_2)(Stream) | Initierar en ny instans av klassen Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_5)(string) | Initierar en ny instans av klassen Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_3)(Stream, string) | Initierar en ny instans av klassen Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_6)(string, string) | Initierar en ny instans av klassen Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_4)(Stream, string, ICustomSecurityHandler) | Initierar en ny instans av klassen Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_7)(string, string, ICustomSecurityHandler) | Initierar en ny instans av klassen Aspose.Pdf.Facades.PdfFileInfo. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author/) { get; set; } | Hämtar eller anger författarinformationen för PDF-dokumentet. |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate/) { get; set; } | Hämtar eller anger skapelsedatum för PDF-dokumentet. |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator/) { get; set; } | Hämtar eller anger skapareinformationen för PDF-dokumentet. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar den dokumentfacade som arbetet sker på. |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection/) { get; } | Returnerar true om den aktuella indatafilen är en 'Portfolio'-fil som innehåller en samling PDF-filer. |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword/) { get; } | Returnerar true om ett lösenord krävs för att ändra behörigheter eller dokumentets säkerhetsegenskap. Observera att denna egenskap endast kan läsas om ett giltigt lösenord har angetts i `PdfFileInfo`-konstruktorn. Om PasswordType är Inaccessible (vilket betyder att ett ogiltigt lösenord har angetts) kommer läsning av denna egenskap att misslyckas med [`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception/). |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword/) { get; } | Returnerar true om ett lösenord krävs för att öppna ett lösenordsskyddat pdf-dokument. |
| [Header](../../aspose.pdf.facades/pdffileinfo/header/) { get; set; } | Hämtar eller anger den anpassade informationen för PDF-dokumentet. |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted/) { get; } | Kontrollerar om PDF-dokumentet är krypterat. |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile/) { get; } | Kontrollerar om källinmatningen är en giltig PDF-fil. |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords/) { get; set; } | Hämtar eller anger Keywords‑informationen för PDF-dokumentet. |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate/) { get; set; } | Hämtar eller anger ModDate‑datuminformationen för PDF-dokumentet. |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages/) { get; } | Hämtar antalet sidor i dokumentet. |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype/) { get; } | Returnerar typen av lösenord som skickades för att skapa PdfFileInfo‑instansen. Se möjliga värden i [`PasswordType`](./passwordtype/). Observera att pdf‑dokumentet kan öppnas med både användar‑ (eller öppnings‑) lösenord och ägarlösenord (eller behörighets‑, redigerings‑) lösenord. |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer/) { get; } | Hämtar producentinformationen för PDF-dokumentet. |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject/) { get; set; } | Hämtar eller anger ämnesinformationen för PDF-dokumentet. |
| [Title](../../aspose.pdf.facades/pdffileinfo/title/) { get; set; } | Hämtar eller anger titelinformationen för PDF-dokumentet. |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation/) { get; set; } | Använder strikta valideringsregler via egenskapen [`IsPdfFile`](./ispdffile/). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf/#bindpdf)(Document) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initierar fasaden. |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo/)() | Rensar all metainformation för PDF-dokumentet. |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close/)() | Avinitialiserar instansen. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avslutar fasaden. |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege/)() | Hämtar behörighetsinställningarna för PDF-dokumentet. |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo/)(string) | Hämtar anpassad information för PDF-dokumentet med egenskapsnamn. Om ingen egenskap matchar namnet returneras en tom sträng. |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight/)(int) | Hämtar höjden på den angivna sidan. |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation/)(int) | Hämtar rotationen för den angivna sidan. |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth/)(int) | Hämtar bredden på den angivna sidan. |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset/)(int) | Hämtar den horisontella förskjutningen för den angivna sidans visningsområde. |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset/)(int) | Hämtar den vertikala förskjutningen för den angivna sidans visningsområde. |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion/)() | Hämtar versionsinformationen för PDF-dokumentet. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save)(Stream) | Sparar PDF-dokumentet till den angivna filen. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save_1)(string) | Sparar PDF-dokumentet till den angivna filen. |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo/#savenewinfo_1)(string) | Spara uppdaterat PDF-dokument till den angivna filen. |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp/)(string) | Ändrar de egenskaper som specificerats explicit genom att sätta filinformation, övriga egenskaper förblir. |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo/)(string, string) | Anger anpassad information för PDF-dokumentet. |

### Se även

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


