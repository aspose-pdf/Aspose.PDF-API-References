---
title: "Position"
linktitle: "Position"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bir konum nesnesini temsil eder."
type: docs
weight: 3940
url: /tr/java/com.aspose.pdf/position/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Position

```
public final class Position extends Object
```

Bir konum nesnesini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Position](#Position-double-double-) | Yeni bir {@code Position} sınıfı örneği başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Belirtilen nesnenin mevcut {@code Position} nesnesine eşit olup olmadığını belirler. |
| [getXIndent](#getXIndent--) | Nesnenin X koordinatını alır. |
| [getYIndent](#getYIndent--) | Nesnenin Y koordinatını alır. |
| [hashCode](#hashCode--) | Objenin bir hash kodu değerini döndürür. Bu yöntem, {@link java.util.HashMap} gibi hash tablolarının faydası için desteklenir. <p> {@code hashCode} metodunun genel sözleşmesi şudur: <ul> <li>Bir Java uygulamasının çalışması sırasında aynı nesne üzerinde birden fazla kez çağrıldığında, {@code hashCode} yöntemi nesne üzerindeki {@code equals} karşılaştırmalarında kullanılan hiçbir bilgi değiştirilmediği sürece aynı tam sayıyı tutarlı bir şekilde döndürmelidir. Bu tam sayı, bir uygulamanın bir çalıştırmasından diğerine aynı kalmak zorunda değildir. <li>Eğer iki nesne {@code equals(Object)} metoduna göre eşitse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması aynı tam sayı sonucunu üretmelidir. <li>{@link java.lang.Object#equals(java.lang.Object)} metoduna göre iki nesne eşit değilse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması farklı tam sayı sonuçları üretmesi <em>gerekmemektedir</em>. Ancak, programcı eşit olmayan nesneler için farklı tam sayı sonuçları üretmenin hash tablolarının performansını artırabileceğinin farkında olmalıdır. </ul> <p> Makul ölçüde pratik olduğu sürece, {@code Object} sınıfı tarafından tanımlanan hashCode yöntemi farklı nesneler için farklı tam sayılar döndürür. (Bu genellikle nesnenin iç adresini bir tam sayıya dönüştürerek uygulanır, ancak bu uygulama tekniği Java<span style="font-size:70%"><sup>TM</sup></span> programlama dili tarafından zorunlu kılınmaz.) |
| [setXIndent](#setXIndent-double-) | Nesnenin X koordinatını ayarlar. |
| [setYIndent](#setYIndent-double-) | Nesnenin Y koordinatını ayarlar. |
| [toString](#toString--) | Mevcut {@code Position} nesnesi için dize temsilini alır. |

### Position {#Position-double-double-}
```
public Position(double xIndent, double yIndent)
```

Yeni bir {@code Position} sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xIndent |  | X koordinat değeri. |
| yIndent |  | Y koordinat değeri. |

### equals {#equals-java.lang.Object-}
Belirtilen nesnenin mevcut {@code Position} nesnesine eşit olup olmadığını belirler.

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Nesnenin X koordinatını alır.

**Returns:**
double değer

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Nesnenin Y koordinatını alır.

**Returns:**
double değer

### hashCode {#hashCode--}
```
public int hashCode()
```

Objenin bir hash kodu değerini döndürür. Bu yöntem, {@link java.util.HashMap} gibi hash tablolarının faydası için desteklenir. <p> {@code hashCode} metodunun genel sözleşmesi şudur: <ul> <li>Bir Java uygulamasının çalışması sırasında aynı nesne üzerinde birden fazla kez çağrıldığında, {@code hashCode} yöntemi nesne üzerindeki {@code equals} karşılaştırmalarında kullanılan hiçbir bilgi değiştirilmediği sürece aynı tam sayıyı tutarlı bir şekilde döndürmelidir. Bu tam sayı, bir uygulamanın bir çalıştırmasından diğerine aynı kalmak zorunda değildir. <li>Eğer iki nesne {@code equals(Object)} metoduna göre eşitse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması aynı tam sayı sonucunu üretmelidir. <li>{@link java.lang.Object#equals(java.lang.Object)} metoduna göre iki nesne eşit değilse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması farklı tam sayı sonuçları üretmesi <em>gerekmemektedir</em>. Ancak, programcı eşit olmayan nesneler için farklı tam sayı sonuçları üretmenin hash tablolarının performansını artırabileceğinin farkında olmalıdır. </ul> <p> Makul ölçüde pratik olduğu sürece, {@code Object} sınıfı tarafından tanımlanan hashCode yöntemi farklı nesneler için farklı tam sayılar döndürür. (Bu genellikle nesnenin iç adresini bir tam sayıya dönüştürerek uygulanır, ancak bu uygulama tekniği Java<span style="font-size:70%"><sup>TM</sup></span> programlama dili tarafından zorunlu kılınmaz.)

**Returns:**
bu nesne için bir hash kodu değeri. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Nesnenin X koordinatını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Nesnenin Y koordinatını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### toString {#toString--}
```
public String toString()
```

Mevcut {@code Position} nesnesi için dize temsilini alır.

**Returns:**
Position nesnesinin dize temsili.
