---
title: "XImageCollection.Replace"
second_title: "Aspose.PDF för .NET API‑referens"
description: "XImageCollection metod. Ersätt bild i samlingen med en annan bild"
type: docs
weight: 150
url: /sv/net/aspose.pdf/ximagecollection/replace/
---
## Replace(int, Stream) {#replace}

Ersätt bilden i samlingen med en annan bild.

```csharp
public void Replace(int index, Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Index för samlingsobjekt som kommer att ersättas i intervallet [1..images count]. |
| ström | Stream | Ström som innehåller bilddata (i JPEG-format). |

### Se även

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Replace(int, Stream, int, bool) {#replace_2}

Ersätt bilden i samlingen med en annan bild.

```csharp
public void Replace(int index, Stream stream, int quality, bool isBlackAndWhite)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Index för samlingsobjekt som kommer att ersättas i intervallet [1..images count]. |
| ström | Stream | Ström som innehåller bilddata (i JPEG-format). |
| kvalitet | Int32 | Kvalitet på JPEG-komprimering, i procent (giltiga värden är 0..100). |
| isBlackAndWhite | Boolean | Om true, komprimeras bilden med CCITT-komprimeringsmetod som ger bättre kompression för svart‑och‑vit bild. Kan endast användas för svart‑och‑vita bilder. |

### Se även

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Replace(int, Stream, int) {#replace_1}

Ersätt bilden i samlingen med en annan bild.

```csharp
public void Replace(int index, Stream stream, int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Index för samlingsobjekt som kommer att ersättas i intervallet [1..images count]. |
| ström | Stream | Ström som innehåller bilddata (i JPEG-format). |
| kvalitet | Int32 | JPEG-kvalitet. |

### Se även

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


