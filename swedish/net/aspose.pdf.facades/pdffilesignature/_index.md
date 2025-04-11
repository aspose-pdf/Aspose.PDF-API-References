---
title: Class PdfFileSignature
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileSignature klass. Representerar en klass för att signera en pdf-fil med ett certifikat
type: docs
weight: 4560
url: /sv/net/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature klass

Representerar en klass för att signera en pdf-fil med ett certifikat.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfFileSignature](pdffilesignature/#constructor)() | Konstruktören för PdfFileSignature klass. |
| [PdfFileSignature](pdffilesignature/#constructor_1)(Document) | Initierar ett nytt `PdfFileSignature` objekt baserat på *dokumentet*. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar dokumentets fasad som arbetas med. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified/) { get; } | Hämtar flaggan som avgör om ett dokument är certifierat eller inte. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled/) { get; } | Hämtar flaggan för LTV aktiverad. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance/) { get; set; } | Sätter eller hämtar en grafisk utseende för signaturen. Egenskapens värde representerar bildfilens namn. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream/) { get; set; } | Sätter eller hämtar en grafisk utseende för signaturen. Egenskapens värde representerar bildström. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initierar fasaden. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_1)(Stream) | Binder en Pdf-ström för redigering. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_2)(string) | Binder en Pdf-fil för redigering. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify_1)(string, DocMDPSignature) | Certifierar dokumentet med MDP-signaturen som placeras i redan presenterat signaturfält. Innan signering måste signaturfältet vara tomt, dvs. fältet får inte innehålla signaturordbok. Således har pdf-dokumentet redan signaturfält, du bör inte ange platsen för att stämpla signaturen, motsvarande sida och rektangel tas från signaturfältet som hittas av signaturnamn (se sigName-parameter). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | Certifierar dokumentet med MDP-signaturen. Sådana data som signaturorsak, kontakt och plats måste tillhandahållas av motsvarande egenskaper hos Signatur-objektet sig. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close/)() | Stänger fasaden. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature/)() | Kontrollerar om pdf:en har en digital signatur eller inte. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights/)() | Kontrollerar om pdf:en har användningsrättigheter eller inte. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument/#coverswholedocument)(SignatureName) | Kontrollerar om signaturen täcker hela dokumentet. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avsätter fasaden. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate/#extractcertificate)(SignatureName) | Extraherar signaturens enskilda X.509-certifikat som en ström. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage/#extractimage)(SignatureName) | Extraherar signaturens bild. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions/)() | Returnerar värdet för åtkomsträttigheter för certifierat dokument av MDP-signaturtyp. |
| [GetBlankSignatureNames](../../aspose.pdf.facades/pdffilesignature/getblanksignaturenames/)() | Hämtar namnen på alla tomma signaturfält. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo/#getcontactinfo)(SignatureName) | Hämtar kontaktinformationen för en signatur. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime/#getdatetime)(SignatureName) | Hämtar signaturens datum och tid. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation/#getlocation)(SignatureName) | Hämtar platsen för en signatur. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason/#getreason)(SignatureName) | Hämtar orsaken till en signatur. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision/#getrevision)(SignatureName) | Hämtar revisionen av en signatur. |
| [GetSignatureNames](../../aspose.pdf.facades/pdffilesignature/getsignaturenames/)(bool) | Hämtar namnen på alla icke-tomma signaturer. |
| [GetSignaturesInfo](../../aspose.pdf.facades/pdffilesignature/getsignaturesinfo/)() | Hämtar information om alla signaturalgoritmer som finns i PDF-dokumentet. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername/#getsignername)(SignatureName) | Hämtar namnet på personen eller organisationen som signerar pdf-dokumentet. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision/)() | Hämtar den totala revisionen. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature)(SignatureName) | Tar bort signaturen enligt signaturens namn. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature_1)(SignatureName, bool) | Tar bort signaturen enligt signaturens namn. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffilesignature/removesignatures/)() | Tar bort alla signaturer. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights/)() | Tar bort användningsrättighetsposten. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_1)(Stream) | Sparar resultat-PDF till ström. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_2)(string) | Sparar resultat-PDF till fil. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate/)(string, string) | Sätter certifikatfil och lösenord för signeringsrutinen. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_4)(string, Signature) | Signera dokumentet med den angivna typens signatur som placeras i redan presenterat signaturfält. Innan signering måste signaturfältet vara tomt, dvs. fältet får inte innehålla signaturordbok. Således har pdf-dokumentet redan signaturfält, du bör inte ange platsen för att stämpla signaturen, motsvarande sida och rektangel tas från signaturfältet som hittas av signaturnamn (se SigName-parameter). Sådana data som signaturorsak, kontakt och plats måste tillhandahållas av motsvarande egenskaper hos Signatur-objektet sig. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign)(int, bool, Rectangle, Signature) | Signera dokumentet med den angivna typens signatur. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_5)(string, string, string, string, Signature) | Signera dokumentet med den angivna typens signatur som placeras i redan presenterat signaturfält. Innan signering måste signaturfältet vara tomt, dvs. fältet får inte innehålla signaturordbok. Således har pdf-dokumentet redan signaturfält, du bör inte ange platsen för att stämpla signaturen, motsvarande sida och rektangel tas från signaturfältet som hittas av signaturnamn (se SigName-parameter). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_1)(int, string, string, string, bool, Rectangle) | Gör en signatur på pdf-dokumentet. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_2)(int, string, string, string, bool, Rectangle, Signature) | Signera dokumentet med den angivna typens signatur. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | Signera dokumentet med den angivna typens signatur som placeras i redan presenterat signaturfält. Innan signering måste pdf-dokumentet redan ha signaturfält, motsvarande sida och rektangel tas från signaturfältet som hittas av signaturnamn (se SigName-parameter). |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature)(SignatureName) | Kontrollerar giltigheten av en signatur. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_1)(SignatureName, ValidationOptions, out ValidationResult) | Kontrollerar giltigheten av en signatur. |

### Se Även

* klass [SaveableFacade](../saveablefacade/)
* namnrymd [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../)