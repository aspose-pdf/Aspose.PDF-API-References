---
title: "PdfFileSignature"
linktitle: "PdfFileSignature"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe permettant de signer un fichier PDF avec un certificat."
type: docs
weight: 530
url: /fr/java/com.aspose.pdf.facades/pdffilesignature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSignature, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSignature, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSignature

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSignature extends SaveableFacade
```

Représente une classe permettant de signer un fichier PDF avec un certificat.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfFileSignature](#PdfFileSignature--) | Le constructeur de la classe PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-com.aspose.pdf.IDocument-) | Le constructeur de la classe PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-) | Le constructeur de la classe PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-java.lang.String-) | Le constructeur de la classe PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-java.lang.String-java.lang.String-) | Le constructeur de la classe PdfFileSignature. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | Lie un flux Pdf pour l'édition. |
| [bindPdf](#bindPdf-java.lang.String-) | Lie un fichier Pdf pour l'édition. |
| [certify](#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-) | Certifie le document avec la signature MDP. |
| [certify](#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-) | Certifie le document avec la signature MDP qui est placée dans un champ de signature déjà présent. Avant de signer, le champ de signature doit être vide, c’est‑à‑dire qu’il ne doit pas contenir de dictionnaire de signature. Ainsi, le document PDF possède déjà un champ de signature ; vous ne devez pas fournir l’emplacement pour apposer la signature, la page correspondante et le rectangle sont récupérés à partir du champ de signature trouvé par le nom de signature (voir le paramètre sigName). |
| [close](#close--) | Ferme la façade. |
| [containsSignature](#containsSignature--) | Vérifie si le PDF possède une signature numérique ou non. |
| [containsUsageRights](#containsUsageRights--) | Vérifie si le PDF possède des droits d’utilisation ou non. |
| [coversWholeDocument](#coversWholeDocument-com.aspose.pdf.facades.SignatureName-) | Vérifie si la signature couvre l’ensemble du document. |
| [coversWholeDocument](#coversWholeDocument-java.lang.String-) | Vérifie si la signature couvre l’ensemble du document. |
| [dispose](#dispose--) | Ferme la façade. Cette méthode est obsolète, utilisez close() à la place. |
| [extractCertificate](#extractCertificate-com.aspose.pdf.facades.SignatureName-) | Extrait le certificat X.509 unique de la signature sous forme de flux. |
| [extractCertificate](#extractCertificate-java.lang.String-) | Extrait le certificat X.509 unique de la signature sous forme de flux. |
| [extractImage](#extractImage-com.aspose.pdf.facades.SignatureName-) | Extrait l’image de la signature. |
| [extractImage](#extractImage-java.lang.String-) | Extrait l’image de la signature. |
| [getAccessPermissions](#getAccessPermissions--) | Renvoie la valeur des autorisations d'accès du document certifié par le type de signature MDP. |
| [getBlankSignNames](#getBlankSignNames--) | Obtient les noms de tous les champs de signature vides. |
| [getContactInfo](#getContactInfo-com.aspose.pdf.facades.SignatureName-) | Obtient les informations de contact d'une signature. |
| [getContactInfo](#getContactInfo-java.lang.String-) | Obtient les informations de contact d'une signature. |
| [getDateTime](#getDateTime-com.aspose.pdf.facades.SignatureName-) | Obtient la date et l'heure de la signature. |
| [getDateTime](#getDateTime-java.lang.String-) | Obtient la date et l'heure de la signature. |
| [getLocation](#getLocation-com.aspose.pdf.facades.SignatureName-) | Obtient l'emplacement d'une signature. |
| [getLocation](#getLocation-java.lang.String-) | Obtient l'emplacement d'une signature. |
| [getReason](#getReason-com.aspose.pdf.facades.SignatureName-) | Obtient le motif d'une signature. |
| [getReason](#getReason-java.lang.String-) | Obtient le motif d'une signature. |
| [getRevision](#getRevision-com.aspose.pdf.facades.SignatureName-) | Obtient la révision d'une signature. |
| [getRevision](#getRevision-java.lang.String-) | Obtient la révision d'une signature. |
| [getSignatureAppearance](#getSignatureAppearance--) | Obtient une apparence graphique pour la signature. La valeur de la propriété représente le nom du fichier image. |
| [getSignatureAppearanceStream](#getSignatureAppearanceStream--) | Obtient une apparence graphique pour la signature. La valeur de la propriété représente le flux d'image. |
| [getSignatureNames](#getSignatureNames--) | / * <p> / * Obtient les noms de toutes les signatures non vides. / * </p> / * <p> / * <pre> / * string inFile=TestPath + "example1.pdf"; / * PdfFileSignature pdfSign=new PdfFileSignature(); / * pdfSign.bindPdf(inFile); / * java.util.List<String> names=pdfSign.getSignatureNames(); / * for(int i=0;i<names.size();i++) / * { / * System.out.println("signature name:" + names[i]); / * System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); / * System.out.println("revision:" + pdfSign.getRevision(names[i])); / * System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); / * System.out.println("reason:" + pdfSign.getReason(names[i])); / * System.out.println("location:" + pdfSign.getLocation(names[i])); / * System.out.println("datatime:" + pdfSign.getDateTime(names[i])); / * } / * System.out.println("totalvision:" + pdfSign.GetTotalRevision()); / * / * </pre> / * |
| [getSignatureNames](#getSignatureNames-boolean-) | Obtient les noms de toutes les signatures non vides. string inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); java.util.List names=pdfSign.getSignatureNames(); for(int i=0;i<names.size();i++) { System.out.println("signature name:" + names[i]); System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); System.out.println("revision:" + pdfSign.getRevision(names[i])); System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); System.out.println("reason:" + pdfSign.getReason(names[i])); System.out.println("location:" + pdfSign.getLocation(names[i])); System.out.println("datatime:" + pdfSign.getDateTime(names[i])); } System.out.println("totalvision:" + pdfSign.GetTotalRevision()); |
| [getSignaturesInfo](#getSignaturesInfo--) | Récupère les informations sur tous les algorithmes de signatures présents dans le document PDF. |
| [getSignerName](#getSignerName-com.aspose.pdf.facades.SignatureName-) | Obtient le nom de la personne ou de l'organisation qui signe le document PDF. |
| [getSignerName](#getSignerName-java.lang.String-) | Obtient le nom de la personne ou de l'organisation qui signe le document PDF. |
| [getSignNames](#getSignNames--) | <p> Obtient les noms de toutes les signatures non vides. </p> <hr> |
| [getSignNames](#getSignNames-boolean-) | <p> Obtient les noms de toutes les signatures non vides. </p> <hr> <pre> String inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); ArrayList names=pdfSign.getSignNames(true); for(int i=0;i<names.Count;i++) { System.out.println("signature name:"+(String)names[i]); System.out.println("coverswholedocument:"+pdfSign.IsCoversWholeDocument((String)names[i])); System.out.println("revision:"+pdfSign.GetRevision((String)names[i])); System.out.println("verifysigned:"+pdfSign.VerifySigned((String)names[i])); System.out.println("reason:"+pdfSign.GetReason((String)names[i])); System.out.println("location:"+pdfSign.GetLocation((String)names[i])); System.out.println("datatime:"+pdfSign.GetDateTime((String)names[i])); } System.out.println("totalvision:"+pdfSign.GetTotalRevision()); </pre> |
| [getTotalRevision](#getTotalRevision--) | Obtient la révision totale. |
| [isCertified](#isCertified--) | Obtient le drapeau déterminant si un document est certifié ou non. |
| [isContainSignature](#isContainSignature--) | Vérifie si le PDF possède une signature numérique ou non. |
| [isCoversWholeDocument](#isCoversWholeDocument-java.lang.String-) | Vérifie si la signature couvre l’ensemble du document. |
| [isLtvEnabled](#isLtvEnabled--) | Obtient le drapeau LTV activé. |
| [removeSignature](#removeSignature-com.aspose.pdf.facades.SignatureName-) | Supprime la signature selon le nom de la signature. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i]); } pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeSignature](#removeSignature-com.aspose.pdf.facades.SignatureName-boolean-) | Supprime la signature selon le nom de la signature. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i], false); } pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeSignature](#removeSignature-java.lang.String-) | <p> Supprime la signature selon le nom de la signature. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i)); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre> |
| [removeSignature](#removeSignature-java.lang.String-boolean-) | <p> Supprime la signature selon le nom de la signature. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.BindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i), false); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre> |
| [removeSignatures](#removeSignatures--) | Supprime toutes les signatures. string inFile = TestPath + "example1.pdf"; var pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); pdfSign.removeSignatures(); pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeUsageRights](#removeUsageRights--) | Supprime l'entrée des droits d'utilisation. |
| [save](#save--) | Enregistrez le fichier PDF signé. Le nom de fichier de sortie doit être fourni au préalable à l'aide du constructeur correspondant de PdfFileSignature. |
| [save](#save-java.io.OutputStream-) | Enregistrez le fichier PDF signé. Le nom de fichier de sortie doit être fourni au préalable à l'aide du constructeur correspondant de PdfFileSignature. |
| [save](#save-java.lang.String-) | Enregistrez le fichier PDF signé. Le nom de fichier de sortie doit être fourni au préalable à l'aide du constructeur correspondant de PdfFileSignature. |
| [setCertificate](#setCertificate-java.lang.String-java.lang.String-) | Définissez le fichier de certificat et le mot de passe pour la routine de signature. |
| [setSignatureAppearance](#setSignatureAppearance-java.lang.String-) | Définit une apparence graphique pour la signature. La valeur de la propriété représente le nom du fichier image. |
| [setSignatureAppearanceStream](#setSignatureAppearanceStream-java.io.InputStream-) | Définit une apparence graphique pour la signature. La valeur de la propriété représente le flux d'image. |
| [sign](#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Signez le document avec la signature du type indiqué. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-) | Effectuez une signature sur le document PDF. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Signez le document avec la signature du type indiqué. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Signez le document avec la signature du type indiqué qui est placée dans un champ de signature déjà présent. |
| [sign](#sign-java.lang.String-com.aspose.pdf.Signature-) | <p> Signez le document avec la signature du type indiqué qui est placée dans un champ de signature déjà présent. Avant de signer, le champ de signature doit être vide, c’est‑à‑dire qu’il ne doit pas contenir de dictionnaire de signature. Ainsi, le document PDF possède déjà un champ de signature ; vous ne devez pas fournir l’emplacement pour apposer la signature, la page et le rectangle correspondants sont récupérés à partir du champ de signature trouvé par le nom de la signature (voir le paramètre SigName). Des données telles que la raison de la signature, le contact et le lieu doivent être fournies via les propriétés correspondantes de l’objet Signature sig. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); sig.setReason ( "Some reason"); sig.setContact ( "Smith"); sig.setLocation ( "New York"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", sig); pdfSign.save(); </pre> |
| [sign](#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-) | <p> Signez le document avec la signature du type indiqué qui est placée dans un champ de signature déjà présent. Avant de signer, le champ de signature doit être vide, c’est‑à‑dire qu’il ne doit pas contenir de dictionnaire de signature. Ainsi, le document PDF possède déjà un champ de signature ; vous ne devez pas fournir l’emplacement pour apposer la signature, la page et le rectangle correspondants sont récupérés à partir du champ de signature trouvé par le nom de la signature (voir le paramètre SigName). </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", "Allen", "success", "ChangSha", sig); pdfSign.save(); </pre> |
| [tryExtractCertificate](#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-java.io.OutputStream:A-) | Extrait le certificat X.509 unique de la signature sous forme de flux. |
| [tryExtractCertificate](#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2:A-) | Extrait le certificat X.509 unique de la signature. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-) | Vérifie la validité d’une signature. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Vérifie la validité d’une signature. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | Vérifie la validité d’une signature. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Vérifie la validité d’une signature. |
| [verifySignature](#verifySignature-java.lang.String-) | Vérifie la validité d’une signature. |
| [verifySignature](#verifySignature-java.lang.String-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Vérifie la validité d’une signature. |
| [verifySigned](#verifySigned-java.lang.String-) | Vérifie la validité d’une signature. La méthode est obsolète et sera supprimée dans la version 25.1. Utilisez la méthode VerifySignature à la place. |

### PdfFileSignature {#PdfFileSignature--}
```
public PdfFileSignature()
```

Le constructeur de la classe PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-com.aspose.pdf.IDocument-}
Le constructeur de la classe PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-}
Le constructeur de la classe PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-java.lang.String-}
Le constructeur de la classe PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-java.lang.String-java.lang.String-}
Le constructeur de la classe PdfFileSignature.

### bindPdf {#bindPdf-java.io.InputStream-}
Lie un flux Pdf pour l'édition.

### bindPdf {#bindPdf-java.lang.String-}
Lie un fichier Pdf pour l'édition.

### certify {#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-}
Certifie le document avec la signature MDP.

### certify {#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-}
Certifie le document avec la signature MDP qui est placée dans un champ de signature déjà présent. Avant de signer, le champ de signature doit être vide, c’est‑à‑dire qu’il ne doit pas contenir de dictionnaire de signature. Ainsi, le document PDF possède déjà un champ de signature ; vous ne devez pas fournir l’emplacement pour apposer la signature, la page correspondante et le rectangle sont récupérés à partir du champ de signature trouvé par le nom de signature (voir le paramètre sigName).

### close {#close--}
```
public void close()
```

Ferme la façade.

### containsSignature {#containsSignature--}
```
public boolean containsSignature()
```

Vérifie si le PDF possède une signature numérique ou non.

**Returns:**
Renvoie un résultat de type bool.

### containsUsageRights {#containsUsageRights--}
```
public boolean containsUsageRights()
```

Vérifie si le PDF possède des droits d’utilisation ou non.

**Returns:**
Renvoie un résultat de type bool.

### coversWholeDocument {#coversWholeDocument-com.aspose.pdf.facades.SignatureName-}
Vérifie si la signature couvre l’ensemble du document.

### coversWholeDocument {#coversWholeDocument-java.lang.String-}
Vérifie si la signature couvre l’ensemble du document.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Ferme la façade. Cette méthode est obsolète, utilisez close() à la place.

### extractCertificate {#extractCertificate-com.aspose.pdf.facades.SignatureName-}
Extrait le certificat X.509 unique de la signature sous forme de flux.

### extractCertificate {#extractCertificate-java.lang.String-}
Extrait le certificat X.509 unique de la signature sous forme de flux.

### extractImage {#extractImage-com.aspose.pdf.facades.SignatureName-}
Extrait l’image de la signature.

### extractImage {#extractImage-java.lang.String-}
Extrait l’image de la signature.

### getAccessPermissions {#getAccessPermissions--}
```
public DocMDPAccessPermissions getAccessPermissions()
```

Renvoie la valeur des autorisations d'accès du document certifié par le type de signature MDP.

**Returns:**
PdfException Si le document est en cours de certification, renvoie la valeur des autorisations d'accès ; sinon, est levée. @see com.aspose.pdf.DocMDPAccessPermissions

### getBlankSignNames {#getBlankSignNames--}
```
@Deprecated public List < String > getBlankSignNames()
```

Obtient les noms de tous les champs de signature vides.

**Returns:**
Renvoie une arrayList. @deprecated Utilisez GetBlankSignatureNames() à la place.

### getContactInfo {#getContactInfo-com.aspose.pdf.facades.SignatureName-}
Obtient les informations de contact d'une signature.

### getContactInfo {#getContactInfo-java.lang.String-}
Obtient les informations de contact d'une signature.

### getDateTime {#getDateTime-com.aspose.pdf.facades.SignatureName-}
Obtient la date et l'heure de la signature.

### getDateTime {#getDateTime-java.lang.String-}
Obtient la date et l'heure de la signature.

### getLocation {#getLocation-com.aspose.pdf.facades.SignatureName-}
Obtient l'emplacement d'une signature.

### getLocation {#getLocation-java.lang.String-}
Obtient l'emplacement d'une signature.

### getReason {#getReason-com.aspose.pdf.facades.SignatureName-}
Obtient le motif d'une signature.

### getReason {#getReason-java.lang.String-}
Obtient le motif d'une signature.

### getRevision {#getRevision-com.aspose.pdf.facades.SignatureName-}
Obtient la révision d'une signature.

### getRevision {#getRevision-java.lang.String-}
Obtient la révision d'une signature.

### getSignatureAppearance {#getSignatureAppearance--}
```
public String getSignatureAppearance()
```

Obtient une apparence graphique pour la signature. La valeur de la propriété représente le nom du fichier image.

**Returns:**
valeur String

### getSignatureAppearanceStream {#getSignatureAppearanceStream--}
```
public InputStream getSignatureAppearanceStream()
```

Obtient une apparence graphique pour la signature. La valeur de la propriété représente le flux d'image.

**Returns:**
Élément InputStream

### getSignatureNames {#getSignatureNames--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< SignatureName > getSignatureNames()
```

