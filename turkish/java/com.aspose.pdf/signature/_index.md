---
title: "Signature"
linktitle: "Signature"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF belgesindeki imza nesnesini temsil eden soyut bir sınıf. İmzalar, imza nesnelerinin değerlerine sahip alanlardır; sonuncusu, doğrulama için kullanılan verileri içerir."
type: docs
weight: 4490
url: /tr/java/com.aspose.pdf/signature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Signature

```
public abstract class Signature extends Object
```

PDF belgesindeki imza nesnesini temsil eden soyut bir sınıf. İmzalar, imza nesnelerinin değerlerine sahip alanlardır; sonuncusu belge geçerliliğini doğrulamak için kullanılan verileri içerir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Signature](#Signature--) | Yeni {@code Signature} sınıfının bir örneğini başlatır. |
| [Signature](#Signature-java.io.InputStream-java.lang.String-) | Yeni {@code Signature} sınıfının bir örneğini başlatır. |
| [Signature](#Signature-java.lang.String-java.lang.String-) | Yeni {@code Signature} sınıfının bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [close](#close--) | Gerekirse geçici akışları kapatan yıkıcı. |
| [getAuthority](#getAuthority--) | Belgeyi imzalayan kişi ya da otoritenin adı. |
| [getByteRange](#getByteRange--) | Özet hesaplaması için tam bayt aralığını tanımlayacak (başlangıç bayt ofseti, bayt cinsinden uzunluk) tamsayı çiftlerinden oluşan diziyi al. |
| [getContactInfo](#getContactInfo--) | İmzayı doğrulamak için alıcının imzalayanla iletişime geçmesini sağlayan, imzalayan tarafından sağlanan bilgileri al, ör. bir telefon numarası. |
| [getCustomAppearance](#getCustomAppearance--) | Özel görünümü alır/ayarlar. |
| [getCustomSign](#getCustomSign--) | Belgeyi özel olarak özetleyip imzalayan temsilci (Beta). {@code Temsilci içinde belgeyi özetlediğiniz ve imzaladığınız algoritma, sertifikanın özel anahtarının türüyle eşleşmelidir.} |
| [getCustomSignHash](#getCustomSignHash--) | Belge özeti üzerinde özel imza yapan temsilci (Beta). {@code Temsilci içinde özeti imzaladığınız algoritma, sertifikanın özel anahtarının türüyle eşleşmelidir.} |
| [getDate](#getDate--) | İmzalama zamanını al. |
| [getDefaultSignatureLength](#getDefaultSignatureLength--) | İmza verisinin bayt cinsinden varsayılan uzunluğunu alır veya ayarlar. Bu, imzanın bayt cinsinden uzunluğunun bir tahminidir. {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) parametresi ayarlıysa, {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) aracılığıyla imzalamak için kullanılır. Varsayılan değer 3000. |
| [getImageInternal](#getImageInternal--) | Görüntü akışını alır. Yalnızca dahili kullanım için |
| [getLocation](#getLocation--) | İmzalamanın CPU ana bilgisayar adını veya fiziksel konumunu alır. |
| [getOcspSettings](#getOcspSettings--) | ocsp ayarlarını alır/ayarlar. |
| [getReason](#getReason--) | İmzalamanın nedenini alır, örneğin (Kabul ettim!, Pip B.). |
| [getSignatureAlgorithmInfo](#getSignatureAlgorithmInfo--) | İmzada kullanılan imza algoritması hakkında bilgileri alır. |
| [getSignatureReferences](#getSignatureReferences--) | İmza Referanslarını al |
| [getTimestampSettings](#getTimestampSettings--) | Zaman damgası ayarlarını alır. |
| [getUseLtv](#getUseLtv--) | ltv doğrulama bayrağını alır/ayarlar. |
| [isAvoidEstimatingSignatureLength](#isAvoidEstimatingSignatureLength--) | İmza uzunluğunu tahmin etmeyi önleyip önlemeyeceğini belirten bir seçeneği alır ve ayarlar. İmza belgesi oluşturulmadan önce imza uzunluğunu tahmin etmeyi önler. {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) ve {@code ExternalSignature} aracılığıyla imzalamak için kullanılır. {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}) değerinden daha uzun bir imza döndürürse, {@code SignatureLengthMismatchException} fırlatılır. Varsayılan değer {@code false}. |
| [isShowProperties](#isShowProperties--) | İmza özelliklerini gösterme/gizleme zorunluluğu. ShowProperties true olduğunda imza alanı önceden tanımlı bir görünüm formatına sahiptir (temsil eden dizeler): ------------------------------------------- Dijital olarak imzalayan {certificate subject} Tarih: {signature.Date} Neden: {signature.Reason} Konum: {signature.Location} ------------------------------------------- burada {X}, X değerinin yer tutucusudur. Ayrıca imzanın bir resmi olabilir; bu durumda listelenen dizeler resmin üzerine yerleştirilir. ShowProperties varsayılan olarak true'tur. |
| [setAuthority](#setAuthority-java.lang.String-) | Belgeyi imzalayan kişi ya da otoritenin adını ayarlar. |
| [setAvoidEstimatingSignatureLength](#setAvoidEstimatingSignatureLength-boolean-) | İmza uzunluğunu tahmin etmeyi önleyip önlemeyeceğini belirten bir seçeneği alır ve ayarlar. İmza belgesi oluşturulmadan önce imza uzunluğunu tahmin etmeyi önler. {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) ve {@code ExternalSignature} aracılığıyla imzalamak için kullanılır. {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}) değerinden daha uzun bir imza döndürürse, {@code SignatureLengthMismatchException} fırlatılır. Varsayılan değer {@code false}. |
| [setContactInfo](#setContactInfo-java.lang.String-) | İmzayı doğrulamak için alıcının imzalayanla iletişime geçmesini sağlayan, imzalayan tarafından sağlanan bilgileri ayarlar, ör. bir telefon numarası. |
| [setCustomAppearance](#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-) | Özel görünümü alır/ayarlar. |
| [setCustomSign](#setCustomSign-com.aspose.pdf.CustomSign-) | Belgeyi özel olarak özetleyip imzalayan temsilci (Beta). {@code Temsilci içinde belgeyi özetlediğiniz ve imzaladığınız algoritma, sertifikanın özel anahtarının türüyle eşleşmelidir.} |
| [setCustomSignHash](#setCustomSignHash-com.aspose.pdf.SignHash-) | Belge özeti üzerinde özel imza yapan temsilci (Beta). {@code Temsilci içinde özeti imzaladığınız algoritma, sertifikanın özel anahtarının türüyle eşleşmelidir.} |
| [setDate](#setDate-java.util.Date-) | İmzalama zamanını ayarlar. |
| [setDefaultSignatureLength](#setDefaultSignatureLength-int-) | İmza verisinin bayt cinsinden varsayılan uzunluğunu alır veya ayarlar. Bu, imzanın bayt cinsinden uzunluğunun bir tahminidir. {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) parametresi ayarlıysa, {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) aracılığıyla imzalamak için kullanılır. Varsayılan değer 3000. |
| [setImage](#setImage-java.io.InputStream-) | Görüntü akışını ayarlar. |
| [setImageInternal](#setImageInternal-com.aspose.ms.System.IO.Stream-) |  |
| [setLocation](#setLocation-java.lang.String-) | İmzalamanın CPU ana bilgisayar adını veya fiziksel konumunu ayarlar. |
| [setOcspSettings](#setOcspSettings-com.aspose.pdf.OcspSettings-) | ocsp ayarlarını alır/ayarlar. |
| [setReason](#setReason-java.lang.String-) | İmzalama nedeni ayarlar, örneğin (I agreed!, Pip B.). |
| [setShowProperties](#setShowProperties-boolean-) | İmza özelliklerini gösterme/gizleme zorunluluğu. ShowProperties true olduğunda imza alanı önceden tanımlı bir görünüm formatına sahiptir (temsil eden dizeler): ------------------------------------------- Dijital olarak imzalayan {certificate subject} Tarih: {signature.Date} Neden: {signature.Reason} Konum: {signature.Location} ------------------------------------------- burada {X}, X değerinin yer tutucusudur. Ayrıca imzanın bir resmi olabilir; bu durumda listelenen dizeler resmin üzerine yerleştirilir. ShowProperties varsayılan olarak true'tur. |
| [setTimestampSettings](#setTimestampSettings-com.aspose.pdf.TimestampSettings-) | Zaman damgası ayarlarını ayarlar. |
| [setUseLtv](#setUseLtv-boolean-) | ltv doğrulama bayrağını alır/ayarlar. |
| [verify](#verify--) | Bu imzayla ilgili belgeyi doğrular ve belge geçerliyse true, aksi takdirde false döndürür. |
| [verify](#verify-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Bu imzayla ilgili belgeyi doğrular ve belge geçerliyse true, aksi takdirde false döndürür. |
| [verify](#verify-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Bu imzayla ilgili belgeyi doğrular ve belge geçerliyse true, aksi takdirde false döndürür. |

### Signature {#Signature--}
```
public Signature()
```

Yeni {@code Signature} sınıfının bir örneğini başlatır.

### Signature {#Signature-java.io.InputStream-java.lang.String-}
Yeni {@code Signature} sınıfının bir örneğini başlatır.

### Signature {#Signature-java.lang.String-java.lang.String-}
Yeni {@code Signature} sınıfının bir örneğini başlatır.

### close {#close--}
```
public void close()
```

Gerekirse geçici akışları kapatan yıkıcı.

### getAuthority {#getAuthority--}
```
public final String getAuthority()
```

Belgeyi imzalayan kişi ya da otoritenin adı.

**Returns:**
String değeri

### getByteRange {#getByteRange--}
```
public int[] getByteRange()
```

Özet hesaplaması için tam bayt aralığını tanımlayacak (başlangıç bayt ofseti, bayt cinsinden uzunluk) tamsayı çiftlerinden oluşan diziyi al.

**Returns:**
int değer dizisi

### getContactInfo {#getContactInfo--}
```
public String getContactInfo()
```

İmzayı doğrulamak için alıcının imzalayanla iletişime geçmesini sağlayan, imzalayan tarafından sağlanan bilgileri al, ör. bir telefon numarası.

**Returns:**
String değeri

### getCustomAppearance {#getCustomAppearance--}
```
public final SignatureCustomAppearance getCustomAppearance()
```

Özel görünümü alır/ayarlar.

**Returns:**
SignatureCustomAppearance örneği

### getCustomSign {#getCustomSign--}
```
public final CustomSign getCustomSign()
```

Belgeyi özel olarak özetleyip imzalayan temsilci (Beta). {@code Temsilci içinde belgeyi özetlediğiniz ve imzaladığınız algoritma, sertifikanın özel anahtarının türüyle eşleşmelidir.}

**Returns:**
SignHash örneği

### getCustomSignHash {#getCustomSignHash--}
```
public final SignHash getCustomSignHash()
```

Belge özeti üzerinde özel imza yapan temsilci (Beta). {@code Temsilci içinde özeti imzaladığınız algoritma, sertifikanın özel anahtarının türüyle eşleşmelidir.}

**Returns:**
SignHash örneği

### getDate {#getDate--}
```
public Date getDate()
```

İmzalama zamanını al.

**Returns:**
Date değeri

### getDefaultSignatureLength {#getDefaultSignatureLength--}
```
public final int getDefaultSignatureLength()
```

İmza verisinin bayt cinsinden varsayılan uzunluğunu alır veya ayarlar. Bu, imzanın bayt cinsinden uzunluğunun bir tahminidir. {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) parametresi ayarlıysa, {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) aracılığıyla imzalamak için kullanılır. Varsayılan değer 3000.

**Returns:**
int değer

### getImageInternal {#getImageInternal--}
```
public com.aspose.ms.System.IO.Stream getImageInternal()
```

Görüntü akışını alır. Yalnızca dahili kullanım için

**Returns:**
Stream nesnesi

### getLocation {#getLocation--}
```
public String getLocation()
```

İmzalamanın CPU ana bilgisayar adını veya fiziksel konumunu alır.

**Returns:**
String değeri

### getOcspSettings {#getOcspSettings--}
```
public OcspSettings getOcspSettings()
```

ocsp ayarlarını alır/ayarlar.

**Returns:**
OcspSettings örneği

### getReason {#getReason--}
```
public String getReason()
```

İmzalamanın nedenini alır, örneğin (Kabul ettim!, Pip B.).

**Returns:**
String değeri

### getSignatureAlgorithmInfo {#getSignatureAlgorithmInfo--}
```
public final com.aspose.pdf.engine.security.SignatureAlgorithmInfo getSignatureAlgorithmInfo()
```

İmzada kullanılan imza algoritması hakkında bilgileri alır.

**Returns:**
İmza algoritması hakkında detayları içeren { SignatureAlgorithmInfo} örneği.

### getSignatureReferences {#getSignatureReferences--}
```
public List <com.aspose.pdf.engine.security.impl.signatures.SignatureReference> getSignatureReferences()
```

İmza Referanslarını al

**Returns:**
{@code java.util.List<SignatureReference> nesnesi}

### getTimestampSettings {#getTimestampSettings--}
```
public TimestampSettings getTimestampSettings()
```

Zaman damgası ayarlarını alır.

**Returns:**
TimestampSettings

### getUseLtv {#getUseLtv--}
```
public final boolean getUseLtv()
```

ltv doğrulama bayrağını alır/ayarlar.

**Returns:**
boolean değer

### isAvoidEstimatingSignatureLength {#isAvoidEstimatingSignatureLength--}
```
public final boolean isAvoidEstimatingSignatureLength()
```

İmza uzunluğunu tahmin etmeyi önleyip önlemeyeceğini belirten bir seçeneği alır ve ayarlar. İmza belgesi oluşturulmadan önce imza uzunluğunu tahmin etmeyi önler. {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) ve {@code ExternalSignature} aracılığıyla imzalamak için kullanılır. {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}) değerinden daha uzun bir imza döndürürse, {@code SignatureLengthMismatchException} fırlatılır. Varsayılan değer {@code false}.

**Returns:**
boolean değer

### isShowProperties {#isShowProperties--}
```
public boolean isShowProperties()
```

İmza özelliklerini gösterme/gizleme zorunluluğu. ShowProperties true olduğunda imza alanı önceden tanımlı bir görünüm formatına sahiptir (temsil eden dizeler): ------------------------------------------- Dijital olarak imzalayan {certificate subject} Tarih: {signature.Date} Neden: {signature.Reason} Konum: {signature.Location} ------------------------------------------- burada {X}, X değerinin yer tutucusudur. Ayrıca imzanın bir resmi olabilir; bu durumda listelenen dizeler resmin üzerine yerleştirilir. ShowProperties varsayılan olarak true'tur.

**Returns:**
boolean değer

### setAuthority {#setAuthority-java.lang.String-}
Belgeyi imzalayan kişi ya da otoritenin adını ayarlar.

### setAvoidEstimatingSignatureLength {#setAvoidEstimatingSignatureLength-boolean-}
```
public final void setAvoidEstimatingSignatureLength(boolean value)
```

İmza uzunluğunu tahmin etmeyi önleyip önlemeyeceğini belirten bir seçeneği alır ve ayarlar. İmza belgesi oluşturulmadan önce imza uzunluğunu tahmin etmeyi önler. {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) ve {@code ExternalSignature} aracılığıyla imzalamak için kullanılır. {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}) değerinden daha uzun bir imza döndürürse, {@code SignatureLengthMismatchException} fırlatılır. Varsayılan değer {@code false}.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setContactInfo {#setContactInfo-java.lang.String-}
İmzayı doğrulamak için alıcının imzalayanla iletişime geçmesini sağlayan, imzalayan tarafından sağlanan bilgileri ayarlar, ör. bir telefon numarası.

### setCustomAppearance {#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-}
Özel görünümü alır/ayarlar.

### setCustomSign {#setCustomSign-com.aspose.pdf.CustomSign-}
Belgeyi özel olarak özetleyip imzalayan temsilci (Beta). {@code Temsilci içinde belgeyi özetlediğiniz ve imzaladığınız algoritma, sertifikanın özel anahtarının türüyle eşleşmelidir.}

### setCustomSignHash {#setCustomSignHash-com.aspose.pdf.SignHash-}
Belge özeti üzerinde özel imza yapan temsilci (Beta). {@code Temsilci içinde özeti imzaladığınız algoritma, sertifikanın özel anahtarının türüyle eşleşmelidir.}

### setDate {#setDate-java.util.Date-}
İmzalama zamanını ayarlar.

### setDefaultSignatureLength {#setDefaultSignatureLength-int-}
```
public final void setDefaultSignatureLength(int value)
```

İmza verisinin bayt cinsinden varsayılan uzunluğunu alır veya ayarlar. Bu, imzanın bayt cinsinden uzunluğunun bir tahminidir. {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) parametresi ayarlıysa, {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) aracılığıyla imzalamak için kullanılır. Varsayılan değer 3000.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setImage {#setImage-java.io.InputStream-}
Görüntü akışını ayarlar.

### setImageInternal {#setImageInternal-com.aspose.ms.System.IO.Stream-}


### setLocation {#setLocation-java.lang.String-}
İmzalamanın CPU ana bilgisayar adını veya fiziksel konumunu ayarlar.

### setOcspSettings {#setOcspSettings-com.aspose.pdf.OcspSettings-}
ocsp ayarlarını alır/ayarlar.

### setReason {#setReason-java.lang.String-}
İmzalama nedeni ayarlar, örneğin (I agreed!, Pip B.).

### setShowProperties {#setShowProperties-boolean-}
```
public void setShowProperties(boolean value)
```

İmza özelliklerini gösterme/gizleme zorunluluğu. ShowProperties true olduğunda imza alanı önceden tanımlı bir görünüm formatına sahiptir (temsil eden dizeler): ------------------------------------------- Dijital olarak imzalayan {certificate subject} Tarih: {signature.Date} Neden: {signature.Reason} Konum: {signature.Location} ------------------------------------------- burada {X}, X değerinin yer tutucusudur. Ayrıca imzanın bir resmi olabilir; bu durumda listelenen dizeler resmin üzerine yerleştirilir. ShowProperties varsayılan olarak true'tur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setTimestampSettings {#setTimestampSettings-com.aspose.pdf.TimestampSettings-}
Zaman damgası ayarlarını ayarlar.

### setUseLtv {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```

ltv doğrulama bayrağını alır/ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### verify {#verify--}
```
public boolean verify()
```

Bu imzayla ilgili belgeyi doğrular ve belge geçerliyse true, aksi takdirde false döndürür.

**Returns:**
belge geçerliyse true.

### verify {#verify-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Bu imzayla ilgili belgeyi doğrular ve belge geçerliyse true, aksi takdirde false döndürür.

**Returns:**
belge geçerliyse true.

### verify {#verify-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Bu imzayla ilgili belgeyi doğrular ve belge geçerliyse true, aksi takdirde false döndürür.

**Returns:**
belge geçerliyse true.
