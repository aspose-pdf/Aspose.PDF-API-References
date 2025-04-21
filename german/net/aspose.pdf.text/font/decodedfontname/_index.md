---
title: Font.DecodedFontName
second_title: Aspose.PDF for .NET API Reference
description: Schriftart-Eigenschaft. Manchmal können PDF-Schriftarten einen spezifischen Schriftartnamen haben. Dieser Name ist der Wert der PDF-Schriftarteigenschaft "BaseFont" und manchmal kann diese Eigenschaft in hexadezimaler Form dargestellt werden. Wenn man diesen Namen direkt liest, kann er in unleserlicher Form dargestellt werden. Um eine lesbare Form zu erhalten, ist es notwendig, den Schriftartnamen nach Regeln zu dekodieren, die spezifisch für diese Schriftart sind. Diese Eigenschaft gibt den dekodierten Schriftartnamen zurück, verwenden Sie ihn also für Fälle, in denen Sie auf einen unleserlichen [`FontName`](../fontname/) stoßen. Wenn die Eigenschaft [`FontName`](../fontname/) eine lesbare Form hat, wird diese Eigenschaft die gleiche wie [`FontName`](../fontname/) sein, sodass Sie diese Eigenschaft in allen Fällen verwenden können, in denen Sie den Schriftartnamen in einer lesbaren Form benötigen.
type: docs
weight: 20
url: /de/net/aspose.pdf.text/font/decodedfontname/
---
## Font.DecodedFontName-Eigenschaft

Manchmal können PDF-Schriftarten (normalerweise chinesische/japanische/koreanische Schriftarten) einen spezifischen Schriftartnamen haben. Dieser Name ist der Wert der PDF-Schriftarteigenschaft "BaseFont" und manchmal kann diese Eigenschaft in hexadezimaler Form dargestellt werden. Wenn man diesen Namen direkt liest, kann er in unleserlicher Form dargestellt werden. Um eine lesbare Form zu erhalten, ist es notwendig, den Schriftartnamen nach Regeln zu dekodieren, die spezifisch für diese Schriftart sind. Diese Eigenschaft gibt den dekodierten Schriftartnamen zurück, verwenden Sie ihn also für Fälle, in denen Sie auf einen unleserlichen [`FontName`](../fontname/) stoßen. Wenn die Eigenschaft [`FontName`](../fontname/) eine lesbare Form hat, wird diese Eigenschaft die gleiche wie [`FontName`](../fontname/) sein, sodass Sie diese Eigenschaft in allen Fällen verwenden können, in denen Sie den Schriftartnamen in einer lesbaren Form benötigen.

```csharp
public string DecodedFontName { get; }
```

### Siehe auch

* Klasse [Font](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)