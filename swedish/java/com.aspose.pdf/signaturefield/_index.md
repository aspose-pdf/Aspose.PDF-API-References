---
title: "SignatureField"
linktitle: "SignatureField"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar signaturformulärfält."
type: docs
weight: 4510
url: /sv/java/com.aspose.pdf/signaturefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.Field, com.aspose.pdf.SignatureField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class SignatureField extends Field
```

Representerar signaturformulärfält.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SignatureField](#SignatureField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Initierar en ny instans av klassen {@code SignatureField}. |
| [SignatureField](#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Initierar en ny instans av klassen {@code SignatureField}. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [clear](#clear--) | Tar bort signaturobjektet från fältet. |
| [extractCertificate](#extractCertificate--) | Extraherar det enda X.509-certifikatet i DER-format som en ström. |
| [extractCertificateObject](#extractCertificateObject--) | Extraherar det enda X.509-certifikatobjektet. |
| [extractImage](#extractImage--) | Extraherar signaturens bild som en JPEG-kodad ström. |
| [extractImage](#extractImage-com.aspose.pdf.ImageType-) | Extraherar signaturens bild som en JPEG-kodad ström. |
| [getSignature](#getSignature--) | Hämtar signaturobjektet. Detta objekt innehåller signaturdata enligt offentliga nyckelkriptografiska standarder. Klasserna {@code PKCS1}, {@code PKCS7} och {@code PKCS7Detached} representerar alla stödda typer av signaturobjekt. |
| [sign](#sign-com.aspose.pdf.Signature-) | Signera dokumentet med detta signaturfält. |
| [sign](#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-) | Signerar dokumentet med detta signaturfält. |

### SignatureField {#SignatureField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Initierar en ny instans av klassen {@code SignatureField}.

### SignatureField {#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Initierar en ny instans av klassen {@code SignatureField}.

### clear {#clear--}
```
public void clear()
```

Tar bort signaturobjektet från fältet.

### extractCertificate {#extractCertificate--}
```
public InputStream extractCertificate()
```

Extraherar det enda X.509-certifikatet i DER-format som en ström.

**Returns:**
Om certifikatet hittades returneras ett X.509‑certifikat; annars null.

### extractCertificateObject {#extractCertificateObject--}
```
public final com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 extractCertificateObject()
```

Extraherar det enda X.509-certifikatobjektet.

**Returns:**
Om certifikatet hittades returneras ett X.509‑certifikat; annars null.

### extractImage {#extractImage--}
```
public InputStream extractImage()
```

Extraherar signaturens bild som en JPEG-kodad ström.

**Returns:**
Om bilden hittades framgångsrikt returneras ett JPEG‑kodad strömobjekt; annars null.

### extractImage {#extractImage-com.aspose.pdf.ImageType-}
Extraherar signaturens bild som en JPEG-kodad ström.

**Returns:**
Om bilden hittades framgångsrikt returneras ett JPEG‑kodad strömobjekt; annars null.

### getSignature {#getSignature--}
```
public final Signature getSignature()
```

Hämtar signaturobjektet. Detta objekt innehåller signaturdata enligt offentliga nyckelkriptografiska standarder. Klasserna {@code PKCS1}, {@code PKCS7} och {@code PKCS7Detached} representerar alla stödda typer av signaturobjekt.

**Returns:**
Signaturobjekt

### sign {#sign-com.aspose.pdf.Signature-}
Signera dokumentet med detta signaturfält.

### sign {#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-}
Signerar dokumentet med detta signaturfält.
