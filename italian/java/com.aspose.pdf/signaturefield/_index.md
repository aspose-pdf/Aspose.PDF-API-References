---
title: "SignatureField"
linktitle: "SignatureField"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta il campo modulo della firma."
type: docs
weight: 4510
url: /it/java/com.aspose.pdf/signaturefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.Field, com.aspose.pdf.SignatureField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class SignatureField extends Field
```

Rappresenta il campo modulo della firma.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SignatureField](#SignatureField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Inizializza una nuova istanza della classe {@code SignatureField}. |
| [SignatureField](#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Inizializza una nuova istanza della classe {@code SignatureField}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [clear](#clear--) | Rimuove l'oggetto firma dal campo. |
| [extractCertificate](#extractCertificate--) | Estrae il singolo certificato X.509 in formato DER come flusso. |
| [extractCertificateObject](#extractCertificateObject--) | Estrae l'oggetto certificato X.509 singolo. |
| [extractImage](#extractImage--) | Estrae l'immagine della firma come flusso codificato JPEG. |
| [extractImage](#extractImage-com.aspose.pdf.ImageType-) | Estrae l'immagine della firma come flusso codificato JPEG. |
| [getSignature](#getSignature--) | Ottiene l'oggetto firma. Questo oggetto contiene i dati della firma relativi agli standard crittografici a chiave pubblica. Le classi {@code PKCS1}, {@code PKCS7} e {@code PKCS7Detached} rappresentano tutti i tipi supportati di oggetti firma. |
| [sign](#sign-com.aspose.pdf.Signature-) | Firma il documento utilizzando questo campo firma. |
| [sign](#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-) | Firma il documento utilizzando questo campo firma. |

### SignatureField {#SignatureField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Inizializza una nuova istanza della classe {@code SignatureField}.

### SignatureField {#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Inizializza una nuova istanza della classe {@code SignatureField}.

### clear {#clear--}
```
public void clear()
```

Rimuove l'oggetto firma dal campo.

### extractCertificate {#extractCertificate--}
```
public InputStream extractCertificate()
```

Estrae il singolo certificato X.509 in formato DER come flusso.

**Returns:**
Se il certificato è stato trovato restituisce il singolo certificato X.509; altrimenti, null.

### extractCertificateObject {#extractCertificateObject--}
```
public final com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 extractCertificateObject()
```

Estrae l'oggetto certificato X.509 singolo.

**Returns:**
Se il certificato è stato trovato restituisce il singolo certificato X.509; altrimenti, null.

### extractImage {#extractImage--}
```
public InputStream extractImage()
```

Estrae l'immagine della firma come flusso codificato JPEG.

**Returns:**
Se l'immagine è stata trovata con successo restituisce l'oggetto flusso codificato JPEG; altrimenti, null.

### extractImage {#extractImage-com.aspose.pdf.ImageType-}
Estrae l'immagine della firma come flusso codificato JPEG.

**Returns:**
Se l'immagine è stata trovata con successo restituisce l'oggetto flusso codificato JPEG; altrimenti, null.

### getSignature {#getSignature--}
```
public final Signature getSignature()
```

Ottiene l'oggetto firma. Questo oggetto contiene i dati della firma relativi agli standard crittografici a chiave pubblica. Le classi {@code PKCS1}, {@code PKCS7} e {@code PKCS7Detached} rappresentano tutti i tipi supportati di oggetti firma.

**Returns:**
Oggetto firma

### sign {#sign-com.aspose.pdf.Signature-}
Firma il documento utilizzando questo campo firma.

### sign {#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-}
Firma il documento utilizzando questo campo firma.
