---
title: "XImage"
linktitle: "XImage"
second_title: "Aspose.PDF for Java API Referansı"
description: "görüntü X-Object'ini temsil eden sınıf."
type: docs
weight: 5610
url: /tr/java/com.aspose.pdf/ximage/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XImage

```
public final class XImage extends Object
```

görüntü X-Object'ini temsil eden sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XImage](#XImage-com.aspose.pdf.engine.data.IPdfDataStream-) | yalnızca dahili kullanım için |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addStencilMask](#addStencilMask-java.io.InputStream-) | XImage'e bir şablon maskesi ekler. |
| [containsTransparency](#containsTransparency--) | Görüntü şeffaflık içeriyorsa true; aksi takdirde false döndürür. |
| [delete](#delete--) | Görüntüyü üst koleksiyondan siler. |
| [detectColorType](#detectColorType-java.awt.image.BufferedImage-) | Görüntünün renk tipini döndürür. |
| [getAlternativeText](#getAlternativeText-com.aspose.pdf.Page-) | XImage için Alternatif Metin içeren bir dizi dize döndürür. |
| [getColorType](#getColorType--) | Görüntünün renk tipini döndürür. |
| [getEngineImg](#getEngineImg--) | IPdfImage nesnesi, görüntüyü tanımlar. Yalnızca dahili |
| [getFilterType](#getFilterType--) | Görüntü filtre tipini alır. |
| [getGrayscaled](#getGrayscaled--) | Görüntünün gri tonlamalı sürümünü alır. |
| [getHeight](#getHeight--) | Görüntünün yüksekliğini alır. |
| [getImage](#getImage--) | Yalnızca dahili kullanım için |
| [getMetadata](#getMetadata--) | Görüntünün meta verileri. |
| [getName](#getName--) | Görüntünün adını alır. Lütfen sayfa içeriklerinde referansları olan bir görüntünün adını değiştirirseniz belgenin hatalı olabileceğini unutmayın. Bu durumda XImage.Rename metodunu kullanın. |
| [getNameInCollection](#getNameInCollection--) | Görüntünün koleksiyonundaki adını döndürür. |
| [getRawBytes](#getRawBytes--) | Görüntüyü kod çözmeden ham baytları döndürür. |
| [getRawImageData](#getRawImageData--) | Kaynak görüntüden ham görüntü verilerini alır. |
| [getRawParameters](#getRawParameters--) | Ham görüntü parametrelerini alır |
| [getWidth](#getWidth--) | Görüntünün genişliğini alır. |
| [isImage](#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-) | İlkel bir görüntü ise true döndürür. |
| [isImageMask](#isImageMask--) | Görüntünün bir görüntü maskesi olarak ele alınıp alınmayacağını gösteren bir bayrak alır (bkz. 8.9.6, "Masked Images"). Bu bayrak true ise, BitsPerComponent değeri 1 olmalı ve Mask ile ColorSpace belirtilmemelidir; maskelenmemiş alanlar mevcut dolgu olmayan renk ile boyanmalıdır. Varsayılan değer: false. Değer: True, görüntünün bir görüntü maskesi olduğu durumdur. |
| [isTheSameObject](#isTheSameObject-com.aspose.pdf.XImage-) | Her iki görüntü aynı nesneye referans veriyorsa true döndürür. |
| [rename](#rename-java.lang.String-) | Görüntüyü yeniden adlandırır ve görüntüye yapılan tüm referansları yeni adla değiştirir |
| [replace](#replace-java.io.InputStream-) | Görüntüyü {@code image} içinde belirtilen akışa yerleştirir. * |
| [save](#save-java.io.OutputStream-) | Görüntü verilerini akışa JPEG görüntüsü olarak kaydeder. |
| [save](#save-java.io.OutputStream-float-float-) | Görüntüyü istenen formatta akışa kaydeder. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | Görüntüyü istenen formatta akışa kaydeder. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | Görüntüyü istenen formatta akışa kaydeder. |
| [save](#save-java.io.OutputStream-int-) | Görüntüyü belirtilen çözünürlükte istenen formatta akışa kaydeder. |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-) | Görüntüyü istenen formatta akışa kaydeder. |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-) |  |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-int-) | Görüntü verilerini belirtilen çözünürlükte JPEG görüntüsü olarak akışa kaydeder. |
| [setName](#setName-java.lang.String-) | Görüntü adını ayarlar. Sayfa içeriğinde referansları olan bir görüntünün adını değiştirirseniz belgenin hatalı olabileceğini lütfen unutmayın. Bu durumda XImage.Rename metodunu kullanın. |
| [toStream](#toStream--) | Orijinal görüntü akışını döndürür. |
| [toString](#toString--) | XImage nesnesi özelliklerinin bir string temsilini döndürür. |
| [trySetAlternativeText](#trySetAlternativeText-java.lang.String-com.aspose.pdf.Page-) | Sayfadaki bir XImage için alternatif metni ayarlar. |

### XImage {#XImage-com.aspose.pdf.engine.data.IPdfDataStream-}
yalnızca dahili kullanım için

### addStencilMask {#addStencilMask-java.io.InputStream-}
XImage'e bir şablon maskesi ekler.

### containsTransparency {#containsTransparency--}
```
public boolean containsTransparency()
```

Görüntü şeffaflık içeriyorsa true; aksi takdirde false döndürür.

**Returns:**
boolean değer

### delete {#delete--}
```
public void delete()
```

Görüntüyü üst koleksiyondan siler.

### detectColorType {#detectColorType-java.awt.image.BufferedImage-}
Görüntünün renk tipini döndürür.

### getAlternativeText {#getAlternativeText-com.aspose.pdf.Page-}
XImage için Alternatif Metin içeren bir dizi dize döndürür.

### getColorType {#getColorType--}
```
public ColorType getColorType()
```

Görüntünün renk tipini döndürür.

**Returns:**
Renk türü değeri.

### getEngineImg {#getEngineImg--}
```
public com.aspose.pdf.engine.data.IPdfDataStream getEngineImg()
```

IPdfImage nesnesi, görüntüyü tanımlar. Yalnızca dahili

**Returns:**
IPdfDataStream

### getFilterType {#getFilterType--}
```
public final ImageFilterType getFilterType()
```

Görüntü filtre tipini alır.

**Returns:**
ImageFilterType öğesi

### getGrayscaled {#getGrayscaled--}
```
public BufferedImage getGrayscaled()
```

Görüntünün gri tonlamalı sürümünü alır.

**Returns:**
BufferedImage

### getHeight {#getHeight--}
```
public int getHeight()
```

Görüntünün yüksekliğini alır.

**Returns:**
int değer

### getImage {#getImage--}
```
public com.aspose.ms.System.Drawing.Bitmap getImage()
```

Yalnızca dahili kullanım için

**Returns:**
Görüntü

### getMetadata {#getMetadata--}
```
public final Metadata getMetadata()
```

Görüntünün meta verileri.

**Returns:**
Metadata örneği

### getName {#getName--}
```
public String getName()
```

Görüntünün adını alır. Lütfen sayfa içeriklerinde referansları olan bir görüntünün adını değiştirirseniz belgenin hatalı olabileceğini unutmayın. Bu durumda XImage.Rename metodunu kullanın.

**Returns:**
Dize

### getNameInCollection {#getNameInCollection--}
```
public String getNameInCollection()
```

Görüntünün koleksiyonundaki adını döndürür.

**Returns:**
Görüntü anahtarı (ad).

### getRawBytes {#getRawBytes--}
```
public byte[] getRawBytes()
```

Görüntüyü kod çözmeden ham baytları döndürür.

**Returns:**
bayt dizisi

### getRawImageData {#getRawImageData--}
```
public final byte[] getRawImageData()
```

Kaynak görüntüden ham görüntü verilerini alır.

**Returns:**
Orijinal görüntü verilerini içeren bir {@link byte[]}.

### getRawParameters {#getRawParameters--}
```
public XImage.RawParameters getRawParameters()
```

Ham görüntü parametrelerini alır

**Returns:**
RawParameters örneği

### getWidth {#getWidth--}
```
public int getWidth()
```

Görüntünün genişliğini alır.

**Returns:**
int değer

### isImage {#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-}
İlkel bir görüntü ise true döndürür.

### isImageMask {#isImageMask--}
```
public final boolean isImageMask()
```

Görüntünün bir görüntü maskesi olarak ele alınıp alınmayacağını gösteren bir bayrak alır (bkz. 8.9.6, "Masked Images"). Bu bayrak true ise, BitsPerComponent değeri 1 olmalı ve Mask ile ColorSpace belirtilmemelidir; maskelenmemiş alanlar mevcut dolgu olmayan renk ile boyanmalıdır. Varsayılan değer: false. Değer: True, görüntünün bir görüntü maskesi olduğu durumdur.

**Returns:**
boolean değer

### isTheSameObject {#isTheSameObject-com.aspose.pdf.XImage-}
Her iki görüntü aynı nesneye referans veriyorsa true döndürür.

### rename {#rename-java.lang.String-}
Görüntüyü yeniden adlandırır ve görüntüye yapılan tüm referansları yeni adla değiştirir

### replace {#replace-java.io.InputStream-}
Görüntüyü {@code image} içinde belirtilen akışa yerleştirir. *

### save {#save-java.io.OutputStream-}
Görüntü verilerini akışa JPEG görüntüsü olarak kaydeder.

### save {#save-java.io.OutputStream-float-float-}
Görüntüyü istenen formatta akışa kaydeder.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
Görüntüyü istenen formatta akışa kaydeder.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
Görüntüyü istenen formatta akışa kaydeder.

### save {#save-java.io.OutputStream-int-}
Görüntüyü belirtilen çözünürlükte istenen formatta akışa kaydeder.

### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-}
Görüntüyü istenen formatta akışa kaydeder.

### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-}


### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-int-}
Görüntü verilerini belirtilen çözünürlükte JPEG görüntüsü olarak akışa kaydeder.

### setName {#setName-java.lang.String-}
Görüntü adını ayarlar. Sayfa içeriğinde referansları olan bir görüntünün adını değiştirirseniz belgenin hatalı olabileceğini lütfen unutmayın. Bu durumda XImage.Rename metodunu kullanın.

### toStream {#toStream--}
```
public InputStream toStream()
```

Orijinal görüntü akışını döndürür.

**Returns:**
Orijinal görüntü akışı.

### toString {#toString--}
```
public String toString()
```

XImage nesnesi özelliklerinin bir string temsilini döndürür.

**Returns:**
String örneği

### trySetAlternativeText {#trySetAlternativeText-java.lang.String-com.aspose.pdf.Page-}
Sayfadaki bir XImage için alternatif metni ayarlar.
