---
title: PdfFileSignature
second_title: Aspose.PDF för .NET API Referens
description: Representerar en klass för att signera en pdf-fil med ett certifikat.
type: docs
weight: 2570
url: /sv/net/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature class

Representerar en klass för att signera en pdf-fil med ett certifikat.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PdfFileSignature](pdffilesignature#constructor)() | Konstruktören av klassen PdfFileSignature. |
| [PdfFileSignature](pdffilesignature#constructor_1)(Document) | Initierar ny[`PdfFileSignature`](../pdffilesignature) objekt på basen av*document* . |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Får dokumentfasaden arbetar på. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified) { get; } | Får flaggan som avgör om ett dokument är certifierat eller inte. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled) { get; } | Får flaggan LTV-aktiverad. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance) { get; set; } | Ställer in eller får ett grafiskt utseende för signaturen. Egenskapens värde representerar bildfilens namn. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream) { get; set; } | Ställer in eller får ett grafiskt utseende för signaturen. Egenskapens värde representerar bildström. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initierar fasaden. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf#bindpdf_1)(Stream) | Binder en PDF-ström för redigering. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf#bindpdf_2)(string) | Binder en pdf-fil för redigering. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify#certify_1)(string, DocMDPSignature) | Certifiera dokumentet med MDP-signaturen som är placerad i redan presenterat signaturfält. Innan signering måste signaturfältet vara tomt, dvs. fältet får inte innehålla signaturordbok. Således pdf-dokumentet har redan signaturfält, du ska inte ange platsen för att stämpla signaturen, motsvarande sida och rektangel tas från signaturfältet som hittas av signaturnamnet (se parametern sigName). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | Certifiera dokumentet med MDP-signaturen. Sådana uppgifter som signaturorsak, kontakt och plats måste tillhandahållas av motsvarande egenskaper för Signaturobjektet sig. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close)() | Stänger fasaden. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature)() | Kontrollerar om pdf:en har en digital signatur eller inte. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights)() | Kontrollerar om pdf:en har en användningsrätt eller inte. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument)(string) | Kontrollerar om signaturen täcker hela dokumentet. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Disponerar fasaden. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate)(string) | Extraherar signaturens enda X.509-certifikat som en ström. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage)(string) | Extraherar signaturens bild. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions)() | Returnerar åtkomstbehörighetsvärdet för certifierat dokument av MDP-signaturtypen. |
| [GetBlankSignNames](../../aspose.pdf.facades/pdffilesignature/getblanksignnames)() | Hämtar namnen på alla tomma signaturfält. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo)(string) | Får kontaktinformationen för en signatur. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime)(string) | Hämtar signaturens datetime. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation)(string) | Hämtar platsen för en signatur. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason)(string) | Får orsaken till en signatur. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision)(string) | Får revidering av en signatur. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername)(string) | Får namnet på den person eller organisation som signerar pdf-dokumentet. |
| [GetSignNames](../../aspose.pdf.facades/pdffilesignature/getsignnames)(bool) | Hämtar namnen på alla inte tomma signaturer. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision)() | Hämtar den totala revisionen. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature#removesignature)(string) | Ta bort signaturen enligt namnet på signaturen. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature#removesignature_1)(string, bool) | Tar bort signaturen enligt namnet på signaturen. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights)() | Tar bort posten för användningsrättigheter. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save#save_1)(Stream) | Sparar resultatet PDF för att streama. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save#save_2)(string) | Sparar resultatet PDF till fil. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate)(string, string) | Ställ in certifikatfil och lösenord för signeringsrutinen. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_4)(string, Signature) | Signera dokumentet med den givna typen signatur som är placerad i redan presenterat signaturfält. Innan signering måste signaturfältet vara tomt, dvs fältet får inte innehålla signaturlexikon. Således pdf-dokument har redan signaturfält, du ska inte ange platsen för att stämpla signaturen tas motsvarande sida och rektangel från signaturfält som hittas av signaturnamn (se SigName parameter). Sådana data som signaturorsak, kontakt och plats måste tillhandahållas av motsvarande egenskaper för Signaturobjektet sig. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign)(int, bool, Rectangle, Signature) | Signera dokumentet med den angivna typen signatur. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_5)(string, string, string, string, Signature) | Signera dokumentet med den givna typen signatur som är placerad i redan presenterat signaturfält. Innan signering måste signaturfältet vara tomt, dvs fältet får inte innehålla signaturlexikon. Således pdf-dokument har redan signaturfält, du ska inte ange platsen för att stämpla signaturen tas motsvarande sida och rektangel från signaturfältet som hittas av signaturnamnet (se SigName parameter). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_1)(int, string, string, string, bool, Rectangle) | Gör en signatur på pdf-dokumentet. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_2)(int, string, string, string, bool, Rectangle, Signature) | Signera dokumentet med den angivna typen signatur. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | Signera dokumentet med den givna typen signatur som placeras i redan presenterat signaturfält. Innan man signerar pdf-dokument bör man redan ha signaturfält, motsvarande sida och rektangel är hämtade från signaturfält som hittas av signaturnamn (se SigName parameter) . |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature)(string) | Kontrollerar giltigheten av en signatur. |
| [VerifySigned](../../aspose.pdf.facades/pdffilesignature/verifysigned)(string) | Kontrollerar giltigheten av en signatur. |

### Se även

* class [SaveableFacade](../saveablefacade)
* namnutrymme [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
