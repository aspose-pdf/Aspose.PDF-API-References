---
title: "Damga"
linktitle: "Damga"
second_title: "Aspose.PDF for Java API Referansı"
description: "Damga temsil eden sınıf."
type: docs
weight: 700
url: /tr/java/com.aspose.pdf.facades/stamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Stamp

```
public final class Stamp extends Object
```

Damga temsil eden sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Stamp](#Stamp--) | Stamp nesnesi için yapıcı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [bindImage](#bindImage-java.io.InputStream-) | Damga olarak kullanılacak resmi ayarlar. |
| [bindImage](#bindImage-java.lang.String-) | <p> Görüntüyü damga olarak ayarlar. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindLogo](#bindLogo-com.aspose.pdf.facades.FormattedText-) | Metni damga olarak ayarlar. |
| [bindPdf](#bindPdf-java.io.InputStream-int-) | <p> PDF dosyasını ve damga olarak kullanılacak sayfa numarasını ayarlar. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. InputStream stream = new FileInputStream("stamp.pdf"); stamp.bindPdf(stream, 1); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindPdf](#bindPdf-java.lang.String-int-) | <p> PDF dosyasını ve damga olarak kullanılacak sayfa numarasını ayarlar. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. stamp.bindPdf("stamp.pdf", 1); stamp.isBackground (true); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindTextState](#bindTextState-com.aspose.pdf.TextState-) | Damga metninin metin durumunu ayarlar. |
| [close](#close--) | Bu örneği kapatır |
| [getBlendingSpace](#getBlendingSpace--) | Sayfada şeffaflık ve harmanlama işlemlerini gerçekleştirmek için kullanılan bir renk uzayını tanımlayan BlendingColorSpace değerini alır. |
| [getOpacity](#getOpacity--) | Damganın opaklığını alır. |
| [getPageNumber](#getPageNumber--) | Sayfa numarasını alır. |
| [getPages](#getPages--) | Damga tarafından etkilenecek sayfa numaralarını içeren diziyi alır. |
| [getQuality](#getQuality--) | Damga görüntüsünün kalitesini yüzde olarak alır. Geçerli değerler 0..100%. |
| [getRotation](#getRotation--) | Damganın derece cinsinden dönüşünü alır. |
| [getStampId](#getStampId--) | Damganın tanımlayıcısını alır. |
| [isBackground](#isBackground--) | Arka plan durumunu alır. true ise damga, damgalanmış sayfanın arka planına yerleştirilir. Varsayılan olarak false olarak ayarlanmıştır. |
| [setBackground](#setBackground-boolean-) | Arka plan durumunu ayarlar. true ise damga, damgalanmış sayfanın arka planına yerleştirilir. Varsayılan olarak false olarak ayarlanmıştır. |
| [setBlendingSpace](#setBlendingSpace-com.aspose.pdf.facades.BlendingColorSpace-) | Sayfada şeffaflık ve harmanlama işlemlerini gerçekleştirmek için kullanılan bir renk uzayını tanımlayan BlendingColorSpace değerini ayarlar. |
| [setImageSize](#setImageSize-float-float-) | Görüntü damgasının boyutunu ayarlar. Görüntü belirtilen değerlere göre ölçeklendirilecektir. |
| [setOpacity](#setOpacity-float-) | Damganın opaklığını ayarlar. |
| [setOrigin](#setOrigin-float-float-) | Damganın yerleştirileceği sayfadaki konumu ayarlar. |
| [setPageNumber](#setPageNumber-int-) | Sayfa numarasını ayarlar. |
| [setPages](#setPages-int:A-) | <p> Damga tarafından etkilenecek sayfa numaralarını içeren diziyi ayarlar. Pages = null ise belgenin tüm sayfaları etkilenir. </p> |
| [setQuality](#setQuality-int-) | Görüntü damgasının kalitesini yüzde olarak ayarlar. Geçerli değerler 0..100%. |
| [setRotation](#setRotation-float-) | <p> Damganın derece cinsinden dönüşünü alır veya ayarlar. </p> |
| [setStampId](#setStampId-int-) | Damganın tanımlayıcısını ayarlar. |

### Stamp {#Stamp--}
```
public Stamp()
```

Stamp nesnesi için yapıcı.

### bindImage {#bindImage-java.io.InputStream-}
Damga olarak kullanılacak resmi ayarlar.

### bindImage {#bindImage-java.lang.String-}
<p> Görüntüyü damga olarak ayarlar. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindLogo {#bindLogo-com.aspose.pdf.facades.FormattedText-}
Metni damga olarak ayarlar.

### bindPdf {#bindPdf-java.io.InputStream-int-}
<p> PDF dosyasını ve damga olarak kullanılacak sayfa numarasını ayarlar. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. InputStream stream = new FileInputStream("stamp.pdf"); stamp.bindPdf(stream, 1); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindPdf {#bindPdf-java.lang.String-int-}
<p> PDF dosyasını ve damga olarak kullanılacak sayfa numarasını ayarlar. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. stamp.bindPdf("stamp.pdf", 1); stamp.isBackground (true); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindTextState {#bindTextState-com.aspose.pdf.TextState-}
Damga metninin metin durumunu ayarlar.

### close {#close--}
```
public void close()
```

Bu örneği kapatır

### getBlendingSpace {#getBlendingSpace--}
```
public BlendingColorSpace getBlendingSpace()
```

Sayfada şeffaflık ve harmanlama işlemlerini gerçekleştirmek için kullanılan bir renk uzayını tanımlayan BlendingColorSpace değerini alır.

**Returns:**
int değer @see BlendingColorSpace

### getOpacity {#getOpacity--}
```
public float getOpacity()
```

Damganın opaklığını alır.

**Returns:**
float değer

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Sayfa numarasını alır.

**Returns:**
int değer

### getPages {#getPages--}
```
public int[] getPages()
```

Damga tarafından etkilenecek sayfa numaralarını içeren diziyi alır.

**Returns:**
int dizisi

### getQuality {#getQuality--}
```
public int getQuality()
```

Damga görüntüsünün kalitesini yüzde olarak alır. Geçerli değerler 0..100%.

**Returns:**
int değer

### getRotation {#getRotation--}
```
public float getRotation()
```

Damganın derece cinsinden dönüşünü alır.

**Returns:**
float değer

### getStampId {#getStampId--}
```
public int getStampId()
```

Damganın tanımlayıcısını alır.

**Returns:**
int değer

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Arka plan durumunu alır. true ise damga, damgalanmış sayfanın arka planına yerleştirilir. Varsayılan olarak false olarak ayarlanmıştır.

**Returns:**
boolean değer

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Arka plan durumunu ayarlar. true ise damga, damgalanmış sayfanın arka planına yerleştirilir. Varsayılan olarak false olarak ayarlanmıştır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setBlendingSpace {#setBlendingSpace-com.aspose.pdf.facades.BlendingColorSpace-}
Sayfada şeffaflık ve harmanlama işlemlerini gerçekleştirmek için kullanılan bir renk uzayını tanımlayan BlendingColorSpace değerini ayarlar.

### setImageSize {#setImageSize-float-float-}
```
public void setImageSize(float width, float height)
```

Görüntü damgasının boyutunu ayarlar. Görüntü belirtilen değerlere göre ölçeklendirilecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik |  | Görüntü genişliği. |
| yükseklik |  | Görüntü yüksekliği. |

### setOpacity {#setOpacity-float-}
```
public void setOpacity(float value)
```

Damganın opaklığını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |

### setOrigin {#setOrigin-float-float-}
```
public void setOrigin(float originX, float originY)
```

Damganın yerleştirileceği sayfadaki konumu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| originX |  | Mühürün X koordinatı. |
| originY |  | Mühürün Y koordinatı. |

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

Sayfa numarasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setPages {#setPages-int:A-}
```
public void setPages(int[] value)
```

<p> Damga tarafından etkilenecek sayfa numaralarını içeren diziyi ayarlar. Pages = null ise belgenin tüm sayfaları etkilenir. </p>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int array <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.bindLogo(new FormattedText(text)); //put stamp only on 1st, 4th and 6th page. stamp.setPages(new int[] { 1, 4, 6 }); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |

### setQuality {#setQuality-int-}
```
public void setQuality(int value)
```

Görüntü damgasının kalitesini yüzde olarak ayarlar. Geçerli değerler 0..100%.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setRotation {#setRotation-float-}
```
public void setRotation(float value)
```

<p> Damganın derece cinsinden dönüşünü alır veya ayarlar. </p>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindLogo(new FormattedText("STAMP")); stamp.setRotation(90); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

Damganın tanımlayıcısını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |
