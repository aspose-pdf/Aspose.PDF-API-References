---
title: Page.AddImage
second_title: Aspose.PDF for .NET API Reference
description: Sayfa yöntemi. Sayfaya resim ekler ve belirtilen dikdörtgenin ortasında konumlandırır, resim oranını korur.
type: docs
weight: 350
url: /tr/net/aspose.pdf/page/addimage/
---
## AddImage(Stream, Rectangle, Rectangle, bool) {#addimage}

Sayfaya resim ekler ve belirtilen dikdörtgenin ortasında konumlandırır, resmin oranını korur.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, Rectangle bbox = null, 
    bool autoAdjustRectangle = true)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageStream | Stream | Resmin akışı. |
| imageRect | Rectangle | Resmin konumu. |
| bbox | Rectangle | Resmin bbox'u. |
| autoAdjustRectangle | Boolean | Resmi giriş dikdörtgeninin ortasında ayarlar. |

### Ayrıca Bakınız

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Stream, Rectangle, Rectangle) {#addimage_3}

Aranabilir resmi sayfaya ekler ve belirtilen dikdörtgenin ortasında konumlandırır, resmin oranını korur.

```csharp
public void AddImage(string hocr, Stream imageStream, Rectangle imageRect, Rectangle bbox = null)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hocr | String | Resmin hocr'u. |
| imageStream | Stream | Resmin akışı. |
| imageRect | Rectangle | Resmin konumu. |
| bbox | Rectangle | Resmin bbox'u. |

### Ayrıca Bakınız

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, Rectangle, int, int, bool, Rectangle) {#addimage_1}

Sayfaya resim ekler ve resmi dikdörtgen konumuna göre yerleştirir.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, 
    bool saveImageProportions, Rectangle bbox = null)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageStream | Stream | Resmin akışı. |
| imageRect | Rectangle | Sayfadaki resmin varsayılan konumu. |
| imageWidth | Int32 | Resmin genişliği. |
| imageHeight | Int32 | Resmin yüksekliği. |
| saveImageProportions | Boolean | Bayrak true olarak ayarlandığında resim dikdörtgen konumuna yerleştirilir; aksi takdirde, dikdörtgenin boyutu resim boyutuna eşit olur. |
| bbox | Rectangle | Resmin bbox'u. |

### Ayrıca Bakınız

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Rectangle) {#addimage_2}

Sayfaya resim ekler ve belirtilen dikdörtgenin ortasında konumlandırır, resmin oranını korur.

```csharp
public void AddImage(string imagePath, Rectangle rectangle)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imagePath | String | Resmin yolu. |
| rectangle | Rectangle | Resmin konumu. |

### Ayrıca Bakınız

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)