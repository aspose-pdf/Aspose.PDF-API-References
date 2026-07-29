---
title: "PdfFileSignature"
linktitle: "PdfFileSignature"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bir PDF dosyasını sertifika ile imzalamak için bir sınıfı temsil eder."
type: docs
weight: 530
url: /tr/java/com.aspose.pdf.facades/pdffilesignature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSignature, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSignature, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSignature

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSignature extends SaveableFacade
```

Bir PDF dosyasını sertifika ile imzalamak için bir sınıfı temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfFileSignature](#PdfFileSignature--) | PdfFileSignature sınıfının yapıcısı. |
| [PdfFileSignature](#PdfFileSignature-com.aspose.pdf.IDocument-) | PdfFileSignature sınıfının yapıcısı. |
| [PdfFileSignature](#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-) | PdfFileSignature sınıfının yapıcısı. |
| [PdfFileSignature](#PdfFileSignature-java.lang.String-) | PdfFileSignature sınıfının yapıcısı. |
| [PdfFileSignature](#PdfFileSignature-java.lang.String-java.lang.String-) | PdfFileSignature sınıfının yapıcısı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | Düzenleme için bir Pdf akışını bağlar. |
| [bindPdf](#bindPdf-java.lang.String-) | Düzenleme için bir Pdf dosyasını bağlar. |
| [certify](#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-) | Belgeyi, zaten mevcut olan imza alanına yerleştirilmiş MDP imzası ile onaylar. İmzalamadan önce imza alanı boş olmalıdır, yani alan imza sözlüğü içermemelidir. Bu nedenle pdf belgesinde zaten bir imza alanı vardır, imzayı damgalamak için bir yer sağlamamalısınız; ilgili sayfa ve dikdörtgen, imza adı (sigName parametresine bakın) ile bulunan imza alanından alınır. |
| [certify](#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-) | Pdf'nin dijital imzası olup olmadığını kontrol eder. |
| [close](#close--) | Facade'i kapatır. |
| [containsSignature](#containsSignature--) | Pdf'nin kullanım hakları olup olmadığını kontrol eder. |
| [containsUsageRights](#containsUsageRights--) | İmzanın tüm belgeyi kapsayıp kapsamadığını kontrol eder. |
| [coversWholeDocument](#coversWholeDocument-com.aspose.pdf.facades.SignatureName-) | Facade'i kapatır. Bu yöntem artık kullanılmamaktadır, yerine close() kullanın. |
| [coversWholeDocument](#coversWholeDocument-java.lang.String-) | Facade'i kapatır. Bu yöntem artık kullanılmamaktadır, yerine close() kullanın. |
| [dispose](#dispose--) | İmzanın tek X.509 sertifikasını akış olarak çıkarır. |
| [extractCertificate](#extractCertificate-com.aspose.pdf.facades.SignatureName-) | İmzanın görüntüsünü çıkarır. |
| [extractCertificate](#extractCertificate-java.lang.String-) | İmzanın görüntüsünü çıkarır. |
| [extractImage](#extractImage-com.aspose.pdf.facades.SignatureName-) | İmzanın görüntüsünü çıkarır. |
| [extractImage](#extractImage-java.lang.String-) | İmzanın görüntüsünü çıkarır. |
| [getAccessPermissions](#getAccessPermissions--) | MDP imza türü tarafından sertifikalı belgenin erişim izinleri değerini döndürür. |
| [getBlankSignNames](#getBlankSignNames--) | Tüm boş imza alanlarının adlarını alır. |
| [getContactInfo](#getContactInfo-com.aspose.pdf.facades.SignatureName-) | Bir imzanın iletişim bilgilerini alır. |
| [getContactInfo](#getContactInfo-java.lang.String-) | Bir imzanın iletişim bilgilerini alır. |
| [getDateTime](#getDateTime-com.aspose.pdf.facades.SignatureName-) | İmzanın tarih ve saat bilgisini alır. |
| [getDateTime](#getDateTime-java.lang.String-) | İmzanın tarih ve saat bilgisini alır. |
| [getLocation](#getLocation-com.aspose.pdf.facades.SignatureName-) | İmzanın konumunu alır. |
| [getLocation](#getLocation-java.lang.String-) | İmzanın konumunu alır. |
| [getReason](#getReason-com.aspose.pdf.facades.SignatureName-) | İmzanın nedenini alır. |
| [getReason](#getReason-java.lang.String-) | İmzanın nedenini alır. |
| [getRevision](#getRevision-com.aspose.pdf.facades.SignatureName-) | İmzanın revizyonunu alır. |
| [getRevision](#getRevision-java.lang.String-) | İmzanın revizyonunu alır. |
| [getSignatureAppearance](#getSignatureAppearance--) | İmza için grafik görünüm alır. Özellik değeri görüntü dosya adını temsil eder. |
| [getSignatureAppearanceStream](#getSignatureAppearanceStream--) | İmza için grafik görünüm alır. Özellik değeri görüntü akışını temsil eder. |
| [getSignatureNames](#getSignatureNames--) | / * <p> / * Boş olmayan tüm imzaların adlarını alır. / * </p> / * <p> / * <pre> / * string inFile=TestPath + \"example1.pdf\"; / * PdfFileSignature pdfSign=new PdfFileSignature(); / * pdfSign.bindPdf(inFile); / * java.util.List<String> names=pdfSign.getSignatureNames(); / * for(int i=0;i<names.size();i++) / * { / * System.out.println(\"signature name:\" + names[i]); / * System.out.println(\"coverswholedocument:\" + pdfSign.coversWholeDocument(names[i])); / * System.out.println(\"revision:\" + pdfSign.getRevision(names[i])); / * System.out.println(\"verifysigned:\" + pdfSign.verifySignature(names[i])); / * System.out.println(\"reason:\" + pdfSign.getReason(names[i])); / * System.out.println(\"location:\" + pdfSign.getLocation(names[i])); / * System.out.println(\"datatime:\" + pdfSign.getDateTime(names[i])); / * } / * System.out.println(\"totalvision:\" + pdfSign.GetTotalRevision()); / * / * </pre> / * |
| [getSignatureNames](#getSignatureNames-boolean-) | Boş olmayan tüm imzaların adlarını alır. string inFile=TestPath + \"example1.pdf\"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); java.util.List names=pdfSign.getSignatureNames(); for(int i=0;i<names.size();i++) { System.out.println(\"signature name:\" + names[i]); System.out.println(\"coverswholedocument:\" + pdfSign.coversWholeDocument(names[i])); System.out.println(\"revision:\" + pdfSign.getRevision(names[i])); System.out.println(\"verifysigned:\" + pdfSign.verifySignature(names[i])); System.out.println(\"reason:\" + pdfSign.getReason(names[i])); System.out.println(\"location:\" + pdfSign.getLocation(names[i])); System.out.println(\"datatime:\" + pdfSign.getDateTime(names[i])); } System.out.println(\"totalvision:\" + pdfSign.GetTotalRevision()); |
| [getSignaturesInfo](#getSignaturesInfo--) | PDF belgesinde bulunan tüm imza algoritmaları hakkında bilgi alır. |
| [getSignerName](#getSignerName-com.aspose.pdf.facades.SignatureName-) | PDF belgesini imzalayan kişi veya kuruluşun adını alır. |
| [getSignerName](#getSignerName-java.lang.String-) | PDF belgesini imzalayan kişi veya kuruluşun adını alır. |
| [getSignNames](#getSignNames--) | <p> Boş olmayan tüm imzaların adlarını alır. </p> <hr> |
| [getSignNames](#getSignNames-boolean-) | <p> Boş olmayan tüm imzaların adlarını alır. </p> <hr> <pre> String inFile=TestPath + \"example1.pdf\"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); ArrayList names=pdfSign.getSignNames(true); for(int i=0;i<names.Count;i++) { System.out.println(\"signature name:\"+(String)names[i]); System.out.println(\"coverswholedocument:\"+pdfSign.IsCoversWholeDocument((String)names[i])); System.out.println(\"revision:\"+pdfSign.GetRevision((String)names[i])); System.out.println(\"verifysigned:\"+pdfSign.VerifySigned((String)names[i])); System.out.println(\"reason:\"+pdfSign.GetReason((String)names[i])); System.out.println(\"location:\"+pdfSign.GetLocation((String)names[i])); System.out.println(\"datatime:\"+pdfSign.GetDateTime((String)names[i])); } System.out.println(\"totalvision:\"+pdfSign.GetTotalRevision()); </pre> |
| [getTotalRevision](#getTotalRevision--) | Toplam revizyonu alır. |
| [isCertified](#isCertified--) | Bir belgenin sertifikalı olup olmadığını belirleyen bayrağı alır. |
| [isContainSignature](#isContainSignature--) | Pdf'nin kullanım hakları olup olmadığını kontrol eder. |
| [isCoversWholeDocument](#isCoversWholeDocument-java.lang.String-) | Facade'i kapatır. Bu yöntem artık kullanılmamaktadır, yerine close() kullanın. |
| [isLtvEnabled](#isLtvEnabled--) | LTV etkin bayrağını alır. |
| [removeSignature](#removeSignature-com.aspose.pdf.facades.SignatureName-) | İmzanın adına göre imzayı kaldır. string inFile = TestPath + \"example1.pdf\"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i]); } pdfSign.save(TestPath + \"signed_removed.pdf\"); |
| [removeSignature](#removeSignature-com.aspose.pdf.facades.SignatureName-boolean-) | İmzanın adına göre imzayı kaldırır. string inFile = TestPath + \"example1.pdf\"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i], false); } pdfSign.save(TestPath + \"signed_removed.pdf\"); |
| [removeSignature](#removeSignature-java.lang.String-) | <p> İmzanın adına göre imzayı kaldır. </p> <hr> <pre> String inFile = TestPath + \"example1.pdf\"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i)); } pdfSign.save(TestPath + \"signed_removed.pdf\"); </pre> |
| [removeSignature](#removeSignature-java.lang.String-boolean-) | <p> İmzanın adına göre imzayı kaldırır. </p> <hr> <pre> String inFile = TestPath + \"example1.pdf\"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.BindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i), false); } pdfSign.save(TestPath + \"signed_removed.pdf\"); </pre> |
| [removeSignatures](#removeSignatures--) | Tüm imzaları kaldırır. string inFile = TestPath + \"example1.pdf\"; var pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); pdfSign.removeSignatures(); pdfSign.save(TestPath + \"signed_removed.pdf\"); |
| [removeUsageRights](#removeUsageRights--) | Kullanım hakları girişini kaldırır. |
| [save](#save--) | İmzalı pdf dosyasını kaydet. Çıktı dosya adı, ilgili PdfFileSignature yapıcısı yardımıyla önceden sağlanmalıdır. |
| [save](#save-java.io.OutputStream-) | İmzalı pdf dosyasını kaydet. Çıktı dosya adı, ilgili PdfFileSignature yapıcısı yardımıyla önceden sağlanmalıdır. |
| [save](#save-java.lang.String-) | İmzalı pdf dosyasını kaydet. Çıktı dosya adı, ilgili PdfFileSignature yapıcısı yardımıyla önceden sağlanmalıdır. |
| [setCertificate](#setCertificate-java.lang.String-java.lang.String-) | İmzalama rutini için sertifika dosyasını ve şifreyi ayarla. |
| [setSignatureAppearance](#setSignatureAppearance-java.lang.String-) | İmza için grafik görünüm ayarlar. Özellik değeri görüntü dosya adını temsil eder. |
| [setSignatureAppearanceStream](#setSignatureAppearanceStream-java.io.InputStream-) | İmza için grafik görünüm ayarlar. Özellik değeri görüntü akışını temsil eder. |
| [sign](#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Belirtilen tipteki imza ile belgeyi imzala. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-) | Pdf belgesine bir imza ekle. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Belirtilen tipteki imza ile belgeyi imzala. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Belirtilen tipteki imza, zaten mevcut imza alanına yerleştirilmiş olarak belgeyi imzala. |
| [sign](#sign-java.lang.String-com.aspose.pdf.Signature-) | <p> Belirtilen tipteki imza, zaten mevcut imza alanına yerleştirilmiş olarak belgeyi imzala. İmzalamadan önce imza alanı boş olmalıdır, yani alan imza sözlüğü içermemelidir. Bu nedenle pdf belgesinde zaten bir imza alanı vardır, imzayı damgalamak için konum sağlamamalısınız; ilgili sayfa ve dikdörtgen, imza adıyla bulunan imza alanından alınır (SigName parametresine bakın). İmza nedeni, iletişim ve konum gibi veriler, Signature nesnesi sig'in ilgili özellikleriyle sağlanmalıdır. </p> <hr> <pre> String inFile = TestPath + \"example1.pdf\"; String outFile = TestPath + \"signature.pdf\"; PKCS1 sig = new PKCS1(\"certificate.pfx\", \"password\"); sig.setReason ( \"Some reason\"); sig.setContact ( \"Smith\"); sig.setLocation ( \"New York\"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + \"butterfly.jpg\"); pdfSign.sign(\"Signature1\", sig); pdfSign.save(); </pre> |
| [sign](#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-) | <p> Belirtilen tipteki imza, zaten mevcut imza alanına yerleştirilmiş olarak belgeyi imzala. İmzalamadan önce imza alanı boş olmalıdır, yani alan imza sözlüğü içermemelidir. Bu nedenle pdf belgesinde zaten bir imza alanı vardır, imzayı damgalamak için konum sağlamamalısınız; ilgili sayfa ve dikdörtgen, imza adıyla bulunan imza alanından alınır (SigName parametresine bakın). </p> <hr> <pre> String inFile = TestPath + \"example1.pdf\"; String outFile = TestPath + \"signature.pdf\"; PKCS1 sig = new PKCS1(\"certificate.pfx\", \"password\"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + \"butterfly.jpg\"); pdfSign.sign(\"Signature1\", \"Allen\", \"success\", \"ChangSha\", sig); pdfSign.save(); </pre> |
| [tryExtractCertificate](#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-java.io.OutputStream:A-) | İmzanın görüntüsünü çıkarır. |
| [tryExtractCertificate](#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2:A-) | İmzanın tek X.509 sertifikasını çıkarır. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-) | Bir imzanın geçerliliğini kontrol eder. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Bir imzanın geçerliliğini kontrol eder. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | Bir imzanın geçerliliğini kontrol eder. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Bir imzanın geçerliliğini kontrol eder. |
| [verifySignature](#verifySignature-java.lang.String-) | Bir imzanın geçerliliğini kontrol eder. |
| [verifySignature](#verifySignature-java.lang.String-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Bir imzanın geçerliliğini kontrol eder. |
| [verifySigned](#verifySigned-java.lang.String-) | Bir imzanın geçerliliğini kontrol eder. Metod kullanımdan kaldırılmıştır ve 25.1 sürümünde silinecektir. Bunun yerine VerifySignature metodunu kullanın. |

### PdfFileSignature {#PdfFileSignature--}
```
public PdfFileSignature()
```

PdfFileSignature sınıfının yapıcısı.

### PdfFileSignature {#PdfFileSignature-com.aspose.pdf.IDocument-}
PdfFileSignature sınıfının yapıcısı.

### PdfFileSignature {#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-}
PdfFileSignature sınıfının yapıcısı.

### PdfFileSignature {#PdfFileSignature-java.lang.String-}
PdfFileSignature sınıfının yapıcısı.

### PdfFileSignature {#PdfFileSignature-java.lang.String-java.lang.String-}
PdfFileSignature sınıfının yapıcısı.

### bindPdf {#bindPdf-java.io.InputStream-}
Düzenleme için bir Pdf akışını bağlar.

### bindPdf {#bindPdf-java.lang.String-}
Düzenleme için bir Pdf dosyasını bağlar.

### certify {#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-}
Belgeyi, zaten mevcut olan imza alanına yerleştirilmiş MDP imzası ile onaylar. İmzalamadan önce imza alanı boş olmalıdır, yani alan imza sözlüğü içermemelidir. Bu nedenle pdf belgesinde zaten bir imza alanı vardır, imzayı damgalamak için bir yer sağlamamalısınız; ilgili sayfa ve dikdörtgen, imza adı (sigName parametresine bakın) ile bulunan imza alanından alınır.

### certify {#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-}
Pdf'nin dijital imzası olup olmadığını kontrol eder.

### close {#close--}
```
public void close()
```

Facade'i kapatır.

### containsSignature {#containsSignature--}
```
public boolean containsSignature()
```

Pdf'nin kullanım hakları olup olmadığını kontrol eder.

**Returns:**
Bool tipinde bir sonuç döndürür.

### containsUsageRights {#containsUsageRights--}
```
public boolean containsUsageRights()
```

İmzanın tüm belgeyi kapsayıp kapsamadığını kontrol eder.

**Returns:**
Bool tipinde bir sonuç döndürür.

### coversWholeDocument {#coversWholeDocument-com.aspose.pdf.facades.SignatureName-}
Facade'i kapatır. Bu yöntem artık kullanılmamaktadır, yerine close() kullanın.

### coversWholeDocument {#coversWholeDocument-java.lang.String-}
Facade'i kapatır. Bu yöntem artık kullanılmamaktadır, yerine close() kullanın.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

İmzanın tek X.509 sertifikasını akış olarak çıkarır.

### extractCertificate {#extractCertificate-com.aspose.pdf.facades.SignatureName-}
İmzanın görüntüsünü çıkarır.

### extractCertificate {#extractCertificate-java.lang.String-}
İmzanın görüntüsünü çıkarır.

### extractImage {#extractImage-com.aspose.pdf.facades.SignatureName-}
İmzanın görüntüsünü çıkarır.

### extractImage {#extractImage-java.lang.String-}
İmzanın görüntüsünü çıkarır.

### getAccessPermissions {#getAccessPermissions--}
```
public DocMDPAccessPermissions getAccessPermissions()
```

MDP imza türü tarafından sertifikalı belgenin erişim izinleri değerini döndürür.

**Returns:**
PdfException Belge sertifikalandırılıyorsa, erişim izinleri değerini döndürür; aksi takdirde, fırlatılır. @see com.aspose.pdf.DocMDPAccessPermissions

### getBlankSignNames {#getBlankSignNames--}
```
@Deprecated public List < String > getBlankSignNames()
```

Tüm boş imza alanlarının adlarını alır.

**Returns:**
Bir arrayList döndürür. @deprecated Bunun yerine GetBlankSignatureNames() kullanın.

### getContactInfo {#getContactInfo-com.aspose.pdf.facades.SignatureName-}
Bir imzanın iletişim bilgilerini alır.

### getContactInfo {#getContactInfo-java.lang.String-}
Bir imzanın iletişim bilgilerini alır.

### getDateTime {#getDateTime-com.aspose.pdf.facades.SignatureName-}
İmzanın tarih ve saat bilgisini alır.

### getDateTime {#getDateTime-java.lang.String-}
İmzanın tarih ve saat bilgisini alır.

### getLocation {#getLocation-com.aspose.pdf.facades.SignatureName-}
İmzanın konumunu alır.

### getLocation {#getLocation-java.lang.String-}
İmzanın konumunu alır.

### getReason {#getReason-com.aspose.pdf.facades.SignatureName-}
İmzanın nedenini alır.

### getReason {#getReason-java.lang.String-}
İmzanın nedenini alır.

### getRevision {#getRevision-com.aspose.pdf.facades.SignatureName-}
İmzanın revizyonunu alır.

### getRevision {#getRevision-java.lang.String-}
İmzanın revizyonunu alır.

### getSignatureAppearance {#getSignatureAppearance--}
```
public String getSignatureAppearance()
```

İmza için grafik görünüm alır. Özellik değeri görüntü dosya adını temsil eder.

**Returns:**
String değeri

### getSignatureAppearanceStream {#getSignatureAppearanceStream--}
```
public InputStream getSignatureAppearanceStream()
```

İmza için grafik görünüm alır. Özellik değeri görüntü akışını temsil eder.

**Returns:**
InputStream öğesi

### getSignatureNames {#getSignatureNames--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< SignatureName > getSignatureNames()
```

