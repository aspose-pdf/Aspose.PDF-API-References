---
title: Enum PositioningMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PositioningMode 列挙型。位置決定モードを定義します。可能な値には、レガシーの後方互換性と現在の更新されたテキスト位置計算方法が含まれます。
type: docs
weight: 4650
url: /ja/net/aspose.pdf.facades/positioningmode/
---
## PositioningMode 列挙型

位置決定モードを定義します。可能な値には、レガシー（後方互換性）と現在（更新されたテキスト位置計算方法）が含まれます。

```csharp
public enum PositioningMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Legacy | `0` | レガシーテキスト位置決定 |
| ModernLineSpacing | `1` | 更新された行間隔、垂直位置計算は古いルールに基づいて行われます（つまり、テキストは指定された矩形の左下隅に対して相対的に配置されます） |
| Current | `2` | 更新された行間隔と垂直位置計算は左下隅ではなく左上隅に基づいて行われます。 |

### 参照

* 名前空間 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../)