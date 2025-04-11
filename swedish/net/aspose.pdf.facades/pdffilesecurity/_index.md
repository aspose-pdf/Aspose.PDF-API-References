---
title: Class PdfFileSecurity
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileSecurity klass. Representerar kryptering eller dekryptering av en Pdf-fil med ägar- eller användarlösenord som ändrar säkerhetsinställningen och lösenordet
type: docs
weight: 4550
url: /sv/net/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity klass

Representerar kryptering eller dekryptering av en Pdf-fil med ägar- eller användarlösenord, ändrar säkerhetsinställningen och lösenordet.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity/#constructor)() | Initierar objektet av PdfFileSecurity. |
| [PdfFileSecurity](pdffilesecurity/#constructor_1)(Document) | Initierar ett nytt `PdfFileSecurity`-objekt baserat på *dokumentet*. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar dokumentfacaden som arbetar med. |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception/) { get; } | Returnerar undantaget som kastades av den senaste operationen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initierar facaden. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_1)(Stream) | Initierar facaden. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_2)(string) | Initierar facaden. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword)(string, string, string) | Ändrar användarlösenordet och ägarens lösenord med ägarens lösenord, behåller de ursprungliga säkerhetsinställningarna. Det nya användarlösenordet och det nya ägarens lösenord kan vara null eller tomma. Ägarens lösenord kommer att ersättas med en slumpmässig sträng om det nya ägarens lösenord är null eller tomt. Kastar ett undantag om processen misslyckas. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Ändrar användarlösenordet och lösenordet med ägarens lösenord, tillåter att återställa Pdf-dokumentets säkerhet. Det nya användarlösenordet och det nya ägarens lösenord kan vara null eller tomma. Ägarens lösenord kommer att ersättas med en slumpmässig sträng om det nya ägarens lösenord är null eller tomt. Kastar ett undantag om processen misslyckas. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Ändrar användarlösenordet och lösenordet med ägarens lösenord, tillåter att återställa Pdf-dokumentets säkerhet. Det nya användarlösenordet och det nya ägarens lösenord kan vara null eller tomma. Ägarens lösenord kommer att ersättas med en slumpmässig sträng om det nya ägarens lösenord är null eller tomt. Det finns 6 möjliga kombinationer av KeySize och Algorithm-värden. Men (KeySize.x40, Algorithm.AES) och (KeySize.x256, Algorithm.RC4) är ogiltiga och motsvarande undantag kommer att uppstå om kit stöter på denna kombination. Kastar ett undantag om processen misslyckas. |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close/)() | Stänger facaden. |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile/)(string) | Dekrypterar ett krypterat Pdf-dokument med ägarens lösenord. Om dokumentet inte har ägarens lösenord, är det tillåtet att använda användarlösenordet. Kastar ett undantag om processen misslyckas. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avsätter facaden. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile)(string, string, DocumentPrivilege, KeySize) | Krypterar Pdf-filen med användarlösenord och ägarens lösenord och ställer in dokumentets privilegier för åtkomst. Användarlösenordet och ägarens lösenord kan vara null eller tomma. Ägarens lösenord kommer att ersättas med en slumpmässig sträng om det angivna ägarens lösenord är null eller tomt. Kastar ett undantag om processen misslyckas. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | Krypterar Pdf-filen med användarlösenord och ägarens lösenord och ställer in dokumentets privilegier för åtkomst. Användarlösenordet och ägarens lösenord kan vara null eller tomma. Ägarens lösenord kommer att ersättas med en slumpmässig sträng om det angivna ägarens lösenord är null eller tomt. Det finns 6 möjliga kombinationer av KeySize och Algorithm-värden. Men (KeySize.x40, Algorithm.AES) och (KeySize.x256, Algorithm.RC4) är ogiltiga och motsvarande undantag kommer att uppstå om kit stöter på denna kombination. Kastar ett undantag om processen misslyckas. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Sparar PDF-dokumentet till den angivna strömmen. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Sparar PDF-dokumentet till den angivna filen. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege)(DocumentPrivilege) | Ställer in Pdf-filens säkerhet med tomma användar-/ägarlösenord. Ägarens lösenord kommer att läggas till med en slumpmässig sträng. Kastar ett undantag om processen misslyckas. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege_1)(string, string, DocumentPrivilege) | Ställer in Pdf-filens säkerhet med ursprungligt lösenord. Kastar ett undantag om processen misslyckas. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword)(string, string, string) | Ändrar användarlösenordet och ägarens lösenord med ägarens lösenord, behåller de ursprungliga säkerhetsinställningarna. Det nya användarlösenordet och det nya ägarens lösenord kan vara null eller tomma. Ägarens lösenord kommer att ersättas med en slumpmässig sträng om det nya ägarens lösenord är null eller tomt. Kastar inte ett undantag om processen misslyckas. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Ändrar användarlösenordet och lösenordet med ägarens lösenord, tillåter att återställa Pdf-dokumentets säkerhet. Det nya användarlösenordet och det nya ägarens lösenord kan vara null eller tomma. Ägarens lösenord kommer att ersättas med en slumpmässig sträng om det nya ägarens lösenord är null eller tomt. Kastar inte ett undantag om processen misslyckas. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Ändrar användarlösenordet och lösenordet med ägarens lösenord, tillåter att återställa Pdf-dokumentets säkerhet. Det nya användarlösenordet och det nya ägarens lösenord kan vara null eller tomma. Ägarens lösenord kommer att ersättas med en slumpmässig sträng om det nya ägarens lösenord är null eller tomt. Det finns 6 möjliga kombinationer av KeySize och Algorithm-värden. Men (KeySize.x40, Algorithm.AES) och (KeySize.x256, Algorithm.RC4) är ogiltiga och motsvarande undantag kommer att uppstå om kit stöter på denna kombination. Kastar inte ett undantag om processen misslyckas. |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile/)(string) | Dekrypterar ett krypterat Pdf-dokument med ägarens lösenord. Om dokumentet inte har ägarens lösenord, är det tillåtet att använda användarlösenordet. Kastar inte ett undantag om processen misslyckas. |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile/)(string, string, DocumentPrivilege, KeySize) | Krypterar Pdf-filen med användarlösenord och ägarens lösenord och ställer in dokumentets privilegier för åtkomst. Användarlösenordet och ägarens lösenord kan vara null eller tomma. Ägarens lösenord kommer att ersättas med en slumpmässig sträng om det angivna ägarens lösenord är null eller tomt. Kastar inte ett undantag om processen misslyckas. |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege/)(string, string, DocumentPrivilege) | Ställer in Pdf-filens säkerhet med ursprungligt lösenord. Kastar inte ett undantag om processen misslyckas. |

### Se Även

* klass [SaveableFacade](../saveablefacade/)
* namnrymd [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)