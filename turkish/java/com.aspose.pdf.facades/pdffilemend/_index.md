---
title: "PdfFileMend"
linktitle: "PdfFileMend"
second_title: "Aspose.PDF for Java API Referansı"
description: "Mevcut PDF belgesinin sayfalarına metin ve resim eklemek için bir sınıfı temsil eder."
type: docs
weight: 500
url: /tr/java/com.aspose.pdf.facades/pdffilemend/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileMend, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileMend, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileMend

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileMend extends SaveableFacade
```

Mevcut PDF belgesinin sayfalarına metin ve resim eklemek için bir sınıfı temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfFileMend](#PdfFileMend--) | Yapıcı. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-) | Yapıcı. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | Yapıcı. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-) | Yapıcı. |
| [PdfFileMend](#PdfFileMend-java.io.InputStream-java.io.OutputStream-) | Yapıcı. |
| [PdfFileMend](#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | Yapıcı. |
| [PdfFileMend](#PdfFileMend-java.lang.String-java.lang.String-) | Yapıcı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addImage](#addImage-java.io.InputStream-int:A-float-float-float-float-) | <p> Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resmi ekler. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resmi ekler. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int-float-float-float-float-) | <p> Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resmi ekler. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resmi ekler. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int:A-float-float-float-float-) | <p> Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resmi ekler. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resmi ekler. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int-float-float-float-float-) | <p> Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resmi ekler. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resmi ekler. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre> |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer:A-float-float-float-float-) | Henüz uygulanmadı. |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-) | Henüz uygulanmadı. |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | Henüz uygulanmadı. |
| [close](#close--) | PdfFileMend nesnesini kapatır. |
| [dispose](#dispose--) | PdfFileMend nesnesini kapatır. Bu yöntem artık kullanılmamaktadır, yerine close() kullanın. |
| [getDocument](#getDocument--) | Belgeyi alır {@code PdfFileMend} üzerinde çalıştığı. |
| [getInputFile](#getInputFile--) | Girdi dosyasını alır. |
| [getInputStream](#getInputStream--) | Girdi akışını alır. |
| [getOutputFile](#getOutputFile--) | Çıktı dosyasını alır. |
| [getOutputStream](#getOutputStream--) | Çıktı akışını alır. |
| [getTextPositioningMode](#getTextPositioningMode--) | Metin konumlandırma stratejisini alır. {@code PositioningMode} Varsayılan mod Legacy'dir. |
| [getWrapMode](#getWrapMode--) | Kelime kaydırma algoritmasını alır. |
| [save](#save-java.io.OutputStream-) | PDF belgesini belirtilen dosyaya kaydeder. |
| [save](#save-java.lang.String-) | PDF belgesini belirtilen dosyaya kaydeder. |
| [setInputFile](#setInputFile-java.lang.String-) | Kullanımdan kaldırıldı. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Giriş akışını ayarlar. |
| [setOutputFile](#setOutputFile-java.lang.String-) | Çıktı dosyasını ayarlar. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Bu yöntem kullanımdan kaldırılmıştır. Facade sonuçlarını almak için Save(outputStream) yöntemini kullanın. |
| [setTextPositioningMode](#setTextPositioningMode-int-) | Metin konumlandırma stratejisini ayarlar. {@code PositioningMode} Varsayılan mod Legacy'dir. |
| [setWordWrap](#setWordWrap-boolean-) | AddText yöntemlerinde kelime kaydırmayı gösteren bir bool değerini ayarlar. Değer true ise, FormattedText içindeki metin kelime kaydırılır. Varsayılan olarak değer false'tur. |
| [setWrapMode](#setWrapMode-int-) | Kelime kaydırma algoritmasını ayarlar. |

### PdfFileMend {#PdfFileMend--}
```
public PdfFileMend()
```

Yapıcı.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-}
Yapıcı.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
Yapıcı.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-}
Yapıcı.

### PdfFileMend {#PdfFileMend-java.io.InputStream-java.io.OutputStream-}
Yapıcı.

### PdfFileMend {#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
Yapıcı.

### PdfFileMend {#PdfFileMend-java.lang.String-java.lang.String-}
Yapıcı.

### addImage {#addImage-java.io.InputStream-int:A-float-float-float-float-}
<p> Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resmi ekler. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resmi ekler. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int-float-float-float-float-}
<p> Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resmi ekler. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resmi ekler. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int:A-float-float-float-float-}
<p> Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resmi ekler. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resmi ekler. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int-float-float-float-float-}
<p> Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resmi ekler. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resmi ekler. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre>

### addText {#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer:A-float-float-float-float-}
Henüz uygulanmadı.

### addText {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-}
Henüz uygulanmadı.

### addText {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
Henüz uygulanmadı.

### close {#close--}
```
public void close()
```

PdfFileMend nesnesini kapatır.

### dispose {#dispose--}
```
public void dispose()
```

PdfFileMend nesnesini kapatır. Bu yöntem artık kullanılmamaktadır, yerine close() kullanın.

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Belgeyi alır {@code PdfFileMend} üzerinde çalıştığı.

**Returns:**
IDocument nesnesi

### getInputFile {#getInputFile--}
```
@Deprecated public String getInputFile()
```

Girdi dosyasını alır.

**Returns:**
String değeri

### getInputStream {#getInputStream--}
```
public InputStream getInputStream()
```

Girdi akışını alır.

**Returns:**
girdi akışı.

### getOutputFile {#getOutputFile--}
```
@Deprecated public String getOutputFile()
```

Çıktı dosyasını alır.

**Returns:**
String değeri

### getOutputStream {#getOutputStream--}
```
@Deprecated public OutputStream getOutputStream()
```

Çıktı akışını alır.

**Returns:**
çıktı akışı.

### getTextPositioningMode {#getTextPositioningMode--}
```
public int getTextPositioningMode()
```

Metin konumlandırma stratejisini alır. {@code PositioningMode} Varsayılan mod Legacy'dir.

**Returns:**
PositioningMode öğesi @see PositioningMode

### getWrapMode {#getWrapMode--}
```
public int getWrapMode()
```

Kelime kaydırma algoritmasını alır.

**Returns:**
WordWrapMode değeri @see WordWrapMode

### save {#save-java.io.OutputStream-}
PDF belgesini belirtilen dosyaya kaydeder.

### save {#save-java.lang.String-}
PDF belgesini belirtilen dosyaya kaydeder.

### setInputFile {#setInputFile-java.lang.String-}
Kullanımdan kaldırıldı.

### setInputStream {#setInputStream-java.io.InputStream-}
Giriş akışını ayarlar.

### setOutputFile {#setOutputFile-java.lang.String-}
Çıktı dosyasını ayarlar.

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Bu yöntem kullanımdan kaldırılmıştır. Facade sonuçlarını almak için Save(outputStream) yöntemini kullanın.

### setTextPositioningMode {#setTextPositioningMode-int-}
```
public void setTextPositioningMode(int value)
```

Metin konumlandırma stratejisini ayarlar. {@code PositioningMode} Varsayılan mod Legacy'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | PositioningMode öğesi @see PositioningMode |

### setWordWrap {#setWordWrap-boolean-}
```
public void setWordWrap(boolean value)
```

AddText yöntemlerinde kelime kaydırmayı gösteren bir bool değerini ayarlar. Değer true ise, FormattedText içindeki metin kelime kaydırılır. Varsayılan olarak değer false'tur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setWrapMode {#setWrapMode-int-}
```
public void setWrapMode(int value)
```

Kelime kaydırma algoritmasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | WordWrapMode öğesi @see WordWrapMode |
