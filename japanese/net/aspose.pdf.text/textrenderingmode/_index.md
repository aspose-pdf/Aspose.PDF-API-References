---
title: "Enum TextRenderingMode"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Text.TextRenderingMode 列挙型。テキスト描画モード Tmode は、テキストを表示する際にグリフの輪郭がストロークされるか、塗りつぶされるか、クリッピング境界として使用されるか、またはこれら3つの組み合わせになるかを決定します。"
type: docs
weight: 11180
url: /ja/net/aspose.pdf.text/textrenderingmode/
---
## TextRenderingMode enumeration

テキスト描画モード（Tmode）は、テキストを表示する際にグリフの輪郭をストロークするか、塗りつぶすか、クリッピング境界として使用するか、またはこれら三つの組み合わせのいずれかになるかを決定します。

```csharp
public enum TextRenderingMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| FillText | `0` | テキストを塗りつぶす。 |
| StrokeText | `1` | テキストをストロークする。 |
| FillThenStrokeText | `2` | テキストを塗りつぶし、次にストロークする。 |
| Invisible | `3` | テキストを塗りつぶさずストロークもしない（不可視）。 |
| FillTextAndAddPathToClipping | `4` | テキストを塗りつぶし、クリッピング用にパスへ追加する（9.3.6「Text Rendering Mode」を参照）。 |
| StrokeTextAndAddPathToClipping | `5` | テキストをストロークし、クリッピング用にパスへ追加する。 |
| FillThenStrokeTextAndAddPathToClipping | `6` | テキストを塗りつぶし、次にストロークし、クリッピング用にパスへ追加する。 |
| AddPathToClipping | `7` | テキストをクリッピング用にパスへ追加する。 |

### 関連項目

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


