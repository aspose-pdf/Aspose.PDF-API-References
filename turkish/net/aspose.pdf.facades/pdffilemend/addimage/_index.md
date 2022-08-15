---
title: AddImage
second_title: Aspose.PDF for .NET API Referansı
description: Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resim ekler.
type: docs
weight: 50
url: /tr/net/aspose.pdf.facades/pdffilemend/addimage/
---
## AddImage(Stream, int, float, float, float, float) {#addimage}

Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resim ekler.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| imageStream | Stream | Giriş görüntü akışı. |
| pageNum | Int32 | Resmi alacak sayfa sayısı. |
| lowerLeftX | Single | Görüntü dikdörtgeninin sol alt x'i. |
| lowerLeftY | Single | Görüntü dikdörtgeninin sol alt y. |
| upperRightX | Single | Görüntü dikdörtgeninin sağ üst x'i. |
| upperRightY | Single | Görüntü dikdörtgeninin sağ üst y. |

### Geri dönüş değeri

Başarı yanlışsa doğrudur, aksi halde yanlıştır.

### Örnekler

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100);
}
mendor.Close();
```

### Ayrıca bakınız

* class [PdfFileMend](../../pdffilemend)
* ad alanı [Aspose.Pdf.Facades](../../pdffilemend)
* toplantı [Aspose.PDF](../../../)

---

## AddImage(Stream, int, float, float, float, float, CompositingParameters) {#addimage_1}

Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resim ekler.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| imageStream | Stream | Giriş görüntü akışı. |
| pageNum | Int32 | Resmi alacak sayfa sayısı. |
| lowerLeftX | Single | Görüntü dikdörtgeninin sol alt x'i. |
| lowerLeftY | Single | Görüntü dikdörtgeninin sol alt y. |
| upperRightX | Single | Görüntü dikdörtgeninin sağ üst x'i. |
| upperRightY | Single | Görüntü dikdörtgeninin sağ üst y. |
| compositingParameters | CompositingParameters | Görüntü için grafik birleştirme parametreleri. |

### Geri dönüş değeri

Başarı yanlışsa doğrudur, aksi halde yanlıştır.

### Örnekler

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Ayrıca bakınız

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* ad alanı [Aspose.Pdf.Facades](../../pdffilemend)
* toplantı [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float) {#addimage_2}

Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resim ekler.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| imageStream | Stream | Giriş görüntü akışı. |
| pageNums | Int32[] | Resmi alacak sayfaların sayısı. |
| lowerLeftX | Single | Görüntü dikdörtgeninin sol alt x'i. |
| lowerLeftY | Single | Görüntü dikdörtgeninin sol alt y. |
| upperRightX | Single | Görüntü dikdörtgeninin sağ üst x'i. |
| upperRightY | Single | Görüntü dikdörtgeninin sağ üst y. |

### Geri dönüş değeri

Başarı yanlışsa doğrudur, aksi halde yanlıştır.

### Örnekler

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
}
mendor.Close();
```

### Ayrıca bakınız

* class [PdfFileMend](../../pdffilemend)
* ad alanı [Aspose.Pdf.Facades](../../pdffilemend)
* toplantı [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float, CompositingParameters) {#addimage_3}

Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resim ekler.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| imageStream | Stream | Giriş görüntü akışı. |
| pageNums | Int32[] | Resmi alacak sayfaların sayısı. |
| lowerLeftX | Single | Görüntü dikdörtgeninin sol alt x'i. |
| lowerLeftY | Single | Görüntü dikdörtgeninin sol alt y. |
| upperRightX | Single | Görüntü dikdörtgeninin sağ üst x'i. |
| upperRightY | Single | Görüntü dikdörtgeninin sağ üst y. |
| compositingParameters | CompositingParameters | Görüntüler için grafik birleştirme parametreleri. |

### Geri dönüş değeri

Başarı yanlışsa doğrudur, aksi halde yanlıştır.

### Örnekler

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Ayrıca bakınız

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* ad alanı [Aspose.Pdf.Facades](../../pdffilemend)
* toplantı [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float) {#addimage_4}

Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resim ekler.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| imageName | String | Girdi görüntü dosyasının yolu. |
| pageNum | Int32 | Resmi alacak sayfa sayısı. |
| lowerLeftX | Single | Görüntü dikdörtgeninin sol alt x'i. |
| lowerLeftY | Single | Görüntü dikdörtgeninin sol alt y. |
| upperRightX | Single | Görüntü dikdörtgeninin sağ üst x'i. |
| upperRightY | Single | Görüntü dikdörtgeninin sağ üst y. |

### Geri dönüş değeri

Başarı yanlışsa doğrudur, aksi halde yanlıştır.

### Örnekler

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Ayrıca bakınız

* class [PdfFileMend](../../pdffilemend)
* ad alanı [Aspose.Pdf.Facades](../../pdffilemend)
* toplantı [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float, CompositingParameters) {#addimage_5}

Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resim ekler.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| imageName | String | Girdi görüntü dosyasının yolu. |
| pageNum | Int32 | Resmi alacak sayfa sayısı. |
| lowerLeftX | Single | Görüntü dikdörtgeninin sol alt x'i. |
| lowerLeftY | Single | Görüntü dikdörtgeninin sol alt y. |
| upperRightX | Single | Görüntü dikdörtgeninin sağ üst x'i. |
| upperRightY | Single | Görüntü dikdörtgeninin sağ üst y. |
| compositingParameters | CompositingParameters | Görüntüler için grafik birleştirme parametreleri. |

### Geri dönüş değeri

Başarı yanlışsa doğrudur, aksi halde yanlıştır.

### Örnekler

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Ayrıca bakınız

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* ad alanı [Aspose.Pdf.Facades](../../pdffilemend)
* toplantı [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float) {#addimage_6}

Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resim ekler.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| imageName | String | Girdi görüntü dosyasının yolu. |
| pageNums | Int32[] | Resmi alacak sayfaların sayısı. |
| lowerLeftX | Single | Görüntü dikdörtgeninin sol alt x'i. |
| lowerLeftY | Single | Görüntü dikdörtgeninin sol alt y. |
| upperRightX | Single | Görüntü dikdörtgeninin sağ üst x'i. |
| upperRightY | Single | Görüntü dikdörtgeninin sağ üst y. |

### Geri dönüş değeri

Başarı yanlışsa doğrudur, aksi halde yanlıştır.

### Örnekler

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Ayrıca bakınız

* class [PdfFileMend](../../pdffilemend)
* ad alanı [Aspose.Pdf.Facades](../../pdffilemend)
* toplantı [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float, CompositingParameters) {#addimage_7}

Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resim ekler.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| imageName | String | Girdi görüntü dosyasının yolu. |
| pageNums | Int32[] | Resmi alacak sayfaların sayısı. |
| lowerLeftX | Single | Görüntü dikdörtgeninin sol alt x'i. |
| lowerLeftY | Single | Görüntü dikdörtgeninin sol alt y. |
| upperRightX | Single | Görüntü dikdörtgeninin sağ üst x'i. |
| upperRightY | Single | Görüntü dikdörtgeninin sağ üst y. |
| compositingParameters | CompositingParameters | Görüntüler için grafik birleştirme parametreleri. |

### Geri dönüş değeri

Başarı yanlışsa doğrudur, aksi halde yanlıştır.

### Örnekler

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Ayrıca bakınız

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* ad alanı [Aspose.Pdf.Facades](../../pdffilemend)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
