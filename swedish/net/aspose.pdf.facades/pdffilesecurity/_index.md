---
title: PdfFileSecurity
second_title: Aspose.PDF för .NET API Referens
description: Representerar kryptering eller dekryptering av en PDF-fil med ägar- eller användarlösenord ändring av säkerhetsinställning och lösenord.
type: docs
weight: 2560
url: /sv/net/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity class

Representerar kryptering eller dekryptering av en PDF-fil med ägar- eller användarlösenord, ändring av säkerhetsinställning och lösenord.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity#constructor)() | Initiera objektet för PdfFileSecurity. |
| [PdfFileSecurity](pdffilesecurity#constructor_1)(Document) | Initierar ny[`PdfFileSecurity`](../pdffilesecurity) objekt på basen av*document* . |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Får dokumentfasaden arbetar på. |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception) { get; } | Returnerar undantag som orsakades av den senaste operationen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initierar fasaden. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf#bindpdf_1)(Stream) | Initierar fasaden. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf#bindpdf_2)(string) | Initierar fasaden. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword)(string, string, string) | Ändrar användarlösenordet och ägarlösenordet med ägarlösenordet, behåller de ursprungliga säkerhetsinställningarna. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomt. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Kastar ett undantag om processen misslyckades. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Ändrar användarlösenordet och lösenordet med ägarlösenordet, gör det möjligt att återställa Pdf-dokumentsäkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomt. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Kastar ett undantag om processen misslyckades. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Ändrar användarlösenordet och lösenordet med ägarlösenordet, gör det möjligt att återställa Pdf-dokumentsäkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomt. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Det finns 6 möjliga kombinationer av KeySize och Algoritmvärden. Men (KeySize.x40, Algorithm.AES) och (KeySize.x256, Algorithm.RC4) är ogiltiga och motsvarande undantag kommer att höjas om kitet stöter på denna kombination. Kastar ett undantag om processen misslyckades._x000d |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close)() | Stänger fasaden. |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile)(string) | Dekrypterar ett krypterat PDF-dokument med ägarlösenord. Om dokumentet inte har ägarlösenord, är det tillåtet att använda användarlösenord. Kastar ett undantag om processen misslyckades. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Disponerar fasaden. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile#encryptfile)(string, string, DocumentPrivilege, KeySize) | Krypterar Pdf-fil med användarlösenord och ägarlösenord och ställer in dokumentets behörigheter för åtkomst. Användarlösenordet och ägarlösenordet kan vara null eller tomt. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det inmatade ägarlösenordet är null eller tomt. Kastar undantag om processen misslyckades. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | Krypterar Pdf-fil med användarlösenord och ägarlösenord och ställer in dokumentets behörigheter för åtkomst. Användarlösenordet och ägarlösenordet kan vara null eller tomt. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det inmatade ägarlösenordet är null eller tomt. Det finns 6 möjliga kombinationer av KeySize- och Algoritmvärden. Emellertid (KeySize.x40, Algorithm.AES) och (KeySize.x256, Algorithm.RC4) är ogiltiga och motsvarande undantag kommer att höjas om kitet stöter på denna kombination. Kastar ett undantag om processen misslyckades. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Sparar PDF-dokumentet till den angivna strömmen. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Sparar PDF-dokumentet till den angivna filen. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege#setprivilege)(DocumentPrivilege) | Ställer in Pdf-filsäkerhet med tomma användar-/ägarlösenord. Ägarlösenordet kommer att läggas till med en slumpmässig sträng. Kastar ett undantag om processen misslyckades. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege#setprivilege_1)(string, string, DocumentPrivilege) | Ställer in Pdf-filsäkerhet med originallösenord. Kastar ett undantag om processen misslyckades. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword)(string, string, string) | Ändrar användarlösenordet och ägarlösenordet med ägarlösenordet, behåller de ursprungliga säkerhetsinställningarna. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomt. Ägarlösenordet kommer att ersättas Ger inget undantag om processen misslyckades. med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Ändrar användarlösenordet och lösenordet med ägarlösenordet, gör det möjligt att återställa Pdf-dokumentsäkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomt. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Ger inget undantag om processen misslyckades. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Ändrar användarlösenordet och lösenordet med ägarlösenordet, gör det möjligt att återställa Pdf-dokumentsäkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomt. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Det finns 6 möjliga kombinationer av KeySize och Algoritmvärden. Emellertid (KeySize.x40, Algorithm.AES) och (KeySize.x256, Algorithm.RC4) är ogiltiga och motsvarande undantag kommer att höjas om kitet stöter på denna kombination. Ger inget undantag om processen misslyckades._x0000 |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile)(string) | Dekrypterar ett krypterat PDF-dokument med ägarlösenord. Om dokumentet inte har ägarlösenord, är det tillåtet att använda användarlösenord. Ger inget undantag om processen misslyckades. |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile)(string, string, DocumentPrivilege, KeySize) | Krypterar Pdf-fil med användarlösenord och ägarlösenord och ställer in dokumentets behörigheter för åtkomst. Användarlösenordet och ägarlösenordet kan vara null eller tomt. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det inmatade ägarlösenordet är null eller tomt. Ger inget undantag om processen misslyckades. |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege)(string, string, DocumentPrivilege) | Ställer in Pdf-filsäkerhet med originallösenord. Ger inget undantag om processen misslyckades. |

### Se även

* class [SaveableFacade](../saveablefacade)
* namnutrymme [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
