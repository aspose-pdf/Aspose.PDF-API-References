---
title: "SystemFontSource"
linktitle: "SystemFontSource"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sisteme yüklü tüm yazı tiplerini temsil eder."
type: docs
weight: 4770
url: /tr/java/com.aspose.pdf/systemfontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.SystemFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.SystemFontSource

```
public final class SystemFontSource extends FontSource
```

Sisteme yüklü tüm yazı tiplerini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SystemFontSource](#SystemFontSource--) | Sınıfın yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Sistem yazı tipi kaynağı nesnelerinin eşit olup olmadığını denetle. |
| [getFontDefinitions](#getFontDefinitions--) | Yalnızca dahili kullanım için |
| [hashCode](#hashCode--) | Objenin bir hash kodu değerini döndürür. Bu yöntem, {@link java.util.HashMap} gibi hash tablolarının faydası için desteklenir. <p> {@code hashCode} metodunun genel sözleşmesi şudur: <ul> <li>Bir Java uygulamasının çalışması sırasında aynı nesne üzerinde birden fazla kez çağrıldığında, {@code hashCode} yöntemi nesne üzerindeki {@code equals} karşılaştırmalarında kullanılan hiçbir bilgi değiştirilmediği sürece aynı tam sayıyı tutarlı bir şekilde döndürmelidir. Bu tam sayı, bir uygulamanın bir çalıştırmasından diğerine aynı kalmak zorunda değildir. <li>Eğer iki nesne {@code equals(Object)} metoduna göre eşitse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması aynı tam sayı sonucunu üretmelidir. <li>{@link java.lang.Object#equals(java.lang.Object)} metoduna göre iki nesne eşit değilse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması farklı tam sayı sonuçları üretmesi <em>gerekmemektedir</em>. Ancak, programcı eşit olmayan nesneler için farklı tam sayı sonuçları üretmenin hash tablolarının performansını artırabileceğinin farkında olmalıdır. </ul> <p> Makul ölçüde pratik olduğu sürece, {@code Object} sınıfı tarafından tanımlanan hashCode yöntemi farklı nesneler için farklı tam sayılar döndürür. (Bu genellikle nesnenin iç adresini bir tam sayıya dönüştürerek uygulanır, ancak bu uygulama tekniği Java<span style="font-size:70%"><sup>TM</sup></span> programlama dili tarafından zorunlu kılınmaz.) |

### SystemFontSource {#SystemFontSource--}
```
public SystemFontSource()
```

Sınıfın yeni bir örneğini başlatır.

### equals {#equals-java.lang.Object-}
Sistem yazı tipi kaynağı nesnelerinin eşit olup olmadığını denetle.

### getFontDefinitions {#getFontDefinitions--}
```
public com.aspose.font.FontDefinition[] getFontDefinitions()
```

Yalnızca dahili kullanım için

**Returns:**
FontDefinition[] nesnesi

### hashCode {#hashCode--}
```
public int hashCode()
```

Objenin bir hash kodu değerini döndürür. Bu yöntem, {@link java.util.HashMap} gibi hash tablolarının faydası için desteklenir. <p> {@code hashCode} metodunun genel sözleşmesi şudur: <ul> <li>Bir Java uygulamasının çalışması sırasında aynı nesne üzerinde birden fazla kez çağrıldığında, {@code hashCode} yöntemi nesne üzerindeki {@code equals} karşılaştırmalarında kullanılan hiçbir bilgi değiştirilmediği sürece aynı tam sayıyı tutarlı bir şekilde döndürmelidir. Bu tam sayı, bir uygulamanın bir çalıştırmasından diğerine aynı kalmak zorunda değildir. <li>Eğer iki nesne {@code equals(Object)} metoduna göre eşitse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması aynı tam sayı sonucunu üretmelidir. <li>{@link java.lang.Object#equals(java.lang.Object)} metoduna göre iki nesne eşit değilse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması farklı tam sayı sonuçları üretmesi <em>gerekmemektedir</em>. Ancak, programcı eşit olmayan nesneler için farklı tam sayı sonuçları üretmenin hash tablolarının performansını artırabileceğinin farkında olmalıdır. </ul> <p> Makul ölçüde pratik olduğu sürece, {@code Object} sınıfı tarafından tanımlanan hashCode yöntemi farklı nesneler için farklı tam sayılar döndürür. (Bu genellikle nesnenin iç adresini bir tam sayıya dönüştürerek uygulanır, ancak bu uygulama tekniği Java<span style="font-size:70%"><sup>TM</sup></span> programlama dili tarafından zorunlu kılınmaz.)

**Returns:**
bu nesne için bir hash kodu değeri. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode
