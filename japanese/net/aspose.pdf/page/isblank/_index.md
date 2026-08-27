---
title: "Page.IsBlank"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Page メソッド。ページが空白かどうかを示すフラグを取得します。"
type: docs
weight: 490
url: /ja/net/aspose.pdf/page/isblank/
---
## Page.IsBlank method

ページが空白かどうかのフラグを取得します。

```csharp
public bool IsBlank(double fillThresholdFactor)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fillThresholdFactor | Double | 検出感度を管理する塗りつぶし閾値です。範囲は [0..1) である必要があります。 |

### 戻り値

True - ページが空白の場合; それ以外は false。

## 備考

ページが空であるかどうかを判断するために、ページ全体の領域に対する塗りつぶされた領域の比率を計算します。この比率を fillThresholdFactor パラメータと比較し、比率がそれより小さい場合、ページは空であるとみなされます。

### 関連項目

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


