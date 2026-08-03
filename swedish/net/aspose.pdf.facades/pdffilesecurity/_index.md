---
title: "Klass PdfFileSecurity"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.PdfFileSecurity-klass. Representerar kryptering eller dekryptering av en Pdf‑fil med ägare‑ eller användarlösenord samt ändring av säkerhetsinställningarna och lösenordet."
type: docs
weight: 4670
url: /sv/net/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity class

Representerar kryptering eller dekryptering av en Pdf file med ägare‑ eller användarlösenord, ändring av säkerhetsinställningarna och lösenordet.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity/#constructor)() | Initiera objektet av PdfFileSecurity. |
| [PdfFileSecurity](pdffilesecurity/#constructor_1)(Document) | Initierar ett nytt `PdfFileSecurity`‑objekt baserat på *document*. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar den dokumentfacade som arbetet sker på. |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception/) { get; } | Returnerar undantaget som kastades av den senaste operationen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initierar fasaden. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_1)(Stream) | Initierar fasaden. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_2)(string) | Initierar fasaden. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword)(string, string, string) | Ändrar användarlösenordet och ägarlösenordet med ägarlösenordet, behåller de ursprungliga säkerhetsinställningarna. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet ersätts med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Kastar ett undantag om processen misslyckas. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Ändrar användarlösenordet och lösenordet med ägarlösenordet, möjliggör återställning av Pdf‑dokumentets säkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet ersätts med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Kastar ett undantag om processen misslyckas. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Ändrar användarlösenordet och lösenordet med ägarlösenordet, möjliggör återställning av Pdf‑dokumentets säkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet ersätts med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Det finns 6 möjliga kombinationer av KeySize‑ och Algorithm‑värden. Dock är (KeySize.x40, Algorithm.AES) och (KeySize.x256, Algorithm.RC4) ogiltiga och motsvarande undantag kommer att kastas om verktyget stöter på denna kombination. Kastar ett undantag om processen misslyckas. |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close/)() | Stänger fasaden. |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile/)(string) | Dekrypterar ett krypterat Pdf‑dokument med ägarlösenord. Om dokumentet saknar ägarlösenord tillåts användning av användarlösenord. Kastar ett undantag om processen misslyckas. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avslutar fasaden. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile)(string, string, DocumentPrivilege, KeySize) | Krypterar Pdf‑fil med användarlösenord och ägarlösenord och ställer in dokumentets åtkomstbehörigheter. Användarlösenordet och ägarlösenordet kan vara null eller tomma. Ägarlösenordet ersätts med en slumpmässig sträng om det angivna ägarlösenordet är null eller tomt. Kastar ett undantag om processen misslyckas. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | Krypterar Pdf‑fil med användarlösenord och ägarlösenord och sätter dokumentets behörigheter för åtkomst. Användarlösenordet och ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det angivna ägarlösenordet är null eller tomt. Det finns 6 möjliga kombinationer av KeySize‑ och Algorithm‑värden. Dock är (KeySize.x40, Algorithm.AES) och (KeySize.x256, Algorithm.RC4) ogiltiga och motsvarande undantag kommer att kastas om verktyget stöter på denna kombination. Kastar ett undantag om processen misslyckas. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Sparar PDF-dokumentet till den angivna strömmen. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Sparar PDF-dokumentet till den angivna filen. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege)(DocumentPrivilege) | Ställer in Pdf‑filens säkerhet med tomma användar‑/ägarlösenord. Ägarlösenordet kommer att läggas till med en slumpmässig sträng. Kastar ett undantag om processen misslyckas. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege_1)(string, string, DocumentPrivilege) | Ställer in Pdf‑filens säkerhet med originallösenordet. Kastar ett undantag om processen misslyckas. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword)(string, string, string) | Ändrar användarlösenordet och ägarlösenordet med ägarlösenordet, behåller de ursprungliga säkerhetsinställningarna. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Kastar inte ett undantag om processen misslyckas. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Ändrar användarlösenordet och lösenordet med ägarlösenordet, möjliggör återställning av Pdf‑dokumentets säkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Kastar inte ett undantag om processen misslyckas. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Ändrar användarlösenordet och lösenordet med ägarlösenordet, möjliggör återställning av Pdf‑dokumentets säkerhet. Det nya användarlösenordet och det nya ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det nya ägarlösenordet är null eller tomt. Det finns 6 möjliga kombinationer av KeySize‑ och Algorithm‑värden. Dock är (KeySize.x40, Algorithm.AES) och (KeySize.x256, Algorithm.RC4) ogiltiga och motsvarande undantag kommer att kastas om verktyget stöter på denna kombination. Kastar inte ett undantag om processen misslyckas. |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile/)(string) | Dekrypterar ett krypterat Pdf‑dokument med ägarlösenord. Om dokumentet inte har ägarlösenord tillåts användning av användarlösenord. Kastar inte ett undantag om processen misslyckas. |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile/)(string, string, DocumentPrivilege, KeySize) | Krypterar Pdf‑fil med användarlösenord och ägarlösenord och sätter dokumentets behörigheter för åtkomst. Användarlösenordet och ägarlösenordet kan vara null eller tomma. Ägarlösenordet kommer att ersättas med en slumpmässig sträng om det angivna ägarlösenordet är null eller tomt. Kastar inte ett undantag om processen misslyckas. |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege/)(string, string, DocumentPrivilege) | Ställer in Pdf‑filens säkerhet med originallösenordet. Kastar inte ett undantag om processen misslyckas. |

### Se även

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


