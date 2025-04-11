---
title: XImageCollection.Replace
second_title: Aspose.PDF for .NET API Reference
description: طريقة XImageCollection. استبدال صورة في المجموعة بصورة أخرى
type: docs
weight: 150
url: /ar/net/aspose.pdf/ximagecollection/replace/
---
## Replace(int, Stream) {#replace}

استبدال صورة في المجموعة بصورة أخرى.

```csharp
public void Replace(int index, Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | فهرس عنصر المجموعة الذي سيتم استبداله في نطاق [1..عدد الصور]. |
| stream | Stream | تدفق يحتوي على بيانات الصورة (بتنسيق JPEG). |

### See Also

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Replace(int, Stream, int, bool) {#replace_2}

استبدال صورة في المجموعة بصورة أخرى.

```csharp
public void Replace(int index, Stream stream, int quality, bool isBlackAndWhite)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | فهرس عنصر المجموعة الذي سيتم استبداله في نطاق [1..عدد الصور]. |
| stream | Stream | تدفق يحتوي على بيانات الصورة (بتنسيق JPEG). |
| quality | Int32 | جودة ضغط JPEG، بالنسبة المئوية (القيم الصالحة هي 0..100). |
| isBlackAndWhite | Boolean | إذا كانت صحيحة، يتم ضغط الصورة بطريقة ضغط CCITT التي توفر ضغطًا أفضل للصورة بالأبيض والأسود. يمكن استخدامها فقط للصور بالأبيض والأسود. |

### See Also

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Replace(int, Stream, int) {#replace_1}

استبدال صورة في المجموعة بصورة أخرى.

```csharp
public void Replace(int index, Stream stream, int quality)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | فهرس عنصر المجموعة الذي سيتم استبداله في نطاق [1..عدد الصور]. |
| stream | Stream | تدفق يحتوي على بيانات الصورة (بتنسيق JPEG). |
| quality | Int32 | جودة JPEG. |

### See Also

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)