/ * <p> / * Boş olmayan tüm imzaların adlarını alır. / * </p> / * <p> / * <pre> / * string inFile=TestPath + \"example1.pdf\"; / * PdfFileSignature pdfSign=new PdfFileSignature(); / * pdfSign.bindPdf(inFile); / * java.util.List<String> names=pdfSign.getSignatureNames(); / * for(int i=0;i<names.size();i++) / * { / * System.out.println(\"signature name:\" + names[i]); / * System.out.println(\"coverswholedocument:\" + pdfSign.coversWholeDocument(names[i])); / * System.out.println(\"revision:\" + pdfSign.getRevision(names[i])); / * System.out.println(\"verifysigned:\" + pdfSign.verifySignature(names[i])); / * System.out.println(\"reason:\" + pdfSign.getReason(names[i])); / * System.out.println(\"location:\" + pdfSign.getLocation(names[i])); / * System.out.println(\"datatime:\" + pdfSign.getDateTime(names[i])); / * } / * System.out.println(\"totalvision:\" + pdfSign.GetTotalRevision()); / * / * </pre> / *

**Returns:**
Bir IList<SignatureName> döndürür. /

### getSignatureNames {#getSignatureNames-boolean-}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< SignatureName > getSignatureNames(boolean onlyActive)
```

Boş olmayan tüm imzaların adlarını alır. string inFile=TestPath + \"example1.pdf\"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); java.util.List names=pdfSign.getSignatureNames(); for(int i=0;i<names.size();i++) { System.out.println(\"signature name:\" + names[i]); System.out.println(\"coverswholedocument:\" + pdfSign.coversWholeDocument(names[i])); System.out.println(\"revision:\" + pdfSign.getRevision(names[i])); System.out.println(\"verifysigned:\" + pdfSign.verifySignature(names[i])); System.out.println(\"reason:\" + pdfSign.getReason(names[i])); System.out.println(\"location:\" + pdfSign.getLocation(names[i])); System.out.println(\"datatime:\" + pdfSign.getDateTime(names[i])); } System.out.println(\"totalvision:\" + pdfSign.GetTotalRevision());

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| onlyActive |  | true ise, yalnızca aktif imzaları döndürür; aksi takdirde, tüm imzaları döndürür. |

**Returns:**
Bir IList<SignatureName> döndürür.

### getSignaturesInfo {#getSignaturesInfo--}
```
public final List <com.aspose.pdf.engine.security.SignatureAlgorithmInfo> getSignaturesInfo()
```

PDF belgesinde bulunan tüm imza algoritmaları hakkında bilgi alır.

**Returns:**
Her imza hakkında bilgi içeren {@link SignatureAlgorithmInfo} örneklerinin bir listesi.

### getSignerName {#getSignerName-com.aspose.pdf.facades.SignatureName-}
PDF belgesini imzalayan kişi veya kuruluşun adını alır.

### getSignerName {#getSignerName-java.lang.String-}
PDF belgesini imzalayan kişi veya kuruluşun adını alır.

### getSignNames {#getSignNames--}
```
public final List < String > getSignNames()
```

<p> Boş olmayan tüm imzaların adlarını alır. </p> <hr>

**Returns:**
Bir arrayList döndürür.

### getSignNames {#getSignNames-boolean-}
```
@Deprecated public List < String > getSignNames(boolean onlyActive)
```

<p> Boş olmayan tüm imzaların adlarını alır. </p> <hr> <pre> String inFile=TestPath + \"example1.pdf\"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); ArrayList names=pdfSign.getSignNames(true); for(int i=0;i<names.Count;i++) { System.out.println(\"signature name:\"+(String)names[i]); System.out.println(\"coverswholedocument:\"+pdfSign.IsCoversWholeDocument((String)names[i])); System.out.println(\"revision:\"+pdfSign.GetRevision((String)names[i])); System.out.println(\"verifysigned:\"+pdfSign.VerifySigned((String)names[i])); System.out.println(\"reason:\"+pdfSign.GetReason((String)names[i])); System.out.println(\"location:\"+pdfSign.GetLocation((String)names[i])); System.out.println(\"datatime:\"+pdfSign.GetDateTime((String)names[i])); } System.out.println(\"totalvision:\"+pdfSign.GetTotalRevision()); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| onlyActive |  | boolean değer, true ise yalnızca aktif imzaları döndürür; aksi takdirde tüm imzaları döndürür. |

**Returns:**
Bir arrayList döndürür. @deprecated Bu yöntem aynı imza adlarını üretebilir ve doğrulama sırasında ayırt edilemez. Bunun yerine getSignatureNames(boolean onlyActive) kullanın.

### getTotalRevision {#getTotalRevision--}
```
public int getTotalRevision()
```

Toplam revizyonu alır.

**Returns:**
İmza revizyonunun toplam sayısını döndürür.

### isCertified {#isCertified--}
```
public boolean isCertified()
```

Bir belgenin sertifikalı olup olmadığını belirleyen bayrağı alır.

**Returns:**
boolean değer

### isContainSignature {#isContainSignature--}
```
@Deprecated public boolean isContainSignature()
```

Pdf'nin kullanım hakları olup olmadığını kontrol eder.

**Returns:**
Bool tipinde bir sonuç döndürür.

### isCoversWholeDocument {#isCoversWholeDocument-java.lang.String-}
Facade'i kapatır. Bu yöntem artık kullanılmamaktadır, yerine close() kullanın.

### isLtvEnabled {#isLtvEnabled--}
```
public final boolean isLtvEnabled()
```

LTV etkin bayrağını alır.

**Returns:**
boolean değer

### removeSignature {#removeSignature-com.aspose.pdf.facades.SignatureName-}
İmzanın adına göre imzayı kaldır. string inFile = TestPath + \"example1.pdf\"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i]); } pdfSign.save(TestPath + \"signed_removed.pdf\");

### removeSignature {#removeSignature-com.aspose.pdf.facades.SignatureName-boolean-}
İmzanın adına göre imzayı kaldırır. string inFile = TestPath + \"example1.pdf\"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i], false); } pdfSign.save(TestPath + \"signed_removed.pdf\");

### removeSignature {#removeSignature-java.lang.String-}
<p> İmzanın adına göre imzayı kaldır. </p> <hr> <pre> String inFile = TestPath + \"example1.pdf\"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i)); } pdfSign.save(TestPath + \"signed_removed.pdf\"); </pre>

### removeSignature {#removeSignature-java.lang.String-boolean-}
<p> İmzanın adına göre imzayı kaldırır. </p> <hr> <pre> String inFile = TestPath + \"example1.pdf\"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.BindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i), false); } pdfSign.save(TestPath + \"signed_removed.pdf\"); </pre>

### removeSignatures {#removeSignatures--}
```
public final void removeSignatures()
```

Tüm imzaları kaldırır. string inFile = TestPath + \"example1.pdf\"; var pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); pdfSign.removeSignatures(); pdfSign.save(TestPath + \"signed_removed.pdf\");

### removeUsageRights {#removeUsageRights--}
```
public void removeUsageRights()
```

Kullanım hakları girişini kaldırır.

### save {#save--}
```
@Deprecated public void save()
```

İmzalı pdf dosyasını kaydet. Çıktı dosya adı, ilgili PdfFileSignature yapıcısı yardımıyla önceden sağlanmalıdır.

### save {#save-java.io.OutputStream-}
İmzalı pdf dosyasını kaydet. Çıktı dosya adı, ilgili PdfFileSignature yapıcısı yardımıyla önceden sağlanmalıdır.

### save {#save-java.lang.String-}
İmzalı pdf dosyasını kaydet. Çıktı dosya adı, ilgili PdfFileSignature yapıcısı yardımıyla önceden sağlanmalıdır.

### setCertificate {#setCertificate-java.lang.String-java.lang.String-}
İmzalama rutini için sertifika dosyasını ve şifreyi ayarla.

### setSignatureAppearance {#setSignatureAppearance-java.lang.String-}
İmza için grafik görünüm ayarlar. Özellik değeri görüntü dosya adını temsil eder.

### setSignatureAppearanceStream {#setSignatureAppearanceStream-java.io.InputStream-}
İmza için grafik görünüm ayarlar. Özellik değeri görüntü akışını temsil eder.

### sign {#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Belirtilen tipteki imza ile belgeyi imzala.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-}
Pdf belgesine bir imza ekle.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Belirtilen tipteki imza ile belgeyi imzala.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Belirtilen tipteki imza, zaten mevcut imza alanına yerleştirilmiş olarak belgeyi imzala.

### sign {#sign-java.lang.String-com.aspose.pdf.Signature-}
<p> Belirtilen tipteki imza, zaten mevcut imza alanına yerleştirilmiş olarak belgeyi imzala. İmzalamadan önce imza alanı boş olmalıdır, yani alan imza sözlüğü içermemelidir. Bu nedenle pdf belgesinde zaten bir imza alanı vardır, imzayı damgalamak için konum sağlamamalısınız; ilgili sayfa ve dikdörtgen, imza adıyla bulunan imza alanından alınır (SigName parametresine bakın). İmza nedeni, iletişim ve konum gibi veriler, Signature nesnesi sig'in ilgili özellikleriyle sağlanmalıdır. </p> <hr> <pre> String inFile = TestPath + \"example1.pdf\"; String outFile = TestPath + \"signature.pdf\"; PKCS1 sig = new PKCS1(\"certificate.pfx\", \"password\"); sig.setReason ( \"Some reason\"); sig.setContact ( \"Smith\"); sig.setLocation ( \"New York\"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + \"butterfly.jpg\"); pdfSign.sign(\"Signature1\", sig); pdfSign.save(); </pre>

### sign {#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-}
<p> Belirtilen tipteki imza, zaten mevcut imza alanına yerleştirilmiş olarak belgeyi imzala. İmzalamadan önce imza alanı boş olmalıdır, yani alan imza sözlüğü içermemelidir. Bu nedenle pdf belgesinde zaten bir imza alanı vardır, imzayı damgalamak için konum sağlamamalısınız; ilgili sayfa ve dikdörtgen, imza adıyla bulunan imza alanından alınır (SigName parametresine bakın). </p> <hr> <pre> String inFile = TestPath + \"example1.pdf\"; String outFile = TestPath + \"signature.pdf\"; PKCS1 sig = new PKCS1(\"certificate.pfx\", \"password\"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + \"butterfly.jpg\"); pdfSign.sign(\"Signature1\", \"Allen\", \"success\", \"ChangSha\", sig); pdfSign.save(); </pre>

### tryExtractCertificate {#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-java.io.OutputStream:A-}
İmzanın görüntüsünü çıkarır.

### tryExtractCertificate {#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2:A-}
İmzanın tek X.509 sertifikasını çıkarır.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-}
Bir imzanın geçerliliğini kontrol eder.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Bir imzanın geçerliliğini kontrol eder.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
Bir imzanın geçerliliğini kontrol eder.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Bir imzanın geçerliliğini kontrol eder.

### verifySignature {#verifySignature-java.lang.String-}
Bir imzanın geçerliliğini kontrol eder.

### verifySignature {#verifySignature-java.lang.String-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Bir imzanın geçerliliğini kontrol eder.

### verifySigned {#verifySigned-java.lang.String-}
Bir imzanın geçerliliğini kontrol eder. Metod kullanımdan kaldırılmıştır ve 25.1 sürümünde silinecektir. Bunun yerine VerifySignature metodunu kullanın.
