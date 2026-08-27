---
title: "PdfFileSignature"
linktitle: "PdfFileSignature"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en klass för att signera en pdf-fil med ett certifikat."
type: docs
weight: 530
url: /sv/java/com.aspose.pdf.facades/pdffilesignature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSignature, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSignature, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSignature

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSignature extends SaveableFacade
```

Representerar en klass för att signera en pdf-fil med ett certifikat.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PdfFileSignature](#PdfFileSignature--) | Konstruktorn för PdfFileSignature-klassen. |
| [PdfFileSignature](#PdfFileSignature-com.aspose.pdf.IDocument-) | Konstruktorn för PdfFileSignature-klassen. |
| [PdfFileSignature](#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-) | Konstruktorn för PdfFileSignature-klassen. |
| [PdfFileSignature](#PdfFileSignature-java.lang.String-) | Konstruktorn för PdfFileSignature-klassen. |
| [PdfFileSignature](#PdfFileSignature-java.lang.String-java.lang.String-) | Konstruktorn för PdfFileSignature-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | Kopplar en Pdf-ström för redigering. |
| [bindPdf](#bindPdf-java.lang.String-) | Kopplar en Pdf-fil för redigering. |
| [certify](#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-) | Certifiera dokumentet med MDP-signaturen. |
| [certify](#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-) | Certifiera dokumentet med MDP-signaturen som är placerad i ett redan befintligt signaturfält. Innan signering måste signaturfältet vara tomt, d.v.s. fältet får inte innehålla signaturordbok. Således har pdf-dokumentet redan ett signaturfält, du bör inte ange platsen för att stämpla signaturen, motsvarande sida och rektangel tas från signaturfältet som hittas via signaturens namn (se parametern sigName). |
| [close](#close--) | Stänger fasaden. |
| [containsSignature](#containsSignature--) | Kontrollerar om pdf-filen har en digital signatur eller inte. |
| [containsUsageRights](#containsUsageRights--) | Kontrollerar om pdf-filen har användarrättigheter eller inte. |
| [coversWholeDocument](#coversWholeDocument-com.aspose.pdf.facades.SignatureName-) | Kontrollerar om signaturen täcker hela dokumentet. |
| [coversWholeDocument](#coversWholeDocument-java.lang.String-) | Kontrollerar om signaturen täcker hela dokumentet. |
| [dispose](#dispose--) | Stänger fasaden. Denna metod är föråldrad, använd close() istället. |
| [extractCertificate](#extractCertificate-com.aspose.pdf.facades.SignatureName-) | Extraherar signaturens enda X.509-certifikat som en ström. |
| [extractCertificate](#extractCertificate-java.lang.String-) | Extraherar signaturens enda X.509-certifikat som en ström. |
| [extractImage](#extractImage-com.aspose.pdf.facades.SignatureName-) | Extraherar signaturens bild. |
| [extractImage](#extractImage-java.lang.String-) | Extraherar signaturens bild. |
| [getAccessPermissions](#getAccessPermissions--) | Returnerar åtkomstbehörighetsvärdet för ett certifierat dokument med MDP‑signaturtypen. |
| [getBlankSignNames](#getBlankSignNames--) | Hämtar namnen på alla tomma signaturfält. |
| [getContactInfo](#getContactInfo-com.aspose.pdf.facades.SignatureName-) | Hämtar kontaktinformationen för en signatur. |
| [getContactInfo](#getContactInfo-java.lang.String-) | Hämtar kontaktinformationen för en signatur. |
| [getDateTime](#getDateTime-com.aspose.pdf.facades.SignatureName-) | Hämtar signaturens datum och tid. |
| [getDateTime](#getDateTime-java.lang.String-) | Hämtar signaturens datum och tid. |
| [getLocation](#getLocation-com.aspose.pdf.facades.SignatureName-) | Hämtar platsen för en signatur. |
| [getLocation](#getLocation-java.lang.String-) | Hämtar platsen för en signatur. |
| [getReason](#getReason-com.aspose.pdf.facades.SignatureName-) | Hämtar anledningen till en signatur. |
| [getReason](#getReason-java.lang.String-) | Hämtar anledningen till en signatur. |
| [getRevision](#getRevision-com.aspose.pdf.facades.SignatureName-) | Hämtar revisionen av en signatur. |
| [getRevision](#getRevision-java.lang.String-) | Hämtar revisionen av en signatur. |
| [getSignatureAppearance](#getSignatureAppearance--) | Hämtar ett grafiskt utseende för signaturen. Egenskapsvärdet representerar bildfilens namn. |
| [getSignatureAppearanceStream](#getSignatureAppearanceStream--) | Hämtar ett grafiskt utseende för signaturen. Egenskapsvärdet representerar bildström. |
| [getSignatureNames](#getSignatureNames--) | / * <p> / * Hämtar namnen på alla icke‑tomma signaturer. / * </p> / * <p> / * <pre> / * string inFile=TestPath + "example1.pdf"; / * PdfFileSignature pdfSign=new PdfFileSignature(); / * pdfSign.bindPdf(inFile); / * java.util.List<String> names=pdfSign.getSignatureNames(); / * for(int i=0;i<names.size();i++) / * { / * System.out.println("signature name:" + names[i]); / * System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); / * System.out.println("revision:" + pdfSign.getRevision(names[i])); / * System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); / * System.out.println("reason:" + pdfSign.getReason(names[i])); / * System.out.println("location:" + pdfSign.getLocation(names[i])); / * System.out.println("datatime:" + pdfSign.getDateTime(names[i])); / * } / * System.out.println("totalvision:" + pdfSign.GetTotalRevision()); / * / * </pre> / * |
| [getSignatureNames](#getSignatureNames-boolean-) | Hämtar namnen på alla icke‑tomma signaturer. string inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); java.util.List names=pdfSign.getSignatureNames(); for(int i=0;i<names.size();i++) { System.out.println("signature name:" + names[i]); System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); System.out.println("revision:" + pdfSign.getRevision(names[i])); System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); System.out.println("reason:" + pdfSign.getReason(names[i])); System.out.println("location:" + pdfSign.getLocation(names[i])); System.out.println("datatime:" + pdfSign.getDateTime(names[i])); } System.out.println("totalvision:" + pdfSign.GetTotalRevision()); |
| [getSignaturesInfo](#getSignaturesInfo--) | Hämtar information om alla signaturalgoritmer som finns i PDF-dokumentet. |
| [getSignerName](#getSignerName-com.aspose.pdf.facades.SignatureName-) | Hämtar namnet på personen eller organisationen som signerar PDF-dokumentet. |
| [getSignerName](#getSignerName-java.lang.String-) | Hämtar namnet på personen eller organisationen som signerar PDF-dokumentet. |
| [getSignNames](#getSignNames--) | <p> Hämtar namnen på alla icke‑tomma signaturer. </p> <hr> |
| [getSignNames](#getSignNames-boolean-) | <p> Hämtar namnen på alla icke‑tomma signaturer. </p> <hr> <pre> String inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); ArrayList names=pdfSign.getSignNames(true); for(int i=0;i<names.Count;i++) { System.out.println("signature name:"+(String)names[i]); System.out.println("coverswholedocument:"+pdfSign.IsCoversWholeDocument((String)names[i])); System.out.println("revision:"+pdfSign.GetRevision((String)names[i])); System.out.println("verifysigned:"+pdfSign.VerifySigned((String)names[i])); System.out.println("reason:"+pdfSign.GetReason((String)names[i])); System.out.println("location:"+pdfSign.GetLocation((String)names[i])); System.out.println("datatime:"+pdfSign.GetDateTime((String)names[i])); } System.out.println("totalvision:"+pdfSign.GetTotalRevision()); </pre> |
| [getTotalRevision](#getTotalRevision--) | Hämtar den totala revisionen. |
| [isCertified](#isCertified--) | Hämtar flaggan som bestämmer om ett dokument är certifierat eller inte. |
| [isContainSignature](#isContainSignature--) | Kontrollerar om pdf-filen har en digital signatur eller inte. |
| [isCoversWholeDocument](#isCoversWholeDocument-java.lang.String-) | Kontrollerar om signaturen täcker hela dokumentet. |
| [isLtvEnabled](#isLtvEnabled--) | Hämtar flaggan för LTV‑aktiverad. |
| [removeSignature](#removeSignature-com.aspose.pdf.facades.SignatureName-) | Ta bort signaturen enligt signaturens namn. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i]); } pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeSignature](#removeSignature-com.aspose.pdf.facades.SignatureName-boolean-) | Tar bort signaturen enligt signaturens namn. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i], false); } pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeSignature](#removeSignature-java.lang.String-) | <p> Ta bort signaturen enligt signaturens namn. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i)); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre> |
| [removeSignature](#removeSignature-java.lang.String-boolean-) | <p> Tar bort signaturen enligt signaturens namn. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.BindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i), false); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre> |
| [removeSignatures](#removeSignatures--) | Tar bort alla signaturer. string inFile = TestPath + "example1.pdf"; var pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); pdfSign.removeSignatures(); pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeUsageRights](#removeUsageRights--) | Tar bort posten för användarrättigheter. |
| [save](#save--) | Spara signerad PDF‑fil. Utdatafilnamnet måste anges i förväg med hjälp av motsvarande PdfFileSignature‑konstruktor. |
| [save](#save-java.io.OutputStream-) | Spara signerad PDF‑fil. Utdatafilnamnet måste anges i förväg med hjälp av motsvarande PdfFileSignature‑konstruktor. |
| [save](#save-java.lang.String-) | Spara signerad PDF‑fil. Utdatafilnamnet måste anges i förväg med hjälp av motsvarande PdfFileSignature‑konstruktor. |
| [setCertificate](#setCertificate-java.lang.String-java.lang.String-) | Ange certifikatfil och lösenord för signeringsrutinen. |
| [setSignatureAppearance](#setSignatureAppearance-java.lang.String-) | Ställer in en grafisk framställning för signaturen. Egendomsvärdet representerar bildfilens namn. |
| [setSignatureAppearanceStream](#setSignatureAppearanceStream-java.io.InputStream-) | Ställer in en grafisk framställning för signaturen. Egendomsvärdet representerar bildström. |
| [sign](#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Signera dokumentet med den angivna typ‑signaturen. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-) | Skapa en signatur i PDF‑dokumentet. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Signera dokumentet med den angivna typ‑signaturen. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Signera dokumentet med den angivna typens signatur som är placerad i redan presenterat signaturfält. |
| [sign](#sign-java.lang.String-com.aspose.pdf.Signature-) | <p> Signera dokumentet med den angivna typens signatur som är placerad i redan presenterat signaturfält. Innan signering måste signaturfältet vara tomt, i.e. fältet får inte innehålla signaturdictionary. Således har pdf-dokumentet redan ett signaturfält, du bör inte ange platsen för att stämpla signaturen, motsvarande sida och rektangel tas från signaturfältet som hittas via signaturnamnet (se SigName parameter). Sådana data som signaturorsak, kontakt och plats måste tillhandahållas av motsvarande egenskaper i Signature object sig. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); sig.setReason ( "Some reason"); sig.setContact ( "Smith"); sig.setLocation ( "New York"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", sig); pdfSign.save(); </pre> |
| [sign](#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-) | <p> Signera dokumentet med den angivna typens signatur som är placerad i redan presenterat signaturfält. Innan signering måste signaturfältet vara tomt, i.e. fältet får inte innehålla signaturdictionary. Således har pdf-dokumentet redan ett signaturfält, du bör inte ange platsen för att stämpla signaturen, motsvarande sida och rektangel tas från signaturfältet som hittas via signaturnamnet (se SigName parameter). </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", "Allen", "success", "ChangSha", sig); pdfSign.save(); </pre> |
| [tryExtractCertificate](#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-java.io.OutputStream:A-) | Extraherar signaturens enda X.509-certifikat som en ström. |
| [tryExtractCertificate](#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2:A-) | Extraherar signaturens enda X.509‑certifikat. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-) | Kontrollerar giltigheten för en signatur. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Kontrollerar giltigheten för en signatur. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | Kontrollerar giltigheten för en signatur. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Kontrollerar giltigheten för en signatur. |
| [verifySignature](#verifySignature-java.lang.String-) | Kontrollerar giltigheten för en signatur. |
| [verifySignature](#verifySignature-java.lang.String-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Kontrollerar giltigheten för en signatur. |
| [verifySigned](#verifySigned-java.lang.String-) | Kontrollerar giltigheten för en signatur. Metoden är föråldrad och kommer att tas bort i version 25.1. Använd VerifySignature‑metoden istället. |

### PdfFileSignature {#PdfFileSignature--}
```
public PdfFileSignature()
```

Konstruktorn för PdfFileSignature-klassen.

### PdfFileSignature {#PdfFileSignature-com.aspose.pdf.IDocument-}
Konstruktorn för PdfFileSignature-klassen.

### PdfFileSignature {#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-}
Konstruktorn för PdfFileSignature-klassen.

### PdfFileSignature {#PdfFileSignature-java.lang.String-}
Konstruktorn för PdfFileSignature-klassen.

### PdfFileSignature {#PdfFileSignature-java.lang.String-java.lang.String-}
Konstruktorn för PdfFileSignature-klassen.

### bindPdf {#bindPdf-java.io.InputStream-}
Kopplar en Pdf-ström för redigering.

### bindPdf {#bindPdf-java.lang.String-}
Kopplar en Pdf-fil för redigering.

### certify {#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-}
Certifiera dokumentet med MDP-signaturen.

### certify {#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-}
Certifiera dokumentet med MDP-signaturen som är placerad i ett redan befintligt signaturfält. Innan signering måste signaturfältet vara tomt, d.v.s. fältet får inte innehålla signaturordbok. Således har pdf-dokumentet redan ett signaturfält, du bör inte ange platsen för att stämpla signaturen, motsvarande sida och rektangel tas från signaturfältet som hittas via signaturens namn (se parametern sigName).

### close {#close--}
```
public void close()
```

Stänger fasaden.

### containsSignature {#containsSignature--}
```
public boolean containsSignature()
```

Kontrollerar om pdf-filen har en digital signatur eller inte.

**Returns:**
Returnerar ett resultat av typen bool.

### containsUsageRights {#containsUsageRights--}
```
public boolean containsUsageRights()
```

Kontrollerar om pdf-filen har användarrättigheter eller inte.

**Returns:**
Returnerar ett resultat av typen bool.

### coversWholeDocument {#coversWholeDocument-com.aspose.pdf.facades.SignatureName-}
Kontrollerar om signaturen täcker hela dokumentet.

### coversWholeDocument {#coversWholeDocument-java.lang.String-}
Kontrollerar om signaturen täcker hela dokumentet.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Stänger fasaden. Denna metod är föråldrad, använd close() istället.

### extractCertificate {#extractCertificate-com.aspose.pdf.facades.SignatureName-}
Extraherar signaturens enda X.509-certifikat som en ström.

### extractCertificate {#extractCertificate-java.lang.String-}
Extraherar signaturens enda X.509-certifikat som en ström.

### extractImage {#extractImage-com.aspose.pdf.facades.SignatureName-}
Extraherar signaturens bild.

### extractImage {#extractImage-java.lang.String-}
Extraherar signaturens bild.

### getAccessPermissions {#getAccessPermissions--}
```
public DocMDPAccessPermissions getAccessPermissions()
```

Returnerar åtkomstbehörighetsvärdet för ett certifierat dokument med MDP‑signaturtypen.

**Returns:**
PdfException Om dokumentet certifieras, returneras åtkomstbehörighetsvärdet; annars kastas det. @see com.aspose.pdf.DocMDPAccessPermissions

### getBlankSignNames {#getBlankSignNames--}
```
@Deprecated public List < String > getBlankSignNames()
```

Hämtar namnen på alla tomma signaturfält.

**Returns:**
Returnerar en arrayList. @deprecated Använd GetBlankSignatureNames() istället.

### getContactInfo {#getContactInfo-com.aspose.pdf.facades.SignatureName-}
Hämtar kontaktinformationen för en signatur.

### getContactInfo {#getContactInfo-java.lang.String-}
Hämtar kontaktinformationen för en signatur.

### getDateTime {#getDateTime-com.aspose.pdf.facades.SignatureName-}
Hämtar signaturens datum och tid.

### getDateTime {#getDateTime-java.lang.String-}
Hämtar signaturens datum och tid.

### getLocation {#getLocation-com.aspose.pdf.facades.SignatureName-}
Hämtar platsen för en signatur.

### getLocation {#getLocation-java.lang.String-}
Hämtar platsen för en signatur.

### getReason {#getReason-com.aspose.pdf.facades.SignatureName-}
Hämtar anledningen till en signatur.

### getReason {#getReason-java.lang.String-}
Hämtar anledningen till en signatur.

### getRevision {#getRevision-com.aspose.pdf.facades.SignatureName-}
Hämtar revisionen av en signatur.

### getRevision {#getRevision-java.lang.String-}
Hämtar revisionen av en signatur.

### getSignatureAppearance {#getSignatureAppearance--}
```
public String getSignatureAppearance()
```

Hämtar ett grafiskt utseende för signaturen. Egenskapsvärdet representerar bildfilens namn.

**Returns:**
String värde

### getSignatureAppearanceStream {#getSignatureAppearanceStream--}
```
public InputStream getSignatureAppearanceStream()
```

Hämtar ett grafiskt utseende för signaturen. Egenskapsvärdet representerar bildström.

**Returns:**
InputStream‑element

### getSignatureNames {#getSignatureNames--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< SignatureName > getSignatureNames()
```