/ * <p> / * Obtient les noms de toutes les signatures non vides. / * </p> / * <p> / * <pre> / * string inFile=TestPath + "example1.pdf"; / * PdfFileSignature pdfSign=new PdfFileSignature(); / * pdfSign.bindPdf(inFile); / * java.util.List<String> names=pdfSign.getSignatureNames(); / * for(int i=0;i<names.size();i++) / * { / * System.out.println("signature name:" + names[i]); / * System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); / * System.out.println("revision:" + pdfSign.getRevision(names[i])); / * System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); / * System.out.println("reason:" + pdfSign.getReason(names[i])); / * System.out.println("location:" + pdfSign.getLocation(names[i])); / * System.out.println("datatime:" + pdfSign.getDateTime(names[i])); / * } / * System.out.println("totalvision:" + pdfSign.GetTotalRevision()); / * / * </pre> / *

**Returns:**
Renvoie une IList<SignatureName>. /

### getSignatureNames {#getSignatureNames-boolean-}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< SignatureName > getSignatureNames(boolean onlyActive)
```

Obtient les noms de toutes les signatures non vides. string inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); java.util.List names=pdfSign.getSignatureNames(); for(int i=0;i<names.size();i++) { System.out.println("signature name:" + names[i]); System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); System.out.println("revision:" + pdfSign.getRevision(names[i])); System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); System.out.println("reason:" + pdfSign.getReason(names[i])); System.out.println("location:" + pdfSign.getLocation(names[i])); System.out.println("datatime:" + pdfSign.getDateTime(names[i])); } System.out.println("totalvision:" + pdfSign.GetTotalRevision());

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| onlyActive |  | si vrai, renvoie uniquement les signatures actives ; sinon, renvoie toutes les signatures. |

**Returns:**
Renvoie une IList<SignatureName>.

### getSignaturesInfo {#getSignaturesInfo--}
```
public final List <com.aspose.pdf.engine.security.SignatureAlgorithmInfo> getSignaturesInfo()
```

Récupère les informations sur tous les algorithmes de signatures présents dans le document PDF.

**Returns:**
Une liste d'instances {@link SignatureAlgorithmInfo} contenant des informations sur chaque signature.

### getSignerName {#getSignerName-com.aspose.pdf.facades.SignatureName-}
Obtient le nom de la personne ou de l'organisation qui signe le document PDF.

### getSignerName {#getSignerName-java.lang.String-}
Obtient le nom de la personne ou de l'organisation qui signe le document PDF.

### getSignNames {#getSignNames--}
```
public final List < String > getSignNames()
```

<p> Obtient les noms de toutes les signatures non vides. </p> <hr>

**Returns:**
Renvoie une arrayList.

### getSignNames {#getSignNames-boolean-}
```
@Deprecated public List < String > getSignNames(boolean onlyActive)
```

<p> Obtient les noms de toutes les signatures non vides. </p> <hr> <pre> String inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); ArrayList names=pdfSign.getSignNames(true); for(int i=0;i<names.Count;i++) { System.out.println("signature name:"+(String)names[i]); System.out.println("coverswholedocument:"+pdfSign.IsCoversWholeDocument((String)names[i])); System.out.println("revision:"+pdfSign.GetRevision((String)names[i])); System.out.println("verifysigned:"+pdfSign.VerifySigned((String)names[i])); System.out.println("reason:"+pdfSign.GetReason((String)names[i])); System.out.println("location:"+pdfSign.GetLocation((String)names[i])); System.out.println("datatime:"+pdfSign.GetDateTime((String)names[i])); } System.out.println("totalvision:"+pdfSign.GetTotalRevision()); </pre>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| onlyActive |  | Valeur booléenne, si vrai, renvoie uniquement les signatures actives ; sinon, renvoie toutes les signatures. |

**Returns:**
Renvoie une arrayList. @deprecated La méthode peut produire les mêmes noms de signature, qui ne peuvent pas être distingués lors de la vérification. Utilisez getSignatureNames(boolean onlyActive) à la place.

### getTotalRevision {#getTotalRevision--}
```
public int getTotalRevision()
```

Obtient la révision totale.

**Returns:**
Renvoie le nombre total de révisions de signature.

### isCertified {#isCertified--}
```
public boolean isCertified()
```

Obtient le drapeau déterminant si un document est certifié ou non.

**Returns:**
valeur booléenne

### isContainSignature {#isContainSignature--}
```
@Deprecated public boolean isContainSignature()
```

Vérifie si le PDF possède une signature numérique ou non.

**Returns:**
Renvoie un résultat de type bool.

### isCoversWholeDocument {#isCoversWholeDocument-java.lang.String-}
Vérifie si la signature couvre l’ensemble du document.

### isLtvEnabled {#isLtvEnabled--}
```
public final boolean isLtvEnabled()
```

Obtient le drapeau LTV activé.

**Returns:**
valeur booléenne

### removeSignature {#removeSignature-com.aspose.pdf.facades.SignatureName-}
Supprime la signature selon le nom de la signature. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i]); } pdfSign.save(TestPath + "signed_removed.pdf");

### removeSignature {#removeSignature-com.aspose.pdf.facades.SignatureName-boolean-}
Supprime la signature selon le nom de la signature. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i], false); } pdfSign.save(TestPath + "signed_removed.pdf");

### removeSignature {#removeSignature-java.lang.String-}
<p> Supprime la signature selon le nom de la signature. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i)); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre>

### removeSignature {#removeSignature-java.lang.String-boolean-}
<p> Supprime la signature selon le nom de la signature. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.BindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i), false); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre>

### removeSignatures {#removeSignatures--}
```
public final void removeSignatures()
```

Supprime toutes les signatures. string inFile = TestPath + "example1.pdf"; var pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); pdfSign.removeSignatures(); pdfSign.save(TestPath + "signed_removed.pdf");

### removeUsageRights {#removeUsageRights--}
```
public void removeUsageRights()
```

Supprime l'entrée des droits d'utilisation.

### save {#save--}
```
@Deprecated public void save()
```

Enregistrez le fichier PDF signé. Le nom de fichier de sortie doit être fourni au préalable à l'aide du constructeur correspondant de PdfFileSignature.

### save {#save-java.io.OutputStream-}
Enregistrez le fichier PDF signé. Le nom de fichier de sortie doit être fourni au préalable à l'aide du constructeur correspondant de PdfFileSignature.

### save {#save-java.lang.String-}
Enregistrez le fichier PDF signé. Le nom de fichier de sortie doit être fourni au préalable à l'aide du constructeur correspondant de PdfFileSignature.

### setCertificate {#setCertificate-java.lang.String-java.lang.String-}
Définissez le fichier de certificat et le mot de passe pour la routine de signature.

### setSignatureAppearance {#setSignatureAppearance-java.lang.String-}
Définit une apparence graphique pour la signature. La valeur de la propriété représente le nom du fichier image.

### setSignatureAppearanceStream {#setSignatureAppearanceStream-java.io.InputStream-}
Définit une apparence graphique pour la signature. La valeur de la propriété représente le flux d'image.

### sign {#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Signez le document avec la signature du type indiqué.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-}
Effectuez une signature sur le document PDF.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Signez le document avec la signature du type indiqué.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Signez le document avec la signature du type indiqué qui est placée dans un champ de signature déjà présent.

### sign {#sign-java.lang.String-com.aspose.pdf.Signature-}
<p> Signez le document avec la signature du type indiqué qui est placée dans un champ de signature déjà présent. Avant de signer, le champ de signature doit être vide, c’est‑à‑dire qu’il ne doit pas contenir de dictionnaire de signature. Ainsi, le document PDF possède déjà un champ de signature ; vous ne devez pas fournir l’emplacement pour apposer la signature, la page et le rectangle correspondants sont récupérés à partir du champ de signature trouvé par le nom de la signature (voir le paramètre SigName). Des données telles que la raison de la signature, le contact et le lieu doivent être fournies via les propriétés correspondantes de l’objet Signature sig. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); sig.setReason ( "Some reason"); sig.setContact ( "Smith"); sig.setLocation ( "New York"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", sig); pdfSign.save(); </pre>

### sign {#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-}
<p> Signez le document avec la signature du type indiqué qui est placée dans un champ de signature déjà présent. Avant de signer, le champ de signature doit être vide, c’est‑à‑dire qu’il ne doit pas contenir de dictionnaire de signature. Ainsi, le document PDF possède déjà un champ de signature ; vous ne devez pas fournir l’emplacement pour apposer la signature, la page et le rectangle correspondants sont récupérés à partir du champ de signature trouvé par le nom de la signature (voir le paramètre SigName). </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", "Allen", "success", "ChangSha", sig); pdfSign.save(); </pre>

### tryExtractCertificate {#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-java.io.OutputStream:A-}
Extrait le certificat X.509 unique de la signature sous forme de flux.

### tryExtractCertificate {#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2:A-}
Extrait le certificat X.509 unique de la signature.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-}
Vérifie la validité d’une signature.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Vérifie la validité d’une signature.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
Vérifie la validité d’une signature.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Vérifie la validité d’une signature.

### verifySignature {#verifySignature-java.lang.String-}
Vérifie la validité d’une signature.

### verifySignature {#verifySignature-java.lang.String-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Vérifie la validité d’une signature.

### verifySigned {#verifySigned-java.lang.String-}
Vérifie la validité d’une signature. La méthode est obsolète et sera supprimée dans la version 25.1. Utilisez la méthode VerifySignature à la place.
