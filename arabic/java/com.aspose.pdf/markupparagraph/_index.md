---
title: "MarkupParagraph"
linktitle: "MarkupParagraph"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فقرة."
type: docs
weight: 2880
url: /ar/java/com.aspose.pdf/markupparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MarkupParagraph

```
public final class MarkupParagraph extends Object
```

يمثل فقرة.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getContinuationPageNumbers](#getContinuationPageNumbers--) | قائمة أرقام الصفحات التي يُستمر فيها الفقرة. سيتطابق مع الصفحة التي بدأت فيها الفقرة إذا استمرت في العمود التالي على نفس الصفحة. |
| [getFragments](#getFragments--) | <p> مجموعة من كائنات {@code TextFragment} غير الفارغة للفقرة. </p><hr> كائن {@code TextFragment} يوفّر الوصول إلى نص نتيجة البحث، خصائص النص، ويسمح بتحرير النص وتغيير حالة النص (الخط، حجم الخط، اللون، إلخ). |
| [getFragmentsInternal](#getFragmentsInternal--) |  |
| [getLines](#getLines--) | <p> أسطر الفقرة. كل سطر ممثل بقائمة من أجزاء النص. </p><hr> كائن {@code TextFragment} يوفّر الوصول إلى نص نتيجة البحث، خصائص النص، ويسمح بتحرير النص وتغيير حالة النص (الخط، حجم الخط، اللون، إلخ). |
| [getLinesInternal](#getLinesInternal--) |  |
| [getPoints](#getPoints--) | نقاط المضلع الذي يصف الفقرة. النقطة البداية هي الزاوية السفلية اليسرى للفقرة. والنقاط التالية تكون بترتيب عكس اتجاه عقارب الساعة. |
| [getSecondaryPoints](#getSecondaryPoints--) | نقاط المضلع الثانوي الذي يصف استمرارية الفقرة. لن تكون فارغة إذا استمرت الفقرة في العمود أو الصفحة التالية. النقطة البداية هي الزاوية السفلية اليسرى للفقرة. والنقاط التالية تكون بترتيب عكس اتجاه عقارب الساعة. |
| [getText](#getText--) | يحصل على كائن نص {@code string} الذي يمثّله كائن {@code MarkupParagraph}. |
| [setText](#setText-java.lang.String-) | يحصل أو يعيّن نص الفقرة. |

### getContinuationPageNumbers {#getContinuationPageNumbers--}
```
public final List < Integer > getContinuationPageNumbers()
```

قائمة أرقام الصفحات التي يُستمر فيها الفقرة. سيتطابق مع الصفحة التي بدأت فيها الفقرة إذا استمرت في العمود التالي على نفس الصفحة.

**Returns:**
قائمة من Integer

### getFragments {#getFragments--}
```
public List < TextFragment > getFragments()
```

<p> مجموعة من كائنات {@code TextFragment} غير الفارغة للفقرة. </p><hr> كائن {@code TextFragment} يوفّر الوصول إلى نص نتيجة البحث، خصائص النص، ويسمح بتحرير النص وتغيير حالة النص (الخط، حجم الخط، اللون، إلخ).

**Returns:**
قائمة من مثيلات TextFragment

### getFragmentsInternal {#getFragmentsInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< TextFragment > getFragmentsInternal()
```



### getLines {#getLines--}
```
public List <com.aspose.ms.System.Collections.Generic.List< TextFragment >> getLines()
```

<p> أسطر الفقرة. كل سطر ممثل بقائمة من أجزاء النص. </p><hr> كائن {@code TextFragment} يوفّر الوصول إلى نص نتيجة البحث، خصائص النص، ويسمح بتحرير النص وتغيير حالة النص (الخط، حجم الخط، اللون، إلخ).

**Returns:**
قائمة من مثيلات TextFragment

### getLinesInternal {#getLinesInternal--}
```
public com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Collections.Generic.List< TextFragment >> getLinesInternal()
```



### getPoints {#getPoints--}
```
public Point [] getPoints()
```

نقاط المضلع الذي يصف الفقرة. النقطة البداية هي الزاوية السفلية اليسرى للفقرة. والنقاط التالية تكون بترتيب عكس اتجاه عقارب الساعة.

**Returns:**
مصفوفة من مثيلات Point

### getSecondaryPoints {#getSecondaryPoints--}
```
public final List < Point []> getSecondaryPoints()
```

نقاط المضلع الثانوي الذي يصف استمرارية الفقرة. لن تكون فارغة إذا استمرت الفقرة في العمود أو الصفحة التالية. النقطة البداية هي الزاوية السفلية اليسرى للفقرة. والنقاط التالية تكون بترتيب عكس اتجاه عقارب الساعة.

**Returns:**
قائمة من Point[]

### getText {#getText--}
```
public String getText()
```

يحصل على كائن نص {@code string} الذي يمثّله كائن {@code MarkupParagraph}.

**Returns:**
قيمة سلسلة

### setText {#setText-java.lang.String-}
يحصل أو يعيّن نص الفقرة.
