---
title: XImageCollection.Replace
second_title: Aspose.PDF for .NET API Reference
description: XImageCollection-Methode. Ersetzen Sie ein Bild in der Sammlung durch ein anderes Bild
type: docs
weight: 150
url: /de/net/aspose.pdf/ximagecollection/replace/
---
## Replace(int, Stream) {#replace}

Ersetzen Sie ein Bild in der Sammlung durch ein anderes Bild.

```csharp
public void Replace(int index, Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Index des Sammlungselements, das im Bereich [1..Anzahl der Bilder] ersetzt wird. |
| stream | Stream | Stream, der Bilddaten (im JPEG-Format) enthält. |

### Siehe auch

* Klasse [XImageCollection](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Replace(int, Stream, int, bool) {#replace_2}

Ersetzen Sie ein Bild in der Sammlung durch ein anderes Bild.

```csharp
public void Replace(int index, Stream stream, int quality, bool isBlackAndWhite)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Index des Sammlungselements, das im Bereich [1..Anzahl der Bilder] ersetzt wird. |
| stream | Stream | Stream, der Bilddaten (im JPEG-Format) enthält. |
| quality | Int32 | Qualität der JPEG-Kompression, in Prozent (gültige Werte sind 0..100). |
| isBlackAndWhite | Boolean | Wenn wahr, wird das Bild mit dem CCITT-Kompressionsverfahren komprimiert, das eine bessere Kompression für Schwarz-Weiß-Bilder bietet. Kann nur für Schwarz-Weiß-Bilder verwendet werden. |

### Siehe auch

* Klasse [XImageCollection](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Replace(int, Stream, int) {#replace_1}

Ersetzen Sie ein Bild in der Sammlung durch ein anderes Bild.

```csharp
public void Replace(int index, Stream stream, int quality)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Index des Sammlungselements, das im Bereich [1..Anzahl der Bilder] ersetzt wird. |
| stream | Stream | Stream, der Bilddaten (im JPEG-Format) enthält. |
| quality | Int32 | JPEG-Qualität. |

### Siehe auch

* Klasse [XImageCollection](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)