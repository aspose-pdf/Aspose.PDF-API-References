---
title: "Aspose::Pdf::Facades::PdfFileSignature class"
linktitle: "PdfFileSignature"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileSignature class. Representerar en klass för att signera en pdf‑fil med ett certifikat i C++."
type: docs
weight: 2500
url: /sv/cpp/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature class


Representerar en klass för att signera en pdf-fil med ett certifikat.

```cpp
class PdfFileSignature : public Aspose::Pdf::Facades::SaveableFacade
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BindPdf](./bindpdf/)(System::String) override | Kopplar en [Pdf](../../aspose.pdf/) fil för redigering. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Kopplar en [Pdf](../../aspose.pdf/) ström för redigering. |
| [Certify](./certify/)(int32_t, const System::String\&, const System::String\&, const System::String\&, bool, System::Drawing::Rectangle, const System::SharedPtr\<Forms::DocMDPSignature\>\&) | Certifiera dokumentet med MDP‑signaturen. Sådana data som signaturorsak, kontakt och plats måste tillhandahållas via motsvarande egenskaper i Signature‑objektet sig. |
| [Certify](./certify/)(const System::String\&, const System::SharedPtr\<Forms::DocMDPSignature\>\&) | Certifiera dokumentet med MDP‑signaturen som är placerad i ett redan befintligt signaturfält. Innan signering måste signaturfältet vara tomt, d.v.s. fältet får inte innehålla en signatur‑dictionary. Således har pdf‑dokumentet redan ett signaturfält; du ska inte ange platsen för att stämpla signaturen, motsvarande sida och rektangel tas från signaturfältet som hittas via signaturnamnet (se parametern sigName). |
| [Close](./close/)() override | Stänger fasaden. |
| [ContainsSignature](./containssignature/)() | Kontrollerar om pdf‑filen har en digital signatur eller inte. |
| [ContainsUsageRights](./containsusagerights/)() | Kontrollerar om pdf‑filen har användarrättigheter eller inte. |
| [CoversWholeDocument](./coverswholedocument/)(const System::String\&) | Kontrollerar om signaturen täcker hela dokumentet. |
| [CoversWholeDocument](./coverswholedocument/)(const System::SharedPtr\<SignatureName\>\&) | Kontrollerar om signaturen täcker hela dokumentet. |
| [ExtractCertificate](./extractcertificate/)(const System::String\&) | Extraherar signaturens enda X.509‑certifikat som en ström. |
| [ExtractCertificate](./extractcertificate/)(const System::SharedPtr\<SignatureName\>\&) | Extraherar signaturens enda X.509‑certifikat som en ström. |
| [ExtractImage](./extractimage/)(const System::String\&) | Extraherar signaturens bild. |
| [ExtractImage](./extractimage/)(const System::SharedPtr\<SignatureName\>\&) | Extraherar signaturens bild. |
| [get_IsCertified](./get_iscertified/)() | Hämtar flaggan som avgör om ett dokument är certifierat eller inte. |
| [get_IsLtvEnabled](./get_isltvenabled/)() | Hämtar flaggan för LTV‑aktivering. |
| [get_SignatureAppearance](./get_signatureappearance/)() const | Ställer in eller hämtar ett grafiskt utseende för signaturen. Egenskapsvärdet representerar bildfilens namn. |
| [get_SignatureAppearanceStream](./get_signatureappearancestream/)() const | Ställer in eller hämtar ett grafiskt utseende för signaturen. Egenskapsvärdet representerar bildström. |
| [GetAccessPermissions](./getaccesspermissions/)() | Returnerar åtkomstbehörighetsvärdet för ett certifierat dokument enligt MDP‑signaturtypen. |
| [GetBlankSignatureNames](./getblanksignaturenames/)() | Hämtar namnen på alla tomma signaturfält. |
| [GetBlankSignNames](./getblanksignnames/)() | Hämtar namnen på alla tomma signaturfält. |
| [GetContactInfo](./getcontactinfo/)(const System::String\&) | Hämtar kontaktinformationen för en signatur. |
| [GetContactInfo](./getcontactinfo/)(const System::SharedPtr\<SignatureName\>\&) | Hämtar kontaktinformationen för en signatur. |
| [GetDateTime](./getdatetime/)(const System::String\&) | Hämtar signaturens datum och tid. |
| [GetDateTime](./getdatetime/)(const System::SharedPtr\<SignatureName\>\&) | Hämtar signaturens datum och tid. |
| [GetLocation](./getlocation/)(const System::String\&) | Hämtar platsen för en signatur. |
| [GetLocation](./getlocation/)(const System::SharedPtr\<SignatureName\>\&) | Hämtar platsen för en signatur. |
| [GetReason](./getreason/)(const System::String\&) | Hämtar orsaken till en signatur. |
| [GetReason](./getreason/)(const System::SharedPtr\<SignatureName\>\&) | Hämtar orsaken till en signatur. |
| [GetRevision](./getrevision/)(const System::String\&) | Hämtar revisionen av en signatur. |
| [GetRevision](./getrevision/)(const System::SharedPtr\<SignatureName\>\&) | Hämtar revisionen av en signatur. |
| [GetSignatureNames](./getsignaturenames/)(bool) | Hämtar namnen på alla icke‑tomma signaturer. |
| [GetSignaturesInfo](./getsignaturesinfo/)() | Hämtar information om alla signaturalgoritmer som finns i PDF‑dokumentet. |
| [GetSignerName](./getsignername/)(const System::String\&) | Hämtar namnet på personen eller organisationen som signerar PDF‑dokumentet. |
| [GetSignerName](./getsignername/)(const System::SharedPtr\<SignatureName\>\&) | Hämtar namnet på personen eller organisationen som signerar PDF‑dokumentet. |
| [GetSignNames](./getsignnames/)(bool) | Hämtar namnen på alla icke‑tomma signaturer. |
| [GetTotalRevision](./gettotalrevision/)() | Hämtar den totala revisionen. |
| [IsContainSignature](./iscontainsignature/)() | Kontrollerar om pdf‑filen har en digital signatur eller inte. |
| [IsCoversWholeDocument](./iscoverswholedocument/)(const System::String\&) | Kontrollerar om signaturen täcker hela dokumentet. |
| [PdfFileSignature](./pdffilesignature/)() | Konstruktorn för klassen [PdfFileSignature](./). |
| [PdfFileSignature](./pdffilesignature/)(const System::String\&) | Konstruktorn för klassen [PdfFileSignature](./). |
| [PdfFileSignature](./pdffilesignature/)(const System::String\&, const System::String\&) | Konstruktorn för klassen [PdfFileSignature](./). |
| [PdfFileSignature](./pdffilesignature/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Initierar ett nytt [PdfFileSignature](./)-objekt baserat på *dokumentet*. |
| [PdfFileSignature](./pdffilesignature/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) | Initierar ett nytt [PdfFileSignature](./)-objekt baserat på *dokumentet*. |
| [RemoveSignature](./removesignature/)(const System::String\&) | Ta bort signaturen enligt signaturens namn. |
| [RemoveSignature](./removesignature/)(const System::SharedPtr\<SignatureName\>\&) | Ta bort signaturen enligt signaturens namn. |
| [RemoveSignature](./removesignature/)(const System::String\&, bool) | Tar bort signaturen enligt signaturens namn. |
| [RemoveSignature](./removesignature/)(const System::SharedPtr\<SignatureName\>\&, bool) | Tar bort signaturen enligt signaturens namn. |
| [RemoveSignatures](./removesignatures/)() | Tar bort alla signaturer. |
| [RemoveUsageRights](./removeusagerights/)() | Tar bort posten för användarrättigheter. |
| [Save](./save/)(System::String) override | Sparar den resulterande PDF-filen till en fil. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Sparar den resulterande PDF-filen till en ström. |
| [Save](./save/)() | Spara den signerade PDF‑filen. Utdatafilnamnet måste anges i förväg med hjälp av motsvarande [PdfFileSignature](./)-konstruktör. |
| [set_SignatureAppearance](./set_signatureappearance/)(const System::String\&) | Ställer in eller hämtar ett grafiskt utseende för signaturen. Egenskapsvärdet representerar bildfilens namn. |
| [set_SignatureAppearanceStream](./set_signatureappearancestream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ställer in eller hämtar ett grafiskt utseende för signaturen. Egenskapsvärdet representerar bildström. |
| [SetCertificate](./setcertificate/)(const System::String\&, const System::String\&) | Ange certifikatfil och lösenord för signeringsrutinen. |
| [Sign](./sign/)(int32_t, const System::String\&, const System::String\&, const System::String\&, bool, System::Drawing::Rectangle) | Skapa en signatur i PDF‑dokumentet. |
| [Sign](./sign/)(int32_t, const System::String\&, const System::String\&, const System::String\&, bool, System::Drawing::Rectangle, const System::SharedPtr\<Forms::Signature\>\&) | Signera dokumentet med den angivna typens signatur. |
| [Sign](./sign/)(int32_t, bool, System::Drawing::Rectangle, const System::SharedPtr\<Forms::Signature\>\&) | Signera dokumentet med den angivna typens signatur. |
| [Sign](./sign/)(const System::String\&, const System::String\&, const System::String\&, const System::String\&, const System::SharedPtr\<Forms::Signature\>\&) | Signera dokumentet med den angivna typens signatur som placeras i ett redan presenterat signaturfält. Före signering måste signaturfältet vara tomt, d.v.s. fältet får inte innehålla en signaturordbok. Således har PDF‑dokumentet redan ett signaturfält, du bör inte ange platsen för att stämpla signaturen; motsvarande sida och rektangel tas från signaturfältet som hittas via signaturens namn (se SigName parameter). |
| [Sign](./sign/)(int32_t, const System::String\&, const System::String\&, const System::String\&, const System::String\&, bool, System::Drawing::Rectangle, const System::SharedPtr\<Forms::Signature\>\&) | Signera dokumentet med den angivna typens signatur som placeras i ett redan presenterat signaturfält. Före signering bör PDF‑dokumentet redan ha ett signaturfält; motsvarande sida och rektangel tas från signaturfältet som hittas via signaturens namn (se SigName parameter). |
| [Sign](./sign/)(const System::String\&, const System::SharedPtr\<Forms::Signature\>\&) | Signera dokumentet med den angivna typens signatur som placeras i ett redan presenterat signaturfält. Före signering måste signaturfältet vara tomt, d.v.s. fältet får inte innehålla en signaturordbok. Således har PDF‑dokumentet redan ett signaturfält, du bör inte ange platsen för att stämpla signaturen; motsvarande sida och rektangel tas från signaturfältet som hittas via signaturens namn (se SigName parameter). Sådan data som signaturorsak, kontakt och plats måste tillhandahållas via motsvarande egenskaper i Signature‑objektet sig. |
| [TryExtractCertificate](./tryextractcertificate/)(const System::SharedPtr\<SignatureName\>\&, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&) | Extraherar signaturens enda X.509‑certifikat. |
| [TryExtractCertificate](./tryextractcertificate/)(const System::SharedPtr\<SignatureName\>\&, System::SharedPtr\<System::IO::Stream\>\&) | Extraherar signaturens enda X.509‑certifikat som en ström. |
| [TryVerifySignature](./tryverifysignature/)(const System::SharedPtr\<SignatureName\>\&, System::SharedPtr\<Security::VerificationResult\>\&) | Försök att kontrollera giltigheten för en signatur. |
| [TryVerifySignature](./tryverifysignature/)(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) | Försök att kontrollera giltigheten för en signatur. |
| [TryVerifySignature](./tryverifysignature/)(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&, System::SharedPtr\<Security::VerificationResult\>\&) | Försök att kontrollera giltigheten för en signatur. Verifiering utförs med hjälp av det externa offentliga nyckelcertifikatet. |
| [TryVerifySignature](./tryverifysignature/)(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, System::SharedPtr\<Security::VerificationResult\>\&) | Försök att kontrollera giltigheten för en signatur. Verifiering utförs med hjälp av det externa offentliga nyckelcertifikatet. |
| [VerifySignature](./verifysignature/)(const System::String\&) | Kontrollerar giltigheten för en signatur. |
| [VerifySignature](./verifysignature/)(const System::SharedPtr\<SignatureName\>\&) | Kontrollerar giltigheten för en signatur. |
| [VerifySignature](./verifysignature/)(const System::String\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) | Kontrollerar giltigheten för en signatur. |
| [VerifySignature](./verifysignature/)(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) | Kontrollerar giltigheten för en signatur. |
| [VerifySignature](./verifysignature/)(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&, const System::SharedPtr\<Security::ValidationOptions\>\&, System::SharedPtr\<Security::ValidationResult\>\&) | Kontrollerar giltigheten för en signatur. Verifiering utförs med hjälp av det externa offentliga nyckelcertifikatet. |
| [VerifySignature](./verifysignature/)(const System::SharedPtr\<SignatureName\>\&, const System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\&) | Kontrollerar giltigheten för en signatur. Verifiering utförs med hjälp av det externa offentliga nyckelcertifikatet. |
| [VerifySigned](./verifysigned/)(const System::String\&) | Kontrollerar giltigheten för en signatur. Metoden är föråldrad och kommer att tas bort i version 25.1. Använd VerifySignature‑metoden istället. |
## Se även

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
