---
title: "FileFontSource"
linktitle: "FileFontSource"
second_title: "Aspose.PDF for Java API Referansı"
description: "Tek bir yazı tipi dosyası kaynağını temsil eder."
type: docs
weight: 1450
url: /tr/java/com.aspose.pdf/filefontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.FileFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.FileFontSource

```
public final class FileFontSource extends FontSource
```

Tek bir yazı tipi dosyası kaynağını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FileFontSource](#FileFontSource-java.lang.String-) | Yeni bir {@code FileFontSource} sınıfı örneği başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Yazı tipi dosya kaynağı nesnelerinin eşit olup olmadığını kontrol edin. |
| [getFilePath](#getFilePath--) | Yazı tipi dosyasının yolu. |
| [hashCode](#hashCode--) | Nesne için bir karma kod değeri döndürür. Bu yöntem, {@link java.util.HashMap} gibi sağlanan karma tablolarının faydası için desteklenir. <p> {@code hashCode} metodunun genel sözleşmesi şudur: <ul> <li>Bir Java uygulamasının çalışması sırasında aynı nesne üzerinde birden fazla kez çağrıldığında, {@code equals} karşılaştırmalarında kullanılan bilgi değiştirilmediği sürece {@code hashCode} yöntemi tutarlı bir şekilde aynı tam sayıyı döndürmelidir. Bu tam sayı, bir uygulamanın bir çalıştırmasından diğerine aynı kalmak zorunda değildir. <li>İki nesne {@code equals(Object)} metoduna göre eşitse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması aynı tam sayı sonucunu üretmelidir. <li>{@link java.lang.Object#equals(java.lang.Object)} metoduna göre iki nesne eşit değilse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması farklı tam sayı sonuçları üretmesi <em>gerekmez</em>. Ancak, programcı eşit olmayan nesneler için farklı tam sayı sonuçları üretmenin karma tablolarının performansını artırabileceğinin farkında olmalıdır. </ul> <p> Makul ölçüde uygulanabilir olduğu sürece, {@code Object} sınıfı tarafından tanımlanan hashCode metodu farklı nesneler için farklı tam sayılar döndürür. (Bu genellikle nesnenin dahili adresini bir tam sayıya dönüştürerek uygulanır, ancak bu uygulama tekniği Java <span style="font-size:70%"><sup>TM</sup></span> programlama dili tarafından zorunlu kılınmaz.) |
| [setFilePath](#setFilePath-java.lang.String-) | Yazı tipi dosyasının yolu. |

### FileFontSource {#FileFontSource-java.lang.String-}
Yeni bir {@code FileFontSource} sınıfı örneği başlatır.

### equals {#equals-java.lang.Object-}
Yazı tipi dosya kaynağı nesnelerinin eşit olup olmadığını kontrol edin.

### getFilePath {#getFilePath--}
```
public String getFilePath()
```

Yazı tipi dosyasının yolu.

**Returns:**
String değeri

### hashCode {#hashCode--}
```
public int hashCode()
```

Nesne için bir karma kod değeri döndürür. Bu yöntem, {@link java.util.HashMap} gibi sağlanan karma tablolarının faydası için desteklenir. <p> {@code hashCode} metodunun genel sözleşmesi şudur: <ul> <li>Bir Java uygulamasının çalışması sırasında aynı nesne üzerinde birden fazla kez çağrıldığında, {@code equals} karşılaştırmalarında kullanılan bilgi değiştirilmediği sürece {@code hashCode} yöntemi tutarlı bir şekilde aynı tam sayıyı döndürmelidir. Bu tam sayı, bir uygulamanın bir çalıştırmasından diğerine aynı kalmak zorunda değildir. <li>İki nesne {@code equals(Object)} metoduna göre eşitse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması aynı tam sayı sonucunu üretmelidir. <li>{@link java.lang.Object#equals(java.lang.Object)} metoduna göre iki nesne eşit değilse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması farklı tam sayı sonuçları üretmesi <em>gerekmez</em>. Ancak, programcı eşit olmayan nesneler için farklı tam sayı sonuçları üretmenin karma tablolarının performansını artırabileceğinin farkında olmalıdır. </ul> <p> Makul ölçüde uygulanabilir olduğu sürece, {@code Object} sınıfı tarafından tanımlanan hashCode metodu farklı nesneler için farklı tam sayılar döndürür. (Bu genellikle nesnenin dahili adresini bir tam sayıya dönüştürerek uygulanır, ancak bu uygulama tekniği Java <span style="font-size:70%"><sup>TM</sup></span> programlama dili tarafından zorunlu kılınmaz.)

**Returns:**
bu nesne için bir hash kodu değeri. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setFilePath {#setFilePath-java.lang.String-}
Yazı tipi dosyasının yolu.
