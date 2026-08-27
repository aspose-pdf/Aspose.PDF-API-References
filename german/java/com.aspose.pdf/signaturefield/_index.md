---
title: "SignatureField"
linktitle: "SignatureField"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein Signatur-Formularfeld dar."
type: docs
weight: 4510
url: /de/java/com.aspose.pdf/signaturefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.Field, com.aspose.pdf.SignatureField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class SignatureField extends Field
```

Stellt ein Signatur-Formularfeld dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SignatureField](#SignatureField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Initialisiert eine neue Instanz der {@code SignatureField}-Klasse. |
| [SignatureField](#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Initialisiert eine neue Instanz der {@code SignatureField}-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [clear](#clear--) | Entfernt das Signaturobjekt aus dem Feld. |
| [extractCertificate](#extractCertificate--) | Extrahiert das einzelne X.509-Zertifikat im DER-Format als Stream. |
| [extractCertificateObject](#extractCertificateObject--) | Extrahiert das einzelne X.509-Zertifikatsobjekt. |
| [extractImage](#extractImage--) | Extrahiert das Bild der Signatur als JPEG-codierten Stream. |
| [extractImage](#extractImage-com.aspose.pdf.ImageType-) | Extrahiert das Bild der Signatur als JPEG-codierten Stream. |
| [getSignature](#getSignature--) | Liefert das Signaturobjekt. Dieses Objekt enthält Signaturdaten zu Public-Key-Kryptografiestandards. Die Klassen {@code PKCS1}, {@code PKCS7} und {@code PKCS7Detached} repräsentieren alle unterstützten Typen von Signaturobjekten. |
| [sign](#sign-com.aspose.pdf.Signature-) | Signiere das Dokument mit diesem Signaturfeld. |
| [sign](#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-) | Signiert das Dokument mit diesem Signaturfeld. |

### SignatureField {#SignatureField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Initialisiert eine neue Instanz der {@code SignatureField}-Klasse.

### SignatureField {#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Initialisiert eine neue Instanz der {@code SignatureField}-Klasse.

### clear {#clear--}
```
public void clear()
```

Entfernt das Signaturobjekt aus dem Feld.

### extractCertificate {#extractCertificate--}
```
public InputStream extractCertificate()
```

Extrahiert das einzelne X.509-Zertifikat im DER-Format als Stream.

**Returns:**
Falls ein Zertifikat gefunden wurde, wird das einzelne X.509-Zertifikat zurückgegeben; andernfalls null.

### extractCertificateObject {#extractCertificateObject--}
```
public final com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 extractCertificateObject()
```

Extrahiert das einzelne X.509-Zertifikatsobjekt.

**Returns:**
Falls ein Zertifikat gefunden wurde, wird das einzelne X.509-Zertifikat zurückgegeben; andernfalls null.

### extractImage {#extractImage--}
```
public InputStream extractImage()
```

Extrahiert das Bild der Signatur als JPEG-codierten Stream.

**Returns:**
Falls das Bild erfolgreich gefunden wurde, wird das JPEG-codierte Stream-Objekt zurückgegeben; andernfalls null.

### extractImage {#extractImage-com.aspose.pdf.ImageType-}
Extrahiert das Bild der Signatur als JPEG-codierten Stream.

**Returns:**
Falls das Bild erfolgreich gefunden wurde, wird das JPEG-codierte Stream-Objekt zurückgegeben; andernfalls null.

### getSignature {#getSignature--}
```
public final Signature getSignature()
```

Liefert das Signaturobjekt. Dieses Objekt enthält Signaturdaten zu Public-Key-Kryptografiestandards. Die Klassen {@code PKCS1}, {@code PKCS7} und {@code PKCS7Detached} repräsentieren alle unterstützten Typen von Signaturobjekten.

**Returns:**
Signaturobjekt

### sign {#sign-com.aspose.pdf.Signature-}
Signiere das Dokument mit diesem Signaturfeld.

### sign {#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-}
Signiert das Dokument mit diesem Signaturfeld.
