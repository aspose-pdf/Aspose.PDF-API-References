---
title: "XfdfReader"
linktitle: "XfdfReader"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "<p> الفئة التي تقوم بقراءة تنسيق XFDF. </p> <hr> <p> <code> Document doc = new Document(\\\"example.pdf\\\"); InputStream xfdfStream = new FileInputStream(\\\"filename\\\")."
type: docs
weight: 5570
url: /ar/java/com.aspose.pdf/xfdfreader/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XfdfReader

```
public final class XfdfReader extends Object
```

<p> الفئة التي تقوم بقراءة تنسيق XFDF. </p> <hr> <p> <code> Document doc = new Document("example.pdf"); InputStream xfdfStream = new FileInputStream("filename"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save("example_out.pdf"); </code> </p>

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [XfdfReader](#XfdfReader--) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getElements](#getElements-com.aspose.ms.System.Xml.XmlReader-) | يقوم بتحليل ملف XFDF ويعيد المعلومات كجدول تجزئة. |
| [readAnnotations](#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-) | استيراد التعليقات التوضيحية من ملف XFDF ووضعها في المستند. |
| [readFields](#readFields-java.io.InputStream-com.aspose.pdf.IDocument-) | استيراد قيم الحقول من ملف XFDF. |

### XfdfReader {#XfdfReader--}
```
public XfdfReader()
```



### getElements {#getElements-com.aspose.ms.System.Xml.XmlReader-}
يقوم بتحليل ملف XFDF ويعيد المعلومات كجدول تجزئة.

### readAnnotations {#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-}
استيراد التعليقات التوضيحية من ملف XFDF ووضعها في المستند.

### readFields {#readFields-java.io.InputStream-com.aspose.pdf.IDocument-}
استيراد قيم الحقول من ملف XFDF.
