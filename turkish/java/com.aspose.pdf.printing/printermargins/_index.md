---
title: "PrinterMargins"
linktitle: "PrinterMargins"
second_title: "Aspose.PDF for Java API Referansı"
description: "Yazdırılan bir sayfanın kenar boşluklarının boyutlarını belirtir."
type: docs
weight: 70
url: /tr/java/com.aspose.pdf.printing/printermargins/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrinterMargins

```
public class PrinterMargins extends Object
```

Yazdırılan bir sayfanın kenar boşluklarının boyutlarını belirtir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PrinterMargins](#PrinterMargins--) | Margins sınıfının 1 inç genişliğinde kenar boşluklarıyla yeni bir örneğini başlatır. |
| [PrinterMargins](#PrinterMargins-int-int-int-int-) | Margins sınıfının belirtilen sol, sağ, üst ve alt kenar boşluklarıyla yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [deepClone](#deepClone--) | Bu nesnenin, üye üye bir kopyasını alır. |
| [equals](#equals-java.lang.Object-) | Bu Margins'ı belirtilen Nesne ile karşılaştırarak aynı boyutlara sahip olup olmadığını belirler. (Object.Equals(Object) yöntemini geçersiz kılar.) |
| [getBottom](#getBottom--) | Alt kenar boşluğunu, inçin yüzde yüzde biri cinsinden alır veya ayarlar. |
| [getLeft](#getLeft--) | Sol kenar boşluğu genişliğini, inçin yüzde yüzde biri cinsinden alır veya ayarlar. |
| [getRight](#getRight--) | Sağ kenar boşluğu genişliğini, inçin yüzde yüzde biri cinsinden alır veya ayarlar. |
| [getTop](#getTop--) | Üst kenar boşluğu genişliğini, inçin yüzde yüzde biri cinsinden alır veya ayarlar. |
| [hashCode](#hashCode--) | Objenin bir hash kodu değerini döndürür. Bu yöntem, {@link java.util.HashMap} gibi hash tablolarının faydası için desteklenir. <p> {@code hashCode} metodunun genel sözleşmesi şudur: <ul> <li>Bir Java uygulamasının çalışması sırasında aynı nesne üzerinde birden fazla kez çağrıldığında, {@code hashCode} yöntemi nesne üzerindeki {@code equals} karşılaştırmalarında kullanılan hiçbir bilgi değiştirilmediği sürece aynı tam sayıyı tutarlı bir şekilde döndürmelidir. Bu tam sayı, bir uygulamanın bir çalıştırmasından diğerine aynı kalmak zorunda değildir. <li>Eğer iki nesne {@code equals(Object)} metoduna göre eşitse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması aynı tam sayı sonucunu üretmelidir. <li>{@link java.lang.Object#equals(java.lang.Object)} metoduna göre iki nesne eşit değilse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması farklı tam sayı sonuçları üretmesi <em>gerekmemektedir</em>. Ancak, programcı eşit olmayan nesneler için farklı tam sayı sonuçları üretmenin hash tablolarının performansını artırabileceğinin farkında olmalıdır. </ul> <p> Makul ölçüde pratik olduğu sürece, {@code Object} sınıfı tarafından tanımlanan hashCode yöntemi farklı nesneler için farklı tam sayılar döndürür. (Bu genellikle nesnenin iç adresini bir tam sayıya dönüştürerek uygulanır, ancak bu uygulama tekniği Java<span style="font-size:70%"><sup>TM</sup></span> programlama dili tarafından zorunlu kılınmaz.) |
| [op_Equality](#op_Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | İki Margins'ı aynı boyutlara sahip olup olmadığını belirlemek için karşılaştırır. |
| [op_Inequality](#op_Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | İki Margins'ı farklı genişlikte olup olmadığını belirlemek için karşılaştırır. |
| [setBottom](#setBottom-int-) | Alt kenar boşluğunu, inçin yüzde yüzde biri cinsinden alır veya ayarlar. |
| [setLeft](#setLeft-int-) | Sol kenar boşluğu genişliğini, inçin yüzde yüzde biri cinsinden alır veya ayarlar. |
| [setRight](#setRight-int-) | Sağ kenar boşluğu genişliğini, inçin yüzde yüzde biri cinsinden alır veya ayarlar. |
| [setTop](#setTop-int-) | Üst kenar boşluğu genişliğini, inçin yüzde yüzde biri cinsinden alır veya ayarlar. |

### PrinterMargins {#PrinterMargins--}
```
public PrinterMargins()
```

Margins sınıfının 1 inç genişliğinde kenar boşluklarıyla yeni bir örneğini başlatır.

### PrinterMargins {#PrinterMargins-int-int-int-int-}
```
public PrinterMargins(int left, int right, int top, int bottom)
```

Margins sınıfının belirtilen sol, sağ, üst ve alt kenar boşluklarıyla yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sol |  | int değer |
| sağ |  | int değer |
| üst |  | int değer |
| alt |  | int değer |

### deepClone {#deepClone--}
```
public PrinterMargins deepClone()
```

Bu nesnenin, üye üye bir kopyasını alır.

**Returns:**
PrinterMargins nesnesi

### equals {#equals-java.lang.Object-}
Bu Margins'ı belirtilen Nesne ile karşılaştırarak aynı boyutlara sahip olup olmadığını belirler. (Object.Equals(Object) yöntemini geçersiz kılar.)

### getBottom {#getBottom--}
```
public int getBottom()
```

Alt kenar boşluğunu, inçin yüzde yüzde biri cinsinden alır veya ayarlar.

**Returns:**
int değer

### getLeft {#getLeft--}
```
public int getLeft()
```

Sol kenar boşluğu genişliğini, inçin yüzde yüzde biri cinsinden alır veya ayarlar.

**Returns:**
int değer

### getRight {#getRight--}
```
public int getRight()
```

Sağ kenar boşluğu genişliğini, inçin yüzde yüzde biri cinsinden alır veya ayarlar.

**Returns:**
int değer

### getTop {#getTop--}
```
public int getTop()
```

Üst kenar boşluğu genişliğini, inçin yüzde yüzde biri cinsinden alır veya ayarlar.

**Returns:**
int değer

### hashCode {#hashCode--}
```
public int hashCode()
```

Objenin bir hash kodu değerini döndürür. Bu yöntem, {@link java.util.HashMap} gibi hash tablolarının faydası için desteklenir. <p> {@code hashCode} metodunun genel sözleşmesi şudur: <ul> <li>Bir Java uygulamasının çalışması sırasında aynı nesne üzerinde birden fazla kez çağrıldığında, {@code hashCode} yöntemi nesne üzerindeki {@code equals} karşılaştırmalarında kullanılan hiçbir bilgi değiştirilmediği sürece aynı tam sayıyı tutarlı bir şekilde döndürmelidir. Bu tam sayı, bir uygulamanın bir çalıştırmasından diğerine aynı kalmak zorunda değildir. <li>Eğer iki nesne {@code equals(Object)} metoduna göre eşitse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması aynı tam sayı sonucunu üretmelidir. <li>{@link java.lang.Object#equals(java.lang.Object)} metoduna göre iki nesne eşit değilse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması farklı tam sayı sonuçları üretmesi <em>gerekmemektedir</em>. Ancak, programcı eşit olmayan nesneler için farklı tam sayı sonuçları üretmenin hash tablolarının performansını artırabileceğinin farkında olmalıdır. </ul> <p> Makul ölçüde pratik olduğu sürece, {@code Object} sınıfı tarafından tanımlanan hashCode yöntemi farklı nesneler için farklı tam sayılar döndürür. (Bu genellikle nesnenin iç adresini bir tam sayıya dönüştürerek uygulanır, ancak bu uygulama tekniği Java<span style="font-size:70%"><sup>TM</sup></span> programlama dili tarafından zorunlu kılınmaz.)

**Returns:**
bu nesne için bir hash kodu değeri. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### op_Equality {#op_Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
İki Margins'ı aynı boyutlara sahip olup olmadığını belirlemek için karşılaştırır.

### op_Inequality {#op_Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
İki Margins'ı farklı genişlikte olup olmadığını belirlemek için karşılaştırır.

### setBottom {#setBottom-int-}
```
public void setBottom(int value)
```

Alt kenar boşluğunu, inçin yüzde yüzde biri cinsinden alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setLeft {#setLeft-int-}
```
public void setLeft(int value)
```

Sol kenar boşluğu genişliğini, inçin yüzde yüzde biri cinsinden alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setRight {#setRight-int-}
```
public void setRight(int value)
```

Sağ kenar boşluğu genişliğini, inçin yüzde yüzde biri cinsinden alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setTop {#setTop-int-}
```
public void setTop(int value)
```

Üst kenar boşluğu genişliğini, inçin yüzde yüzde biri cinsinden alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |
