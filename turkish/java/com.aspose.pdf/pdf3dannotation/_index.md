---
title: "PDF3DAnnotation"
linktitle: "PDF3DAnnotation"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF3DAnnotation sınıfı. Bu sınıf miras alınamaz. @see Annotation"
type: docs
weight: 3560
url: /tr/java/com.aspose.pdf/pdf3dannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PDF3DAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PDF3DAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PDF3DAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PDF3DAnnotation extends Annotation
```

PDF3DAnnotation sınıfı. Bu sınıf miras alınamaz. @see Annotation

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PDF3DAnnotation](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-) | Yeni bir {@code PDF3DAnnotation} sınıfı örneği başlatır. |
| [PDF3DAnnotation](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-com.aspose.pdf.PDF3DActivation-) | Yeni bir {@code PDF3DAnnotation} sınıfı örneği başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Ek açıklama işleme için ziyaretçiyi kabul eder. |
| [clearImagePreview](#clearImagePreview--) | Görüntü önizlemesini temizler. |
| [getAnnotationType](#getAnnotationType--) | Ek açıklama tipini alır. Değer: Ek açıklama tipi. |
| [getContent](#getContent--) | İçeriği alır veya ayarlar. Değer: İçerik. |
| [getImagePreview](#getImagePreview--) | Görüntü önizlemesini alır. |
| [getLightingScheme](#getLightingScheme--) | Aydınlatma şemasını alır. Değer: Aydınlatma şeması. |
| [getPdf3DArtwork](#getPdf3DArtwork--) | 3D Sanat eserini alır. Değer: PDF3 d sanat eseri. |
| [getRenderMode](#getRenderMode--) | Render modunu alır. Değer: Render modu. |
| [getViewArray](#getViewArray--) | Görünüm dizisini alır. Değer: Görünüm dizisi. |
| [setContent](#setContent-com.aspose.pdf.PDF3DContent-) | İçeriği alır veya ayarlar. Değer: İçerik. |
| [setDefaultViewIndex](#setDefaultViewIndex-int-) | Varsayılan görünümün indeksini ayarlar. |
| [setImagePreview](#setImagePreview-java.io.InputStream-) | Görüntü önizlemesini ayarlar. |
| [setImagePreview](#setImagePreview-java.lang.String-) | Görüntü önizlemesini ayarlar. |

### PDF3DAnnotation {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-}
Yeni bir {@code PDF3DAnnotation} sınıfı örneği başlatır.

### PDF3DAnnotation {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-com.aspose.pdf.PDF3DActivation-}
Yeni bir {@code PDF3DAnnotation} sınıfı örneği başlatır.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Ek açıklama işleme için ziyaretçiyi kabul eder.

### clearImagePreview {#clearImagePreview--}
```
public void clearImagePreview()
```

Görüntü önizlemesini temizler.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ek açıklama tipini alır. Değer: Ek açıklama tipi.

**Returns:**
int değer

### getContent {#getContent--}
```
public PDF3DContent getContent()
```

İçeriği alır veya ayarlar. Değer: İçerik.

**Returns:**
PDF3DContent nesnesi

### getImagePreview {#getImagePreview--}
```
public InputStream getImagePreview()
```

Görüntü önizlemesini alır.

**Returns:**
Görüntü önizlemesi akış olarak.

### getLightingScheme {#getLightingScheme--}
```
public PDF3DLightingScheme getLightingScheme()
```

Aydınlatma şemasını alır. Değer: Aydınlatma şeması.

**Returns:**
PDF3DLightingScheme nesnesi

### getPdf3DArtwork {#getPdf3DArtwork--}
```
public PDF3DArtwork getPdf3DArtwork()
```

3D Sanat eserini alır. Değer: PDF3 d sanat eseri.

**Returns:**
PDF3DArtwork nesnesi

### getRenderMode {#getRenderMode--}
```
public PDF3DRenderMode getRenderMode()
```

Render modunu alır. Değer: Render modu.

**Returns:**
PDF3DRenderMode nesnesi

### getViewArray {#getViewArray--}
```
public PDF3DViewArray getViewArray()
```

Görünüm dizisini alır. Değer: Görünüm dizisi.

**Returns:**
PDF3DViewArray nesnesi

### setContent {#setContent-com.aspose.pdf.PDF3DContent-}
İçeriği alır veya ayarlar. Değer: İçerik.

### setDefaultViewIndex {#setDefaultViewIndex-int-}
```
public void setDefaultViewIndex(int index)
```

Varsayılan görünümün indeksini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Varsayılan görünüm indeksi. |

### setImagePreview {#setImagePreview-java.io.InputStream-}
Görüntü önizlemesini ayarlar.

### setImagePreview {#setImagePreview-java.lang.String-}
Görüntü önizlemesini ayarlar.
