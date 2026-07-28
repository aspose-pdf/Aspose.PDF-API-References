---
title: "FolderFontSource"
linktitle: "FolderFontSource"
second_title: "Aspose.PDF for Java API Referansı"
description: "Yazı tipi dosyalarını içeren klasörü temsil eder."
type: docs
weight: 1640
url: /tr/java/com.aspose.pdf/folderfontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.FolderFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.FolderFontSource

```
public final class FolderFontSource extends FontSource
```

Yazı tipi dosyalarını içeren klasörü temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FolderFontSource](#FolderFontSource-java.lang.String-) | Yeni bir {@code FolderFontSource} sınıfı örneği başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Klasör yazı tipi kaynağı nesnelerinin eşit olup olmadığını kontrol edin. |
| [getFolderPath](#getFolderPath--) | Yazı tipi dosyalarını içeren klasörün yolu. |
| [hashCode](#hashCode--) | Objenin bir hash kodu değerini döndürür. Bu yöntem, {@link java.util.HashMap} gibi hash tablolarının faydası için desteklenir. <p> {@code hashCode} metodunun genel sözleşmesi şudur: <ul> <li>Bir Java uygulamasının çalışması sırasında aynı nesne üzerinde birden fazla kez çağrıldığında, {@code hashCode} yöntemi nesne üzerindeki {@code equals} karşılaştırmalarında kullanılan hiçbir bilgi değiştirilmediği sürece aynı tam sayıyı tutarlı bir şekilde döndürmelidir. Bu tam sayı, bir uygulamanın bir çalıştırmasından diğerine aynı kalmak zorunda değildir. <li>Eğer iki nesne {@code equals(Object)} metoduna göre eşitse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması aynı tam sayı sonucunu üretmelidir. <li>{@link java.lang.Object#equals(java.lang.Object)} metoduna göre iki nesne eşit değilse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması farklı tam sayı sonuçları üretmesi <em>gerekmemektedir</em>. Ancak, programcı eşit olmayan nesneler için farklı tam sayı sonuçları üretmenin hash tablolarının performansını artırabileceğinin farkında olmalıdır. </ul> <p> Makul ölçüde pratik olduğu sürece, {@code Object} sınıfı tarafından tanımlanan hashCode yöntemi farklı nesneler için farklı tam sayılar döndürür. (Bu genellikle nesnenin iç adresini bir tam sayıya dönüştürerek uygulanır, ancak bu uygulama tekniği Java<span style="font-size:70%"><sup>TM</sup></span> programlama dili tarafından zorunlu kılınmaz.) |
| [setFolderPath](#setFolderPath-java.lang.String-) |  |

### FolderFontSource {#FolderFontSource-java.lang.String-}
Yeni bir {@code FolderFontSource} sınıfı örneği başlatır.

### equals {#equals-java.lang.Object-}
Klasör yazı tipi kaynağı nesnelerinin eşit olup olmadığını kontrol edin.

### getFolderPath {#getFolderPath--}
```
public String getFolderPath()
```

Yazı tipi dosyalarını içeren klasörün yolu.

**Returns:**
String değeri

### hashCode {#hashCode--}
```
public int hashCode()
```

Objenin bir hash kodu değerini döndürür. Bu yöntem, {@link java.util.HashMap} gibi hash tablolarının faydası için desteklenir. <p> {@code hashCode} metodunun genel sözleşmesi şudur: <ul> <li>Bir Java uygulamasının çalışması sırasında aynı nesne üzerinde birden fazla kez çağrıldığında, {@code hashCode} yöntemi nesne üzerindeki {@code equals} karşılaştırmalarında kullanılan hiçbir bilgi değiştirilmediği sürece aynı tam sayıyı tutarlı bir şekilde döndürmelidir. Bu tam sayı, bir uygulamanın bir çalıştırmasından diğerine aynı kalmak zorunda değildir. <li>Eğer iki nesne {@code equals(Object)} metoduna göre eşitse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması aynı tam sayı sonucunu üretmelidir. <li>{@link java.lang.Object#equals(java.lang.Object)} metoduna göre iki nesne eşit değilse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması farklı tam sayı sonuçları üretmesi <em>gerekmemektedir</em>. Ancak, programcı eşit olmayan nesneler için farklı tam sayı sonuçları üretmenin hash tablolarının performansını artırabileceğinin farkında olmalıdır. </ul> <p> Makul ölçüde pratik olduğu sürece, {@code Object} sınıfı tarafından tanımlanan hashCode yöntemi farklı nesneler için farklı tam sayılar döndürür. (Bu genellikle nesnenin iç adresini bir tam sayıya dönüştürerek uygulanır, ancak bu uygulama tekniği Java<span style="font-size:70%"><sup>TM</sup></span> programlama dili tarafından zorunlu kılınmaz.)

**Returns:**
bu nesne için bir hash kodu değeri. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setFolderPath {#setFolderPath-java.lang.String-}
