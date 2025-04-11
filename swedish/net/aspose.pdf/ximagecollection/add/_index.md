---
title: XImageCollection.Add
second_title: Aspose.PDF for .NET API Reference
description: XImageCollection metod. Lägger till ny bild i bildlistan. Denna metod lägger till bilden som en referens till samma PdfObject vilket gör att filstorleken kan minskas
type: docs
weight: 70
url: /sv/net/aspose.pdf/ximagecollection/add/
---
## Add(XImage) {#add_2}

Lägger till ny bild i bildlistan. Denna metod lägger till bilden som en referens till samma PdfObject (vilket gör att filstorleken kan minskas)

```csharp
public string Add(XImage image)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | XImage | XImage som ska läggas till. |

### Returvärde

Namnet på den tillagda bilden.

### Se Även

* klass [XImage](../../ximage/)
* klass [XImageCollection](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream) {#add_3}

Lägger till enhet i slutet av samlingen, så enheten kan nås med det sista indexet.

```csharp
public string Add(Stream image)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | Stream | Stream som innehåller bilddata (i JPEG-format). |

### Returvärde

Namnet på den tillagda bilden.

### Se Även

* klass [XImageCollection](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(BitmapInfo) {#add}

Lägger till enhet i slutet av samlingen, så enheten kan nås med det sista indexet.

```csharp
public string Add(BitmapInfo bitmapInfo)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | Objekt som innehåller en array av pixlar och bitmapinformation (Bredd, Höjd, PixelFormat). |

### Returvärde

Namnet på den tillagda bilden.

### Se Även

* klass [BitmapInfo](../../bitmapinfo/)
* klass [XImageCollection](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream, ImageFilterType) {#add_4}

Lägger till enhet i slutet av samlingen, så enheten kan nås med det sista indexet.

```csharp
public string Add(Stream image, ImageFilterType filterType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | Stream | Stream som innehåller bilddata. |
| filterType | ImageFilterType | Typen av bildfilter. |

### Returvärde

Namnet på den tillagda bilden.

### Se Även

* enum [ImageFilterType](../../imagefiltertype/)
* klass [XImageCollection](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(BitmapInfo, ImageFilterType) {#add_1}

Lägger till enhet i slutet av samlingen, så enheten kan nås med det sista indexet.

```csharp
public string Add(BitmapInfo bitmapInfo, ImageFilterType filterType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | Objekt som innehåller en array av pixlar och bitmapinformation (Bredd, Höjd, PixelFormat). |
| filterType | ImageFilterType | Typen av bildfilter. |

### Returvärde

Namnet på den tillagda bilden.

### Se Även

* klass [BitmapInfo](../../bitmapinfo/)
* enum [ImageFilterType](../../imagefiltertype/)
* klass [XImageCollection](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream, int) {#add_5}

Lägger till enhet i slutet av samlingen, så enheten kan nås med det sista indexet.

```csharp
public void Add(Stream image, int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | Stream | Stream som innehåller bilddata (i JPEG-format). |
| quality | Int32 | JPEG-kvalitet. |

### Se Även

* klass [XImageCollection](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)