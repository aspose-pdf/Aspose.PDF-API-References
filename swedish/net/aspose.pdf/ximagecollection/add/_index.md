---
title: "XImageCollection.Add"
second_title: "Aspose.PDF för .NET API‑referens"
description: "XImageCollection-metod. Lägger till en ny bild i bildlistan. Denna metod lägger till bilden som referens till samma PdfObject, vilket möjliggör minskning av filstorleken"
type: docs
weight: 70
url: /sv/net/aspose.pdf/ximagecollection/add/
---
## Add(XImage) {#add_2}

Lägger till en ny bild i bildlistan. Denna metod lägger till bilden som referens till samma PdfObject (vilket möjliggör minskad filstorlek)

```csharp
public string Add(XImage image)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bild | XImage | XImage att lägga till. |

### Returvärde

Namnet på den tillagda bilden.

### Se även

* class [XImage](../../ximage/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream) {#add_3}

Lägger till en entitet i slutet av samlingen, så att entiteten kan nås via det sista indexet.

```csharp
public string Add(Stream image)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bild | Stream | Ström som innehåller bilddata (i JPEG-format). |

### Returvärde

Namnet på den tillagda bilden.

### Se även

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(BitmapInfo) {#add}

Lägger till en entitet i slutet av samlingen, så att entiteten kan nås via det sista indexet.

```csharp
public string Add(BitmapInfo bitmapInfo)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | Objekt som innehåller en array av pixlar och bitmapinformation (Width, Height, PixelFormat). |

### Returvärde

Namnet på den tillagda bilden.

### Se även

* class [BitmapInfo](../../bitmapinfo/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream, ImageFilterType) {#add_4}

Lägger till en entitet i slutet av samlingen, så att entiteten kan nås via det sista indexet.

```csharp
public string Add(Stream image, ImageFilterType filterType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bild | Stream | Ström som innehåller bilddata. |
| filterType | ImageFilterType | Bildfiltertypen. |

### Returvärde

Namnet på den tillagda bilden.

### Se även

* enum [ImageFilterType](../../imagefiltertype/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(BitmapInfo, ImageFilterType) {#add_1}

Lägger till en entitet i slutet av samlingen, så att entiteten kan nås via det sista indexet.

```csharp
public string Add(BitmapInfo bitmapInfo, ImageFilterType filterType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | Objekt som innehåller en array av pixlar och bitmapinformation (Width, Height, PixelFormat). |
| filterType | ImageFilterType | Bildfiltertypen. |

### Returvärde

Namnet på den tillagda bilden.

### Se även

* class [BitmapInfo](../../bitmapinfo/)
* enum [ImageFilterType](../../imagefiltertype/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream, int) {#add_5}

Lägger till en entitet i slutet av samlingen, så att entiteten kan nås via det sista indexet.

```csharp
public void Add(Stream image, int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bild | Stream | Ström som innehåller bilddata (i JPEG-format). |
| kvalitet | Int32 | JPEG-kvalitet. |

### Se även

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


