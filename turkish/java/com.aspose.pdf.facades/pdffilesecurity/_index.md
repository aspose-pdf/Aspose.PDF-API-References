---
title: "PdfFileSecurity"
linktitle: "PdfFileSecurity"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bir PDF dosyasını sahibi veya kullanıcı şifresiyle şifreleme veya şifre çözme, güvenlik ayarlarını ve şifreyi değiştirmeyi temsil eder."
type: docs
weight: 520
url: /tr/java/com.aspose.pdf.facades/pdffilesecurity/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSecurity, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSecurity, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSecurity

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSecurity extends SaveableFacade implements com.aspose.ms.System.IDisposable
```

Bir PDF dosyasını sahibi veya kullanıcı şifresiyle şifreleme veya şifre çözme, güvenlik ayarlarını ve şifreyi değiştirmeyi temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfFileSecurity](#PdfFileSecurity--) | PdfFileSecurity nesnesini başlat. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-) | PdfFileSecurity nesnesini başlat. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-) | PdfFileSecurity nesnesini başlat. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-) | PdfFileSecurity nesnesini başlat. |
| [PdfFileSecurity](#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-) | PdfFileSecurity nesnesini başlat. |
| [PdfFileSecurity](#PdfFileSecurity-java.lang.String-java.lang.String-) | PdfFileSecurity nesnesini başlat. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | Facade'i başlatır. |
| [bindPdf](#bindPdf-java.lang.String-) | Facade'i başlatır. |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-) | Kullanıcı şifresini ve sahibi şifresini, sahibi şifresiyle değiştirir, orijinal güvenlik ayarlarını korur. Yeni kullanıcı şifresi ve yeni sahibi şifresi null veya boş olabilir. Yeni sahibi şifresi null veya boş ise, sahibi şifresi rastgele bir dizeyle değiştirilecektir. İşlem başarısız olursa bir istisna fırlatır. string inFile = "D:\\\\input.pdf"; //TestPath yeniden atanabilir. string outFile = "D:\\\\output.pdf"; //TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.changePassword("owner","newuser","newowner"); |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | <p> Kullanıcı şifresini ve şifreyi, sahibi şifresiyle değiştirir, PDF belgesi güvenliğini sıfırlamaya izin verir. Yeni kullanıcı şifresi ve yeni sahibi şifresi null veya boş olabilir. Yeni sahibi şifresi null veya boş ise, sahibi şifresi rastgele bir dizeyle değiştirilecektir. <p> İşlem başarısız olursa bir istisna fırlatır. </p> <hr> <pre> string inFile = "input.pdf"; //TestPath yeniden atanabilir. string outFile = "output.pdf"; //TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256); </pre> |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | <p> Kullanıcı şifresini ve şifreyi, sahibi şifresiyle değiştirir, PDF belgesi güvenliğini sıfırlamaya izin verir. Yeni kullanıcı şifresi ve yeni sahibi şifresi null veya boş olabilir. Yeni sahibi şifresi null veya boş ise, sahibi şifresi rastgele bir dizeyle değiştirilecektir. KeySize ve Algorithm değerlerinin 6 olası kombinasyonu vardır. Ancak (KeySize.x40, Algorithm.AES) ve (KeySize.x256, Algorithm.RC4) geçersizdir ve kit bu kombinasyonla karşılaşırsa ilgili istisna yükseltilir. </p> <hr> <pre> string inFile = "input.pdf"; //TestPath yeniden atanabilir. string outFile = "output.pdf"; //TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre> |
| [close](#close--) | Facade'i kapatır. |
| [decryptFile](#decryptFile-java.lang.String-) | Şifreli bir PDF belgesini sahibi şifresiyle çözer. Belgenin sahibi şifresi yoksa, kullanıcı şifresi kullanılmasına izin verilir. İşlem başarısız olursa bir istisna fırlatır. string inFile = "input.pdf"; //TestPath yeniden atanabilir. string outFile = "output.pdf"; //TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.decryptFile("ownerpass"); |
| [dispose](#dispose--) | Facade'i kapatır. |
| [encryptFile](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | <p> PDF dosyasını kullanıcı şifresi ve sahibi şifresiyle şifreler ve belgenin erişim ayrıcalıklarını ayarlar. Kullanıcı şifresi ve sahibi şifresi null ve boş olabilir. Girdi sahibi şifresi null veya boş ise, sahibi şifresi rastgele bir dizeyle değiştirilecektir. İşlem başarısız olursa bir istisna fırlatır. </p> <hr> <pre> String inFile = "input.pdf"; //TestPath yeniden atanabilir. String outFile = "output.pdf"; //TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); </pre> |
| [encryptFile](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | <p> Pdf dosyasını kullanıcı şifresi ve sahibi şifresiyle şifreler ve belgenin erişim ayrıcalıklarını ayarlar. Kullanıcı şifresi ve sahibi şifresi null veya boş olabilir. Girdi sahibi şifresi null veya boş ise, sahibi şifresi rastgele bir dizeyle değiştirilecektir. KeySize ve Algorithm değerlerinin 6 olası kombinasyonu vardır. Ancak (KeySize.x40, Algorithm.AES) ve (KeySize.x256, Algorithm.RC4) geçersizdir ve kit bu kombinasyonla karşılaşırsa ilgili istisna yükseltilecektir. İşlem başarısız olursa bir istisna fırlatır. </p> <hr> <pre> String inFile = "input.pdf"; // TestPath yeniden atanabilir. String outFile = "output.pdf"; // TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.encryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre> |
| [getAllowExceptions](#getAllowExceptions--) | Eğer bu değer true olarak ayarlanırsa, işlem başarısızlığında bir istisna fırlatılacaktır. Aksi takdirde, yöntem başarısızlıkta false döner ve son istisna LastException özelliğiyle kontrol edilebilir. |
| [getLastException](#getLastException--) | Son işlem tarafından fırlatılan istisnayı döndürür. |
| [setAllowExceptions](#setAllowExceptions-boolean-) | Eğer bu değer true olarak ayarlanırsa, işlem başarısızlığında bir istisna fırlatılacaktır. Aksi takdirde, yöntem başarısızlıkta false döner ve son istisna LastException özelliğiyle kontrol edilebilir. |
| [setInputFile](#setInputFile-java.lang.String-) | Girdi dosyasını ayarlar. Obsolete("Use bindPdf(inputStream) method for facade initialization.") |
| [setInputStream](#setInputStream-java.io.InputStream-) | Girdi akışını ayarlar. Obsolete("Use bindPdf(inputStream) method for facade initialization.") |
| [setOutputFile](#setOutputFile-java.lang.String-) | Çıktı dosyasını ayarlar. Obsolete("Use save(outputStream) method for getting facade results.") |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Çıktı akışını ayarlar. Obsolete("Use save(outputStream) method for getting facade results.") |
| [setPrivilege](#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-) | <p> Pdf dosyası güvenliğini boş kullanıcı/sahibi şifreleriyle ayarlar. Sahibi şifresi rastgele bir dizeyle eklenecektir. İşlem başarısız olursa bir istisna fırlatır. </p> <hr> <pre> string inFile = "input.pdf"; // TestPath yeniden atanabilir. string outFile = "output.pdf"; // TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(DocumentPrivilege.Print); </pre> |
| [setPrivilege](#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | <p> Pdf dosyası güvenliğini orijinal şifreyle ayarlar. İşlem başarısız olursa bir istisna fırlatır. </p> <hr> <pre> string inFile = "input.pdf"; // TestPath yeniden atanabilir. string outFile = "output.pdf"; // TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint()); </pre> |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-) | Kullanıcı şifresini ve sahibi şifresini, sahibi şifresiyle değiştirir, orijinal güvenlik ayarlarını korur. Yeni kullanıcı şifresi ve yeni sahibi şifresi null veya boş olabilir. Yeni sahibi şifresi null veya boş ise, sahibi şifresi rastgele bir dizeyle değiştirilecektir. İşlem başarısız olsa da bir istisna fırlatmaz. string inFile = "D:\\\\input.pdf"; // TestPath yeniden atanabilir. string outFile = "D:\\\\output.pdf"; // TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner"); |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | Kullanıcı şifresini ve şifreyi, sahibi şifresiyle değiştirir, Pdf belge güvenliğini sıfırlamaya izin verir. Yeni kullanıcı şifresi ve yeni sahibi şifresi null veya boş olabilir. Yeni sahibi şifresi null veya boş ise, sahibi şifresi rastgele bir dizeyle değiştirilecektir. İşlem başarısız olsa da bir istisna fırlatmaz. string inFile = ".D:\\\\input.pdf"; // TestPath yeniden atanabilir. string outFile = "D:\\\\output.pdf"; // TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256); |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | Kullanıcı şifresini ve sahibi şifresini değiştirir, Pdf belge güvenliğini sıfırlamaya izin verir. Yeni kullanıcı şifresi ve yeni sahibi şifresi null veya boş olabilir. Yeni sahibi şifresi null veya boş ise, sahibi şifresi rastgele bir dizeyle değiştirilecektir. KeySize ve Algorithm değerlerinin 6 olası kombinasyonu vardır. Ancak (KeySize.x40, Algorithm.AES) ve (KeySize.x256, Algorithm.RC4) geçersizdir ve kit bu kombinasyonla karşılaşırsa ilgili istisna yükseltilir. İşlem başarısız olsa da bir istisna fırlatmaz. string inFile = "D:\\\\input.pdf"; //TestPath yeniden atanabilir. string outFile = "D:\\\\output.pdf"; //TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES); |
| [tryDecryptFile](#tryDecryptFile-java.lang.String-) | Şifreli bir Pdf belgesini sahibi şifresiyle çözer. Belgenin sahibi şifresi yoksa, kullanıcı şifresi kullanılmasına izin verilir. İşlem başarısız olsa da bir istisna fırlatmaz. string inFile = "input.pdf"; //TestPath yeniden atanabilir. string outFile = "output.pdf"; //TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.TryDecryptFile("ownerpass"); |
| [tryEncryptFile](#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | Pdf dosyasını kullanıcı şifresi ve sahibi şifresiyle şifreler ve belgenin erişim ayrıcalıklarını ayarlar. Kullanıcı şifresi ve sahibi şifresi null veya boş olabilir. Girdi sahibi şifresi null veya boş ise, sahibi şifresi rastgele bir dizeyle değiştirilecektir. İşlem başarısız olsa da bir istisna fırlatmaz. string inFile = "input.pdf"; //TestPath yeniden atanabilir. string outFile = "output.pdf"; //TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); |
| [trySetPrivilege](#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | Pdf dosyası güvenliğini orijinal şifreyle ayarlar. İşlem başarısız olsa da bir istisna fırlatmaz. string inFile = "D:\\\\input.pdf"; //TestPath yeniden atanabilir. string outFile = "D:\\\\output.pdf"; //TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print); |

### PdfFileSecurity {#PdfFileSecurity--}
```
public PdfFileSecurity()
```

PdfFileSecurity nesnesini başlat.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-}
PdfFileSecurity nesnesini başlat.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-}
PdfFileSecurity nesnesini başlat.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-}
PdfFileSecurity nesnesini başlat.

### PdfFileSecurity {#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-}
PdfFileSecurity nesnesini başlat.

### PdfFileSecurity {#PdfFileSecurity-java.lang.String-java.lang.String-}
PdfFileSecurity nesnesini başlat.

### bindPdf {#bindPdf-java.io.InputStream-}
Facade'i başlatır.

### bindPdf {#bindPdf-java.lang.String-}
Facade'i başlatır.

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-}
Kullanıcı şifresini ve sahibi şifresini sahibi şifresiyle değiştirir, orijinal güvenlik ayarlarını korur. Yeni kullanıcı şifresi ve yeni sahibi şifresi null veya boş olabilir. Yeni sahibi şifresi null veya boş ise, sahibi şifresi rastgele bir dizeyle değiştirilecektir. İşlem başarısız olursa bir istisna fırlatır. string inFile = "D:\\input.pdf"; //TestPath yeniden atanabilir. string outFile = "D:\\output.pdf"; //TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.changePassword("owner","newuser","newowner");

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
<p> Kullanıcı şifresini ve şifreyi, sahibi şifresiyle değiştirir, PDF belgesi güvenliğini sıfırlamaya izin verir. Yeni kullanıcı şifresi ve yeni sahibi şifresi null veya boş olabilir. Yeni sahibi şifresi null veya boş ise, sahibi şifresi rastgele bir dizeyle değiştirilecektir. <p> İşlem başarısız olursa bir istisna fırlatır. </p> <hr> <pre> string inFile = "input.pdf"; //TestPath yeniden atanabilir. string outFile = "output.pdf"; //TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256); </pre>

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
<p> Kullanıcı şifresini ve şifreyi, sahibi şifresiyle değiştirir, PDF belgesi güvenliğini sıfırlamaya izin verir. Yeni kullanıcı şifresi ve yeni sahibi şifresi null veya boş olabilir. Yeni sahibi şifresi null veya boş ise, sahibi şifresi rastgele bir dizeyle değiştirilecektir. KeySize ve Algorithm değerlerinin 6 olası kombinasyonu vardır. Ancak (KeySize.x40, Algorithm.AES) ve (KeySize.x256, Algorithm.RC4) geçersizdir ve kit bu kombinasyonla karşılaşırsa ilgili istisna yükseltilir. </p> <hr> <pre> string inFile = "input.pdf"; //TestPath yeniden atanabilir. string outFile = "output.pdf"; //TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre>

### close {#close--}
```
public void close()
```

Facade'i kapatır.

### decryptFile {#decryptFile-java.lang.String-}
Şifreli bir PDF belgesini sahibi şifresiyle çözer. Belgenin sahibi şifresi yoksa, kullanıcı şifresi kullanılmasına izin verilir. İşlem başarısız olursa bir istisna fırlatır. string inFile = "input.pdf"; //TestPath yeniden atanabilir. string outFile = "output.pdf"; //TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.decryptFile("ownerpass");

### dispose {#dispose--}
```
public void dispose()
```

Facade'i kapatır.

### encryptFile {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
<p> PDF dosyasını kullanıcı şifresi ve sahibi şifresiyle şifreler ve belgenin erişim ayrıcalıklarını ayarlar. Kullanıcı şifresi ve sahibi şifresi null ve boş olabilir. Girdi sahibi şifresi null veya boş ise, sahibi şifresi rastgele bir dizeyle değiştirilecektir. İşlem başarısız olursa bir istisna fırlatır. </p> <hr> <pre> String inFile = "input.pdf"; //TestPath yeniden atanabilir. String outFile = "output.pdf"; //TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); </pre>

### encryptFile {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
<p> Pdf dosyasını kullanıcı şifresi ve sahibi şifresiyle şifreler ve belgenin erişim ayrıcalıklarını ayarlar. Kullanıcı şifresi ve sahibi şifresi null veya boş olabilir. Girdi sahibi şifresi null veya boş ise, sahibi şifresi rastgele bir dizeyle değiştirilecektir. KeySize ve Algorithm değerlerinin 6 olası kombinasyonu vardır. Ancak (KeySize.x40, Algorithm.AES) ve (KeySize.x256, Algorithm.RC4) geçersizdir ve kit bu kombinasyonla karşılaşırsa ilgili istisna yükseltilecektir. İşlem başarısız olursa bir istisna fırlatır. </p> <hr> <pre> String inFile = "input.pdf"; // TestPath yeniden atanabilir. String outFile = "output.pdf"; // TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.encryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre>

### getAllowExceptions {#getAllowExceptions--}
```
@Deprecated public final boolean getAllowExceptions()
```

Eğer bu değer true olarak ayarlanırsa, işlem başarısızlığında bir istisna fırlatılacaktır. Aksi takdirde, yöntem başarısızlıkta false döner ve son istisna LastException özelliğiyle kontrol edilebilir.

**Returns:**
boolean değer @deprecated Bu özellik kullanımdan kaldırılmıştır ve istisna fırlatılmasına izin vermek için kullanılamaz.

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

Son işlem tarafından fırlatılan istisnayı döndürür.

**Returns:**
java.lang.RuntimeException

### setAllowExceptions {#setAllowExceptions-boolean-}
```
@Deprecated public final void setAllowExceptions(boolean value)
```

Eğer bu değer true olarak ayarlanırsa, işlem başarısızlığında bir istisna fırlatılacaktır. Aksi takdirde, yöntem başarısızlıkta false döner ve son istisna LastException özelliğiyle kontrol edilebilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer @deprecated Bu özellik kullanımdan kaldırılmıştır ve istisna fırlatılmasına izin vermek için kullanılamaz. |

### setInputFile {#setInputFile-java.lang.String-}
Girdi dosyasını ayarlar. Obsolete("Use bindPdf(inputStream) method for facade initialization.")

### setInputStream {#setInputStream-java.io.InputStream-}
Girdi akışını ayarlar. Obsolete("Use bindPdf(inputStream) method for facade initialization.")

### setOutputFile {#setOutputFile-java.lang.String-}
Çıktı dosyasını ayarlar. Obsolete("Use save(outputStream) method for getting facade results.")

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Çıktı akışını ayarlar. Obsolete("Use save(outputStream) method for getting facade results.")

### setPrivilege {#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-}
<p> Pdf dosyası güvenliğini boş kullanıcı/sahibi şifreleriyle ayarlar. Sahibi şifresi rastgele bir dizeyle eklenecektir. İşlem başarısız olursa bir istisna fırlatır. </p> <hr> <pre> string inFile = "input.pdf"; // TestPath yeniden atanabilir. string outFile = "output.pdf"; // TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(DocumentPrivilege.Print); </pre>

### setPrivilege {#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
<p> Pdf dosyası güvenliğini orijinal şifreyle ayarlar. İşlem başarısız olursa bir istisna fırlatır. </p> <hr> <pre> string inFile = "input.pdf"; // TestPath yeniden atanabilir. string outFile = "output.pdf"; // TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint()); </pre>

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-}
Kullanıcı şifresini ve sahibi şifresini sahibi şifresiyle değiştirir, orijinal güvenlik ayarlarını korur. Yeni kullanıcı şifresi ve yeni sahibi şifresi null veya boş olabilir. Yeni sahibi şifresi null veya boş ise, sahibi şifresi rastgele bir dizeyle değiştirilecektir. İşlem başarısız olsa da bir istisna fırlatmaz. string inFile = "D:\\input.pdf"; //TestPath yeniden atanabilir. string outFile = "D:\\output.pdf"; //TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner");

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
Kullanıcı şifresini ve sahibi şifresiyle şifreyi değiştirir, PDF belge güvenliğini sıfırlamaya izin verir. Yeni kullanıcı şifresi ve yeni sahibi şifresi null veya boş olabilir. Yeni sahibi şifresi null veya boş ise, sahip şifresi rastgele bir dizeyle değiştirilecektir. İşlem başarısız olsa da bir istisna fırlatmaz. string inFile = ".D:\\input.pdf"; //TestPath yeniden atanabilir. string outFile = "D:\\output.pdf"; //TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
Kullanıcı şifresini ve sahibi şifresiyle şifreyi değiştirir, PDF belge güvenliğini sıfırlamaya izin verir. Yeni kullanıcı şifresi ve yeni sahibi şifresi null veya boş olabilir. Yeni sahibi şifresi null veya boş ise, sahip şifresi rastgele bir dizeyle değiştirilecektir. KeySize ve Algorithm değerlerinin 6 olası kombinasyonu vardır. Ancak (KeySize.x40, Algorithm.AES) ve (KeySize.x256, Algorithm.RC4) geçersizdir ve kit bu kombinasyonu tespit ederse ilgili istisna yükseltilecektir. İşlem başarısız olsa da bir istisna fırlatmaz. string inFile = "D:\\input.pdf"; //TestPath yeniden atanabilir. string outFile = "D:\\output.pdf"; //TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

### tryDecryptFile {#tryDecryptFile-java.lang.String-}
Şifreli bir Pdf belgesini sahibi şifresiyle çözer. Belgenin sahibi şifresi yoksa, kullanıcı şifresi kullanılmasına izin verilir. İşlem başarısız olsa da bir istisna fırlatmaz. string inFile = "input.pdf"; //TestPath yeniden atanabilir. string outFile = "output.pdf"; //TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.TryDecryptFile("ownerpass");

### tryEncryptFile {#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
Pdf dosyasını kullanıcı şifresi ve sahibi şifresiyle şifreler ve belgenin erişim ayrıcalıklarını ayarlar. Kullanıcı şifresi ve sahibi şifresi null veya boş olabilir. Girdi sahibi şifresi null veya boş ise, sahibi şifresi rastgele bir dizeyle değiştirilecektir. İşlem başarısız olsa da bir istisna fırlatmaz. string inFile = "input.pdf"; //TestPath yeniden atanabilir. string outFile = "output.pdf"; //TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);

### trySetPrivilege {#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
Orijinal şifreyle PDF dosya güvenliğini ayarlar. İşlem başarısız olsa da bir istisna fırlatmaz. string inFile = "D:\\input.pdf"; //TestPath yeniden atanabilir. string outFile = "D:\\output.pdf"; //TestPath yeniden atanabilir. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);
