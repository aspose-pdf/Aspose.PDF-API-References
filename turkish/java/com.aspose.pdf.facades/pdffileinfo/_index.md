---
title: "PdfFileInfo"
linktitle: "PdfFileInfo"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF belgesinin meta bilgilerine erişmek için bir sınıfı temsil eder."
type: docs
weight: 490
url: /tr/java/com.aspose.pdf.facades/pdffileinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileInfo, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileInfo, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileInfo

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileInfo extends SaveableFacade
```

PDF belgesinin meta bilgilerine erişmek için bir sınıfı temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfFileInfo](#PdfFileInfo--) | com.aspose.pdf.facades.PdfFileInfo sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [PdfFileInfo](#PdfFileInfo-com.aspose.pdf.IDocument-) | com.aspose.pdf.facades.PdfFileInfo sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-) | com.aspose.pdf.facades.PdfFileInfo sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-java.lang.String-) | com.aspose.pdf.facades.PdfFileInfo sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | com.aspose.pdf.facades.PdfFileInfo sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-) | com.aspose.pdf.facades.PdfFileInfo sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-java.lang.String-) | com.aspose.pdf.facades.PdfFileInfo sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | com.aspose.pdf.facades.PdfFileInfo sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Facade'i başlatır. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Facade'i başlatır. |
| [clearInfo](#clearInfo--) | PDF belgesinin tüm meta bilgilerini temizler. |
| [close](#close--) | Bu belge tarafından kullanılan tüm kaynakları kapatır. |
| [dispose](#dispose--) | Bu örnek tarafından kullanılan tüm kaynakları kapatır. Bu yöntem artık kullanılmamaktadır, bunun yerine close() kullanın. |
| [getAuthor](#getAuthor--) | PDF belgesinin Yazar bilgisini alır. |
| [getCreationDate](#getCreationDate--) | PDF belgesinin CreationDate bilgisini alır. |
| [getCreator](#getCreator--) | PDF belgesinin Creator bilgisini alır. |
| [getDocumentPrivilege](#getDocumentPrivilege--) | PDF belgesinin yetki ayarlarını alır. |
| [getHeader](#getHeader--) | <p> PDF belgesinin özelleştirilmiş bilgilerini alır. </p> |
| [getInputFile](#getInputFile--) | Girdi dosyasını alır. |
| [getInputStream](#getInputStream--) | Girdi akışını alır. |
| [getKeywords](#getKeywords--) | PDF belgesinin Anahtar Kelimeler bilgisini alır. |
| [getMetaInfo](#getMetaInfo-java.lang.String-) | PDF belgesinin özelleştirilmiş bilgisini özellik adıyla alır. Eğer isimle eşleşen bir özellik yoksa boş bir dize döndürür. |
| [getModDate](#getModDate--) | PDF belgesinin ModDate tarih bilgisini alır. |
| [getNumberOfPages](#getNumberOfPages--) | Belge sayfalarının sayısını alır. |
| [getPageHeight](#getPageHeight-int-) | Belirtilen sayfanın yüksekliğini alır. |
| [getPageRotation](#getPageRotation-int-) | Belirtilen sayfanın dönüşünü alır. |
| [getPageWidth](#getPageWidth-int-) | Belirtilen sayfanın genişliğini alır. |
| [getPageXOffset](#getPageXOffset-int-) | Belirtilen sayfa görüntü alanının yatay ofsetini alır. |
| [getPageYOffset](#getPageYOffset-int-) | Belirtilen sayfa görüntü alanının dikey ofsetini alır. |
| [getPasswordType](#getPasswordType--) | PdfFileInfo örneği oluşturulurken geçirilen şifre tipini döndürür. Olası değerler için {@code PasswordType} bölümüne bakın. pdf belgesinin hem kullanıcı (veya açma) şifresi hem de sahibi (veya izinler, düzenleme) şifresi ile açılabileceğine dikkat edin. |
| [getPdfVersion](#getPdfVersion--) | PDF belgesinin sürüm bilgisini alır. |
| [getProducer](#getProducer--) | PDF belgesinin Üretici bilgisini alır. |
| [getSubject](#getSubject--) | PDF belgesinin Konu bilgisini alır. |
| [getTitle](#getTitle--) | PDF belgesinin Başlık bilgisini alır. |
| [getUseStrictValidation](#getUseStrictValidation--) | Sıkı doğrulama kurallarını {@code IsPdfFile}({@link #isPdfFile}) özelliği kullanarak uygular. |
| [hasCollection](#hasCollection--) | Mevcut girdi dosyası içinde PDF dosyalarının bir koleksiyonunu barındıran bir 'Portföy' dosyasıysa true döndürür. |
| [hasEditPassword](#hasEditPassword--) | İzinleri veya belge güvenlik özelliğini değiştirmek için şifre gerekiyorsa true döndürür. Bu özelliğin yalnızca {@code PdfFileInfo} yapıcısına geçerli bir şifre sağlanmışsa okunabileceğine dikkat edin. PasswordType Inaccessible (geçersiz şifre sağlandığı anlamına gelir) olduğunda bu özelliği okumak {@code InvalidPasswordException} ile başarısız olur. |
| [hasOpenPassword](#hasOpenPassword--) | Şifre korumalı pdf belgesini açmak için şifre gerekiyorsa true döndürür. |
| [isEncrypted](#isEncrypted--) | PDF belgesinin şifrelenip şifrelenmediğini kontrol eder. |
| [isPdfFile](#isPdfFile--) | Kaynak girdinin geçerli bir PDF dosyası olup olmadığını kontrol eder. |
| [save](#save-java.io.OutputStream-) | PDF belgesini belirtilen dosyaya kaydeder. |
| [saveNewInfo](#saveNewInfo-java.io.OutputStream-) | Belirtilen akışa güncellenmiş PDF belgesini kaydedin. |
| [saveNewInfo](#saveNewInfo-java.lang.String-) | Belirtilen dosyaya güncellenmiş PDF belgesini kaydedin. |
| [saveNewInfoWithXmp](#saveNewInfoWithXmp-java.lang.String-) | Dosya bilgilerini ayarlayarak açıkça belirtilen özellikleri değiştirir, diğer özellikler aynı kalır. |
| [setAuthor](#setAuthor-java.lang.String-) | PDF belgesinin Yazar bilgisini ayarlar. |
| [setCreationDate](#setCreationDate-java.lang.String-) | PDF belgesinin CreationDate bilgisini ayarlar. |
| [setCreator](#setCreator-java.lang.String-) | PDF belgesinin Oluşturucu bilgisini ayarlar. |
| [setHeader](#setHeader-java.util.Map-) | PDF belgesinin özelleştirilmiş bilgisini ayarlar. |
| [setInputFile](#setInputFile-java.lang.String-) | Giriş dosyasını ayarlar. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Giriş akışını ayarlar. |
| [setKeywords](#setKeywords-java.lang.String-) | PDF belgesinin Keywords bilgisini ayarlar. |
| [setMetaInfo](#setMetaInfo-java.lang.String-java.lang.String-) | PDF belgesinin özelleştirilmiş bilgisini ayarlar. |
| [setModDate](#setModDate-java.lang.String-) | PDF belgesinin ModDate tarih bilgisini ayarlar. |
| [setSubject](#setSubject-java.lang.String-) | PDF belgesinin Konu bilgisini ayarlar. |
| [setTitle](#setTitle-java.lang.String-) | PDF belgesinin Başlık bilgisini ayarlar. |
| [setUseStrictValidation](#setUseStrictValidation-boolean-) | Sıkı doğrulama kurallarını {@code IsPdfFile}({@link #isPdfFile}) özelliği kullanarak uygular. |

### PdfFileInfo {#PdfFileInfo--}
```
public PdfFileInfo()
```

com.aspose.pdf.facades.PdfFileInfo sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

### PdfFileInfo {#PdfFileInfo-com.aspose.pdf.IDocument-}
com.aspose.pdf.facades.PdfFileInfo sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-}
com.aspose.pdf.facades.PdfFileInfo sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-java.lang.String-}
com.aspose.pdf.facades.PdfFileInfo sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
com.aspose.pdf.facades.PdfFileInfo sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

### PdfFileInfo {#PdfFileInfo-java.lang.String-}
com.aspose.pdf.facades.PdfFileInfo sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

### PdfFileInfo {#PdfFileInfo-java.lang.String-java.lang.String-}
com.aspose.pdf.facades.PdfFileInfo sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

### PdfFileInfo {#PdfFileInfo-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
com.aspose.pdf.facades.PdfFileInfo sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Facade'i başlatır.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Facade'i başlatır.

### clearInfo {#clearInfo--}
```
public void clearInfo()
```

PDF belgesinin tüm meta bilgilerini temizler.

### close {#close--}
```
public void close()
```

Bu belge tarafından kullanılan tüm kaynakları kapatır.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Bu örnek tarafından kullanılan tüm kaynakları kapatır. Bu yöntem artık kullanılmamaktadır, bunun yerine close() kullanın.

### getAuthor {#getAuthor--}
```
public String getAuthor()
```

PDF belgesinin Yazar bilgisini alır.

**Returns:**
String değeri

### getCreationDate {#getCreationDate--}
```
public String getCreationDate()
```

PDF belgesinin CreationDate bilgisini alır.

**Returns:**
String değeri

### getCreator {#getCreator--}
```
public String getCreator()
```

PDF belgesinin Creator bilgisini alır.

**Returns:**
String değeri

### getDocumentPrivilege {#getDocumentPrivilege--}
```
public DocumentPrivilege getDocumentPrivilege()
```

PDF belgesinin yetki ayarlarını alır.

**Returns:**
PDF belgesinin ayrıcalık ayarları.

### getHeader {#getHeader--}
```
public Map < String , String > getHeader()
```

<p> PDF belgesinin özelleştirilmiş bilgilerini alır. </p>

**Returns:**
{@code Map<String, String>} nesne

### getInputFile {#getInputFile--}
```
@Deprecated public String getInputFile()
```

Girdi dosyasını alır.

**Returns:**
String değeri

### getInputStream {#getInputStream--}
```
@Deprecated public InputStream getInputStream()
```

Girdi akışını alır.

**Returns:**
InputStream nesnesi

### getKeywords {#getKeywords--}
```
public String getKeywords()
```

PDF belgesinin Anahtar Kelimeler bilgisini alır.

**Returns:**
String değeri

### getMetaInfo {#getMetaInfo-java.lang.String-}
PDF belgesinin özelleştirilmiş bilgisini özellik adıyla alır. Eğer isimle eşleşen bir özellik yoksa boş bir dize döndürür.

### getModDate {#getModDate--}
```
public String getModDate()
```

PDF belgesinin ModDate tarih bilgisini alır.

**Returns:**
String değeri

### getNumberOfPages {#getNumberOfPages--}
```
public int getNumberOfPages()
```

Belge sayfalarının sayısını alır.

**Returns:**
int değer

### getPageHeight {#getPageHeight-int-}
```
public float getPageHeight(int pageNum)
```

Belirtilen sayfanın yüksekliğini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNum |  | Sayfa numarası. |

**Returns:**
Sayfanın yüksekliği.

### getPageRotation {#getPageRotation-int-}
```
public int getPageRotation(int pageNum)
```

Belirtilen sayfanın dönüşünü alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNum |  | Sayfa numarası. |

**Returns:**
Sayfanın dönüşü. Değer 0,90,180,270 olabilir.

### getPageWidth {#getPageWidth-int-}
```
public float getPageWidth(int pageNum)
```

Belirtilen sayfanın genişliğini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNum |  | Sayfa numarası. |

**Returns:**
Sayfanın genişliği.

### getPageXOffset {#getPageXOffset-int-}
```
public float getPageXOffset(int pageNum)
```

Belirtilen sayfa görüntü alanının yatay ofsetini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNum |  | Sayfa numarası. |

**Returns:**
Sayfanın sol kenarından yatay kaydırma.

### getPageYOffset {#getPageYOffset-int-}
```
public float getPageYOffset(int pageNum)
```

Belirtilen sayfa görüntü alanının dikey ofsetini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNum |  | Sayfa numarası. |

**Returns:**
Sayfa görüntü alanının dikey kaydırması.

### getPasswordType {#getPasswordType--}
```
public PasswordType getPasswordType()
```

PdfFileInfo örneği oluşturulurken geçirilen şifre tipini döndürür. Olası değerler için {@code PasswordType} bölümüne bakın. pdf belgesinin hem kullanıcı (veya açma) şifresi hem de sahibi (veya izinler, düzenleme) şifresi ile açılabileceğine dikkat edin.

**Returns:**
PasswordType öğesi @see PasswordType

### getPdfVersion {#getPdfVersion--}
```
public String getPdfVersion()
```

PDF belgesinin sürüm bilgisini alır.

**Returns:**
Versiyon dizesi.

### getProducer {#getProducer--}
```
public String getProducer()
```

PDF belgesinin Üretici bilgisini alır.

**Returns:**
String değeri

### getSubject {#getSubject--}
```
public String getSubject()
```

PDF belgesinin Konu bilgisini alır.

**Returns:**
String değeri

### getTitle {#getTitle--}
```
public String getTitle()
```

PDF belgesinin Başlık bilgisini alır.

**Returns:**
String değeri

### getUseStrictValidation {#getUseStrictValidation--}
```
public final boolean getUseStrictValidation()
```

Sıkı doğrulama kurallarını {@code IsPdfFile}({@link #isPdfFile}) özelliği kullanarak uygular.

**Returns:**
boolean değer

### hasCollection {#hasCollection--}
```
public boolean hasCollection()
```

Mevcut girdi dosyası içinde PDF dosyalarının bir koleksiyonunu barındıran bir 'Portföy' dosyasıysa true döndürür.

**Returns:**
boolean değer

### hasEditPassword {#hasEditPassword--}
```
public boolean hasEditPassword()
```

İzinleri veya belge güvenlik özelliğini değiştirmek için şifre gerekiyorsa true döndürür. Bu özelliğin yalnızca {@code PdfFileInfo} yapıcısına geçerli bir şifre sağlanmışsa okunabileceğine dikkat edin. PasswordType Inaccessible (geçersiz şifre sağlandığı anlamına gelir) olduğunda bu özelliği okumak {@code InvalidPasswordException} ile başarısız olur.

**Returns:**
boolean değer

### hasOpenPassword {#hasOpenPassword--}
```
public boolean hasOpenPassword()
```

Şifre korumalı pdf belgesini açmak için şifre gerekiyorsa true döndürür.

**Returns:**
boolean değer

### isEncrypted {#isEncrypted--}
```
public boolean isEncrypted()
```

PDF belgesinin şifrelenip şifrelenmediğini kontrol eder.

**Returns:**
boolean değer

### isPdfFile {#isPdfFile--}
```
public boolean isPdfFile()
```

Kaynak girdinin geçerli bir PDF dosyası olup olmadığını kontrol eder.

**Returns:**
boolean değer

### save {#save-java.io.OutputStream-}
PDF belgesini belirtilen dosyaya kaydeder.

### saveNewInfo {#saveNewInfo-java.io.OutputStream-}
Belirtilen akışa güncellenmiş PDF belgesini kaydedin.

### saveNewInfo {#saveNewInfo-java.lang.String-}
Belirtilen dosyaya güncellenmiş PDF belgesini kaydedin.

### saveNewInfoWithXmp {#saveNewInfoWithXmp-java.lang.String-}
Dosya bilgilerini ayarlayarak açıkça belirtilen özellikleri değiştirir, diğer özellikler aynı kalır.

### setAuthor {#setAuthor-java.lang.String-}
PDF belgesinin Yazar bilgisini ayarlar.

### setCreationDate {#setCreationDate-java.lang.String-}
PDF belgesinin CreationDate bilgisini ayarlar.

### setCreator {#setCreator-java.lang.String-}
PDF belgesinin Oluşturucu bilgisini ayarlar.

### setHeader {#setHeader-java.util.Map-}
PDF belgesinin özelleştirilmiş bilgisini ayarlar.

### setInputFile {#setInputFile-java.lang.String-}
Giriş dosyasını ayarlar.

### setInputStream {#setInputStream-java.io.InputStream-}
Giriş akışını ayarlar.

### setKeywords {#setKeywords-java.lang.String-}
PDF belgesinin Keywords bilgisini ayarlar.

### setMetaInfo {#setMetaInfo-java.lang.String-java.lang.String-}
PDF belgesinin özelleştirilmiş bilgisini ayarlar.

### setModDate {#setModDate-java.lang.String-}
PDF belgesinin ModDate tarih bilgisini ayarlar.

### setSubject {#setSubject-java.lang.String-}
PDF belgesinin Konu bilgisini ayarlar.

### setTitle {#setTitle-java.lang.String-}
PDF belgesinin Başlık bilgisini ayarlar.

### setUseStrictValidation {#setUseStrictValidation-boolean-}
```
public final void setUseStrictValidation(boolean value)
```

Sıkı doğrulama kurallarını {@code IsPdfFile}({@link #isPdfFile}) özelliği kullanarak uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |
