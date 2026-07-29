---
title: "MarkupAnnotation"
linktitle: "MarkupAnnotation"
second_title: "Aspose.PDF for Java API Referansı"
description: "İşaretleme açıklamasını temsil eden soyut sınıf."
type: docs
weight: 2870
url: /tr/java/com.aspose.pdf/markupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class MarkupAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

İşaretleme açıklamasını temsil eden soyut sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MarkupAnnotation](#MarkupAnnotation--) | Yapıcı |
| [MarkupAnnotation](#MarkupAnnotation-com.aspose.pdf.IDocument-) | Yapıcı |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [clearState](#clearState--) | Ek açıklama için durum ve durum modelini temizler. Örneğin, bir ek açıklamanın inceleme durumunu temizler. Not, durum ve statemodel anahtarlarına sahip diğer metin ek açıklamasında depolanan durum. |
| [getCreationDate](#getCreationDate--) | Ek açıklamanın oluşturulduğu tarih ve zamanı alır. |
| [getInReplyTo](#getInReplyTo--) | Bu ek açıklamanın "in reply to" olduğu ek açıklamaya bir referans. Her iki ek açıklama da belgenin aynı sayfasında olmalıdır. |
| [getOpacity](#getOpacity--) | Ek açıklamayı çizerken kullanılacak sabit opaklık değerini alır. |
| [getPopup](#getPopup--) | Bu ek açıklamayla ilişkili metni girmek veya düzenlemek için açılır ek açıklama. |
| [getReplyType](#getReplyType--) | Bu ek açıklama ile InReplyTo tarafından belirtilen ek açıklama arasındaki ilişkiyi ("reply type") belirten bir dize. |
| [getRichText](#getRichText--) | Ek açıklama açıldığında açılır pencerede gösterilecek zengin metin dizesini alır. |
| [getRichText](#getRichText-com.aspose.pdf.engine.data.IPdfDictionary-) | Ek açıklama açıldığında açılır pencerede gösterilecek zengin metin dizesini alır. |
| [getState](#getState--) | Ek açıklamanın durumunu alır. Not, durum ve statemodel anahtarlarına sahip diğer metin ek açıklamasında depolanan durum. |
| [getStateModel](#getStateModel--) | Ek açıklamanın durum modelini alır. Not, durum ve statemodel anahtarlarına sahip diğer metin ek açıklamasında depolanan durum. |
| [getSubject](#getSubject--) | Nesnenin açıklamasını temsil eden metni alır. |
| [getTitle](#getTitle--) | Ek açıklamanın açılır penceresinin başlık çubuğunda açık ve etkin olduğunda gösterilecek bir metin etiketi alır. Bu giriş, ek açıklamayı ekleyen kullanıcıyı tanımlamalıdır. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Ek açıklamanın oluşturulduğu tarih ve zamanı alır. |
| [setInReplyTo](#setInReplyTo-com.aspose.pdf.Annotation-) | Bu ek açıklamanın "in reply to" olduğu ek açıklamaya bir referans. Her iki ek açıklama da belgenin aynı sayfasında olmalıdır. |
| [setMarkedState](#setMarkedState-boolean-) | Ek açıklama için İşaretli ve İşaretsiz durumunu ayarlar. Not, durum ve statemodel anahtarlarına sahip diğer metin ek açıklamasında depolanan durum. |
| [setOpacity](#setOpacity-double-) | Ek açıklamayı çizerken kullanılacak sabit opaklık değerini ayarlar. |
| [setPopup](#setPopup-com.aspose.pdf.PopupAnnotation-) | Bu ek açıklamayla ilişkili metni girmek veya düzenlemek için açılır ek açıklama. |
| [setReplyType](#setReplyType-com.aspose.pdf.ReplyType-) | Bu ek açıklama ile InReplyTo tarafından belirtilen ek açıklama arasındaki ilişkiyi ("reply type") belirten bir dize. |
| [setReviewState](#setReviewState-com.aspose.pdf.AnnotationState-) | Ek açıklama için inceleme durumunu ayarlar. İşaretli ve İşaretsiz durumlar, Review StateModel'e ait olmadıkları için yok sayılır. Durum, hedef ek açıklamayı oluşturan kullanıcı tarafından ayarlanır. Değer, hedef ek açıklamanın Title özelliğinden alınır. Not, durum ve statemodel anahtarlarına sahip diğer metin ek açıklamasında depolanan durum. |
| [setReviewState](#setReviewState-com.aspose.pdf.AnnotationState-java.lang.String-) | Ek açıklama için inceleme durumunu ayarlar. İşaretli ve İşaretsiz durumlar, Review StateModel'e ait olmadıkları için yok sayılır. Not, durum ve statemodel anahtarlarına sahip diğer metin ek açıklamasında depolanan durum. |
| [setRichText](#setRichText-java.lang.String-) | Ek açıklama açıldığında açılır pencerede gösterilecek bir zengin metin dizesi ayarlar. |
| [setSubject](#setSubject-java.lang.String-) | Nesnenin açıklamasını temsil eden metni ayarlar. |
| [setTitle](#setTitle-java.lang.String-) | Ek açıklamanın açılır penceresinin başlık çubuğunda açık ve etkin olduğunda gösterilecek bir metin etiketi ayarlar. Bu giriş, ek açıklamayı ekleyen kullanıcıyı tanımlamalıdır. |

### MarkupAnnotation {#MarkupAnnotation--}
```
public MarkupAnnotation()
```

Yapıcı

### MarkupAnnotation {#MarkupAnnotation-com.aspose.pdf.IDocument-}
Yapıcı

### clearState {#clearState--}
```
public final void clearState()
```

Ek açıklama için durum ve durum modelini temizler. Örneğin, bir ek açıklamanın inceleme durumunu temizler. Not, durum ve statemodel anahtarlarına sahip diğer metin ek açıklamasında depolanan durum.

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Ek açıklamanın oluşturulduğu tarih ve zamanı alır.

**Returns:**
Date nesnesi

### getInReplyTo {#getInReplyTo--}
```
public Annotation getInReplyTo()
```

Bu ek açıklamanın "in reply to" olduğu ek açıklamaya bir referans. Her iki ek açıklama da belgenin aynı sayfasında olmalıdır.

**Returns:**
Ek açıklama değeri

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Ek açıklamayı çizerken kullanılacak sabit opaklık değerini alır.

**Returns:**
double değer

### getPopup {#getPopup--}
```
public PopupAnnotation getPopup()
```

Bu ek açıklamayla ilişkili metni girmek veya düzenlemek için açılır ek açıklama.

**Returns:**
PopupAnnotation değeri

### getReplyType {#getReplyType--}
```
public ReplyType getReplyType()
```

Bu ek açıklama ile InReplyTo tarafından belirtilen ek açıklama arasındaki ilişkiyi ("reply type") belirten bir dize.

**Returns:**
ReplyType değeri @see ReplyType

### getRichText {#getRichText--}
```
public final String getRichText()
```

Ek açıklama açıldığında açılır pencerede gösterilecek zengin metin dizesini alır.

**Returns:**
String değeri

### getRichText {#getRichText-com.aspose.pdf.engine.data.IPdfDictionary-}
Ek açıklama açıldığında açılır pencerede gösterilecek zengin metin dizesini alır.

**Returns:**
String değeri

### getState {#getState--}
```
public final AnnotationState getState()
```

Ek açıklamanın durumunu alır. Not, durum ve statemodel anahtarlarına sahip diğer metin ek açıklamasında depolanan durum.

**Returns:**
Ek açıklama durumu.

### getStateModel {#getStateModel--}
```
public final AnnotationStateModel getStateModel()
```

Ek açıklamanın durum modelini alır. Not, durum ve statemodel anahtarlarına sahip diğer metin ek açıklamasında depolanan durum.

**Returns:**
Ek açıklama durumu modeli.

### getSubject {#getSubject--}
```
public String getSubject()
```

Nesnenin açıklamasını temsil eden metni alır.

**Returns:**
String değeri

### getTitle {#getTitle--}
```
public String getTitle()
```

Ek açıklamanın açılır penceresinin başlık çubuğunda açık ve etkin olduğunda gösterilecek bir metin etiketi alır. Bu giriş, ek açıklamayı ekleyen kullanıcıyı tanımlamalıdır.

**Returns:**
String değeri

### setCreationDate {#setCreationDate-java.util.Date-}
Ek açıklamanın oluşturulduğu tarih ve zamanı alır.

### setInReplyTo {#setInReplyTo-com.aspose.pdf.Annotation-}
Bu ek açıklamanın "in reply to" olduğu ek açıklamaya bir referans. Her iki ek açıklama da belgenin aynı sayfasında olmalıdır.

### setMarkedState {#setMarkedState-boolean-}
```
public final void setMarkedState(boolean marked)
```

Ek açıklama için İşaretli ve İşaretsiz durumunu ayarlar. Not, durum ve statemodel anahtarlarına sahip diğer metin ek açıklamasında depolanan durum.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| işaretli |  | Marked durumunu ayarlıyorsa True, Unmarked durumunu ayarlıyorsa false. |

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Ek açıklamayı çizerken kullanılacak sabit opaklık değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setPopup {#setPopup-com.aspose.pdf.PopupAnnotation-}
Bu ek açıklamayla ilişkili metni girmek veya düzenlemek için açılır ek açıklama.

### setReplyType {#setReplyType-com.aspose.pdf.ReplyType-}
Bu ek açıklama ile InReplyTo tarafından belirtilen ek açıklama arasındaki ilişkiyi ("reply type") belirten bir dize.

### setReviewState {#setReviewState-com.aspose.pdf.AnnotationState-}
Ek açıklama için inceleme durumunu ayarlar. İşaretli ve İşaretsiz durumlar, Review StateModel'e ait olmadıkları için yok sayılır. Durum, hedef ek açıklamayı oluşturan kullanıcı tarafından ayarlanır. Değer, hedef ek açıklamanın Title özelliğinden alınır. Not, durum ve statemodel anahtarlarına sahip diğer metin ek açıklamasında depolanan durum.

### setReviewState {#setReviewState-com.aspose.pdf.AnnotationState-java.lang.String-}
Ek açıklama için inceleme durumunu ayarlar. İşaretli ve İşaretsiz durumlar, Review StateModel'e ait olmadıkları için yok sayılır. Not, durum ve statemodel anahtarlarına sahip diğer metin ek açıklamasında depolanan durum.

### setRichText {#setRichText-java.lang.String-}
Ek açıklama açıldığında açılır pencerede gösterilecek bir zengin metin dizesi ayarlar.

### setSubject {#setSubject-java.lang.String-}
Nesnenin açıklamasını temsil eden metni ayarlar.

### setTitle {#setTitle-java.lang.String-}
Ek açıklamanın açılır penceresinin başlık çubuğunda açık ve etkin olduğunda gösterilecek bir metin etiketi ayarlar. Bu giriş, ek açıklamayı ekleyen kullanıcıyı tanımlamalıdır.
