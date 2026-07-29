---
title: "PdfPageEditor"
linktitle: "PdfPageEditor"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF dosyasının sayfasını düzenlemek için bir sınıfı temsil eder; sayfayı döndürme, yakınlaştırma, konum taşıma ve sayfa boyutunu değiştirme gibi işlemleri içerir."
type: docs
weight: 570
url: /tr/java/com.aspose.pdf.facades/pdfpageeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfPageEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfPageEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfPageEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfPageEditor extends SaveableFacade
```

PDF dosyasının sayfasını düzenlemek için bir sınıfı temsil eder; sayfayı döndürme, yakınlaştırma, konum taşıma ve sayfa boyutunu değiştirme gibi işlemleri içerir.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [BLINDH](#BLINDH) | Dikey Storlar |
| [BLINDV](#BLINDV) | Dikey Storlar |
| [BTWIPE](#BTWIPE) | Alt-Üst Silme |
| [DGLITTER](#DGLITTER) | Diyagonal Parıltı |
| [DISSOLVE](#DISSOLVE) | Eski sayfa çözülür |
| [INBOX](#INBOX) | İçe Doğru Kutu |
| [LRGLITTER](#LRGLITTER) | Sol-Sağ Parıltı |
| [LRWIPE](#LRWIPE) | Sol-Sağ Silme |
| [OUTBOX](#OUTBOX) | Dışa Doğru Kutu |
| [RLWIPE](#RLWIPE) | Sağ-Sol Silme |
| [SPLITHIN](#SPLITHIN) | İÇ Yatay Bölme |
| [SPLITHOUT](#SPLITHOUT) | Dış Yatay Bölme |
| [SPLITVIN](#SPLITVIN) | İç Dikey Bölme |
| [SPLITVOUT](#SPLITVOUT) | Dış Dikey Bölme |
| [TBGLITTER](#TBGLITTER) | Üst-Alt Parıltı |
| [TBWIPE](#TBWIPE) | Üst-Alt Silme |

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfPageEditor](#PdfPageEditor--) | PdfPageEditor sınıfı için yapıcı. |
| [PdfPageEditor](#PdfPageEditor-com.aspose.pdf.Document-) | PdfPageEditor sınıfı için yapıcı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [applyChanges](#applyChanges--) | Belge sayfalarına yapılan değişiklikleri uygula. |
| [getAlignment](#getAlignment--) | Sonuç sayfasındaki orijinal PDF içeriğinin yatay hizalamasını alır, varsayılan AlignmentType.Left'tir. Bunun yerine getHorizontalAlignment kullanın |
| [getDisplayDuration](#getDisplayDuration--) | Sayfalar için görüntüleme süresini alır. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Sonuç sayfasındaki orijinal PDF içeriğinin yatay hizalamasını alır, varsayılan AlignmentType.Left'tir. |
| [getPageBoxSize](#getPageBoxSize-int-java.lang.String-) | <p> Belgedeki belirtilen kutunun boyutunu döndürür. </p> <hr> <pre> Aşağıdaki örnek, 1. sayfanın medya kutusunu nasıl alacağınızı gösterir: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); Rectangle rect = editor.getBoxSize(1, "media"); </pre> |
| [getPageRectangle](#getPageRectangle-com.aspose.pdf.Page-) | Sayfanın boyutunu döndür. |
| [getPageRotation](#getPageRotation-int-) | <p> Belirtilen sayfanın dönüşünü döndürür. </p> <hr> <pre> Aşağıdaki örnek, sayfa dönüşünün nasıl alınacağını gösterir: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); int rotation = editor.getPageSize(1); System.out.println("Rotation of 1st page : " + rotation + " degrees"); </pre> |
| [getPageRotations](#getPageRotations--) | <p> Sayfaların dönüşünü alır, bir hashtable sayfa numarasını ve dönüş derecesini içerir, anahtar sayfa numarasını temsil eder, anahtarın değeri ise dönüşü derece cinsinden temsil eder. </p> |
| [getPages](#getPages--) | <p> Toplam sayfa sayısını döndürür. </p> <hr> <pre> Aşağıdaki örnek, GetPages() metodunun kullanımını gösterir: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); System.out.println("Document has: " + editor.GetPages()); </pre> |
| [getPageSize](#getPageSize--) | Çıktı dosyasının sayfa boyutunu alır. |
| [getPageSize](#getPageSize-int-) | <p> Belirtilen sayfanın sayfa boyutunu döndürür. </p> <hr> <pre> Aşağıdaki örnek, GetPageSize metodunun kullanımını gösterir: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); PageSize size = editor.getPageSize(1); System.out.println("Size of 1st page : " + size.getWidth() + " x " + size.getHeight()); </pre> |
| [getProcessPages](#getProcessPages--) | Düzenlenecek sayfa numaralarını alır. Varsayılan olarak, her sayfa düzenlenecektir. |
| [getRotation](#getRotation--) | Sayfaların dönüşünü alır, dönüş 0, 90, 180 veya 270 olmalıdır. Varsayılan değer 0'dır. |
| [getTransitionDuration](#getTransitionDuration--) | Geçiş efektinin süresini alır. |
| [getTransitionType](#getTransitionType--) | Sunum sırasında bu sayfaya başka bir sayfadan geçiş yaparken kullanılacak geçiş stilini alır. |
| [getVerticalAlignment](#getVerticalAlignment--) | Orijinal PDF içeriğinin sonuç sayfasındaki dikey hizalamasını alır, varsayılan VerticalAlignmentType.Bottom'tır. Bunun yerine getVerticalAlignmentType kullanın |
| [getVerticalAlignmentType](#getVerticalAlignmentType--) | Orijinal PDF içeriğinin sonuç sayfasındaki dikey hizalamasını alır, varsayılan VerticalAlignmentType.Bottom'tır. |
| [getZoom](#getZoom--) | Yakınlaştırma katsayısını al. Değer 1.0 %100'e karşılık gelir. Varsayılan değer 1.0'dır. |
| [isBoxDefined](#isBoxDefined-com.aspose.pdf.Page-java.lang.String-) | Kutunun sayfada tanımlı olup olmadığını kontrol et. |
| [movePosition](#movePosition-float-float-) | <p> Kökeni (0, 0)'dan belirtilen noktaya taşır. Köken sol-alt köşededir ve birim point'tir (1 inç = 72 point). </p> <hr> <pre> PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("input.pdf"); editor.movePosition(-100, 60); editor.save("moved.pdf"); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Değiştirilen belgeyi akışa kaydeder. </p> <hr> <pre> Aşağıdaki örnek, değiştirilen PDF belgesinin akışa nasıl kaydedileceğini gösterir. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre> |
| [save](#save-java.lang.String-) | <p> Değiştirilen belgeyi dosyaya kaydeder. </p> <hr> <pre> Aşağıdaki örnek, değiştirilen PDF belgesinin nasıl kaydedileceğini gösterir PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre> |
| [setAlignment](#setAlignment-com.aspose.pdf.facades.AlignmentType-) | Orijinal PDF içeriğinin sonuç sayfasındaki yatay hizalamasını ayarlar, varsayılan AlignmentType.Left'tır. Bunun yerine setHorizontalAlignment kullanın |
| [setDisplayDuration](#setDisplayDuration-int-) | Sayfalar için görüntüleme süresini ayarlar. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Orijinal PDF içeriğinin sonuç sayfasındaki yatay hizalamasını ayarlar, varsayılan AlignmentType.Left'tır. |
| [setPageRotations](#setPageRotations-java.util.Map-) | Sayfaların dönüşünü ayarlar, bir hashtable sayfa numarasını ve dönüş derecesini içerir, anahtar sayfa numarasını temsil eder, anahtarın değeri ise dönüşü derece cinsinden temsil eder. |
| [setPageSize](#setPageSize-com.aspose.pdf.PageSize-) | Çıktı dosyasının sayfa boyutunu ayarlar. |
| [setProcessPages](#setProcessPages-int:A-) | Düzenlenecek sayfa numaralarını ayarlar. Varsayılan olarak, her sayfa düzenlenecektir. |
| [setRotation](#setRotation-int-) | Sayfaların dönüşünü ayarlar, dönüş 0, 90, 180 veya 270 olmalıdır. Varsayılan değer 0'dır. |
| [setTransitionDuration](#setTransitionDuration-int-) | Geçiş efektinin süresini ayarlar. |
| [setTransitionType](#setTransitionType-int-) | Sunum sırasında bu sayfaya başka bir sayfadan geçiş yaparken kullanılacak geçiş stilini ayarlar. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-) | Orijinal PDF içeriğinin sonuç sayfasındaki dikey hizalamasını ayarlar, varsayılan değer VerticalAlignmentType.Bottom'dur. Bunun yerine setVerticalAlignmentType kullanın. |
| [setVerticalAlignmentType](#setVerticalAlignmentType-com.aspose.pdf.VerticalAlignment-) | Orijinal PDF içeriğinin sonuç sayfasındaki dikey hizalamasını ayarlar, varsayılan değer VerticalAlignmentType.Bottom'dur. |
| [setZoom](#setZoom-float-) | <p> Zoom katsayısını ayarlar. 1.0 değeri %100'e karşılık gelir. Varsayılan değer 1.0'dır. </p> |

### BLINDH {#BLINDH}
```
public static final int BLINDH
```

Dikey Storlar

### BLINDV {#BLINDV}
```
public static final int BLINDV
```

Dikey Storlar

### BTWIPE {#BTWIPE}
```
public static final int BTWIPE
```

Alt-Üst Silme

### DGLITTER {#DGLITTER}
```
public static final int DGLITTER
```

Diyagonal Parıltı

### DISSOLVE {#DISSOLVE}
```
public static final int DISSOLVE
```

Eski sayfa çözülür

### INBOX {#INBOX}
```
public static final int INBOX
```

İçe Doğru Kutu

### LRGLITTER {#LRGLITTER}
```
public static final int LRGLITTER
```

Sol-Sağ Parıltı

### LRWIPE {#LRWIPE}
```
public static final int LRWIPE
```

Sol-Sağ Silme

### OUTBOX {#OUTBOX}
```
public static final int OUTBOX
```

Dışa Doğru Kutu

### RLWIPE {#RLWIPE}
```
public static final int RLWIPE
```

Sağ-Sol Silme

### SPLITHIN {#SPLITHIN}
```
public static final int SPLITHIN
```

İÇ Yatay Bölme

### SPLITHOUT {#SPLITHOUT}
```
public static final int SPLITHOUT
```

Dış Yatay Bölme

### SPLITVIN {#SPLITVIN}
```
public static final int SPLITVIN
```

İç Dikey Bölme

### SPLITVOUT {#SPLITVOUT}
```
public static final int SPLITVOUT
```

Dış Dikey Bölme

### TBGLITTER {#TBGLITTER}
```
public static final int TBGLITTER
```

Üst-Alt Parıltı

### TBWIPE {#TBWIPE}
```
public static final int TBWIPE
```

Üst-Alt Silme

### PdfPageEditor {#PdfPageEditor--}
```
public PdfPageEditor()
```

PdfPageEditor sınıfı için yapıcı.

### PdfPageEditor {#PdfPageEditor-com.aspose.pdf.Document-}
PdfPageEditor sınıfı için yapıcı.

### applyChanges {#applyChanges--}
```
public void applyChanges()
```

Belge sayfalarına yapılan değişiklikleri uygula.

### getAlignment {#getAlignment--}
```
@Deprecated public AlignmentType getAlignment()
```

Sonuç sayfasındaki orijinal PDF içeriğinin yatay hizalamasını alır, varsayılan AlignmentType.Left'tir. Bunun yerine getHorizontalAlignment kullanın

**Returns:**
AlignmentType nesnesi @see HorizontalAlignment

### getDisplayDuration {#getDisplayDuration--}
```
public int getDisplayDuration()
```

Sayfalar için görüntüleme süresini alır.

**Returns:**
int değer

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Sonuç sayfasındaki orijinal PDF içeriğinin yatay hizalamasını alır, varsayılan AlignmentType.Left'tir.

**Returns:**
HorizontalAlignment öğesi @see HorizontalAlignment

### getPageBoxSize {#getPageBoxSize-int-java.lang.String-}
<p> Belgedeki belirtilen kutunun boyutunu döndürür. </p> <hr> <pre> Aşağıdaki örnek, 1. sayfanın medya kutusunu nasıl alacağınızı gösterir: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); Rectangle rect = editor.getBoxSize(1, "media"); </pre>

### getPageRectangle {#getPageRectangle-com.aspose.pdf.Page-}
Sayfanın boyutunu döndür.

### getPageRotation {#getPageRotation-int-}
```
public int getPageRotation(int page)
```

<p> Belirtilen sayfanın dönüşünü döndürür. </p> <hr> <pre> Aşağıdaki örnek, sayfa dönüşünün nasıl alınacağını gösterir: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); int rotation = editor.getPageSize(1); System.out.println("Rotation of 1st page : " + rotation + " degrees"); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sayfa |  | Sayfa indeksi. Belge sayfaları 1'den numaralandırılır. |

**Returns:**
Sayfa dönüşü derece cinsinden.

### getPageRotations {#getPageRotations--}
```
public Map < Integer , Integer > getPageRotations()
```

<p> Sayfaların dönüşünü alır, bir hashtable sayfa numarasını ve dönüş derecesini içerir, anahtar sayfa numarasını temsil eder, anahtarın değeri ise dönüşü derece cinsinden temsil eder. </p>

**Returns:**
{@code Map<Integer, Integer>} nesnesi

### getPages {#getPages--}
```
public int getPages()
```

<p> Toplam sayfa sayısını döndürür. </p> <hr> <pre> Aşağıdaki örnek, GetPages() metodunun kullanımını gösterir: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); System.out.println("Document has: " + editor.GetPages()); </pre>

**Returns:**
Sayfa sayısı.

### getPageSize {#getPageSize--}
```
public PageSize getPageSize()
```

Çıktı dosyasının sayfa boyutunu alır.

**Returns:**
PageSize nesnesi

### getPageSize {#getPageSize-int-}
```
public PageSize getPageSize(int page)
```

<p> Belirtilen sayfanın sayfa boyutunu döndürür. </p> <hr> <pre> Aşağıdaki örnek, GetPageSize metodunun kullanımını gösterir: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); PageSize size = editor.getPageSize(1); System.out.println("Size of 1st page : " + size.getWidth() + " x " + size.getHeight()); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sayfa |  | Sayfa indeksi. Belge sayfaları 1'den numaralandırılır. |

**Returns:**
Sonuç, PageSize örneğidir. Döndürülen nesnenin Width ve Height özelliklerini kullanarak sayfa genişliğini ve yüksekliğini alın.

### getProcessPages {#getProcessPages--}
```
public int[] getProcessPages()
```

Düzenlenecek sayfa numaralarını alır. Varsayılan olarak, her sayfa düzenlenecektir.

**Returns:**
int değerlerinin dizisi

### getRotation {#getRotation--}
```
public int getRotation()
```

Sayfaların dönüşünü alır, dönüş 0, 90, 180 veya 270 olmalıdır. Varsayılan değer 0'dır.

**Returns:**
int değer

### getTransitionDuration {#getTransitionDuration--}
```
public int getTransitionDuration()
```

Geçiş efektinin süresini alır.

**Returns:**
int değer

### getTransitionType {#getTransitionType--}
```
public int getTransitionType()
```

Sunum sırasında bu sayfaya başka bir sayfadan geçiş yaparken kullanılacak geçiş stilini alır.

**Returns:**
int değer

### getVerticalAlignment {#getVerticalAlignment--}
```
@Deprecated public VerticalAlignmentType getVerticalAlignment()
```

Orijinal PDF içeriğinin sonuç sayfasındaki dikey hizalamasını alır, varsayılan VerticalAlignmentType.Bottom'tır. Bunun yerine getVerticalAlignmentType kullanın

**Returns:**
VerticalAlignmentType nesnesi

### getVerticalAlignmentType {#getVerticalAlignmentType--}
```
public VerticalAlignment getVerticalAlignmentType()
```

Orijinal PDF içeriğinin sonuç sayfasındaki dikey hizalamasını alır, varsayılan VerticalAlignmentType.Bottom'tır.

**Returns:**
VerticalAlignmentType öğesi @see VerticalAlignmentType

### getZoom {#getZoom--}
```
public float getZoom()
```

Yakınlaştırma katsayısını al. Değer 1.0 %100'e karşılık gelir. Varsayılan değer 1.0'dır.

**Returns:**
float değer

### isBoxDefined {#isBoxDefined-com.aspose.pdf.Page-java.lang.String-}
Kutunun sayfada tanımlı olup olmadığını kontrol et.

### movePosition {#movePosition-float-float-}
```
public void movePosition(float moveX, float moveY)
```

<p> Kökeni (0, 0)'dan belirtilen noktaya taşır. Köken sol-alt köşededir ve birim point'tir (1 inç = 72 point). </p> <hr> <pre> PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("input.pdf"); editor.movePosition(-100, 60); editor.save("moved.pdf"); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| moveX |  | X-koordinatı. |
| moveY |  | Y-koordinatı. |

### save {#save-java.io.OutputStream-}
<p> Değiştirilen belgeyi akışa kaydeder. </p> <hr> <pre> Aşağıdaki örnek, değiştirilen PDF belgesinin akışa nasıl kaydedileceğini gösterir. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre>

### save {#save-java.lang.String-}
<p> Değiştirilen belgeyi dosyaya kaydeder. </p> <hr> <pre> Aşağıdaki örnek, değiştirilen PDF belgesinin nasıl kaydedileceğini gösterir PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre>

### setAlignment {#setAlignment-com.aspose.pdf.facades.AlignmentType-}
Orijinal PDF içeriğinin sonuç sayfasındaki yatay hizalamasını ayarlar, varsayılan AlignmentType.Left'tır. Bunun yerine setHorizontalAlignment kullanın

### setDisplayDuration {#setDisplayDuration-int-}
```
public void setDisplayDuration(int value)
```

Sayfalar için görüntüleme süresini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Orijinal PDF içeriğinin sonuç sayfasındaki yatay hizalamasını ayarlar, varsayılan AlignmentType.Left'tır.

### setPageRotations {#setPageRotations-java.util.Map-}
Sayfaların dönüşünü ayarlar, bir hashtable sayfa numarasını ve dönüş derecesini içerir, anahtar sayfa numarasını temsil eder, anahtarın değeri ise dönüşü derece cinsinden temsil eder.

### setPageSize {#setPageSize-com.aspose.pdf.PageSize-}
Çıktı dosyasının sayfa boyutunu ayarlar.

### setProcessPages {#setProcessPages-int:A-}
```
public void setProcessPages(int[] value)
```

Düzenlenecek sayfa numaralarını ayarlar. Varsayılan olarak, her sayfa düzenlenecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değerlerinin dizisi |

### setRotation {#setRotation-int-}
```
public void setRotation(int value)
```

Sayfaların dönüşünü ayarlar, dönüş 0, 90, 180 veya 270 olmalıdır. Varsayılan değer 0'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setTransitionDuration {#setTransitionDuration-int-}
```
public void setTransitionDuration(int value)
```

Geçiş efektinin süresini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setTransitionType {#setTransitionType-int-}
```
public void setTransitionType(int value)
```

Sunum sırasında bu sayfaya başka bir sayfadan geçiş yaparken kullanılacak geçiş stilini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-}
Orijinal PDF içeriğinin sonuç sayfasındaki dikey hizalamasını ayarlar, varsayılan değer VerticalAlignmentType.Bottom'dur. Bunun yerine setVerticalAlignmentType kullanın.

### setVerticalAlignmentType {#setVerticalAlignmentType-com.aspose.pdf.VerticalAlignment-}
Orijinal PDF içeriğinin sonuç sayfasındaki dikey hizalamasını ayarlar, varsayılan değer VerticalAlignmentType.Bottom'dur.

### setZoom {#setZoom-float-}
```
public void setZoom(float value)
```

<p> Zoom katsayısını ayarlar. 1.0 değeri %100'e karşılık gelir. Varsayılan değer 1.0'dır. </p>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer <hr> <pre> Aşağıdaki örnek, belge sayfalarının zoom seviyesinin nasıl değiştirileceğini gösterir. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); </pre> |
