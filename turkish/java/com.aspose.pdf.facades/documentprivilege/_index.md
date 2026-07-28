---
title: "DocumentPrivilege"
linktitle: "DocumentPrivilege"
second_title: "Aspose.PDF for Java API Referansı"
description: "Pdf dosyasına erişim için ayrıcalıkları temsil eder. Bakınız{@code PdfFileSecurity}. Bu sınıfı kullanmanın 4 yolu vardır: 1.Önceden tanımlı ayrıcalığı doğrudan kullanma. 2.Bir şeye dayalı."
type: docs
weight: 110
url: /tr/java/com.aspose.pdf.facades/documentprivilege/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.DocumentPrivilege

**All Implemented Interfaces:**
Comparable < Object >

```
public final class DocumentPrivilege extends Object implements Comparable < Object >
```

Pdf dosyasına erişim ayrıcalıklarını temsil eder. {@code PdfFileSecurity}'e bakınız. Bu sınıfı kullanmanın 4 yolu vardır: 1. Önceden tanımlı ayrıcalığı doğrudan kullanmak. 2. Önceden tanımlı bir ayrıcalığa dayanarak bazı belirli izinleri değiştirmek. 3. Önceden tanımlı bir ayrıcalığa dayanarak bazı belirli Adobe Professional izin kombinasyonlarını değiştirmek. 4. yol2 ve yol3'ü karıştırmak. //Way1: Önceden tanımlı ayrıcalığı doğrudan kullanma. DocumentPrivilege privilege = DocumentPrivilege.getPrint(); //Way2: Önceden tanımlı bir ayrıcalığa dayanarak bazı belirli izinleri değiştirme. DocumentPrivilege privilege = DocumentPrivilege.getAllowAll(); privilege.setAllowPrint(false); privilege.setAllowModifyContents(false); //Way3: Önceden tanımlı bir ayrıcalığa dayanarak bazı belirli Adobe Professional izin kombinasyonlarını değiştirme. DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setPrintAllowLevel(2); //Way4: yol2 ve yol3'ü karıştırma DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setAllowPrint(true);

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [compareTo](#compareTo-java.lang.Object-) | İki {@code DocumentPrivilege} nesnesini karşılaştırır. |
| [equals](#equals-java.lang.Object-) | Bir başka nesnenin bu nesneye "eşit" olup olmadığını gösterir. <p> <code>equals</code> yöntemi, null olmayan nesne referansları üzerinde bir eşdeğerlik ilişkisi uygular: <ul> <li>Bu <i>reflexive</i>: herhangi bir null olmayan referans değeri <code>x</code> için, <code>x.equals(x)</code> <code>true</code> döndürmelidir. <li>Bu <i>symmetric</i>: herhangi bir null olmayan referans değerleri <code>x</code> ve <code>y</code> için, <code>x.equals(y)</code> <code>true</code> döndürmelidir ancak ancak <code>y.equals(x)</code> de <code>true</code> döndürürse. <li>Bu <i>transitive</i>: herhangi bir null olmayan referans değerleri <code>x</code>, <code>y</code> ve <code>z</code> için, eğer <code>x.equals(y)</code> <code>true</code> ve <code>y.equals(z)</code> <code>true</code> döndürürse, <code>x.equals(z)</code> de <code>true</code> döndürmelidir. <li>Bu <i>consistent</i>: herhangi bir null olmayan referans değerleri <code>x</code> ve <code>y</code> için, <tt>x.equals(y)</tt> birden çok kez çağrıldığında tutarlı bir şekilde <code>true</code> ya da tutarlı bir şekilde <code>false</code> döndürür, nesneler üzerindeki <code>equals</code> karşılaştırmalarında kullanılan bilgi değiştirilmediği sürece. <li>Herhangi bir null olmayan referans değeri <code>x</code> için, <code>x.equals(null)</code> <code>false</code> döndürmelidir. </ul> <p> <tt>equals</tt> yöntemi, <code>Object</code> sınıfı için nesneler üzerinde mümkün olan en seçici eşdeğerlik ilişkisini uygular; yani, herhangi bir null olmayan referans değerleri <code>x</code> ve <code>y</code> için, bu yöntem <code>true</code> döndürür ancak ancak <code>x</code> ve <code>y</code> aynı nesneye işaret ediyorsa (<code>x == y</code> değeri <code>true</code> olur). <p> Not: bu yöntemi geçersiz kıldığınızda genellikle <tt>hashCode</tt> yönteminin de geçersiz kılınması gerekir, böylece <tt>hashCode</tt> yöntemi için genel sözleşme korunur; bu sözleşme eşit nesnelerin aynı hash koduna sahip olması gerektiğini belirtir. |
| [getAllowAll](#getAllowAll--) | Hepsi izinli. |
| [getAssembly](#getAssembly--) | Dosyanın birleştirilmesine izin verir. |
| [getChangeAllowLevel](#getChangeAllowLevel--) | Belgenin ayrıcalık değişiklik seviyesini alır ve ayarlar. Adobe Professional'ın Changes Allowed ayarları gibi. 0: Hiçbiri. 1: Sayfa ekleme, silme ve döndürme. 2: Form alanlarını doldurma ve mevcut imza alanlarını imzalama. 3: Yorum ekleme, form alanlarını doldurma ve mevcut imza alanlarını imzalama. 4: Sayfa çıkarma dışındaki tüm işlemler. Özellik -1 değerine sahipse, seviye tanımsızdır. |
| [getCopy](#getCopy--) | Dosyanın kopyalanmasına izin verir. |
| [getCopyAllowLevel](#getCopyAllowLevel--) | Belgenin ayrıcalık kopyalama seviyesini alır ve ayarlar. Adobe Professional'ın izin ayarları gibi. 0: Hiçbiri. 1: Görme engelliler için ekran okuyucu cihazlarının metin erişimini etkinleştir. 2: Metin, görüntü ve diğer içeriklerin kopyalanmasını etkinleştir. Özellik -1 değerine sahipse, seviye tanımsızdır. |
| [getDegradedPrinting](#getDegradedPrinting--) | Düşük kaliteli baskıya izin verir. |
| [getFillIn](#getFillIn--) | Dosyada form doldurmaya izin verir. |
| [getForbidAll](#getForbidAll--) | Hepsi yasak. |
| [getModifyAnnotations](#getModifyAnnotations--) | Dosyanın ek açıklamalarını değiştirmeye izin verir. |
| [getModifyContents](#getModifyContents--) | Dosyayı değiştirmeye izin verir. |
| [getPrint](#getPrint--) | Dosyanın yazdırılmasına izin verir. |
| [getPrintAllowLevel](#getPrintAllowLevel--) | Belgenin ayrıcalık yazdırma seviyesini alır ve ayarlar. Adobe Professional'ın Printing Allowed ayarları gibi. 0: Hiçbiri. 1: Düşük Çözünürlük (150 dpi). 2: Yüksek Çözünürlük. Özellik -1 değerine sahipse, seviye tanımsızdır. |
| [getScreenReaders](#getScreenReaders--) | Yalnızca ekranda okunmasına izin verir. |
| [getValue](#getValue--) |  |
| [hashCode](#hashCode--) | Nesne için bir karma kod değeri döndürür. Bu yöntem, <code>java.util.Hashtable</code> gibi sağlanan hash tablolarının faydası için desteklenir. <p> <code>hashCode</code> metodunun genel sözleşmesi şudur: <ul> <li>Bir Java uygulamasının çalışması sırasında aynı nesne üzerinde birden fazla kez çağrıldığında, nesne üzerindeki <tt>equals</tt> karşılaştırmalarında kullanılan bilgi değiştirilmediği sürece <tt>hashCode</tt> yöntemi tutarlı bir şekilde aynı tam sayıyı döndürmelidir. Bu tam sayı, bir uygulama çalıştırmasından diğerine aynı kalmak zorunda değildir. <li><tt>equals(Object)</tt> yöntemine göre iki nesne eşitse, her iki nesnede de <code>hashCode</code> yönteminin çağrılması aynı tam sayı sonucunu üretmelidir. <li>İki nesne {@link java.lang.Object#equals(java.lang.Object)} yöntemine göre eşit değilse, her iki nesnede de <tt>hashCode</tt> yönteminin çağrılması farklı tam sayı sonuçları üretmesi <em>gerekmemektedir</em>. Ancak, programcı eşit olmayan nesneler için farklı tam sayı sonuçları üretmenin hash tablolarının performansını artırabileceğinin farkında olmalıdır. </ul> <p> Mümkün olduğunca pratik bir şekilde, <tt>Object</tt> sınıfı tarafından tanımlanan hashCode yöntemi farklı nesneler için farklı tam sayılar döndürür. (Bu genellikle nesnenin iç adresinin bir tam sayıya dönüştürülmesiyle uygulanır, ancak bu uygulama tekniği Java<span style="font-size:70%"><sup>TM</sup></span> programlama dili tarafından zorunlu kılınmamıştır.) |
| [isAllowAssembly](#isAllowAssembly--) | Montajın izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır. |
| [isAllowCopy](#isAllowCopy--) | Kopyalamanın izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır. |
| [isAllowDegradedPrinting](#isAllowDegradedPrinting--) | Kalitesiz baskının izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır. Ayarlandığında, baskı görünümün düşük seviyeli bir temsiline, muhtemelen kalitesiz bir şekilde sınırlanır. |
| [isAllowFillIn](#isAllowFillIn--) | Form doldurmanın izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır. |
| [isAllowModifyAnnotations](#isAllowModifyAnnotations--) | Ek açıklamaları değiştirmenin izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır. |
| [isAllowModifyContents](#isAllowModifyContents--) | İçerikleri değiştirmenin izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır. |
| [isAllowPrint](#isAllowPrint--) | Yazdırmanın izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır. |
| [isAllowScreenReaders](#isAllowScreenReaders--) | Ekran okuyucuların izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır. |
| [setAllowAssembly](#setAllowAssembly-boolean-) | Montajın izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır. |
| [setAllowCopy](#setAllowCopy-boolean-) | Kopyalamanın izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır. |
| [setAllowDegradedPrinting](#setAllowDegradedPrinting-boolean-) | Kalitesiz baskının izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır. Ayarlandığında, baskı görünümün düşük seviyeli bir temsiline, muhtemelen kalitesiz bir şekilde sınırlanır. |
| [setAllowFillIn](#setAllowFillIn-boolean-) | Form doldurmanın izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır. |
| [setAllowModifyAnnotations](#setAllowModifyAnnotations-boolean-) | Ek açıklamaları değiştirmenin izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır. |
| [setAllowModifyContents](#setAllowModifyContents-boolean-) | İçerikleri değiştirmenin izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır. |
| [setAllowPrint](#setAllowPrint-boolean-) | Yazdırmanın izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır. |
| [setAllowScreenReaders](#setAllowScreenReaders-boolean-) | Ekran okuyucuların izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır. |
| [setChangeAllowLevel](#setChangeAllowLevel-int-) | Belgenin ayrıcalık değişiklik seviyesini alır ve ayarlar. Adobe Professional'ın Changes Allowed ayarları gibi. 0: Hiçbiri. 1: Sayfa ekleme, silme ve döndürme. 2: Form alanlarını doldurma ve mevcut imza alanlarını imzalama. 3: Yorum ekleme, form alanlarını doldurma ve mevcut imza alanlarını imzalama. 4: Sayfa çıkarma dışındaki tüm işlemler. Özellik -1 değerine sahipse, seviye tanımsızdır. |
| [setCopyAllowLevel](#setCopyAllowLevel-int-) | Belgenin ayrıcalık kopyalama seviyesini alır ve ayarlar. Adobe Professional'ın izin ayarları gibi. 0: Hiçbiri. 1: Görme engelliler için ekran okuyucu cihazlarının metin erişimini etkinleştir. 2: Metin, görüntü ve diğer içeriklerin kopyalanmasını etkinleştir. Özellik -1 değerine sahipse, seviye tanımsızdır. |
| [setPrintAllowLevel](#setPrintAllowLevel-int-) | Belgenin ayrıcalık yazdırma seviyesini alır ve ayarlar. Adobe Professional'ın Printing Allowed ayarları gibi. 0: Hiçbiri. 1: Düşük Çözünürlük (150 dpi). 2: Yüksek Çözünürlük. Özellik -1 değerine sahipse, seviye tanımsızdır. |

### compareTo {#compareTo-java.lang.Object-}
İki {@code DocumentPrivilege} nesnesini karşılaştırır.

### equals {#equals-java.lang.Object-}
Bir başka nesnenin bu nesneye "eşit" olup olmadığını gösterir. <p> <code>equals</code> yöntemi, null olmayan nesne referansları üzerinde bir eşdeğerlik ilişkisi uygular: <ul> <li>Bu <i>reflexive</i>: herhangi bir null olmayan referans değeri <code>x</code> için, <code>x.equals(x)</code> <code>true</code> döndürmelidir. <li>Bu <i>symmetric</i>: herhangi bir null olmayan referans değerleri <code>x</code> ve <code>y</code> için, <code>x.equals(y)</code> <code>true</code> döndürmelidir ancak ancak <code>y.equals(x)</code> de <code>true</code> döndürürse. <li>Bu <i>transitive</i>: herhangi bir null olmayan referans değerleri <code>x</code>, <code>y</code> ve <code>z</code> için, eğer <code>x.equals(y)</code> <code>true</code> ve <code>y.equals(z)</code> <code>true</code> döndürürse, <code>x.equals(z)</code> de <code>true</code> döndürmelidir. <li>Bu <i>consistent</i>: herhangi bir null olmayan referans değerleri <code>x</code> ve <code>y</code> için, <tt>x.equals(y)</tt> birden çok kez çağrıldığında tutarlı bir şekilde <code>true</code> ya da tutarlı bir şekilde <code>false</code> döndürür, nesneler üzerindeki <code>equals</code> karşılaştırmalarında kullanılan bilgi değiştirilmediği sürece. <li>Herhangi bir null olmayan referans değeri <code>x</code> için, <code>x.equals(null)</code> <code>false</code> döndürmelidir. </ul> <p> <tt>equals</tt> yöntemi, <code>Object</code> sınıfı için nesneler üzerinde mümkün olan en seçici eşdeğerlik ilişkisini uygular; yani, herhangi bir null olmayan referans değerleri <code>x</code> ve <code>y</code> için, bu yöntem <code>true</code> döndürür ancak ancak <code>x</code> ve <code>y</code> aynı nesneye işaret ediyorsa (<code>x == y</code> değeri <code>true</code> olur). <p> Not: bu yöntemi geçersiz kıldığınızda genellikle <tt>hashCode</tt> yönteminin de geçersiz kılınması gerekir, böylece <tt>hashCode</tt> yöntemi için genel sözleşme korunur; bu sözleşme eşit nesnelerin aynı hash koduna sahip olması gerektiğini belirtir.

### getAllowAll {#getAllowAll--}
```
public static DocumentPrivilege getAllowAll()
```

Hepsi izinli.

**Returns:**
DocumentPrivilege öğesi

### getAssembly {#getAssembly--}
```
public static DocumentPrivilege getAssembly()
```

Dosyanın birleştirilmesine izin verir.

**Returns:**
DocumentPrivilege öğesi

### getChangeAllowLevel {#getChangeAllowLevel--}
```
public final int getChangeAllowLevel()
```

Belgenin ayrıcalık değişiklik seviyesini alır ve ayarlar. Adobe Professional'ın Changes Allowed ayarları gibi. 0: Hiçbiri. 1: Sayfa ekleme, silme ve döndürme. 2: Form alanlarını doldurma ve mevcut imza alanlarını imzalama. 3: Yorum ekleme, form alanlarını doldurma ve mevcut imza alanlarını imzalama. 4: Sayfa çıkarma dışındaki tüm işlemler. Özellik -1 değerine sahipse, seviye tanımsızdır.

**Returns:**
int değer

### getCopy {#getCopy--}
```
public static DocumentPrivilege getCopy()
```

Dosyanın kopyalanmasına izin verir.

**Returns:**
DocumentPrivilege öğesi

### getCopyAllowLevel {#getCopyAllowLevel--}
```
public final int getCopyAllowLevel()
```

Belgenin ayrıcalık kopyalama seviyesini alır ve ayarlar. Adobe Professional'ın izin ayarları gibi. 0: Hiçbiri. 1: Görme engelliler için ekran okuyucu cihazlarının metin erişimini etkinleştir. 2: Metin, görüntü ve diğer içeriklerin kopyalanmasını etkinleştir. Özellik -1 değerine sahipse, seviye tanımsızdır.

**Returns:**
int değer

### getDegradedPrinting {#getDegradedPrinting--}
```
public static DocumentPrivilege getDegradedPrinting()
```

Düşük kaliteli baskıya izin verir.

**Returns:**
DocumentPrivilege öğesi

### getFillIn {#getFillIn--}
```
public static DocumentPrivilege getFillIn()
```

Dosyada form doldurmaya izin verir.

**Returns:**
DocumentPrivilege öğesi

### getForbidAll {#getForbidAll--}
```
public static DocumentPrivilege getForbidAll()
```

Hepsi yasak.

**Returns:**
DocumentPrivilege öğesi

### getModifyAnnotations {#getModifyAnnotations--}
```
public static DocumentPrivilege getModifyAnnotations()
```

Dosyanın ek açıklamalarını değiştirmeye izin verir.

**Returns:**
DocumentPrivilege öğesi

### getModifyContents {#getModifyContents--}
```
public static DocumentPrivilege getModifyContents()
```

Dosyayı değiştirmeye izin verir.

**Returns:**
DocumentPrivilege öğesi

### getPrint {#getPrint--}
```
public static DocumentPrivilege getPrint()
```

Dosyanın yazdırılmasına izin verir.

**Returns:**
DocumentPrivilege öğesi

### getPrintAllowLevel {#getPrintAllowLevel--}
```
public final int getPrintAllowLevel()
```

Belgenin ayrıcalık yazdırma seviyesini alır ve ayarlar. Adobe Professional'ın Printing Allowed ayarları gibi. 0: Hiçbiri. 1: Düşük Çözünürlük (150 dpi). 2: Yüksek Çözünürlük. Özellik -1 değerine sahipse, seviye tanımsızdır.

**Returns:**
int değer

### getScreenReaders {#getScreenReaders--}
```
public static DocumentPrivilege getScreenReaders()
```

Yalnızca ekranda okunmasına izin verir.

**Returns:**
DocumentPrivilege öğesi

### getValue {#getValue--}
```
public final int getValue()
```



### hashCode {#hashCode--}
```
public int hashCode()
```

Nesne için bir karma kod değeri döndürür. Bu yöntem, <code>java.util.Hashtable</code> gibi sağlanan hash tablolarının faydası için desteklenir. <p> <code>hashCode</code> metodunun genel sözleşmesi şudur: <ul> <li>Bir Java uygulamasının çalışması sırasında aynı nesne üzerinde birden fazla kez çağrıldığında, nesne üzerindeki <tt>equals</tt> karşılaştırmalarında kullanılan bilgi değiştirilmediği sürece <tt>hashCode</tt> yöntemi tutarlı bir şekilde aynı tam sayıyı döndürmelidir. Bu tam sayı, bir uygulama çalıştırmasından diğerine aynı kalmak zorunda değildir. <li><tt>equals(Object)</tt> yöntemine göre iki nesne eşitse, her iki nesnede de <code>hashCode</code> yönteminin çağrılması aynı tam sayı sonucunu üretmelidir. <li>İki nesne {@link java.lang.Object#equals(java.lang.Object)} yöntemine göre eşit değilse, her iki nesnede de <tt>hashCode</tt> yönteminin çağrılması farklı tam sayı sonuçları üretmesi <em>gerekmemektedir</em>. Ancak, programcı eşit olmayan nesneler için farklı tam sayı sonuçları üretmenin hash tablolarının performansını artırabileceğinin farkında olmalıdır. </ul> <p> Mümkün olduğunca pratik bir şekilde, <tt>Object</tt> sınıfı tarafından tanımlanan hashCode yöntemi farklı nesneler için farklı tam sayılar döndürür. (Bu genellikle nesnenin iç adresinin bir tam sayıya dönüştürülmesiyle uygulanır, ancak bu uygulama tekniği Java<span style="font-size:70%"><sup>TM</sup></span> programlama dili tarafından zorunlu kılınmamıştır.)

**Returns:**
Bu nesne için bir karma kod değeri. @see java.lang.Object#equals(java.lang.Object) @see java.util.Hashtable

### isAllowAssembly {#isAllowAssembly--}
```
public boolean isAllowAssembly()
```

Montajın izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır.

**Returns:**
boolean değer

### isAllowCopy {#isAllowCopy--}
```
public boolean isAllowCopy()
```

Kopyalamanın izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır.

**Returns:**
boolean değer

### isAllowDegradedPrinting {#isAllowDegradedPrinting--}
```
public boolean isAllowDegradedPrinting()
```

Kalitesiz baskının izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır. Ayarlandığında, baskı görünümün düşük seviyeli bir temsiline, muhtemelen kalitesiz bir şekilde sınırlanır.

**Returns:**
boolean değer

### isAllowFillIn {#isAllowFillIn--}
```
public boolean isAllowFillIn()
```

Form doldurmanın izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır.

**Returns:**
boolean değer

### isAllowModifyAnnotations {#isAllowModifyAnnotations--}
```
public boolean isAllowModifyAnnotations()
```

Ek açıklamaları değiştirmenin izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır.

**Returns:**
boolean değer

### isAllowModifyContents {#isAllowModifyContents--}
```
public boolean isAllowModifyContents()
```

İçerikleri değiştirmenin izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır.

**Returns:**
boolean değer

### isAllowPrint {#isAllowPrint--}
```
public boolean isAllowPrint()
```

Yazdırmanın izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır.

**Returns:**
boolean değer

### isAllowScreenReaders {#isAllowScreenReaders--}
```
public boolean isAllowScreenReaders()
```

Ekran okuyucuların izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır.

**Returns:**
boolean değer

### setAllowAssembly {#setAllowAssembly-boolean-}
```
public void setAllowAssembly(boolean value)
```

Montajın izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setAllowCopy {#setAllowCopy-boolean-}
```
public void setAllowCopy(boolean value)
```

Kopyalamanın izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setAllowDegradedPrinting {#setAllowDegradedPrinting-boolean-}
```
public void setAllowDegradedPrinting(boolean value)
```

Kalitesiz baskının izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır. Ayarlandığında, baskı görünümün düşük seviyeli bir temsiline, muhtemelen kalitesiz bir şekilde sınırlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setAllowFillIn {#setAllowFillIn-boolean-}
```
public void setAllowFillIn(boolean value)
```

Form doldurmanın izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setAllowModifyAnnotations {#setAllowModifyAnnotations-boolean-}
```
public void setAllowModifyAnnotations(boolean value)
```

Ek açıklamaları değiştirmenin izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setAllowModifyContents {#setAllowModifyContents-boolean-}
```
public void setAllowModifyContents(boolean value)
```

İçerikleri değiştirmenin izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setAllowPrint {#setAllowPrint-boolean-}
```
public void setAllowPrint(boolean value)
```

Yazdırmanın izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setAllowScreenReaders {#setAllowScreenReaders-boolean-}
```
public void setAllowScreenReaders(boolean value)
```

Ekran okuyucuların izin verilip verilmediğini ayarlar. true izin verir ve false yasaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setChangeAllowLevel {#setChangeAllowLevel-int-}
```
public void setChangeAllowLevel(int value)
```

Belgenin ayrıcalık değişiklik seviyesini alır ve ayarlar. Adobe Professional'ın Changes Allowed ayarları gibi. 0: Hiçbiri. 1: Sayfa ekleme, silme ve döndürme. 2: Form alanlarını doldurma ve mevcut imza alanlarını imzalama. 3: Yorum ekleme, form alanlarını doldurma ve mevcut imza alanlarını imzalama. 4: Sayfa çıkarma dışındaki tüm işlemler. Özellik -1 değerine sahipse, seviye tanımsızdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setCopyAllowLevel {#setCopyAllowLevel-int-}
```
public void setCopyAllowLevel(int value)
```

Belgenin ayrıcalık kopyalama seviyesini alır ve ayarlar. Adobe Professional'ın izin ayarları gibi. 0: Hiçbiri. 1: Görme engelliler için ekran okuyucu cihazlarının metin erişimini etkinleştir. 2: Metin, görüntü ve diğer içeriklerin kopyalanmasını etkinleştir. Özellik -1 değerine sahipse, seviye tanımsızdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setPrintAllowLevel {#setPrintAllowLevel-int-}
```
public void setPrintAllowLevel(int value)
```

Belgenin ayrıcalık yazdırma seviyesini alır ve ayarlar. Adobe Professional'ın Printing Allowed ayarları gibi. 0: Hiçbiri. 1: Düşük Çözünürlük (150 dpi). 2: Yüksek Çözünürlük. Özellik -1 değerine sahipse, seviye tanımsızdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |
