---
title: "Klass PdfFileSignature"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.PdfFileSignature class. Representerar en klass för att signera en pdf-fil med ett certifikat"
type: docs
weight: 4680
url: /sv/net/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature class

Representerar en klass för att signera en pdf file med ett certifikat.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfFileSignature](pdffilesignature/#constructor)() | Konstruktorn för PdfFileSignature-klassen. |
| [PdfFileSignature](pdffilesignature/#constructor_1)(Document) | Initierar ett nytt `PdfFileSignature`-objekt baserat på *dokumentet*. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar den dokumentfacade som arbetet sker på. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified/) { get; } | Hämtar flaggan som avgör om ett dokument är certifierat eller inte. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled/) { get; } | Hämtar LTV-aktiveringsflaggan. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance/) { get; set; } | Ställer in eller hämtar en grafisk utseende för signaturen. Egenskapsvärdet representerar bildfilens namn. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream/) { get; set; } | Ställer in eller hämtar ett grafiskt utseende för signaturen. Egenskapsvärdet representerar bildströmmen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initierar fasaden. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_1)(Stream) | Kopplar en Pdf-ström för redigering. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_2)(string) | Kopplar en Pdf-fil för redigering. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify_1)(string, DocMDPSignature) | Certifiera dokumentet med MDP-signaturen som placeras i ett redan presenterat signaturfält. Innan signering måste signaturfältet vara tomt, d.v.s. fältet får inte innehålla en signaturdictionary. Således har pdf-dokumentet redan ett signaturfält, du ska inte ange platsen för att stämpla signaturen; motsvarande sida och rektangel tas från signaturfältet som hittas via signaturnamnet (se parametern sigName). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | Certifiera dokumentet med MDP-signaturen. Sådan data som signaturens anledning, kontakt och plats måste tillhandahållas via motsvarande egenskaper i Signature-objektet sig. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close/)() | Stänger fasaden. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature/)() | Kontrollerar om pdf-filen har en digital signatur eller inte. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights/)() | Kontrollerar om pdf-filen har användarrättigheter eller inte. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument/#coverswholedocument)(SignatureName) | Kontrollerar om signaturen täcker hela dokumentet. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avslutar fasaden. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate/#extractcertificate)(SignatureName) | Extraherar signaturens enda X.509-certifikat som en ström. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage/#extractimage)(SignatureName) | Extraherar signaturens bild. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions/)() | Returnerar åtkomstbehörighetsvärdet för det certifierade dokumentet enligt MDP-signaturtypen. |
| [GetBlankSignatureNames](../../aspose.pdf.facades/pdffilesignature/getblanksignaturenames/)() | Hämtar namnen på alla tomma signaturfält. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo/#getcontactinfo)(SignatureName) | Hämtar kontaktinformationen för en signatur. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime/#getdatetime)(SignatureName) | Hämtar signaturens datum och tid. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation/#getlocation)(SignatureName) | Hämtar signaturens plats. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason/#getreason)(SignatureName) | Hämtar signaturens anledning. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision/#getrevision)(SignatureName) | Hämtar signaturens revision. |
| [GetSignatureNames](../../aspose.pdf.facades/pdffilesignature/getsignaturenames/)(bool) | Hämtar namnen på alla icke-tomma signaturer. |
| [GetSignaturesInfo](../../aspose.pdf.facades/pdffilesignature/getsignaturesinfo/)() | Hämtar information om alla signaturalgoritmer som finns i PDF-dokumentet. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername/#getsignername)(SignatureName) | Hämtar namnet på personen eller organisationen som signerar pdf-dokumentet. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision/)() | Hämtar den totala revisionen. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature)(SignatureName) | Ta bort signaturen enligt signaturens namn. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature_1)(SignatureName, bool) | Tar bort signaturen enligt signaturens namn. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffilesignature/removesignatures/)() | Tar bort alla signaturer. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights/)() | Tar bort posten för användarrättigheter. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_1)(Stream) | Sparar den resulterande PDF-filen till en ström. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_2)(string) | Sparar den resulterande PDF-filen till en fil. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate/)(string, string) | Ange certifikatfil och lösenord för signeringsrutinen. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_4)(string, Signature) | Signera dokumentet med den angivna typens signatur som placeras i ett redan presenterat signaturfält. Innan signering måste signaturfältet vara tomt, dvs. fältet får inte innehålla en signaturdictionary. Således har pdf Document redan ett signaturfält, du ska inte ange platsen för att stämpla signaturen, motsvarande **Page** och **Rectangle** tas från signaturfältet som hittas via signaturnamnet (se SigName‑parameter). Sådana data som signaturens anledning, kontakt och plats måste tillhandahållas av motsvarande egenskaper i Signature‑objektet sig. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign)(int, bool, Rectangle, Signature) | Signera dokumentet med den angivna typens signatur. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_5)(string, string, string, string, Signature) | Signera dokumentet med den angivna typens signatur som placeras i ett redan presenterat signaturfält. Innan signering måste signaturfältet vara tomt, dvs. fältet får inte innehålla en signaturdictionary. Således har pdf Document redan ett signaturfält, du ska inte ange platsen för att stämpla signaturen, motsvarande **Page** och **Rectangle** tas från signaturfältet som hittas via signaturnamnet (se SigName‑parameter). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_1)(int, string, string, string, bool, Rectangle) | Skapa en signatur i pdf Document. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_2)(int, string, string, string, bool, Rectangle, Signature) | Signera dokumentet med den angivna typens signatur. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | Signera dokumentet med den angivna typens signatur som placeras i ett redan presenterat signaturfält. Innan signering bör pdf Document redan ha ett signaturfält, motsvarande **Page** och **Rectangle** tas från signaturfältet som hittas via signaturnamnet (se SigName‑parameter). |
| [TryExtractCertificate](../../aspose.pdf.facades/pdffilesignature/tryextractcertificate/#tryextractcertificate)(SignatureName, out Stream) | Extraherar signaturens enda X.509-certifikat som en ström. |
| [TryExtractCertificate](../../aspose.pdf.facades/pdffilesignature/tryextractcertificate/#tryextractcertificate_1)(SignatureName, out X509Certificate2) | Extraherar signaturens enda X.509‑certifikat. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature)(SignatureName) | Kontrollerar giltigheten för en signatur. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_2)(SignatureName, X509Certificate2) | Kontrollerar giltigheten för en signatur. Verifiering utförs med hjälp av det externa offentliga nyckelcertifikatet. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_1)(SignatureName, ValidationOptions, out ValidationResult) | Kontrollerar giltigheten för en signatur. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_3)(SignatureName, X509Certificate2, ValidationOptions, out ValidationResult) | Kontrollerar giltigheten för en signatur. Verifiering utförs med hjälp av det externa offentliga nyckelcertifikatet. |

### Se även

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


