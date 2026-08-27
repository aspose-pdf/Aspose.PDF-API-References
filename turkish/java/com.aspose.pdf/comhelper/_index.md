---
title: "ComHelper"
linktitle: "ComHelper"
second_title: "Aspose.PDF for Java API Referansı"
description: "<p> COM istemcileri için bir belgeyi Aspose.PDF'e yükleme yöntemleri sağlar. </p> <hr> <p> ComHelper sınıfını kullanarak bir dosyadan veya akıştan bir belgeyi Document nesnesine yükleyin.</p>"
type: docs
weight: 760
url: /tr/java/com.aspose.pdf/comhelper/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ComHelper

```
public class ComHelper extends Object
```

<p> COM istemcilerine bir belgeyi Aspose.PDF'ye yüklemek için yöntemler sağlar. </p> <hr> <p> COM uygulamasında bir dosya veya akıştan bir Document nesnesine belge yüklemek için ComHelper sınıfını kullanın. Document sınıfı yeni bir belge oluşturmak için varsayılan bir yapıcı sağlar ve ayrıca bir dosya veya akıştan belge yüklemek için aşırı yüklenmiş yapıcılar sunar. .NET uygulamasında Aspose.Words kullanıyorsanız, Document yapıcılarının tümünü doğrudan kullanabilirsiniz, ancak bir COM uygulamasında Aspose.PDF kullanıyorsanız yalnızca varsayılan Document yapıcısı mevcuttur. </p>

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ComHelper](#ComHelper--) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [openFile](#openFile-java.lang.String-) | Sadece {@code filename} kullanarak Document oluşturup döndürün. {@code Document(Stream)} ile aynı. |
| [openFile](#openFile-java.lang.String-com.aspose.pdf.LoadOptions-) | Gerekli dönüştürme seçeneklerini sağlayarak bir dosyadan mevcut bir belgeyi açın ve PDF belgesi elde edin. |
| [openFile](#openFile-java.lang.String-java.lang.String-) | Şifreli belgeyle çalışmak için {@code Document} sınıfının yeni bir örneğini başlatıp döndürün. |
| [openFile](#openFile-java.lang.String-java.lang.String-boolean-) | Şifreli belgeyle çalışmak için {@code Document} sınıfının yeni bir örneğini başlatın. |
| [openStream](#openStream-java.io.InputStream-) | {@code input} akışından yeni bir Document örneğini başlatıp döndürün. |
| [openStream](#openStream-java.io.InputStream-boolean-) | {@code input} akışından yeni bir Document örneğini başlatıp döndürün. |
| [openStream](#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Gerekli dönüştürmeyi sağlayarak bir akıştan mevcut bir belgeyi açıp döndürün, PDF belgesi elde edin. |
| [openStream](#openStream-java.io.InputStream-java.lang.String-) | {@code input} akışından yeni bir Document örneğini başlatıp döndürün. |
| [openStream](#openStream-java.io.InputStream-java.lang.String-boolean-) | {@code input} akışından yeni bir Document örneğini başlatıp döndürün. |

### ComHelper {#ComHelper--}
```
public ComHelper()
```



### openFile {#openFile-java.lang.String-}
Sadece {@code filename} kullanarak Document oluşturup döndürün. {@code Document(Stream)} ile aynı.

### openFile {#openFile-java.lang.String-com.aspose.pdf.LoadOptions-}
Gerekli dönüştürme seçeneklerini sağlayarak bir dosyadan mevcut bir belgeyi açın ve PDF belgesi elde edin.

### openFile {#openFile-java.lang.String-java.lang.String-}
Şifreli belgeyle çalışmak için {@code Document} sınıfının yeni bir örneğini başlatıp döndürün.

### openFile {#openFile-java.lang.String-java.lang.String-boolean-}
Şifreli belgeyle çalışmak için {@code Document} sınıfının yeni bir örneğini başlatın.

### openStream {#openStream-java.io.InputStream-}
{@code input} akışından yeni bir Document örneğini başlatıp döndürün.

### openStream {#openStream-java.io.InputStream-boolean-}
{@code input} akışından yeni bir Document örneğini başlatıp döndürün.

### openStream {#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-}
Gerekli dönüştürmeyi sağlayarak bir akıştan mevcut bir belgeyi açıp döndürün, PDF belgesi elde edin.

### openStream {#openStream-java.io.InputStream-java.lang.String-}
{@code input} akışından yeni bir Document örneğini başlatıp döndürün.

### openStream {#openStream-java.io.InputStream-java.lang.String-boolean-}
{@code input} akışından yeni bir Document örneğini başlatıp döndürün.
