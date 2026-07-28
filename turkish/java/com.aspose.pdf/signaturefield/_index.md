---
title: "SignatureField"
linktitle: "SignatureField"
second_title: "Aspose.PDF for Java API Referansı"
description: "İmza form alanını temsil eder."
type: docs
weight: 4510
url: /tr/java/com.aspose.pdf/signaturefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.Field, com.aspose.pdf.SignatureField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class SignatureField extends Field
```

İmza form alanını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SignatureField](#SignatureField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Yeni bir {@code SignatureField} sınıfı örneği başlatır. |
| [SignatureField](#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Yeni bir {@code SignatureField} sınıfı örneği başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [clear](#clear--) | İmza nesnesini alandan kaldırır. |
| [extractCertificate](#extractCertificate--) | Tek X.509 sertifikasını DER formatında bir akış olarak çıkarır. |
| [extractCertificateObject](#extractCertificateObject--) | Tek X.509 sertifika nesnesini çıkarır. |
| [extractImage](#extractImage--) | İmzanın görüntüsünü jpeg kodlu akış olarak çıkarır. |
| [extractImage](#extractImage-com.aspose.pdf.ImageType-) | İmzanın görüntüsünü jpeg kodlu akış olarak çıkarır. |
| [getSignature](#getSignature--) | İmza nesnesini alır. Bu nesne, açık anahtar kriptografik standartlarıyla ilgili imza verilerini içerir. {@code PKCS1}, {@code PKCS7} ve {@code PKCS7Detached} sınıfları, desteklenen tüm imza nesnesi türlerini temsil eder. |
| [sign](#sign-com.aspose.pdf.Signature-) | Bu imza alanını kullanarak belgeyi imzalayın. |
| [sign](#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-) | Bu imza alanını kullanarak belgeyi imzalar. |

### SignatureField {#SignatureField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Yeni bir {@code SignatureField} sınıfı örneği başlatır.

### SignatureField {#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Yeni bir {@code SignatureField} sınıfı örneği başlatır.

### clear {#clear--}
```
public void clear()
```

İmza nesnesini alandan kaldırır.

### extractCertificate {#extractCertificate--}
```
public InputStream extractCertificate()
```

Tek X.509 sertifikasını DER formatında bir akış olarak çıkarır.

**Returns:**
Sertifika bulunursa tek X.509 sertifikasını döndürür; aksi takdirde null.

### extractCertificateObject {#extractCertificateObject--}
```
public final com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 extractCertificateObject()
```

Tek X.509 sertifika nesnesini çıkarır.

**Returns:**
Sertifika bulunursa tek X.509 sertifikasını döndürür; aksi takdirde null.

### extractImage {#extractImage--}
```
public InputStream extractImage()
```

İmzanın görüntüsünü jpeg kodlu akış olarak çıkarır.

**Returns:**
Görüntü başarıyla bulunursa jpeg kodlu akış nesnesini döndürür; aksi takdirde null.

### extractImage {#extractImage-com.aspose.pdf.ImageType-}
İmzanın görüntüsünü jpeg kodlu akış olarak çıkarır.

**Returns:**
Görüntü başarıyla bulunursa jpeg kodlu akış nesnesini döndürür; aksi takdirde null.

### getSignature {#getSignature--}
```
public final Signature getSignature()
```

İmza nesnesini alır. Bu nesne, açık anahtar kriptografik standartlarıyla ilgili imza verilerini içerir. {@code PKCS1}, {@code PKCS7} ve {@code PKCS7Detached} sınıfları, desteklenen tüm imza nesnesi türlerini temsil eder.

**Returns:**
İmza nesnesi

### sign {#sign-com.aspose.pdf.Signature-}
Bu imza alanını kullanarak belgeyi imzalayın.

### sign {#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-}
Bu imza alanını kullanarak belgeyi imzalar.
