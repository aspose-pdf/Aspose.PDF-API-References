---
title: XImageCollection.Replace
second_title: Aspose.PDF for .NET API Reference
description: XImageCollection metod. Ersätt bild i samlingen med en annan bild
type: docs
weight: 150
url: /sv/net/aspose.pdf/ximagecollection/replace/
---
## Replace(int, Stream) {#replace}

Ersätt bild i samlingen med en annan bild.

```csharp
public void Replace(int index, Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Index för samlingsobjektet som kommer att ersättas i [1..antal bilder] intervall. |
| stream | Stream | Stream som innehåller bilddata (i JPEG-format). |

### Se Även

* klass [XImageCollection](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)

---

## Replace(int, Stream, int, bool) {#replace_2}

Ersätt bild i samlingen med en annan bild.

```csharp
public void Replace(int index, Stream stream, int quality, bool isBlackAndWhite)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Index för samlingsobjektet som kommer att ersättas i [1..antal bilder] intervall. |
| stream | Stream | Stream som innehåller bilddata (i JPEG-format). |
| quality | Int32 | Kvalitet på JPEG-kompression, i procent (giltiga värden är 0..100). |
| isBlackAndWhite | Boolean | Om sant, komprimeras bilden med CCITT-komprimeringsmetod som ger bättre kompression för svartvita bilder. Kan endast användas för svartvita bilder. |

### Se Även

* klass [XImageCollection](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)

---

## Replace(int, Stream, int) {#replace_1}

Ersätt bild i samlingen med en annan bild.

```csharp
public void Replace(int index, Stream stream, int quality)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Index för samlingsobjektet som kommer att ersättas i [1..antal bilder] intervall. |
| stream | Stream | Stream som innehåller bilddata (i JPEG-format). |
| quality | Int32 | JPEG-kvalitet. |

### Se Även

* klass [XImageCollection](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)