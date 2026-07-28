---
title: "StampAnnotation"
linktitle: "StampAnnotation"
second_title: "Aspose.PDF for Java API Referansı"
description: "<p> Kauçuk damga ek açıklamasını temsil eder. Bu ek açıklama türü, sayfaya bir kauçuk damga ile basılmış gibi görünmesi amaçlanan metin veya grafik gösterir. </p> <hr>."
type: docs
weight: 4630
url: /tr/java/com.aspose.pdf/stampannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.StampAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class StampAnnotation extends MarkupAnnotation
```

<p> Lastik damga açıklamasını temsil eder. Bu tür açıklama, sayfaya bir lastik damga ile basılmış gibi görünmesi amaçlanan metin veya grafik gösterir. </p> <hr> <pre> Next code snippet demonstrates how to add 2 stamps into the first pdf document page. Input document comes from inFile and changes are saved into the outFile. The first stamp has icon NotForPublicRelease and the second comes with image from rubber.jpg. Document document = new Document(inFile); StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease); stamp1.setRect ( new Rectangle(100, 100, 120, 120)) document.getPages().get(1).getAnnotations().add(stamp1); StampAnnotation stamp2 = new StampAnnotation(new FileStream("rubber.jpg", FileMode.Open)); stamp2.setRect ( new Rectangle(200, 200, 220, 220)) document.getPages().get(1).getAnnotations().add(stamp2); document.save(outFile); </pre>

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [StampAnnotation](#StampAnnotation-com.aspose.pdf.IDocument-) | Yapıcı |
| [StampAnnotation](#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Belirtilen sayfada yeni Damga ek açıklaması oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Ek açıklama koleksiyonunda gezinirken {@code AnnotationSelector} ziyaretçisini kabul eder. |
| [clear](#clear--) | Statik örnekleri temizle |
| [getAnnotationType](#getAnnotationType--) | Ek açıklamanın tipini alır. |
| [getIcon](#getIcon--) | Kauçuk damga için simgeyi alır. |
| [getImage](#getImage--) | Ek açıklamanın görüntüsünü alır. |
| [setBase64SVGImage](#setBase64SVGImage-java.lang.String-) | Ek açıklamanın SVG görüntüsünü Base64 dizesi olarak ayarlar. |
| [setIcon](#setIcon-com.aspose.pdf.StampIcon-) | Kauçuk damga için simgeyi ayarlar. |
| [setImage](#setImage-java.io.InputStream-) | Ek açıklamanın görüntüsünü ayarlar. |

### StampAnnotation {#StampAnnotation-com.aspose.pdf.IDocument-}
Yapıcı

### StampAnnotation {#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Belirtilen sayfada yeni Damga ek açıklaması oluşturur.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Ek açıklama koleksiyonunda gezinirken {@code AnnotationSelector} ziyaretçisini kabul eder.

### clear {#clear--}
```
public static void clear()
```

Statik örnekleri temizle

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ek açıklamanın tipini alır.

**Returns:**
AnnotationType öğesi @see AnnotationType

### getIcon {#getIcon--}
```
public StampIcon getIcon()
```

Kauçuk damga için simgeyi alır.

**Returns:**
StampIcon değeri

### getImage {#getImage--}
```
public InputStream getImage()
```

Ek açıklamanın görüntüsünü alır.

**Returns:**
InputStream nesnesi

### setBase64SVGImage {#setBase64SVGImage-java.lang.String-}
Ek açıklamanın SVG görüntüsünü Base64 dizesi olarak ayarlar.

### setIcon {#setIcon-com.aspose.pdf.StampIcon-}
Kauçuk damga için simgeyi ayarlar.

### setImage {#setImage-java.io.InputStream-}
Ek açıklamanın görüntüsünü ayarlar.
