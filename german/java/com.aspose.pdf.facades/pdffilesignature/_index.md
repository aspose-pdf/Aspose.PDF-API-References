---
title: "PdfFileSignature"
linktitle: "PdfFileSignature"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Klasse zum Signieren einer PDF‑Datei mit einem Zertifikat dar."
type: docs
weight: 530
url: /de/java/com.aspose.pdf.facades/pdffilesignature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSignature, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSignature, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSignature

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSignature extends SaveableFacade
```

Stellt eine Klasse zum Signieren einer PDF‑Datei mit einem Zertifikat dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfFileSignature](#PdfFileSignature--) | Der Konstruktor der Klasse PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-com.aspose.pdf.IDocument-) | Der Konstruktor der Klasse PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-) | Der Konstruktor der Klasse PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-java.lang.String-) | Der Konstruktor der Klasse PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-java.lang.String-java.lang.String-) | Der Konstruktor der Klasse PdfFileSignature. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | Bindet einen Pdf-Stream zum Bearbeiten. |
| [bindPdf](#bindPdf-java.lang.String-) | Bindet eine Pdf-Datei zum Bearbeiten. |
| [certify](#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-) | Bescheinigt das Dokument mit der MDP-Signatur. |
| [certify](#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-) | Bescheinigt das Dokument mit der MDP-Signatur, die in einem bereits vorhandenen Signaturfeld platziert ist. Vor dem Signieren muss das Signaturfeld leer sein, d. h. das Feld darf kein Signaturverzeichnis enthalten. Da das pdf-Dokument bereits ein Signaturfeld hat, müssen Sie den Ort zum Anbringen der Signatur nicht angeben; die entsprechende Seite und das Rechteck werden aus dem Signaturfeld übernommen, das über den Signaturnamen gefunden wird (siehe Parameter sigName). |
| [close](#close--) | Schließt die Fassade. |
| [containsSignature](#containsSignature--) | Prüft, ob das pdf eine digitale Signatur hat oder nicht. |
| [containsUsageRights](#containsUsageRights--) | Prüft, ob das pdf Nutzungsrechte hat oder nicht. |
| [coversWholeDocument](#coversWholeDocument-com.aspose.pdf.facades.SignatureName-) | Prüft, ob die Signatur das gesamte Dokument abdeckt. |
| [coversWholeDocument](#coversWholeDocument-java.lang.String-) | Prüft, ob die Signatur das gesamte Dokument abdeckt. |
| [dispose](#dispose--) | Schließt die Fassade. Diese Methode ist veraltet, verwenden Sie stattdessen close(). |
| [extractCertificate](#extractCertificate-com.aspose.pdf.facades.SignatureName-) | Extrahiert das einzelne X.509-Zertifikat der Signatur als Stream. |
| [extractCertificate](#extractCertificate-java.lang.String-) | Extrahiert das einzelne X.509-Zertifikat der Signatur als Stream. |
| [extractImage](#extractImage-com.aspose.pdf.facades.SignatureName-) | Extrahiert das Bild der Signatur. |
| [extractImage](#extractImage-java.lang.String-) | Extrahiert das Bild der Signatur. |
| [getAccessPermissions](#getAccessPermissions--) | Gibt den Zugriffsberechtigungswert des zertifizierten Dokuments anhand des MDP-Signaturtyps zurück. |
| [getBlankSignNames](#getBlankSignNames--) | Ermittelt die Namen aller leeren Signaturfelder. |
| [getContactInfo](#getContactInfo-com.aspose.pdf.facades.SignatureName-) | Ermittelt die Kontaktinformationen einer Signatur. |
| [getContactInfo](#getContactInfo-java.lang.String-) | Ermittelt die Kontaktinformationen einer Signatur. |
| [getDateTime](#getDateTime-com.aspose.pdf.facades.SignatureName-) | Ermittelt das Datum und die Uhrzeit der Signatur. |
| [getDateTime](#getDateTime-java.lang.String-) | Ermittelt das Datum und die Uhrzeit der Signatur. |
| [getLocation](#getLocation-com.aspose.pdf.facades.SignatureName-) | Ermittelt den Ort einer Signatur. |
| [getLocation](#getLocation-java.lang.String-) | Ermittelt den Ort einer Signatur. |
| [getReason](#getReason-com.aspose.pdf.facades.SignatureName-) | Ermittelt den Grund einer Signatur. |
| [getReason](#getReason-java.lang.String-) | Ermittelt den Grund einer Signatur. |
| [getRevision](#getRevision-com.aspose.pdf.facades.SignatureName-) | Ermittelt die Revision einer Signatur. |
| [getRevision](#getRevision-java.lang.String-) | Ermittelt die Revision einer Signatur. |
| [getSignatureAppearance](#getSignatureAppearance--) | Ermittelt ein grafisches Erscheinungsbild für die Signatur. Der Property-Wert stellt den Bilddateinamen dar. |
| [getSignatureAppearanceStream](#getSignatureAppearanceStream--) | Ermittelt ein grafisches Erscheinungsbild für die Signatur. Der Property-Wert stellt den Bild-Stream dar. |
| [getSignatureNames](#getSignatureNames--) | / * <p> / * Ermittelt die Namen aller nicht leeren Signaturen. / * </p> / * <p> / * <pre> / * string inFile=TestPath + "example1.pdf"; / * PdfFileSignature pdfSign=new PdfFileSignature(); / * pdfSign.bindPdf(inFile); / * java.util.List<String> names=pdfSign.getSignatureNames(); / * for(int i=0;i<names.size();i++) / * { / * System.out.println("signature name:" + names[i]); / * System.out.println("coverswholeddocument:" + pdfSign.coversWholeDocument(names[i])); / * System.out.println("revision:" + pdfSign.getRevision(names[i])); / * System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); / * System.out.println("reason:" + pdfSign.getReason(names[i])); / * System.out.println("location:" + pdfSign.getLocation(names[i])); / * System.out.println("datatime:" + pdfSign.getDateTime(names[i])); / * } / * System.out.println("totalvision:" + pdfSign.GetTotalRevision()); / * / * </pre> / * |
| [getSignatureNames](#getSignatureNames-boolean-) | Ermittelt die Namen aller nicht leeren Signaturen. string inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); java.util.List names=pdfSign.getSignatureNames(); for(int i=0;i<names.size();i++) { System.out.println("signature name:" + names[i]); System.out.println("coverswholeddocument:" + pdfSign.coversWholeDocument(names[i])); System.out.println("revision:" + pdfSign.getRevision(names[i])); System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); System.out.println("reason:" + pdfSign.getReason(names[i])); System.out.println("location:" + pdfSign.getLocation(names[i])); System.out.println("datatime:" + pdfSign.getDateTime(names[i])); } System.out.println("totalvision:" + pdfSign.GetTotalRevision()); |
| [getSignaturesInfo](#getSignaturesInfo--) | Ruft Informationen über alle im PDF-Dokument vorhandenen Signaturalgorithmen ab. |
| [getSignerName](#getSignerName-com.aspose.pdf.facades.SignatureName-) | Ermittelt den Namen der Person oder Organisation, die das PDF-Dokument signiert. |
| [getSignerName](#getSignerName-java.lang.String-) | Ermittelt den Namen der Person oder Organisation, die das PDF-Dokument signiert. |
| [getSignNames](#getSignNames--) | <p> Ermittelt die Namen aller nicht leeren Signaturen. </p> <hr> |
| [getSignNames](#getSignNames-boolean-) | <p> Ermittelt die Namen aller nicht leeren Signaturen. </p> <hr> <pre> String inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); ArrayList names=pdfSign.getSignNames(true); for(int i=0;i<names.Count;i++) { System.out.println("signature name:"+(String)names[i]); System.out.println("coverswholedocument:"+pdfSign.IsCoversWholeDocument((String)names[i])); System.out.println("revision:"+pdfSign.GetRevision((String)names[i])); System.out.println("verifysigned:"+pdfSign.VerifySigned((String)names[i])); System.out.println("reason:"+pdfSign.GetReason((String)names[i]); System.out.println("location:"+pdfSign.GetLocation((String)names[i]); System.out.println("datatime:"+pdfSign.GetDateTime((String)names[i])); } System.out.println("totalvision:"+pdfSign.GetTotalRevision()); </pre> |
| [getTotalRevision](#getTotalRevision--) | Ermittelt die gesamte Revision. |
| [isCertified](#isCertified--) | Ermittelt das Flag, das bestimmt, ob ein Dokument zertifiziert ist oder nicht. |
| [isContainSignature](#isContainSignature--) | Prüft, ob das pdf eine digitale Signatur hat oder nicht. |
| [isCoversWholeDocument](#isCoversWholeDocument-java.lang.String-) | Prüft, ob die Signatur das gesamte Dokument abdeckt. |
| [isLtvEnabled](#isLtvEnabled--) | Ermittelt das aktivierte LTV-Flag. |
| [removeSignature](#removeSignature-com.aspose.pdf.facades.SignatureName-) | Entfernt die Signatur anhand des Namens der Signatur. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i]); } pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeSignature](#removeSignature-com.aspose.pdf.facades.SignatureName-boolean-) | Entfernt die Signatur anhand des Namens der Signatur. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i], false); } pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeSignature](#removeSignature-java.lang.String-) | <p> Entfernt die Signatur anhand des Namens der Signatur. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i)); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre> |
| [removeSignature](#removeSignature-java.lang.String-boolean-) | <p> Entfernt die Signatur anhand des Namens der Signatur. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.BindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i), false); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre> |
| [removeSignatures](#removeSignatures--) | Entfernt alle Signaturen. string inFile = TestPath + "example1.pdf"; var pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); pdfSign.removeSignatures(); pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeUsageRights](#removeUsageRights--) | Entfernt den Eintrag für Nutzungsrechte. |
| [save](#save--) | Speichert die signierte PDF-Datei. Der Ausgabedateiname muss zuvor mit dem entsprechenden PdfFileSignature-Konstruktor angegeben werden. |
| [save](#save-java.io.OutputStream-) | Speichert die signierte PDF-Datei. Der Ausgabedateiname muss zuvor mit dem entsprechenden PdfFileSignature-Konstruktor angegeben werden. |
| [save](#save-java.lang.String-) | Speichert die signierte PDF-Datei. Der Ausgabedateiname muss zuvor mit dem entsprechenden PdfFileSignature-Konstruktor angegeben werden. |
| [setCertificate](#setCertificate-java.lang.String-java.lang.String-) | Legt die Zertifikatsdatei und das Passwort für den Signaturvorgang fest. |
| [setSignatureAppearance](#setSignatureAppearance-java.lang.String-) | Legt ein grafisches Erscheinungsbild für die Signatur fest. Der Eigenschaftswert stellt den Bilddateinamen dar. |
| [setSignatureAppearanceStream](#setSignatureAppearanceStream-java.io.InputStream-) | Legt ein grafisches Erscheinungsbild für die Signatur fest. Der Eigenschaftswert stellt einen Bildstrom dar. |
| [sign](#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Signieren Sie das Dokument mit der angegebenen Signaturart. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-) | Erstellen Sie eine Signatur im PDF-Dokument. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Signieren Sie das Dokument mit der angegebenen Signaturart. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Signieren Sie das Dokument mit der angegebenen Signaturart, die in einem bereits vorhandenen Signaturfeld platziert ist. |
| [sign](#sign-java.lang.String-com.aspose.pdf.Signature-) | <p> Signieren Sie das Dokument mit der angegebenen Signaturart, die in einem bereits vorhandenen Signaturfeld platziert ist. Vor dem Signieren muss das Signaturfeld leer sein, d. h. das Feld darf kein Signatur‑Dictionary enthalten. Da das PDF‑Dokument bereits ein Signaturfeld hat, müssen Sie den Ort zum Anbringen der Signatur nicht angeben; die entsprechende Seite und das Rechteck werden aus dem Signaturfeld übernommen, das über den Signaturnamen gefunden wird (siehe Parameter SigName). Daten wie Signaturgrund, Kontakt und Ort müssen über die entsprechenden Eigenschaften des Signature‑Objekts sig bereitgestellt werden. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); sig.setReason ( "Some reason"); sig.setContact ( "Smith"); sig.setLocation ( "New York"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", sig); pdfSign.save(); </pre> |
| [sign](#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-) | <p> Signieren Sie das Dokument mit der angegebenen Signaturart, die in einem bereits vorhandenen Signaturfeld platziert ist. Vor dem Signieren muss das Signaturfeld leer sein, d. h. das Feld darf kein Signatur‑Dictionary enthalten. Da das PDF‑Dokument bereits ein Signaturfeld hat, müssen Sie den Ort zum Anbringen der Signatur nicht angeben; die entsprechende Seite und das Rechteck werden aus dem Signaturfeld übernommen, das über den Signaturnamen gefunden wird (siehe Parameter SigName). </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", "Allen", "success", "ChangSha", sig); pdfSign.save(); </pre> |
| [tryExtractCertificate](#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-java.io.OutputStream:A-) | Extrahiert das einzelne X.509-Zertifikat der Signatur als Stream. |
| [tryExtractCertificate](#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2:A-) | Extrahiert das einzelne X.509-Zertifikat der Signatur. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-) | Überprüft die Gültigkeit einer Signatur. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Überprüft die Gültigkeit einer Signatur. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | Überprüft die Gültigkeit einer Signatur. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Überprüft die Gültigkeit einer Signatur. |
| [verifySignature](#verifySignature-java.lang.String-) | Überprüft die Gültigkeit einer Signatur. |
| [verifySignature](#verifySignature-java.lang.String-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Überprüft die Gültigkeit einer Signatur. |
| [verifySigned](#verifySigned-java.lang.String-) | Überprüft die Gültigkeit einer Signatur. Die Methode ist veraltet und wird in Version 25.1 entfernt. Verwenden Sie stattdessen die Methode VerifySignature. |

### PdfFileSignature {#PdfFileSignature--}
```
public PdfFileSignature()
```

Der Konstruktor der Klasse PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-com.aspose.pdf.IDocument-}
Der Konstruktor der Klasse PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-}
Der Konstruktor der Klasse PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-java.lang.String-}
Der Konstruktor der Klasse PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-java.lang.String-java.lang.String-}
Der Konstruktor der Klasse PdfFileSignature.

### bindPdf {#bindPdf-java.io.InputStream-}
Bindet einen Pdf-Stream zum Bearbeiten.

### bindPdf {#bindPdf-java.lang.String-}
Bindet eine Pdf-Datei zum Bearbeiten.

### certify {#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-}
Bescheinigt das Dokument mit der MDP-Signatur.

### certify {#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-}
Bescheinigt das Dokument mit der MDP-Signatur, die in einem bereits vorhandenen Signaturfeld platziert ist. Vor dem Signieren muss das Signaturfeld leer sein, d. h. das Feld darf kein Signaturverzeichnis enthalten. Da das pdf-Dokument bereits ein Signaturfeld hat, müssen Sie den Ort zum Anbringen der Signatur nicht angeben; die entsprechende Seite und das Rechteck werden aus dem Signaturfeld übernommen, das über den Signaturnamen gefunden wird (siehe Parameter sigName).

### close {#close--}
```
public void close()
```

Schließt die Fassade.

### containsSignature {#containsSignature--}
```
public boolean containsSignature()
```

Prüft, ob das pdf eine digitale Signatur hat oder nicht.

**Returns:**
Gibt ein Ergebnis vom Typ bool zurück.

### containsUsageRights {#containsUsageRights--}
```
public boolean containsUsageRights()
```

Prüft, ob das pdf Nutzungsrechte hat oder nicht.

**Returns:**
Gibt ein Ergebnis vom Typ bool zurück.

### coversWholeDocument {#coversWholeDocument-com.aspose.pdf.facades.SignatureName-}
Prüft, ob die Signatur das gesamte Dokument abdeckt.

### coversWholeDocument {#coversWholeDocument-java.lang.String-}
Prüft, ob die Signatur das gesamte Dokument abdeckt.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Schließt die Fassade. Diese Methode ist veraltet, verwenden Sie stattdessen close().

### extractCertificate {#extractCertificate-com.aspose.pdf.facades.SignatureName-}
Extrahiert das einzelne X.509-Zertifikat der Signatur als Stream.

### extractCertificate {#extractCertificate-java.lang.String-}
Extrahiert das einzelne X.509-Zertifikat der Signatur als Stream.

### extractImage {#extractImage-com.aspose.pdf.facades.SignatureName-}
Extrahiert das Bild der Signatur.

### extractImage {#extractImage-java.lang.String-}
Extrahiert das Bild der Signatur.

### getAccessPermissions {#getAccessPermissions--}
```
public DocMDPAccessPermissions getAccessPermissions()
```

Gibt den Zugriffsberechtigungswert des zertifizierten Dokuments anhand des MDP-Signaturtyps zurück.

**Returns:**
PdfException Wenn das Dokument zertifiziert wird, gibt es den Wert der Zugriffsberechtigungen zurück; andernfalls wird es ausgelöst. @see com.aspose.pdf.DocMDPAccessPermissions

### getBlankSignNames {#getBlankSignNames--}
```
@Deprecated public List < String > getBlankSignNames()
```

Ermittelt die Namen aller leeren Signaturfelder.

**Returns:**
Gibt eine ArrayList zurück. @deprecated Verwenden Sie stattdessen GetBlankSignatureNames().

### getContactInfo {#getContactInfo-com.aspose.pdf.facades.SignatureName-}
Ermittelt die Kontaktinformationen einer Signatur.

### getContactInfo {#getContactInfo-java.lang.String-}
Ermittelt die Kontaktinformationen einer Signatur.

### getDateTime {#getDateTime-com.aspose.pdf.facades.SignatureName-}
Ermittelt das Datum und die Uhrzeit der Signatur.

### getDateTime {#getDateTime-java.lang.String-}
Ermittelt das Datum und die Uhrzeit der Signatur.

### getLocation {#getLocation-com.aspose.pdf.facades.SignatureName-}
Ermittelt den Ort einer Signatur.

### getLocation {#getLocation-java.lang.String-}
Ermittelt den Ort einer Signatur.

### getReason {#getReason-com.aspose.pdf.facades.SignatureName-}
Ermittelt den Grund einer Signatur.

### getReason {#getReason-java.lang.String-}
Ermittelt den Grund einer Signatur.

### getRevision {#getRevision-com.aspose.pdf.facades.SignatureName-}
Ermittelt die Revision einer Signatur.

### getRevision {#getRevision-java.lang.String-}
Ermittelt die Revision einer Signatur.

### getSignatureAppearance {#getSignatureAppearance--}
```
public String getSignatureAppearance()
```

Ermittelt ein grafisches Erscheinungsbild für die Signatur. Der Property-Wert stellt den Bilddateinamen dar.

**Returns:**
String Wert

### getSignatureAppearanceStream {#getSignatureAppearanceStream--}
```
public InputStream getSignatureAppearanceStream()
```

Ermittelt ein grafisches Erscheinungsbild für die Signatur. Der Property-Wert stellt den Bild-Stream dar.

**Returns:**
InputStream-Element

### getSignatureNames {#getSignatureNames--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< SignatureName > getSignatureNames()
```

