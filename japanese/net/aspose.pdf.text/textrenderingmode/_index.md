---
title: Enum TextRenderingMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextRenderingMode 列挙型。テキストレンダリングモード Tmode は、テキストを表示することがグリフのアウトラインをストローク、塗りつぶし、クリッピング境界として使用するか、またはその3つの組み合わせのいずれかを引き起こすかどうかを決定します。
type: docs
weight: 11000
url: /ja/net/aspose.pdf.text/textrenderingmode/
---
## TextRenderingMode 列挙型

テキストレンダリングモード Tmode は、テキストを表示することがグリフのアウトラインをストローク、塗りつぶし、クリッピング境界として使用するか、またはその3つの組み合わせのいずれかを引き起こすかどうかを決定します。

```csharp
public enum TextRenderingMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| FillText | `0` | テキストを塗りつぶします。 |
| StrokeText | `1` | テキストをストロークします。 |
| FillThenStrokeText | `2` | テキストを塗りつぶしてからストロークします。 |
| Invisible | `3` | テキストを塗りつぶさずストロークもしません（不可視）。 |
| FillTextAndAddPathToClipping | `4` | テキストを塗りつぶし、クリッピング用のパスに追加します（9.3.6「テキストレンダリングモード」を参照）。 |
| StrokeTextAndAddPathToClipping | `5` | テキストをストロークし、クリッピング用のパスに追加します。 |
| FillThenStrokeTextAndAddPathToClipping | `6` | テキストを塗りつぶしてからストロークし、クリッピング用のパスに追加します。 |
| AddPathToClipping | `7` | テキストをクリッピング用のパスに追加します。 |

### 参照

* 名前空間 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../)