/ * <p> / * Hämtar namnen på alla icke‑tomma signaturer. / * </p> / * <p> / * <pre> / * string inFile=TestPath + "example1.pdf"; / * PdfFileSignature pdfSign=new PdfFileSignature(); / * pdfSign.bindPdf(inFile); / * java.util.List<String> names=pdfSign.getSignatureNames(); / * for(int i=0;i<names.size();i++) / * { / * System.out.println("signature name:" + names[i]); / * System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); / * System.out.println("revision:" + pdfSign.getRevision(names[i])); / * System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); / * System.out.println("reason:" + pdfSign.getReason(names[i])); / * System.out.println("location:" + pdfSign.getLocation(names[i])); / * System.out.println("datatime:" + pdfSign.getDateTime(names[i])); / * } / * System.out.println("totalvision:" + pdfSign.GetTotalRevision()); / * / * </pre> / *

**Returns:**
Returnerar en IList<SignatureName>. /

### getSignatureNames {#getSignatureNames-boolean-}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< SignatureName > getSignatureNames(boolean onlyActive)
```

Hämtar namnen på alla icke‑tomma signaturer. string inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); java.util.List names=pdfSign.getSignatureNames(); for(int i=0;i<names.size();i++) { System.out.println("signature name:" + names[i]); System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); System.out.println("revision:" + pdfSign.getRevision(names[i])); System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); System.out.println("reason:" + pdfSign.getReason(names[i])); System.out.println("location:" + pdfSign.getLocation(names[i])); System.out.println("datatime:" + pdfSign.getDateTime(names[i])); } System.out.println("totalvision:" + pdfSign.GetTotalRevision());

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| onlyActive |  | om true, returnera endast aktiva signaturer; annars returnera alla signaturer. |

**Returns:**
Returnerar en IList<SignatureName>.

### getSignaturesInfo {#getSignaturesInfo--}
```
public final List <com.aspose.pdf.engine.security.SignatureAlgorithmInfo> getSignaturesInfo()
```

Hämtar information om alla signaturalgoritmer som finns i PDF-dokumentet.

**Returns:**
En lista med {@link SignatureAlgorithmInfo}-instanser som innehåller information om varje signatur.

### getSignerName {#getSignerName-com.aspose.pdf.facades.SignatureName-}
Hämtar namnet på personen eller organisationen som signerar PDF-dokumentet.

### getSignerName {#getSignerName-java.lang.String-}
Hämtar namnet på personen eller organisationen som signerar PDF-dokumentet.

### getSignNames {#getSignNames--}
```
public final List < String > getSignNames()
```

<p> Hämtar namnen på alla icke‑tomma signaturer. </p> <hr>

**Returns:**
Returnerar en arrayList.

### getSignNames {#getSignNames-boolean-}
```
@Deprecated public List < String > getSignNames(boolean onlyActive)
```

<p> Hämtar namnen på alla icke‑tomma signaturer. </p> <hr> <pre> String inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); ArrayList names=pdfSign.getSignNames(true); for(int i=0;i<names.Count;i++) { System.out.println("signature name:"+(String)names[i]); System.out.println("coverswholedocument:"+pdfSign.IsCoversWholeDocument((String)names[i])); System.out.println("revision:"+pdfSign.GetRevision((String)names[i])); System.out.println("verifysigned:"+pdfSign.VerifySigned((String)names[i])); System.out.println("reason:"+pdfSign.GetReason((String)names[i])); System.out.println("location:"+pdfSign.GetLocation((String)names[i])); System.out.println("datatime:"+pdfSign.GetDateTime((String)names[i])); } System.out.println("totalvision:"+pdfSign.GetTotalRevision()); </pre>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| onlyActive |  | booleskt värde, om true, returnera endast aktiva signaturer; annars returnera alla signaturer. |

**Returns:**
Returnerar en arrayList. @deprecated Metoden kan producera samma signaturnamn, vilka inte kan särskiljas under verifiering. Använd getSignatureNames(boolean onlyActive) istället.

### getTotalRevision {#getTotalRevision--}
```
public int getTotalRevision()
```

Hämtar den totala revisionen.

**Returns:**
Returnerar det totala antalet signaturrevisioner.

### isCertified {#isCertified--}
```
public boolean isCertified()
```

Hämtar flaggan som bestämmer om ett dokument är certifierat eller inte.

**Returns:**
booleskt värde

### isContainSignature {#isContainSignature--}
```
@Deprecated public boolean isContainSignature()
```

Kontrollerar om pdf-filen har en digital signatur eller inte.

**Returns:**
Returnerar ett resultat av typen bool.

### isCoversWholeDocument {#isCoversWholeDocument-java.lang.String-}
Kontrollerar om signaturen täcker hela dokumentet.

### isLtvEnabled {#isLtvEnabled--}
```
public final boolean isLtvEnabled()
```

Hämtar flaggan för LTV‑aktiverad.

**Returns:**
booleskt värde

### removeSignature {#removeSignature-com.aspose.pdf.facades.SignatureName-}
Ta bort signaturen enligt signaturens namn. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i]); } pdfSign.save(TestPath + "signed_removed.pdf");

### removeSignature {#removeSignature-com.aspose.pdf.facades.SignatureName-boolean-}
Tar bort signaturen enligt signaturens namn. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i], false); } pdfSign.save(TestPath + "signed_removed.pdf");

### removeSignature {#removeSignature-java.lang.String-}
<p> Ta bort signaturen enligt signaturens namn. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i)); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre>

### removeSignature {#removeSignature-java.lang.String-boolean-}
<p> Tar bort signaturen enligt signaturens namn. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.BindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i), false); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre>

### removeSignatures {#removeSignatures--}
```
public final void removeSignatures()
```

Tar bort alla signaturer. string inFile = TestPath + "example1.pdf"; var pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); pdfSign.removeSignatures(); pdfSign.save(TestPath + "signed_removed.pdf");

### removeUsageRights {#removeUsageRights--}
```
public void removeUsageRights()
```

Tar bort posten för användarrättigheter.

### save {#save--}
```
@Deprecated public void save()
```

Spara signerad PDF‑fil. Utdatafilnamnet måste anges i förväg med hjälp av motsvarande PdfFileSignature‑konstruktor.

### save {#save-java.io.OutputStream-}
Spara signerad PDF‑fil. Utdatafilnamnet måste anges i förväg med hjälp av motsvarande PdfFileSignature‑konstruktor.

### save {#save-java.lang.String-}
Spara signerad PDF‑fil. Utdatafilnamnet måste anges i förväg med hjälp av motsvarande PdfFileSignature‑konstruktor.

### setCertificate {#setCertificate-java.lang.String-java.lang.String-}
Ange certifikatfil och lösenord för signeringsrutinen.

### setSignatureAppearance {#setSignatureAppearance-java.lang.String-}
Ställer in en grafisk framställning för signaturen. Egendomsvärdet representerar bildfilens namn.

### setSignatureAppearanceStream {#setSignatureAppearanceStream-java.io.InputStream-}
Ställer in en grafisk framställning för signaturen. Egendomsvärdet representerar bildström.

### sign {#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Signera dokumentet med den angivna typ‑signaturen.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-}
Skapa en signatur i PDF‑dokumentet.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Signera dokumentet med den angivna typ‑signaturen.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Signera dokumentet med den angivna typens signatur som är placerad i redan presenterat signaturfält.

### sign {#sign-java.lang.String-com.aspose.pdf.Signature-}
<p> Signera dokumentet med den angivna typens signatur som är placerad i redan presenterat signaturfält. Innan signering måste signaturfältet vara tomt, i.e. fältet får inte innehålla signaturdictionary. Således har pdf-dokumentet redan ett signaturfält, du bör inte ange platsen för att stämpla signaturen, motsvarande sida och rektangel tas från signaturfältet som hittas via signaturnamnet (se SigName parameter). Sådana data som signaturorsak, kontakt och plats måste tillhandahållas av motsvarande egenskaper i Signature object sig. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); sig.setReason ( "Some reason"); sig.setContact ( "Smith"); sig.setLocation ( "New York"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", sig); pdfSign.save(); </pre>

### sign {#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-}
<p> Signera dokumentet med den angivna typens signatur som är placerad i redan presenterat signaturfält. Innan signering måste signaturfältet vara tomt, i.e. fältet får inte innehålla signaturdictionary. Således har pdf-dokumentet redan ett signaturfält, du bör inte ange platsen för att stämpla signaturen, motsvarande sida och rektangel tas från signaturfältet som hittas via signaturnamnet (se SigName parameter). </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", "Allen", "success", "ChangSha", sig); pdfSign.save(); </pre>

### tryExtractCertificate {#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-java.io.OutputStream:A-}
Extraherar signaturens enda X.509-certifikat som en ström.

### tryExtractCertificate {#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2:A-}
Extraherar signaturens enda X.509‑certifikat.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-}
Kontrollerar giltigheten för en signatur.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Kontrollerar giltigheten för en signatur.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
Kontrollerar giltigheten för en signatur.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Kontrollerar giltigheten för en signatur.

### verifySignature {#verifySignature-java.lang.String-}
Kontrollerar giltigheten för en signatur.

### verifySignature {#verifySignature-java.lang.String-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Kontrollerar giltigheten för en signatur.

### verifySigned {#verifySigned-java.lang.String-}
Kontrollerar giltigheten för en signatur. Metoden är föråldrad och kommer att tas bort i version 25.1. Använd VerifySignature‑metoden istället.
