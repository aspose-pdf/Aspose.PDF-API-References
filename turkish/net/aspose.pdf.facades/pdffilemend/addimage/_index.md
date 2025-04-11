---
title: PdfFileMend.AddImage
second_title: Aspose.PDF for .NET API Reference
description: PdfFileMend metodu. Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resim ekler
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

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageStream | Stream | Girdi resim akışı. |
| pageNum | Int32 | Resmi alacak sayfanın numarası. |
| lowerLeftX | Single | Resim dikdörtgeninin sol alt x koordinatı. |
| lowerLeftY | Single | Resim dikdörtgeninin sol alt y koordinatı. |
| upperRightX | Single | Resim dikdörtgeninin sağ üst x koordinatı. |
| upperRightY | Single | Resim dikdörtgeninin sağ üst y koordinatı. |

### Dönüş Değeri

Başarılıysa true, aksi takdirde false.

## Örnekler

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100);
}
mendor.Close();
```

### Ayrıca Bakınız

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int, float, float, float, float, CompositingParameters) {#addimage_1}

Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resim ekler.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageStream | Stream | Girdi resim akışı. |
| pageNum | Int32 | Resmi alacak sayfanın numarası. |
| lowerLeftX | Single | Resim dikdörtgeninin sol alt x koordinatı. |
| lowerLeftY | Single | Resim dikdörtgeninin sol alt y koordinatı. |
| upperRightX | Single | Resim dikdörtgeninin sağ üst x koordinatı. |
| upperRightY | Single | Resim dikdörtgeninin sağ üst y koordinatı. |
| compositingParameters | CompositingParameters | Resim için grafik bileşen parametreleri. |

### Dönüş Değeri

Başarılıysa true, aksi takdirde false.

## Örnekler

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Ayrıca Bakınız

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float) {#addimage_2}

Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resim ekler.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageStream | Stream | Girdi resim akışı. |
| pageNums | Int32[] | Resmi alacak sayfaların numaraları. |
| lowerLeftX | Single | Resim dikdörtgeninin sol alt x koordinatı. |
| lowerLeftY | Single | Resim dikdörtgeninin sol alt y koordinatı. |
| upperRightX | Single | Resim dikdörtgeninin sağ üst x koordinatı. |
| upperRightY | Single | Resim dikdörtgeninin sağ üst y koordinatı. |

### Dönüş Değeri

Başarılıysa true, aksi takdirde false.

## Örnekler

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
}
mendor.Close();
```

### Ayrıca Bakınız

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float, CompositingParameters) {#addimage_3}

Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resim ekler.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageStream | Stream | Girdi resim akışı. |
| pageNums | Int32[] | Resmi alacak sayfaların numaraları. |
| lowerLeftX | Single | Resim dikdörtgeninin sol alt x koordinatı. |
| lowerLeftY | Single | Resim dikdörtgeninin sol alt y koordinatı. |
| upperRightX | Single | Resim dikdörtgeninin sağ üst x koordinatı. |
| upperRightY | Single | Resim dikdörtgeninin sağ üst y koordinatı. |
| compositingParameters | CompositingParameters | Resimler için grafik bileşen parametreleri. |

### Dönüş Değeri

Başarılıysa true, aksi takdirde false.

## Örnekler

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Ayrıca Bakınız

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float) {#addimage_4}

Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resim ekler.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageName | String | Girdi resim dosyasının yolu. |
| pageNum | Int32 | Resmi alacak sayfanın numarası. |
| lowerLeftX | Single | Resim dikdörtgeninin sol alt x koordinatı. |
| lowerLeftY | Single | Resim dikdörtgeninin sol alt y koordinatı. |
| upperRightX | Single | Resim dikdörtgeninin sağ üst x koordinatı. |
| upperRightY | Single | Resim dikdörtgeninin sağ üst y koordinatı. |

### Dönüş Değeri

Başarılıysa true, aksi takdirde false.

## Örnekler

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Ayrıca Bakınız

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float, CompositingParameters) {#addimage_5}

Belirtilen koordinatlarda PDF belgesinin belirtilen sayfasına resim ekler.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageName | String | Girdi resim dosyasının yolu. |
| pageNum | Int32 | Resmi alacak sayfanın numarası. |
| lowerLeftX | Single | Resim dikdörtgeninin sol alt x koordinatı. |
| lowerLeftY | Single | Resim dikdörtgeninin sol alt y koordinatı. |
| upperRightX | Single | Resim dikdörtgeninin sağ üst x koordinatı. |
| upperRightY | Single | Resim dikdörtgeninin sağ üst y koordinatı. |
| compositingParameters | CompositingParameters | Resimler için grafik bileşen parametreleri. |

### Dönüş Değeri

Başarılıysa true, aksi takdirde false.

## Örnekler

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Ayrıca Bakınız

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float) {#addimage_6}

Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resim ekler.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageName | String | Girdi resim dosyasının yolu. |
| pageNums | Int32[] | Resmi alacak sayfaların numaraları. |
| lowerLeftX | Single | Resim dikdörtgeninin sol alt x koordinatı. |
| lowerLeftY | Single | Resim dikdörtgeninin sol alt y koordinatı. |
| upperRightX | Single | Resim dikdörtgeninin sağ üst x koordinatı. |
| upperRightY | Single | Resim dikdörtgeninin sağ üst y koordinatı. |

### Dönüş Değeri

Başarılıysa true, aksi takdirde false.

## Örnekler

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Ayrıca Bakınız

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float, CompositingParameters) {#addimage_7}

Belirtilen koordinatlarda PDF belgesinin belirtilen sayfalarına resim ekler.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageName | String | Girdi resim dosyasının yolu. |
| pageNums | Int32[] | Resmi alacak sayfaların numaraları. |
| lowerLeftX | Single | Resim dikdörtgeninin sol alt x koordinatı. |
| lowerLeftY | Single | Resim dikdörtgeninin sol alt y koordinatı. |
| upperRightX | Single | Resim dikdörtgeninin sağ üst x koordinatı. |
| upperRightY | Single | Resim dikdörtgeninin sağ üst y koordinatı. |
| compositingParameters | CompositingParameters | Resimler için grafik bileşen parametreleri. |

### Dönüş Değeri

Başarılıysa true, aksi takdirde false.

## Örnekler

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Ayrıca Bakınız

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)