/ * <p> / * Ermittelt die Namen aller nicht leeren Signaturen. / * </p> / * <p> / * <pre> / * string inFile=TestPath + "example1.pdf"; / * PdfFileSignature pdfSign=new PdfFileSignature(); / * pdfSign.bindPdf(inFile); / * java.util.List<String> names=pdfSign.getSignatureNames(); / * for(int i=0;i<names.size();i++) / * { / * System.out.println("signature name:" + names[i]); / * System.out.println("coverswholeddocument:" + pdfSign.coversWholeDocument(names[i])); / * System.out.println("revision:" + pdfSign.getRevision(names[i])); / * System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); / * System.out.println("reason:" + pdfSign.getReason(names[i])); / * System.out.println("location:" + pdfSign.getLocation(names[i])); / * System.out.println("datatime:" + pdfSign.getDateTime(names[i])); / * } / * System.out.println("totalvision:" + pdfSign.GetTotalRevision()); / * / * </pre> / *

**Returns:**
Gibt eine IList<SignatureName> zurück. /

### getSignatureNames {#getSignatureNames-boolean-}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< SignatureName > getSignatureNames(boolean onlyActive)
```

Ermittelt die Namen aller nicht leeren Signaturen. string inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); java.util.List names=pdfSign.getSignatureNames(); for(int i=0;i<names.size();i++) { System.out.println("signature name:" + names[i]); System.out.println("coverswholeddocument:" + pdfSign.coversWholeDocument(names[i])); System.out.println("revision:" + pdfSign.getRevision(names[i])); System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); System.out.println("reason:" + pdfSign.getReason(names[i])); System.out.println("location:" + pdfSign.getLocation(names[i])); System.out.println("datatime:" + pdfSign.getDateTime(names[i])); } System.out.println("totalvision:" + pdfSign.GetTotalRevision());

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| onlyActive |  | wenn true, werden nur aktive Signaturen zurückgegeben; andernfalls werden alle Signaturen zurückgegeben. |

**Returns:**
Gibt eine IList<SignatureName> zurück.

### getSignaturesInfo {#getSignaturesInfo--}
```
public final List <com.aspose.pdf.engine.security.SignatureAlgorithmInfo> getSignaturesInfo()
```

Ruft Informationen über alle im PDF-Dokument vorhandenen Signaturalgorithmen ab.

**Returns:**
Eine Liste von {@link SignatureAlgorithmInfo}-Instanzen, die Informationen zu jeder Signatur enthalten.

### getSignerName {#getSignerName-com.aspose.pdf.facades.SignatureName-}
Ermittelt den Namen der Person oder Organisation, die das PDF-Dokument signiert.

### getSignerName {#getSignerName-java.lang.String-}
Ermittelt den Namen der Person oder Organisation, die das PDF-Dokument signiert.

### getSignNames {#getSignNames--}
```
public final List < String > getSignNames()
```

<p> Ermittelt die Namen aller nicht leeren Signaturen. </p> <hr>

**Returns:**
Gibt eine ArrayList zurück.

### getSignNames {#getSignNames-boolean-}
```
@Deprecated public List < String > getSignNames(boolean onlyActive)
```

<p> Ermittelt die Namen aller nicht leeren Signaturen. </p> <hr> <pre> String inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); ArrayList names=pdfSign.getSignNames(true); for(int i=0;i<names.Count;i++) { System.out.println("signature name:"+(String)names[i]); System.out.println("coverswholedocument:"+pdfSign.IsCoversWholeDocument((String)names[i])); System.out.println("revision:"+pdfSign.GetRevision((String)names[i])); System.out.println("verifysigned:"+pdfSign.VerifySigned((String)names[i])); System.out.println("reason:"+pdfSign.GetReason((String)names[i]); System.out.println("location:"+pdfSign.GetLocation((String)names[i]); System.out.println("datatime:"+pdfSign.GetDateTime((String)names[i])); } System.out.println("totalvision:"+pdfSign.GetTotalRevision()); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| onlyActive |  | Boolescher Wert, wenn true, werden nur aktive Signaturen zurückgegeben; andernfalls werden alle Signaturen zurückgegeben. |

**Returns:**
Gibt eine ArrayList zurück. @deprecated Die Methode kann dieselben Signaturnamen erzeugen, die während der Verifizierung nicht unterschieden werden können. Verwenden Sie stattdessen getSignatureNames(boolean onlyActive).

### getTotalRevision {#getTotalRevision--}
```
public int getTotalRevision()
```

Ermittelt die gesamte Revision.

**Returns:**
Gibt die Gesamtzahl der Signaturrevisionen zurück.

### isCertified {#isCertified--}
```
public boolean isCertified()
```

Ermittelt das Flag, das bestimmt, ob ein Dokument zertifiziert ist oder nicht.

**Returns:**
boolescher Wert

### isContainSignature {#isContainSignature--}
```
@Deprecated public boolean isContainSignature()
```

Prüft, ob das pdf eine digitale Signatur hat oder nicht.

**Returns:**
Gibt ein Ergebnis vom Typ bool zurück.

### isCoversWholeDocument {#isCoversWholeDocument-java.lang.String-}
Prüft, ob die Signatur das gesamte Dokument abdeckt.

### isLtvEnabled {#isLtvEnabled--}
```
public final boolean isLtvEnabled()
```

Ermittelt das aktivierte LTV-Flag.

**Returns:**
boolescher Wert

### removeSignature {#removeSignature-com.aspose.pdf.facades.SignatureName-}
Entfernt die Signatur anhand des Namens der Signatur. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i]); } pdfSign.save(TestPath + "signed_removed.pdf");

### removeSignature {#removeSignature-com.aspose.pdf.facades.SignatureName-boolean-}
Entfernt die Signatur anhand des Namens der Signatur. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i], false); } pdfSign.save(TestPath + "signed_removed.pdf");

### removeSignature {#removeSignature-java.lang.String-}
<p> Entfernt die Signatur anhand des Namens der Signatur. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i)); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre>

### removeSignature {#removeSignature-java.lang.String-boolean-}
<p> Entfernt die Signatur anhand des Namens der Signatur. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.BindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i), false); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre>

### removeSignatures {#removeSignatures--}
```
public final void removeSignatures()
```

Entfernt alle Signaturen. string inFile = TestPath + "example1.pdf"; var pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); pdfSign.removeSignatures(); pdfSign.save(TestPath + "signed_removed.pdf");

### removeUsageRights {#removeUsageRights--}
```
public void removeUsageRights()
```

Entfernt den Eintrag für Nutzungsrechte.

### save {#save--}
```
@Deprecated public void save()
```

Speichert die signierte PDF-Datei. Der Ausgabedateiname muss zuvor mit dem entsprechenden PdfFileSignature-Konstruktor angegeben werden.

### save {#save-java.io.OutputStream-}
Speichert die signierte PDF-Datei. Der Ausgabedateiname muss zuvor mit dem entsprechenden PdfFileSignature-Konstruktor angegeben werden.

### save {#save-java.lang.String-}
Speichert die signierte PDF-Datei. Der Ausgabedateiname muss zuvor mit dem entsprechenden PdfFileSignature-Konstruktor angegeben werden.

### setCertificate {#setCertificate-java.lang.String-java.lang.String-}
Legt die Zertifikatsdatei und das Passwort für den Signaturvorgang fest.

### setSignatureAppearance {#setSignatureAppearance-java.lang.String-}
Legt ein grafisches Erscheinungsbild für die Signatur fest. Der Eigenschaftswert stellt den Bilddateinamen dar.

### setSignatureAppearanceStream {#setSignatureAppearanceStream-java.io.InputStream-}
Legt ein grafisches Erscheinungsbild für die Signatur fest. Der Eigenschaftswert stellt einen Bildstrom dar.

### sign {#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Signieren Sie das Dokument mit der angegebenen Signaturart.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-}
Erstellen Sie eine Signatur im PDF-Dokument.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Signieren Sie das Dokument mit der angegebenen Signaturart.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Signieren Sie das Dokument mit der angegebenen Signaturart, die in einem bereits vorhandenen Signaturfeld platziert ist.

### sign {#sign-java.lang.String-com.aspose.pdf.Signature-}
<p> Signieren Sie das Dokument mit der angegebenen Signaturart, die in einem bereits vorhandenen Signaturfeld platziert ist. Vor dem Signieren muss das Signaturfeld leer sein, d. h. das Feld darf kein Signatur‑Dictionary enthalten. Da das PDF‑Dokument bereits ein Signaturfeld hat, müssen Sie den Ort zum Anbringen der Signatur nicht angeben; die entsprechende Seite und das Rechteck werden aus dem Signaturfeld übernommen, das über den Signaturnamen gefunden wird (siehe Parameter SigName). Daten wie Signaturgrund, Kontakt und Ort müssen über die entsprechenden Eigenschaften des Signature‑Objekts sig bereitgestellt werden. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); sig.setReason ( "Some reason"); sig.setContact ( "Smith"); sig.setLocation ( "New York"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", sig); pdfSign.save(); </pre>

### sign {#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-}
<p> Signieren Sie das Dokument mit der angegebenen Signaturart, die in einem bereits vorhandenen Signaturfeld platziert ist. Vor dem Signieren muss das Signaturfeld leer sein, d. h. das Feld darf kein Signatur‑Dictionary enthalten. Da das PDF‑Dokument bereits ein Signaturfeld hat, müssen Sie den Ort zum Anbringen der Signatur nicht angeben; die entsprechende Seite und das Rechteck werden aus dem Signaturfeld übernommen, das über den Signaturnamen gefunden wird (siehe Parameter SigName). </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", "Allen", "success", "ChangSha", sig); pdfSign.save(); </pre>

### tryExtractCertificate {#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-java.io.OutputStream:A-}
Extrahiert das einzelne X.509-Zertifikat der Signatur als Stream.

### tryExtractCertificate {#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2:A-}
Extrahiert das einzelne X.509-Zertifikat der Signatur.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-}
Überprüft die Gültigkeit einer Signatur.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Überprüft die Gültigkeit einer Signatur.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
Überprüft die Gültigkeit einer Signatur.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Überprüft die Gültigkeit einer Signatur.

### verifySignature {#verifySignature-java.lang.String-}
Überprüft die Gültigkeit einer Signatur.

### verifySignature {#verifySignature-java.lang.String-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Überprüft die Gültigkeit einer Signatur.

### verifySigned {#verifySigned-java.lang.String-}
Überprüft die Gültigkeit einer Signatur. Die Methode ist veraltet und wird in Version 25.1 entfernt. Verwenden Sie stattdessen die Methode VerifySignature.
