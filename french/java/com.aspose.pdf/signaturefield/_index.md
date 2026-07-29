---
title: "SignatureField"
linktitle: "SignatureField"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente le champ de formulaire de signature."
type: docs
weight: 4510
url: /fr/java/com.aspose.pdf/signaturefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.Field, com.aspose.pdf.SignatureField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class SignatureField extends Field
```

Représente le champ de formulaire de signature.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SignatureField](#SignatureField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Initialise une nouvelle instance de la classe {@code SignatureField}. |
| [SignatureField](#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Initialise une nouvelle instance de la classe {@code SignatureField}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [clear](#clear--) | Supprime l'objet de signature du champ. |
| [extractCertificate](#extractCertificate--) | Extrait le certificat X.509 unique au format DER sous forme de flux. |
| [extractCertificateObject](#extractCertificateObject--) | Extrait l'objet du certificat X.509 unique. |
| [extractImage](#extractImage--) | Extrait l'image de la signature sous forme de flux encodé en JPEG. |
| [extractImage](#extractImage-com.aspose.pdf.ImageType-) | Extrait l'image de la signature sous forme de flux encodé en JPEG. |
| [getSignature](#getSignature--) | Obtient l'objet de signature. Cet objet contient les données de signature relatives aux normes cryptographiques à clé publique. Les classes {@code PKCS1}, {@code PKCS7} et {@code PKCS7Detached} représentent tous les types d'objets de signature pris en charge. |
| [sign](#sign-com.aspose.pdf.Signature-) | Signez le document en utilisant ce champ de signature. |
| [sign](#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-) | Signe le document en utilisant ce champ de signature. |

### SignatureField {#SignatureField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Initialise une nouvelle instance de la classe {@code SignatureField}.

### SignatureField {#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Initialise une nouvelle instance de la classe {@code SignatureField}.

### clear {#clear--}
```
public void clear()
```

Supprime l'objet de signature du champ.

### extractCertificate {#extractCertificate--}
```
public InputStream extractCertificate()
```

Extrait le certificat X.509 unique au format DER sous forme de flux.

**Returns:**
Si le certificat a été trouvé, renvoie le certificat X.509 unique ; sinon, null.

### extractCertificateObject {#extractCertificateObject--}
```
public final com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 extractCertificateObject()
```

Extrait l'objet du certificat X.509 unique.

**Returns:**
Si le certificat a été trouvé, renvoie le certificat X.509 unique ; sinon, null.

### extractImage {#extractImage--}
```
public InputStream extractImage()
```

Extrait l'image de la signature sous forme de flux encodé en JPEG.

**Returns:**
Si l'image a été trouvée avec succès, renvoie l'objet flux encodé en JPEG ; sinon, null.

### extractImage {#extractImage-com.aspose.pdf.ImageType-}
Extrait l'image de la signature sous forme de flux encodé en JPEG.

**Returns:**
Si l'image a été trouvée avec succès, renvoie l'objet flux encodé en JPEG ; sinon, null.

### getSignature {#getSignature--}
```
public final Signature getSignature()
```

Obtient l'objet de signature. Cet objet contient les données de signature relatives aux normes cryptographiques à clé publique. Les classes {@code PKCS1}, {@code PKCS7} et {@code PKCS7Detached} représentent tous les types d'objets de signature pris en charge.

**Returns:**
Objet Signature

### sign {#sign-com.aspose.pdf.Signature-}
Signez le document en utilisant ce champ de signature.

### sign {#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-}
Signe le document en utilisant ce champ de signature.
